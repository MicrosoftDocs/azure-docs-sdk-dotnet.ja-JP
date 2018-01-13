<Type Name="KeyVaultManagementClient" FullName="Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient">
  <TypeSignature Language="C#" Value="public class KeyVaultManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient&gt;, IDisposable, Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient&gt; implements class Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultManagementClient&#xA;Inherits ServiceClient(Of KeyVaultManagementClient)&#xA;Implements IAzureClient, IDisposable, IKeyVaultManagementClient" />
  <TypeSignature Language="F#" Value="type KeyVaultManagementClient = class&#xA;    inherit ServiceClient&lt;KeyVaultManagementClient&gt;&#xA;    interface IKeyVaultManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManagementClient</InterfaceName>
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
            Azure 管理 API は、Azure Key Vault とやり取りする web サービスの RESTful セットを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            KeyVaultManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            KeyVaultManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            KeyVaultManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            省略可能。 サービスのベース URI。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            KeyVaultManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            KeyVaultManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
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
        <param name="baseUri">
            省略可能。 サービスのベース URI。
            </param>
        <param name="credentials">
            必須。 Azure に接続するクライアントに必要な資格情報です。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            KeyVaultManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
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
        <param name="baseUri">
            省略可能。 サービスのベース URI。
            </param>
        <param name="rootHandler">
            省略可能。 Http トランスポートを処理するために使用する http クライアント ハンドラー。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            KeyVaultManagementClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient" Usage="new Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
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
        <param name="baseUri">
            省略可能。 サービスのベース URI。
            </param>
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
            KeyVaultManagementClient クラスの新しいインスタンスを初期化します。
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービスのベース URI。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManagementClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報を取得します。 サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Vaults">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations Vaults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations Vaults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.Vaults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Vaults As IVaultsOperations" />
      <MemberSignature Language="F#" Value="member this.Vaults : Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations" Usage="Microsoft.Azure.Management.KeyVault.Fluent.KeyVaultManagementClient.Vaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.IVaultsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IVaultsOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>