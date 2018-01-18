<Type Name="IntegrationRuntimeConnectionInfo" FullName="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo">
  <TypeSignature Language="C#" Value="public class IntegrationRuntimeConnectionInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IntegrationRuntimeConnectionInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class IntegrationRuntimeConnectionInfo" />
  <TypeSignature Language="F#" Value="type IntegrationRuntimeConnectionInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cc9c4-101">内部設置型データを暗号化するための接続情報はソースの資格情報です。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-101">Connection information for encrypting the on-premises data source credentials.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeConnectionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cc9c4-102">IntegrationRuntimeConnectionInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-102">Initializes a new instance of the IntegrationRuntimeConnectionInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IntegrationRuntimeConnectionInfo (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string serviceToken = null, string identityCertThumbprint = null, string hostServiceUri = null, string version = null, string publicKey = null, Nullable&lt;bool&gt; isIdentityCertExprired = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string serviceToken, string identityCertThumbprint, string hostServiceUri, string version, string publicKey, valuetype System.Nullable`1&lt;bool&gt; isIdentityCertExprired) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional serviceToken As String = null, Optional identityCertThumbprint As String = null, Optional hostServiceUri As String = null, Optional version As String = null, Optional publicKey As String = null, Optional isIdentityCertExprired As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo" Usage="new Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo (additionalProperties, serviceToken, identityCertThumbprint, hostServiceUri, version, publicKey, isIdentityCertExprired)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="serviceToken" Type="System.String" />
        <Parameter Name="identityCertThumbprint" Type="System.String" />
        <Parameter Name="hostServiceUri" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="publicKey" Type="System.String" />
        <Parameter Name="isIdentityCertExprired" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="cc9c4-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="cc9c4-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="serviceToken"><span data-ttu-id="cc9c4-104">サービスで生成されたトークン。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-104">The token generated in service.</span></span> <span data-ttu-id="cc9c4-105">呼び出し元は、統合ランタイムへの認証にこのトークンを使用します。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-105">Callers use this token to authenticate to integration runtime.</span></span></param>
        <param name="identityCertThumbprint"><span data-ttu-id="cc9c4-106">統合ランタイム SSL 証明書の拇印。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-106">The integration runtime SSL certificate thumbprint.</span></span> <span data-ttu-id="cc9c4-107">をクリックして-アプリケーションを使用して、サーバー検証を行うとします。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-107">Click-Once application uses it to do server validation.</span></span></param>
        <param name="hostServiceUri"><span data-ttu-id="cc9c4-108">内部設置型の統合ランタイム ホスト URL。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-108">The on-premises integration runtime host URL.</span></span></param>
        <param name="version"><span data-ttu-id="cc9c4-109">統合ランタイムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-109">The integration runtime version.</span></span></param>
        <param name="publicKey"><span data-ttu-id="cc9c4-110">資格情報を統合ランタイムに転送するときに、資格情報を暗号化するための公開キー。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-110">The public key for encrypting a credential when transferring the credential to the integration runtime.</span></span></param>
        <param name="isIdentityCertExprired"><span data-ttu-id="cc9c4-111">Id 証明書が有効期限が切れているかどうか。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-111">Whether the identity certificate is expired.</span></span></param>
        <summary>
            <span data-ttu-id="cc9c4-112">IntegrationRuntimeConnectionInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-112">Initializes a new instance of the IntegrationRuntimeConnectionInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc9c4-113">メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化</span><span class="sxs-lookup"><span data-stu-id="cc9c4-113">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostServiceUri">
      <MemberSignature Language="C#" Value="public string HostServiceUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostServiceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.HostServiceUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostServiceUri As String" />
      <MemberSignature Language="F#" Value="member this.HostServiceUri : string" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.HostServiceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hostServiceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc9c4-114">内部設置型の統合ランタイム ホスト URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-114">Gets the on-premises integration runtime host URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdentityCertThumbprint">
      <MemberSignature Language="C#" Value="public string IdentityCertThumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IdentityCertThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.IdentityCertThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IdentityCertThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.IdentityCertThumbprint : string" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.IdentityCertThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identityCertThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc9c4-115">統合ランタイムの SSL 証明書の拇印を取得します。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-115">Gets the integration runtime SSL certificate thumbprint.</span></span> <span data-ttu-id="cc9c4-116">をクリックして-アプリケーションを使用して、サーバー検証を行うとします。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-116">Click-Once application uses it to do server validation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsIdentityCertExprired">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsIdentityCertExprired { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsIdentityCertExprired" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.IsIdentityCertExprired" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsIdentityCertExprired As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsIdentityCertExprired : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.IsIdentityCertExprired" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isIdentityCertExprired")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc9c4-117">Id 証明書の有効期限が切れているかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-117">Gets whether the identity certificate is expired.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicKey">
      <MemberSignature Language="C#" Value="public string PublicKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.PublicKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicKey As String" />
      <MemberSignature Language="F#" Value="member this.PublicKey : string" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.PublicKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publicKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc9c4-118">資格情報を統合ランタイムに転送するときに、資格情報を暗号化するための公開キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-118">Gets the public key for encrypting a credential when transferring the credential to the integration runtime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceToken">
      <MemberSignature Language="C#" Value="public string ServiceToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.ServiceToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceToken As String" />
      <MemberSignature Language="F#" Value="member this.ServiceToken : string" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.ServiceToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc9c4-119">サービスで生成されたトークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-119">Gets the token generated in service.</span></span> <span data-ttu-id="cc9c4-120">呼び出し元は、統合ランタイムへの認証にこのトークンを使用します。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-120">Callers use this token to authenticate to integration runtime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string" Usage="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeConnectionInfo.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cc9c4-121">統合ランタイムのバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="cc9c4-121">Gets the integration runtime version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>