<Type Name="WebClientCertificateAuthentication" FullName="Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication">
  <TypeSignature Language="C#" Value="public class WebClientCertificateAuthentication : Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebClientCertificateAuthentication extends Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication" />
  <TypeSignature Language="VB.NET" Value="Public Class WebClientCertificateAuthentication&#xA;Inherits WebLinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type WebClientCertificateAuthentication = class&#xA;    inherit WebLinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("ClientCertificate")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="32c0f-101">クライアント証明書を使用する WebLinkedService ベースの HTTP エンドポイントとの通信を認証します。</span><span class="sxs-lookup"><span data-stu-id="32c0f-101">A WebLinkedService that uses client certificate based authentication to communicate with an HTTP endpoint.</span></span> <span data-ttu-id="32c0f-102">このスキームに依存して相互認証です。サーバーでは、クライアントに有効な資格情報も提供する必要があります。</span><span class="sxs-lookup"><span data-stu-id="32c0f-102">This scheme follows mutual authentication; the server must also provide valid credentials to the client.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebClientCertificateAuthentication ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.#ctor" />
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
            <span data-ttu-id="32c0f-103">WebClientCertificateAuthentication クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="32c0f-103">Initializes a new instance of the WebClientCertificateAuthentication class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebClientCertificateAuthentication (object url, Microsoft.Azure.Management.DataFactory.Models.SecureString pfx, Microsoft.Azure.Management.DataFactory.Models.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object url, class Microsoft.Azure.Management.DataFactory.Models.SecureString pfx, class Microsoft.Azure.Management.DataFactory.Models.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.#ctor(System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,Microsoft.Azure.Management.DataFactory.Models.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As Object, pfx As SecureString, password As SecureString)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication : obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * Microsoft.Azure.Management.DataFactory.Models.SecureString -&gt; Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication" Usage="new Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication (url, pfx, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.Object" />
        <Parameter Name="pfx" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="32c0f-104">例: http://www.microsoft.com、web サービス エンドポイントの URL です。</span><span class="sxs-lookup"><span data-stu-id="32c0f-104">The URL of the web service endpoint, e.g. http://www.microsoft.com .</span></span> <span data-ttu-id="32c0f-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="32c0f-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="pfx"><span data-ttu-id="32c0f-106">PFX ファイルの Base64 でエンコードされた内容。</span><span class="sxs-lookup"><span data-stu-id="32c0f-106">Base64-encoded contents of a PFX file.</span></span></param>
        <param name="password"><span data-ttu-id="32c0f-107">PFX ファイルのパスワードです。</span><span class="sxs-lookup"><span data-stu-id="32c0f-107">Password for the PFX file.</span></span></param>
        <summary>
            <span data-ttu-id="32c0f-108">WebClientCertificateAuthentication クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="32c0f-108">Initializes a new instance of the WebClientCertificateAuthentication class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="32c0f-109">取得または PFX ファイルのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="32c0f-109">Gets or sets password for the PFX file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pfx">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Pfx { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Pfx" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Pfx" />
      <MemberSignature Language="VB.NET" Value="Public Property Pfx As SecureString" />
      <MemberSignature Language="F#" Value="member this.Pfx : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Pfx" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pfx")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="32c0f-110">取得または PFX ファイルの base64 でエンコードされた内容を設定します。</span><span class="sxs-lookup"><span data-stu-id="32c0f-110">Gets or sets base64-encoded contents of a PFX file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebClientCertificateAuthentication.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="webClientCertificateAuthentication.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="32c0f-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="32c0f-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="32c0f-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="32c0f-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>