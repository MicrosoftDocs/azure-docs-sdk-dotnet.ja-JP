<Type Name="OperationalInsightsDataClient" FullName="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient">
  <TypeSignature Language="C#" Value="public class OperationalInsightsDataClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient&gt;, IDisposable, Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationalInsightsDataClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient&gt; implements class Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationalInsightsDataClient&#xA;Inherits ServiceClient(Of OperationalInsightsDataClient)&#xA;Implements IDisposable, IOperationalInsightsDataClient" />
  <TypeSignature Language="F#" Value="type OperationalInsightsDataClient = class&#xA;    inherit ServiceClient&lt;OperationalInsightsDataClient&gt;&#xA;    interface IOperationalInsightsDataClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>0.9.0.1</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Operational Insights データ クライアント
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationalInsightsDataClient (Microsoft.Rest.ServiceClientCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(Microsoft.Rest.ServiceClientCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Microsoft.Rest.ServiceClientCredentials -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient credentials" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">
            必須。 クライアント サブスクリプションを一意に識別するサブスクリプション資格情報。
            </param>
        <summary>
            OperationalInsightsDataClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OperationalInsightsDataClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            OperationalInsightsDataClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationalInsightsDataClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            必須。 クライアント サブスクリプションを一意に識別するサブスクリプション資格情報。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            OperationalInsightsDataClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OperationalInsightsDataClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            OperationalInsightsDataClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OperationalInsightsDataClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            OperationalInsightsDataClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationalInsightsDataClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            必須。 クライアント サブスクリプションを一意に識別するサブスクリプション資格情報。
            </param>
        <param name="rootHandler">
            省略可能。 Http トランスポートを処理するために使用する http クライアント ハンドラー。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            OperationalInsightsDataClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationalInsightsDataClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (baseUri, credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            必須。 クライアント サブスクリプションを一意に識別するサブスクリプション資格情報。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            OperationalInsightsDataClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected OperationalInsightsDataClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            OperationalInsightsDataClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationalInsightsDataClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient" Usage="new Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient (baseUri, credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
            必須。 クライアント サブスクリプションを一意に識別するサブスクリプション資格情報。
            </param>
        <param name="rootHandler">
            省略可能。 Http トランスポートを処理するために使用する http クライアント ハンドラー。
            </param>
        <param name="handlers">
            省略可能。 Http クライアント パイプラインに追加するデリゲート ハンドラー。
            </param>
        <summary>
            OperationalInsightsDataClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AdditionalWorkspaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AdditionalWorkspaces { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AdditionalWorkspaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.AdditionalWorkspaces" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalWorkspaces As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AdditionalWorkspaces : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.AdditionalWorkspaces" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.AdditionalWorkspaces</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リソースの間のクエリで参照されているその他のワークスペース。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアント サブスクリプションを一意に識別するサブスクリプション資格情報。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
    <Member MemberName="NameHeader">
      <MemberSignature Language="C#" Value="public string NameHeader { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NameHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.NameHeader" />
      <MemberSignature Language="VB.NET" Value="Public Property NameHeader As String" />
      <MemberSignature Language="F#" Value="member this.NameHeader : string with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.NameHeader" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.NameHeader</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            呼び出し元のアプリケーションの一意の名前。 これは、製品利用統計情報およびデバッグのためにのみ使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preferences">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.OperationalInsights.Models.ApiPreferences Preferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.OperationalInsights.Models.ApiPreferences Preferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.Preferences" />
      <MemberSignature Language="VB.NET" Value="Public Property Preferences As ApiPreferences" />
      <MemberSignature Language="F#" Value="member this.Preferences : Microsoft.Azure.OperationalInsights.Models.ApiPreferences with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.Preferences" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.Preferences</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.OperationalInsights.Models.ApiPreferences</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            環境設定をクエリします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt; QueryWithHttpMessagesAsync (string query, Nullable&lt;TimeSpan&gt; timespan = null, System.Collections.Generic.IList&lt;string&gt; workspaces = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.HttpOperationResponse`1&lt;class Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt; QueryWithHttpMessagesAsync(string query, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timespan, class System.Collections.Generic.IList`1&lt;string&gt; workspaces, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.QueryWithHttpMessagesAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member QueryWithHttpMessagesAsync : string * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt;&#xA;override this.QueryWithHttpMessagesAsync : string * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt;" Usage="operationalInsightsDataClient.QueryWithHttpMessagesAsync (query, timespan, workspaces, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.QueryWithHttpMessagesAsync(System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient/&lt;QueryWithHttpMessagesAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.HttpOperationResponse&lt;Microsoft.Azure.OperationalInsights.Models.QueryResults&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="timespan" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="workspaces" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query">
            クエリを実行します。
            </param>
        <param name="timespan">
            省略可能。 データをクエリする timespan です。 これは、ISO8601 時間、期間の値です。  この期間が他にも、クエリ式で指定されている、適用されます。
            </param>
        <param name="workspaces">
            クエリに含まれているワークスペースの一覧です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            分析クエリを実行します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            データ、分析クエリを実行します。
            [ここで](/documentation/2-Using-the-API/Query)分析クエリを POST を使用する例を示します。
            </remarks>
        <exception cref="T:Microsoft.Azure.OperationalInsights.Models.ErrorResponseException">
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
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public string RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As String" />
      <MemberSignature Language="F#" Value="member this.RequestId : string with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.RequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.RequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            要求ごとの一意の ID。 これはする要求ごとに生成された場合は指定されていません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
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
    <Member MemberName="WorkspaceId">
      <MemberSignature Language="C#" Value="public string WorkspaceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkspaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.WorkspaceId" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkspaceId As String" />
      <MemberSignature Language="F#" Value="member this.WorkspaceId : string with get, set" Usage="Microsoft.Azure.OperationalInsights.OperationalInsightsDataClient.WorkspaceId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.OperationalInsights.IOperationalInsightsDataClient.WorkspaceId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>0.9.0.1</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ワークスペースの ID です。 これは、ワークスペース ID が Azure ポータルで、プロパティ ブレードからです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>