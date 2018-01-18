<Type Name="ODataLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService">
  <TypeSignature Language="C#" Value="public class ODataLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ODataLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class ODataLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type ODataLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("OData")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="603eb-101">リンクされているデータ プロトコル (OData) サービスを開きます。</span><span class="sxs-lookup"><span data-stu-id="603eb-101">Open Data Protocol (OData) linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ODataLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="603eb-102"><see cref="T:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="603eb-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ODataLinkedService (string url, string authenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, string authenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String, authenticationType As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService (url, authenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url">To be added.</param>
        <param name="authenticationType">To be added.</param>
        <summary>
            <span data-ttu-id="603eb-103">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService" />必須の引数を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="603eb-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="603eb-104">必須。</span><span class="sxs-lookup"><span data-stu-id="603eb-104">Required.</span></span> <span data-ttu-id="603eb-105">OData サービスへの接続に使用する認証の種類です。</span><span class="sxs-lookup"><span data-stu-id="603eb-105">Type of authentication used to connect to the OData service.</span></span> <span data-ttu-id="603eb-106">いずれかを指定する必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.ODataAuthenticationType" />です。</span><span class="sxs-lookup"><span data-stu-id="603eb-106">Must be one of <see cref="T:Microsoft.Azure.Management.DataFactories.Models.ODataAuthenticationType" />.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizedCredential">
      <MemberSignature Language="C#" Value="public string AuthorizedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.AuthorizedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizedCredential As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizedCredential : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.AuthorizedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="603eb-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="603eb-107">Optional.</span></span> <span data-ttu-id="603eb-108">OAuth では、あなたの代理としてのリソースにアクセスする ADF で使用できる資格情報を承認します。</span><span class="sxs-lookup"><span data-stu-id="603eb-108">The OAuth authorized credential that may be used by ADF to access resources on your behalf.</span></span> <span data-ttu-id="603eb-109">各認証には一意を一度だけ使用することがあります。</span><span class="sxs-lookup"><span data-stu-id="603eb-109">Each authorization is unique and may only be used once.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public string EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As String" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="603eb-110">省略可能。</span><span class="sxs-lookup"><span data-stu-id="603eb-110">Optional.</span></span> <span data-ttu-id="603eb-111">Windows 認証の暗号化された資格情報です。</span><span class="sxs-lookup"><span data-stu-id="603eb-111">The encrypted credential for Windows authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayName">
      <MemberSignature Language="C#" Value="public string GatewayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.GatewayName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayName As String" />
      <MemberSignature Language="F#" Value="member this.GatewayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.GatewayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="603eb-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="603eb-112">Optional.</span></span> <span data-ttu-id="603eb-113">Windows 認証の内部設置型ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="603eb-113">The on-premises gateway name for Windows authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="603eb-114">省略可能。</span><span class="sxs-lookup"><span data-stu-id="603eb-114">Optional.</span></span> <span data-ttu-id="603eb-115">OData サービスのパスワードです。</span><span class="sxs-lookup"><span data-stu-id="603eb-115">Password of the OData service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="603eb-116">必須。</span><span class="sxs-lookup"><span data-stu-id="603eb-116">Required.</span></span> <span data-ttu-id="603eb-117">OData サービスのサービス ルート URL です。</span><span class="sxs-lookup"><span data-stu-id="603eb-117">Service root URL of the OData service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.ODataLinkedService.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="603eb-118">省略可能。</span><span class="sxs-lookup"><span data-stu-id="603eb-118">Optional.</span></span> <span data-ttu-id="603eb-119">OData サービスのユーザー名。</span><span class="sxs-lookup"><span data-stu-id="603eb-119">User name of the OData service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>