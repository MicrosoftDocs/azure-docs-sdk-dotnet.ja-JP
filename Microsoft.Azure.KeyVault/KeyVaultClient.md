<Type Name="KeyVaultClient" FullName="Microsoft.Azure.KeyVault.KeyVaultClient">
  <TypeSignature Language="C#" Value="public class KeyVaultClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.KeyVault.KeyVaultClient&gt;, IDisposable, Microsoft.Azure.KeyVault.IKeyVaultClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.KeyVault.KeyVaultClient&gt; implements class Microsoft.Azure.KeyVault.IKeyVaultClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.KeyVaultClient" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultClient&#xA;Inherits ServiceClient(Of KeyVaultClient)&#xA;Implements IAzureClient, IDisposable, IKeyVaultClient" />
  <TypeSignature Language="F#" Value="type KeyVaultClient = class&#xA;    inherit ServiceClient&lt;KeyVaultClient&gt;&#xA;    interface IKeyVaultClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.KeyVault.KeyVaultClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.KeyVault.KeyVaultClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.KeyVault.IKeyVaultClient</InterfaceName>
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
            暗号化キーの操作を実行し、Key Vault サービスに対する操作が資格情報コンテナーのクライアント クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            KeyVaultClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback authenticationCallback, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultClient/AuthenticationCallback authenticationCallback, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (authenticationCallback, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authenticationCallback" Type="Microsoft.Azure.KeyVault.KeyVaultClient+AuthenticationCallback" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="authenticationCallback">認証コールバック</param>
        <param name="handlers">省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。</param>
        <summary>
            コンストラクター
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback authenticationCallback, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultClient/AuthenticationCallback authenticationCallback, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback * System.Net.Http.HttpClient -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (authenticationCallback, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authenticationCallback" Type="Microsoft.Azure.KeyVault.KeyVaultClient+AuthenticationCallback" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="authenticationCallback">認証コールバック</param>
        <param name="httpClient">カスタマイズされた HTTP クライアント </param>
        <summary>
            コンストラクター
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultCredential credential, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultCredential credential, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultCredential,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultCredential * System.Net.Http.HttpClient -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credential, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="Microsoft.Azure.KeyVault.KeyVaultCredential" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credential">キー コンテナー操作の資格情報</param>
        <param name="httpClient">カスタマイズされた HTTP クライアント </param>
        <summary>
            コンストラクター
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
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
            必須。 Azure に接続するクライアントに必要な資格情報です。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            KeyVaultClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            KeyVaultClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
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
        <param name="credentials">
            必須。 Azure に接続するクライアントに必要な資格情報です。
            </param>
        <param name="rootHandler">
            省略可能。 Http トランスポートを処理するために使用する http クライアント ハンドラー。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            KeyVaultClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアント API のバージョンです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt; BackupKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt; BackupKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.BackupKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;&#xA;override this.BackupKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;" Usage="keyVaultClient.BackupKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.BackupKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;BackupKeyWithHttpMessagesAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキーのバックアップをクライアントにダウンロードするように要求します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            キーのバックアップ操作は、保護された形式で、Azure Key Vault からキーをエクスポートします。 この操作では、Azure Key Vault システムの外部で使用できる形式では、キー マテリアルは返しません、返されるキー マテリアルは保護 Azure Key Vault HSM または Azure Key Vault 自体ことに注意してください。
            この操作の目的は、キーのバックアップ、1 つの Azure Key Vault インスタンスでキーを生成し、別の Azure Key Vault インスタンスに復元してクライアントを許可するのにです。 バックアップ操作は、エクスポートする保護対象のフォームでは、Azure Key Vault からのすべてのキー タイプに使用可能性があります。 キーの個別のバージョンは、バックアップすることはできません。 バックアップ/復元は地理的な境界のみ; 内で実行できます別の地理的領域に 1 つの地理的領域からバックアップを復元できないことを意味します。 たとえば、米国の地理的領域からのバックアップを EU の地理的領域に復元できません。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="BackupSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt; BackupSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt; BackupSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.BackupSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;&#xA;override this.BackupSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;" Usage="keyVaultClient.BackupSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.BackupSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;BackupSecretWithHttpMessagesAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したシークレットのバックアップをクライアントにダウンロードするように要求します。
            認証:、シークレット/バックアップ権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; CreateCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; CreateCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.CreateCertificateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateCertificateWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.CreateCertificateWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.CreateCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.CreateCertificateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;CreateCertificateWithHttpMessagesAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="certificatePolicy">
            証明書の管理ポリシー。
            </param>
        <param name="certificateAttributes">
            (省略可能) の証明書の属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しい証明書を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            これが最初のバージョンである場合は、証明書リソースが作成されます。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; CreateKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string kty, Nullable&lt;int&gt; keySize = null, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string curve = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; CreateKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string kty, valuetype System.Nullable`1&lt;int32&gt; keySize, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string curve, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.CreateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.CreateKeyWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.CreateKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, kty, keySize, keyOps, keyAttributes, tags, curve, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.CreateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;CreateKeyWithHttpMessagesAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="kty" Type="System.String" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="curve" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            新しいキーの名前です。 システムでは、新しいキーのバージョン名を生成します。
            </param>
        <param name="kty">
            作成するキーの型。 有効な値は、JsonWebKeyType を参照してください。 使用可能な値が含まれます: 'EC'、' EC HSM'、'RSA'、' RSA-HSM '、'oct'
            </param>
        <param name="keySize">
            キーのサイズ (バイト単位)。 たとえば、1024 または 2048。
            </param>
        <param name="keyOps"></param>
        <param name="keyAttributes"></param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="curve">
            楕円曲線の名前です。 有効な値は、JsonWebKeyCurveName を参照してください。 使用可能な値が含まれます: 'P-256'、'P-384'、'P-521'、'SECP256K1'
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しいキーを作成、格納、キー パラメーターを返し、属性をクライアントにします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            キーの作成処理は、Azure Key Vault 内のすべてのキー タイプの作成に使用できます。 名前付きのキーが既に存在する場合、Azure Key Vault には、キーの新しいバージョンが作成されます。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="DecryptWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; DecryptWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; DecryptWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DecryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DecryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.DecryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.DecryptWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DecryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DecryptWithHttpMessagesAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            アルゴリズムの識別子です。 使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            暗号化されたデータの 1 つのブロックを解除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            DECRYPT 操作は、ターゲット暗号化キーと指定されたアルゴリズムを使用して暗号テキストの整形式ブロックを解除します。 この操作は、ENCRYPT 操作の逆だけでデータの 1 つのブロックは、暗号化が解除された可能性があります、このブロックのサイズは対象のキーと使用するアルゴリズムによって異なります。 DECRYPT 操作は、非対称キーおよび対称キー、キーの秘密部分を使用しているので、Azure Key Vault に格納されているに適用されます。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; DeleteCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; DeleteCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.DeleteCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateContactsWithHttpMessagesAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーの証明書の連絡先を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定した資格情報コンテナー証明書の証明書の連絡先を削除します。
            認証:、証明書/managecontacts 権限が必要です。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; DeleteCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; DeleteCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.DeleteCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateIssuerWithHttpMessagesAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="issuerName">
            発行者の名前です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書の発行者を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            DeleteCertificateIssuer 操作は、資格情報コンテナーから、指定された証明書の発行者を完全に削除します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; DeleteCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; DeleteCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.DeleteCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateOperationWithHttpMessagesAsync&gt;d__93))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書の操作を削除します。 認証:、証明書/更新アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; DeleteCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; DeleteCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;&#xA;override this.DeleteCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;" Usage="keyVaultClient.DeleteCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateWithHttpMessagesAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキー資格情報コンテナーから証明書を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            関連付けられているポリシーと共に証明書オブジェクトのすべてのバージョンを削除します。 削除証明書オブジェクトの個々 のバージョンを削除する証明書を使用することはできません。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; DeleteKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; DeleteKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;&#xA;override this.DeleteKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;" Usage="keyVaultClient.DeleteKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteKeyWithHttpMessagesAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            削除するキーの名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Key Vault に記憶域から任意の型のキーを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            キーの個別のバージョンを削除するキーの削除操作を使用できません。 この操作は、キーが署名/検証、ラップ/ラップ解除または暗号化/暗号化解除操作に使用しないことを意味すると、キーに関連付けられている暗号化マテリアルを削除します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; DeleteSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; DeleteSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.DeleteSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteSasDefinitionWithHttpMessagesAsync&gt;d__106))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="sasDefinitionName">
            SAS の定義の名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたストレージ アカウントから SAS 定義を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; DeleteSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; DeleteSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;&#xA;override this.DeleteSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;" Usage="keyVaultClient.DeleteSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteSecretWithHttpMessagesAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された key vault からシークレットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            削除操作は、Azure Key Vault に格納されているシークレットに適用されます。
            削除は、個々 のバージョンのシークレットに適用できません。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; DeleteStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; DeleteStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.DeleteStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.DeleteStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteStorageAccountWithHttpMessagesAsync&gt;d__100))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストレージ アカウントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="EncryptWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; EncryptWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; EncryptWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.EncryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EncryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.EncryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.EncryptWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.EncryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;EncryptWithHttpMessagesAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            アルゴリズムの識別子です。 使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Key vault に格納されている暗号化キーを使用してバイトの任意の順序を暗号化します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ENCRYPT 操作では、Azure Key Vault に格納されている暗号化キーを使用してバイトの任意の順序を暗号化します。 暗号化操作はサイズが、対象のキーと使用する暗号化アルゴリズムに依存して、データの 1 つのブロックのみをサポートする注意してください。 暗号化操作は、キーの公開部分を使用して非対称キーで保護を実行できるので、Azure Key Vault に格納されている対称キーの厳密に必要だけです。 この操作は、キー参照であるが、パブリックのキー マテリアルにアクセスできない呼び出し元の便宜を図って非対称キーのサポートは。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="GetCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; GetCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; GetCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.GetCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.GetCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateContactsWithHttpMessagesAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーの証明書の連絡先の一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateContacts 操作は、指定されたキー コンテナーに証明書の連絡先のリソースのセットを返します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;&#xA;override this.GetCertificateIssuersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuersNextWithHttpMessagesAsync&gt;d__117))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーの証明書の発行者をリストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateIssuers 操作は、指定されたキー コンテナーに証明書発行者のリソースのセットを返します
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuersWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuersWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;&#xA;override this.GetCertificateIssuersWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuersWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuersWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuersWithHttpMessagesAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーの証明書の発行者をリストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateIssuers 操作は、指定されたキー コンテナーに証明書発行者のリソースのセットを返します
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; GetCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; GetCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.GetCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuerWithHttpMessagesAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="issuerName">
            発行者の名前です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書の発行者の一覧を示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateIssuer 操作は、指定されたキー コンテナーに指定された証明書発行者リソースを返します
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; GetCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; GetCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.GetCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.GetCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateOperationWithHttpMessagesAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書に関連付けられている操作を取得します。 認証:、証明書/取得アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatePolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; GetCertificatePolicyWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; GetCertificatePolicyWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatePolicyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatePolicyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;&#xA;override this.GetCertificatePolicyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;" Usage="keyVaultClient.GetCertificatePolicyWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatePolicyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatePolicyWithHttpMessagesAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            指定されたキー コンテナーに証明書の名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書のポリシーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificatePolicy 操作は、指定されたキー コンテナーに指定された証明書ポリシー リソースを返します
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificatesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatesNextWithHttpMessagesAsync&gt;d__116))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーに証明書の一覧
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificates 操作は、指定されたキー コンテナーに証明書のリソースのセットを返します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificatesWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatesWithHttpMessagesAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーに証明書の一覧
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificates 操作は、指定されたキー コンテナーに証明書のリソースのセットを返します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificateVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateVersionsNextWithHttpMessagesAsync&gt;d__118))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書のバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateVersions 操作は、指定されたキー コンテナーに証明書のバージョンを返します
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificateVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateVersionsWithHttpMessagesAsync (vaultBaseUrl, certificateName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateVersionsWithHttpMessagesAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書のバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetCertificateVersions 操作は、指定されたキー コンテナーに証明書のバージョンを返します
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; GetCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string certificateVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; GetCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string certificateVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.GetCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.GetCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificateVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateWithHttpMessagesAsync&gt;d__90))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            指定された資格情報コンテナー内の証明書の名前。
            </param>
        <param name="certificateVersion">
            証明書のバージョン。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書に関する情報を取得します。 認証:、証明書/取得アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;&#xA;override this.GetDeletedCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificatesNextWithHttpMessagesAsync&gt;d__119))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            現在回復に使用できる、指定したコンテナーに削除された証明書を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetDeletedCertificates 操作では、削除済み状態の回復または削除の準備完了である現在の資格情報コンテナーに証明書を取得します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;&#xA;override this.GetDeletedCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificatesWithHttpMessagesAsync&gt;d__95))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            現在回復に使用できる、指定したコンテナーに削除された証明書を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetDeletedCertificates 操作では、削除済み状態の回復または削除の準備完了である現在の資格情報コンテナーに証明書を取得します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; GetDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; GetDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;&#xA;override this.GetDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificateWithHttpMessagesAsync&gt;d__96))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された削除済み証明書に関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GetDeletedCertificate 操作は、削除された証明書の情報と保有期間、スケジュールされた永続的な削除、および現在の回復レベルでの削除など、その属性を取得します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;&#xA;override this.GetDeletedKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeysNextWithHttpMessagesAsync&gt;d__112))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナー内のキーをリストが削除されました。 認証:、キー/一覧表示権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;&#xA;override this.GetDeletedKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedKeysWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeysWithHttpMessagesAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナー内のキーをリストが削除されました。 認証:、キー/一覧表示権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; GetDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; GetDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;&#xA;override this.GetDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeyWithHttpMessagesAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キーの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            削除済みのキー情報とその属性を取得します。 認証:、キー/取得アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;&#xA;override this.GetDeletedSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretsNextWithHttpMessagesAsync&gt;d__115))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナーに削除された機密情報を一覧表示します。 認証:、シークレット/リスト権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;&#xA;override this.GetDeletedSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretsWithHttpMessagesAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナーに削除された機密情報を一覧表示します。 認証:、シークレット/リスト権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; GetDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; GetDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;&#xA;override this.GetDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretWithHttpMessagesAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            削除された秘密情報とその属性を取得します。
            認証:、シークレット/取得アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeysNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeysNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeysNextWithHttpMessagesAsync&gt;d__111))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナー内のキーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            格納されたキーのパブリック部分を含む JSON Web Key 構造として、Key Vault 内のキーの一覧を取得します。 LIST 操作はすべてのキー型に適用される、ただしのみ、基本キー識別子、属性、およびタグが応答で提供します。 キーの個別のバージョンは、応答には表示されません。 認証:、キー/一覧表示権限が必要です。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeysWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeysWithHttpMessagesAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナー内のキーを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            格納されたキーのパブリック部分を含む JSON Web Key 構造として、Key Vault 内のキーの一覧を取得します。 LIST 操作はすべてのキー型に適用される、ただしのみ、基本キー識別子、属性、およびタグが応答で提供します。 キーの個別のバージョンは、応答には表示されません。 認証:、キー/一覧表示権限が必要です。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeyVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyVersionsNextWithHttpMessagesAsync&gt;d__110))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            同じキー名で個別キー バージョンの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            完全なキー識別子、属性、およびタグは、応答で提供されます。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsWithHttpMessagesAsync (string vaultBaseUrl, string keyName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsWithHttpMessagesAsync(string vaultBaseUrl, string keyName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeyVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeyVersionsWithHttpMessagesAsync (vaultBaseUrl, keyName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyVersionsWithHttpMessagesAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            同じキー名で個別キー バージョンの一覧を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            完全なキー識別子、属性、およびタグは、応答で提供されます。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; GetKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; GetKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.GetKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.GetKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyWithHttpMessagesAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            取得するキーの名前。
            </param>
        <param name="keyVersion">
            バージョン パラメーターを追加するには、特定のバージョンのキーを取得します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            格納されているキーのパブリックの部分を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            キーの取得操作は、すべてのキー タイプに適用できます。 要求されたキーが対称の場合は、し、キー マテリアルではリリースされません応答します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetPendingCertificateSigningRequestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt; GetPendingCertificateSigningRequestWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;string&gt;&gt; GetPendingCertificateSigningRequestWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPendingCertificateSigningRequestWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;&#xA;override this.GetPendingCertificateSigningRequestWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;" Usage="keyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetPendingCertificateSigningRequestWithHttpMessagesAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名、https://myvault.vault.azure.net 例:
            </param>
        <param name="certificateName">
            証明書の名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            保留中の証明書要求応答の署名を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;&#xA;override this.GetSasDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionsNextWithHttpMessagesAsync&gt;d__121))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定のストレージ アカウントのストレージの SAS の定義を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;&#xA;override this.GetSasDefinitionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionsWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionsWithHttpMessagesAsync&gt;d__105))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定のストレージ アカウントのストレージの SAS の定義を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; GetSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; GetSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.GetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionWithHttpMessagesAsync&gt;d__107))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="sasDefinitionName">
            SAS の定義の名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたストレージ アカウントの SAS の定義に関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretsNextWithHttpMessagesAsync&gt;d__113))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された key vault にシークレットの一覧表示
            </summary>
        <returns>To be added.</returns>
        <remarks>
            LIST 操作はただしコンテナー全体に適用可能な基本のシークレット識別子と属性のみが応答で提供します。 個別のシークレット バージョンは、応答には表示されません。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretsWithHttpMessagesAsync&gt;d__66))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された key vault にシークレットの一覧表示
            </summary>
        <returns>To be added.</returns>
        <remarks>
            LIST 操作はただしコンテナー全体に適用可能な基本のシークレット識別子と属性のみが応答で提供します。 個別のシークレット バージョンは、応答には表示されません。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretVersionsNextWithHttpMessagesAsync&gt;d__114))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したシークレットのバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            LIST VERSIONS 操作は、同じ key vault で同じシークレット名を持つすべてのバージョンに適用できます。 完全なシークレット識別子および属性は、応答で提供されます。 シークレットの値が返されないと、現行バージョンのシークレットのみが一覧表示されます。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsWithHttpMessagesAsync (string vaultBaseUrl, string secretName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsWithHttpMessagesAsync(string vaultBaseUrl, string secretName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretVersionsWithHttpMessagesAsync (vaultBaseUrl, secretName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretVersionsWithHttpMessagesAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したシークレットのバージョンを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            LIST VERSIONS 操作は、同じ key vault で同じシークレット名を持つすべてのバージョンに適用できます。 完全なシークレット識別子および属性は、応答で提供されます。 シークレットの値が返されないと、現行バージョンのシークレットのみが一覧表示されます。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; GetSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string secretVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; GetSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string secretVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.GetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.GetSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, secretVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretWithHttpMessagesAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="secretVersion">
            シークレットのバージョン。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーから、指定されたシークレットを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            GET 操作は、Azure Key Vault に格納されているシークレットに適用します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;&#xA;override this.GetStorageAccountsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;" Usage="keyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountsNextWithHttpMessagesAsync&gt;d__120))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナーで管理されているストレージ アカウントを一覧表示
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;&#xA;override this.GetStorageAccountsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;" Usage="keyVaultClient.GetStorageAccountsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountsWithHttpMessagesAsync&gt;d__99))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="maxresults">
            ページに返される結果の最大数。 サービスは最大 25 件の結果を返すが指定されていない場合。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した資格情報コンテナーで管理されているストレージ アカウントを一覧表示
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; GetStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; GetStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.GetStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.GetStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountWithHttpMessagesAsync&gt;d__101))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたストレージ アカウントの情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="ImportCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; ImportCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; ImportCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.ImportCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportCertificateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.ImportCertificateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.ImportCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, base64EncodedCertificate, password, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.ImportCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;ImportCertificateWithHttpMessagesAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="base64EncodedCertificate" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="base64EncodedCertificate">
            インポートする証明書オブジェクトの表現を Base64 にエンコードされます。 この証明書を秘密キーを含める必要があります。
            </param>
        <param name="password">
            Base64EncodedCertificate 内の秘密キーが暗号化されている場合、パスワードは暗号化に使用します。
            </param>
        <param name="certificatePolicy">
            証明書の管理ポリシー。
            </param>
        <param name="certificateAttributes">
            (省略可能) の証明書の属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキー資格情報コンテナーに証明書をインポートします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            既存有効な証明書を Azure Key Vault には秘密キーを含むをインポートします。 インポートする証明書は、PFX または PEM のいずれかの形式であることができます。 キーだけでなく x509 PEM ファイルを含める必要があります PEM 形式での証明書がある場合の証明書。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="ImportKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; ImportKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, Nullable&lt;bool&gt; hsm = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; ImportKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, valuetype System.Nullable`1&lt;bool&gt; hsm, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.ImportKeyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportKeyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.ImportKeyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.ImportKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, key, hsm, keyAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.ImportKeyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;ImportKeyWithHttpMessagesAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="hsm" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            インポートしたキーの名前です。
            </param>
        <param name="key">
            Json web key
            </param>
        <param name="hsm">
            ハードウェア キー (HSM) またはソフトウェア キーとしてインポートするかどうか。
            </param>
        <param name="keyAttributes">
            キー管理の属性です。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            外部で作成されたキーをインポートする格納し、キー パラメーターを返し、属性をクライアントにします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            インポート キー操作は、すべてのキー タイプを Azure Key Vault にインポートするために使用可能性があります。 名前付きのキーが既に存在する場合、Azure Key Vault には、キーの新しいバージョンが作成されます。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="MergeCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; MergeCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.IList&lt;byte[]&gt; x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; MergeCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.IList`1&lt;unsigned int8[]&gt; x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.MergeCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MergeCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.MergeCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.MergeCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, x509Certificates, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.MergeCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;MergeCertificateWithHttpMessagesAsync&gt;d__94))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="x509Certificates" Type="System.Collections.Generic.IList&lt;System.Byte[]&gt;" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="x509Certificates">
            証明書または証明書チェーンをマージします。
            </param>
        <param name="certificateAttributes">
            (省略可能) の証明書の属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のサーバーでキーのペアで、証明書または証明書チェーンをマージします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            MergeCertificate 操作では、証明書またはサービスで現在使用できるキーのペアで証明書チェーンのマージを実行します。
            認証:、証明書/更新アクセス許可が必要です。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedCertificateWithHttpMessagesAsync&gt;d__97))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された削除済み証明書を完全に削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            PurgeDeletedCertificate 操作では、指定された証明書を回復する可能性の元に戻すことの削除を実行します。 操作は回復レベルで 'Purgeable' が指定されていない場合に使用できません。
            明示的な '削除' 権限を許可する必要があります。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedKeyWithHttpMessagesAsync&gt;d__60))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キーの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキーを完全に削除します。 別名、キーを削除します。 認証:、キー/削除アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedSecretWithHttpMessagesAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたシークレットを完全に削除します。 別名、シークレットを削除します。
            認証:、シークレット/削除アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; RecoverDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; RecoverDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.RecoverDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedCertificateWithHttpMessagesAsync&gt;d__98))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            削除済みの証明書の名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            現在のバージョンに戻す、削除された証明書を回復します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            RecoverDeletedCertificate 操作では、削除操作の取り消しを実行します。 操作は、ソフト削除の有効な資格情報コンテナーに適用し、間隔、保有期間 (削除済み証明書の属性で使用可能) 発行する必要があります。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RecoverDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RecoverDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.RecoverDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedKeyWithHttpMessagesAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            削除されたキーの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            削除されたキーに戻します/keys 下にある現在のバージョンを回復します。
            認証:、キー/回復のアクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RecoverDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RecoverDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.RecoverDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedSecretWithHttpMessagesAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            削除されたシークレットの名前
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            /Secrets 下にある現在のバージョンに削除されたシークレット バックアップを復元します。
            認証:、シークレット/回復のアクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="RegenerateStorageAccountKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; RegenerateStorageAccountKeyWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; RegenerateStorageAccountKeyWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateStorageAccountKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.RegenerateStorageAccountKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RegenerateStorageAccountKeyWithHttpMessagesAsync&gt;d__104))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="keyName">
            ストレージ アカウント キーの名前。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたストレージ アカウントの指定したキー値を再生成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="RestoreKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RestoreKeyWithHttpMessagesAsync (string vaultBaseUrl, byte[] keyBundleBackup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RestoreKeyWithHttpMessagesAsync(string vaultBaseUrl, unsigned int8[] keyBundleBackup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RestoreKeyWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreKeyWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.RestoreKeyWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.RestoreKeyWithHttpMessagesAsync (vaultBaseUrl, keyBundleBackup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RestoreKeyWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RestoreKeyWithHttpMessagesAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyBundleBackup" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyBundleBackup">
            キーのバンドルに関連付けられているバックアップ blob です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            資格情報コンテナーにキーをバックアップを復元します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Azure Key Vault、キー、そのキー識別子、属性、およびアクセス制御ポリシーを復元するのには、以前にバックアップ キーをインポートします。 復元操作は、以前にバックアップ キーをインポートするために使用可能性があります。 キーの個別のバージョンを復元することはできません。 キーにはバックアップ時と同じキー名で全体として復元されます。 キー名をターゲット Key Vault では使用できない場合、復元操作は拒否されます。 キー名は、復元中に保持されますが、中に、最終的なキー識別子は、別の資格情報コンテナーにキーを復元した場合に変更されます。 復元では、すべてのバージョンを復元し、バージョン識別子を保持します。 復元操作のセキュリティの制約があります。 ターゲット Key Vault はソース Key Vault、ユーザーがターゲット Key Vault で復元権限を必要と同じ Microsoft Azure サブスクリプションで所有する必要があります。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="RestoreSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RestoreSecretWithHttpMessagesAsync (string vaultBaseUrl, byte[] secretBundleBackup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RestoreSecretWithHttpMessagesAsync(string vaultBaseUrl, unsigned int8[] secretBundleBackup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RestoreSecretWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreSecretWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.RestoreSecretWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.RestoreSecretWithHttpMessagesAsync (vaultBaseUrl, secretBundleBackup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RestoreSecretWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RestoreSecretWithHttpMessagesAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretBundleBackup" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretBundleBackup">
            シークレットのバンドルに関連付けられているバックアップ blob です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            資格情報コンテナーにシークレットをバックアップを復元します。 認証:、シークレット/復元権限が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="SetCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; SetCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, Microsoft.Azure.KeyVault.Models.Contacts contacts, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; SetCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class Microsoft.Azure.KeyVault.Models.Contacts contacts, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetCertificateContactsWithHttpMessagesAsync(System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetCertificateContactsWithHttpMessagesAsync : string * Microsoft.Azure.KeyVault.Models.Contacts * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.SetCertificateContactsWithHttpMessagesAsync : string * Microsoft.Azure.KeyVault.Models.Contacts * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.SetCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, contacts, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetCertificateContactsWithHttpMessagesAsync(System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetCertificateContactsWithHttpMessagesAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="contacts" Type="Microsoft.Azure.KeyVault.Models.Contacts" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="contacts">
            キー コンテナーの証明書の連絡先。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキー資格情報コンテナーの証明書の連絡先を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            指定したキー資格情報コンテナーの証明書の連絡先を設定します。 認証:、証明書/managecontacts 権限が必要です。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; SetCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, string provider, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; SetCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.SetCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.SetCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetCertificateIssuerWithHttpMessagesAsync&gt;d__80))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="issuerName">
            発行者の名前です。
            </param>
        <param name="provider">
            発行元プロバイダー。
            </param>
        <param name="credentials">
            発行者のための資格情報。
            </param>
        <param name="organizationDetails">
            発行元に提供される組織の詳細です。
            </param>
        <param name="attributes">
            発行元のオブジェクトの属性。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書の発行者を設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            SetCertificateIssuer 操作を追加または指定された証明書の発行者を更新します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; SetSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; SetSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.SetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.SetSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetSasDefinitionWithHttpMessagesAsync&gt;d__108))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="sasDefinitionName">
            SAS の定義の名前。
            </param>
        <param name="parameters">
            Sas 定義は、キー/値ペアの形式でのメタデータを作成します。
            </param>
        <param name="sasDefinitionAttributes">
            SAS の定義の属性です。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、指定されたストレージ アカウントに対して新しい SAS 定義を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; SetSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string value, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; SetSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string value, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.SetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.SetSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, value, tags, contentType, secretAttributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetSecretWithHttpMessagesAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="value">
            シークレットの値です。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="contentType">
            パスワードなどの秘密の値の型。
            </param>
        <param name="secretAttributes">
            シークレットの管理の属性です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された key vault のシークレットを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            設定操作では、Azure Key Vault にシークレットを追加します。 名前付きのシークレットが既に存在する場合、Azure Key Vault はシークレットの新しいバージョンを作成します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; SetStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; SetStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStorageAccountWithHttpMessagesAsync : string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.SetStorageAccountWithHttpMessagesAsync : string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.SetStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, resourceId, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetStorageAccountWithHttpMessagesAsync&gt;d__102))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Boolean" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="resourceId">
            ストレージ アカウントのリソース id です。
            </param>
        <param name="activeKeyName">
            現在アクティブなストレージ アカウント キーの名前。
            </param>
        <param name="autoRegenerateKey">
            かどうか keyvault はユーザー用のストレージ アカウントを管理する必要があります。
            </param>
        <param name="regenerationPeriod">
            キーの生成 ISO 8601 形式で指定されている期間。
            </param>
        <param name="storageAccountAttributes">
            ストレージ アカウントの属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、新しいストレージ アカウントを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="SignWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; SignWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; SignWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SignWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SignWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.SignWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.SignWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SignWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SignWithHttpMessagesAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            署名/検証アルゴリズムの識別子です。 可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。 使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキーを使用してダイジェストをから署名を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            サインイン操作は、非対称キーおよび対称キーをこの操作は、キーの秘密部分を使用するために、Azure Key Vault に格納されているに適用されます。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; UnwrapKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; UnwrapKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UnwrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UnwrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.UnwrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.UnwrapKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UnwrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UnwrapKeyWithHttpMessagesAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            アルゴリズムの識別子です。 使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            そのキーをラップするために使用された最初に指定したキーを使用して対称キーのラップを解除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            UNWRAP 操作は、対象キーの暗号化キーを使用して対称キーの復号化をサポートします。 この操作は、WRAP 操作の逆です。 UNWRAP 操作は、非対称キーおよび対称キー、キーの秘密部分を使用しているので、Azure Key Vault に格納されているに適用されます。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; UpdateCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, string provider = null, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; UpdateCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.UpdateCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateIssuerWithHttpMessagesAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="issuerName">
            発行者の名前です。
            </param>
        <param name="provider">
            発行元プロバイダー。
            </param>
        <param name="credentials">
            発行者のための資格情報。
            </param>
        <param name="organizationDetails">
            発行元に提供される組織の詳細です。
            </param>
        <param name="attributes">
            発行元のオブジェクトの属性。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書の発行者を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            UpdateCertificateIssuer 操作は、指定された証明書発行者のエンティティの更新プログラムを実行します。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; UpdateCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, bool cancellationRequested, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; UpdateCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, bool cancellationRequested, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Boolean,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateOperationWithHttpMessagesAsync : string * string * bool * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.UpdateCertificateOperationWithHttpMessagesAsync : string * string * bool * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, cancellationRequested, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Boolean,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateOperationWithHttpMessagesAsync&gt;d__91))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationRequested" Type="System.Boolean" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            証明書の名前。
            </param>
        <param name="cancellationRequested">
            証明書の操作のキャンセルが要求されたかどうかを示します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書の操作を更新します。 認証:、証明書/更新アクセス許可が必要です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificatePolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; UpdateCertificatePolicyWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; UpdateCertificatePolicyWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificatePolicyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;&#xA;override this.UpdateCertificatePolicyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;" Usage="keyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificatePolicy, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificatePolicyWithHttpMessagesAsync&gt;d__88))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            指定された資格情報コンテナー内の証明書の名前。
            </param>
        <param name="certificatePolicy">
            証明書のポリシーです。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            証明書のポリシーを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            証明書のポリシーで指定したメンバーを設定します。 Null として他のユーザーのままにします。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; UpdateCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string certificateVersion, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; UpdateCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string certificateVersion, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.UpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.UpdateCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificateVersion, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateWithHttpMessagesAsync&gt;d__89))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="certificateName">
            指定されたキー コンテナーに証明書の名前。
            </param>
        <param name="certificateVersion">
            証明書のバージョン。
            </param>
        <param name="certificatePolicy">
            証明書の管理ポリシー。
            </param>
        <param name="certificateAttributes">
            (省略可能) の証明書の属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定の証明書に関連付けられている指定された属性を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            UpdateCertificate 操作は指定された証明書の指定した更新プログラムを適用します。要素だけが更新中は、証明書の属性に注意してください。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; UpdateKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; UpdateKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.UpdateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.UpdateKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, keyOps, keyAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateKeyWithHttpMessagesAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            更新するキーの名前。
            </param>
        <param name="keyVersion">
            更新するキーのバージョン。
            </param>
        <param name="keyOps">
            Json web キー操作。 考えられるキーの操作の詳細については、JsonWebKeyOperation を参照してください。
            </param>
        <param name="keyAttributes"></param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            キー操作の変更の更新は、格納されたキーの属性を指定し、任意のキーの型と Azure Key Vault に格納されているキーのバージョンに適用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作を実行するために Key Vault にキーが既に存在しています。 注: キー自体の暗号化マテリアルは変更できません。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; UpdateSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; UpdateSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.UpdateSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateSasDefinitionWithHttpMessagesAsync&gt;d__109))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="sasDefinitionName">
            SAS の定義の名前。
            </param>
        <param name="parameters">
            Sas の定義は、キー/値ペアの形式でメタデータを更新します。
            </param>
        <param name="sasDefinitionAttributes">
            SAS の定義の属性です。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定の SAS 定義に関連付けられている指定された属性を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; UpdateSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string secretVersion, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; UpdateSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string secretVersion, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSecretWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.UpdateSecretWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.UpdateSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, secretVersion, contentType, secretAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateSecretWithHttpMessagesAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="secretName">
            シークレットの名前。
            </param>
        <param name="secretVersion">
            シークレットのバージョン。
            </param>
        <param name="contentType">
            パスワードなどの秘密の値の型。
            </param>
        <param name="secretAttributes">
            シークレットの管理の属性です。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたキー コンテナーに指定されたシークレットを使用して関連付けられている属性を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            更新操作は、既存の格納されているシークレットの指定された属性を変更します。 要求で指定されていない属性のまま変更されません。 シークレット自体の値は変更できません。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; UpdateStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string activeKeyName = null, Nullable&lt;bool&gt; autoRegenerateKey = null, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; UpdateStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string activeKeyName, valuetype System.Nullable`1&lt;bool&gt; autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateStorageAccountWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.UpdateStorageAccountWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.UpdateStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateStorageAccountWithHttpMessagesAsync&gt;d__103))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="storageAccountName">
            ストレージ アカウントの名前。
            </param>
        <param name="activeKeyName">
            現在アクティブなストレージ アカウント キー名。
            </param>
        <param name="autoRegenerateKey">
            かどうか keyvault はユーザー用のストレージ アカウントを管理する必要があります。
            </param>
        <param name="regenerationPeriod">
            キーの生成 ISO 8601 形式で指定されている期間。
            </param>
        <param name="storageAccountAttributes">
            ストレージ アカウントの属性。
            </param>
        <param name="tags">
            キー/値ペアの形式でのアプリケーション固有のメタデータ。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            特定のストレージ アカウントに関連付けられている指定された属性を更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="VerifyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt; VerifyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] digest, byte[] signature, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt; VerifyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] digest, unsigned int8[] signature, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyWithHttpMessagesAsync : string * string * string * string * byte[] * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;&#xA;override this.VerifyWithHttpMessagesAsync : string * string * string * string * byte[] * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;" Usage="keyVaultClient.VerifyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, digest, signature, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;VerifyWithHttpMessagesAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            署名/検証アルゴリズムです。 可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。 使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'
            </param>
        <param name="digest">
            ダイジェストの署名に使用します。
            </param>
        <param name="signature">
            検証対象の署名。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキーを使用して署名を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            検証処理は、Azure Key Vault に格納された対称キーを適用されます。 確認は不要な厳密にキーのパブリック部分を使用して署名の検証を実行できますが、この操作は、キー参照のみを持つ呼び出し元の便宜を図ってサポートので、Azure Key Vault に格納されている非対称キーのないと、キーのパブリックの部分です。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; WrapKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; WrapKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.WrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member WrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.WrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.WrapKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.WrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;WrapKeyWithHttpMessagesAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。
            </param>
        <param name="keyName">
            キー名。
            </param>
        <param name="keyVersion">
            キーのバージョン。
            </param>
        <param name="algorithm">
            アルゴリズムの識別子です。 使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したキーを使用して対称キーをラップします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            WRAP 操作では、以前、Azure Key Vault に格納されているキーの暗号化キーを使用して対称キーの暗号化をサポートします。 WRAP 操作は、キーの公開部分を使用して非対称キーで保護を実行できるので、Azure Key Vault に格納されている対称キーの厳密に必要だけです。 この操作は、キー参照であるが、パブリックのキー マテリアルにアクセスできない呼び出し元の便宜を図って非対称キーのサポートは。
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
        <return>
            応答本文および応答ヘッダーを含む応答オブジェクト。
            </return>
      </Docs>
    </Member>
  </Members>
</Type>