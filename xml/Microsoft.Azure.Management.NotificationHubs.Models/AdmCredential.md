<Type Name="AdmCredential" FullName="Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential">
  <TypeSignature Language="C#" Value="public class AdmCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdmCredential extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class AdmCredential" />
  <TypeSignature Language="F#" Value="type AdmCredential = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2e935-101">NotificationHub AdmCredential の説明です。</span><span class="sxs-lookup"><span data-stu-id="2e935-101">Description of a NotificationHub AdmCredential.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdmCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2e935-102">AdmCredential クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e935-102">Initializes a new instance of the AdmCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdmCredential (string clientId = null, string clientSecret = null, string authTokenUrl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string clientSecret, string authTokenUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientId As String = null, Optional clientSecret As String = null, Optional authTokenUrl As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential : string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential (clientId, clientSecret, authTokenUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="clientSecret" Type="System.String" />
        <Parameter Name="authTokenUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="2e935-103">The client identifier. (クライアント識別子。)</span><span class="sxs-lookup"><span data-stu-id="2e935-103">The client identifier.</span></span></param>
        <param name="clientSecret"><span data-ttu-id="2e935-104">資格情報シークレットのアクセス キー。</span><span class="sxs-lookup"><span data-stu-id="2e935-104">The credential secret access key.</span></span></param>
        <param name="authTokenUrl"><span data-ttu-id="2e935-105">認証トークンの URL です。</span><span class="sxs-lookup"><span data-stu-id="2e935-105">The URL of the authorization token.</span></span></param>
        <summary>
            <span data-ttu-id="2e935-106">AdmCredential クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e935-106">Initializes a new instance of the AdmCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthTokenUrl">
      <MemberSignature Language="C#" Value="public string AuthTokenUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthTokenUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential.AuthTokenUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthTokenUrl As String" />
      <MemberSignature Language="F#" Value="member this.AuthTokenUrl : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential.AuthTokenUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.authTokenUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e935-107">取得または認証トークンの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e935-107">Gets or sets the URL of the authorization token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e935-108">取得またはクライアントの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e935-108">Gets or sets the client identifier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientSecret">
      <MemberSignature Language="C#" Value="public string ClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential.ClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.ClientSecret : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.AdmCredential.ClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientSecret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e935-109">取得または資格情報シークレットのアクセス キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="2e935-109">Gets or sets the credential secret access key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>