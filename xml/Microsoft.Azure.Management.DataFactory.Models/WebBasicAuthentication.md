<Type Name="WebBasicAuthentication" FullName="Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication">
  <TypeSignature Language="C#" Value="public class WebBasicAuthentication : Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebBasicAuthentication extends Microsoft.Azure.Management.DataFactory.Models.WebLinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication" />
  <TypeSignature Language="VB.NET" Value="Public Class WebBasicAuthentication&#xA;Inherits WebLinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type WebBasicAuthentication = class&#xA;    inherit WebLinkedServiceTypeProperties" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Basic")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="90b43-101">基本認証を使用して HTTP エンドポイントと通信 WebLinkedService です。</span><span class="sxs-lookup"><span data-stu-id="90b43-101">A WebLinkedService that uses basic authentication to communicate with an HTTP endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebBasicAuthentication ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.#ctor" />
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
            <span data-ttu-id="90b43-102">WebBasicAuthentication クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="90b43-102">Initializes a new instance of the WebBasicAuthentication class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebBasicAuthentication (object url, object username, Microsoft.Azure.Management.DataFactory.Models.SecureString password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object url, object username, class Microsoft.Azure.Management.DataFactory.Models.SecureString password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.#ctor(System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As Object, username As Object, password As SecureString)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication : obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString -&gt; Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication" Usage="new Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication (url, username, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.Object" />
        <Parameter Name="username" Type="System.Object" />
        <Parameter Name="password" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="90b43-103">例: http://www.microsoft.com、web サービス エンドポイントの URL です。</span><span class="sxs-lookup"><span data-stu-id="90b43-103">The URL of the web service endpoint, e.g. http://www.microsoft.com .</span></span> <span data-ttu-id="90b43-104">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="90b43-104">Type: string (or Expression with resultType string).</span></span></param>
        <param name="username"><span data-ttu-id="90b43-105">基本認証のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="90b43-105">User name for Basic authentication.</span></span> <span data-ttu-id="90b43-106">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="90b43-106">Type: string (or Expression with resultType string).</span></span></param>
        <param name="password"><span data-ttu-id="90b43-107">基本認証のパスワード。</span><span class="sxs-lookup"><span data-stu-id="90b43-107">The password for Basic authentication.</span></span></param>
        <summary>
            <span data-ttu-id="90b43-108">WebBasicAuthentication クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="90b43-108">Initializes a new instance of the WebBasicAuthentication class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As SecureString" />
      <MemberSignature Language="F#" Value="member this.Password : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.Password" />
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
            <span data-ttu-id="90b43-109">取得または基本認証のパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="90b43-109">Gets or sets the password for Basic authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public object Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As Object" />
      <MemberSignature Language="F#" Value="member this.Username : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="90b43-110">取得または基本認証のユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="90b43-110">Gets or sets user name for Basic authentication.</span></span> <span data-ttu-id="90b43-111">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="90b43-111">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.WebBasicAuthentication.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="webBasicAuthentication.Validate " />
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
            <span data-ttu-id="90b43-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="90b43-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="90b43-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="90b43-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>