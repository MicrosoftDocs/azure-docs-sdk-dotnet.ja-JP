<Type Name="OnPremisesOdbcLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService">
  <TypeSignature Language="C#" Value="public class OnPremisesOdbcLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OnPremisesOdbcLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class OnPremisesOdbcLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type OnPremisesOdbcLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("OnPremisesOdbc")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="75929-101">オープン データベース コネクティビティ (ODBC) データ ソースのリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="75929-101">Linked Service for Open Database Connectivity (ODBC) data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OnPremisesOdbcLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OnPremisesOdbcLinkedService (string gatewayName, string connectionString, string authenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string gatewayName, string connectionString, string authenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (gatewayName As String, connectionString As String, authenticationType As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService : string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService (gatewayName, connectionString, authenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="gatewayName">To be added.</param>
        <param name="connectionString">To be added.</param>
        <param name="authenticationType">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.AuthenticationType" />
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
            <span data-ttu-id="75929-102">必須。</span><span class="sxs-lookup"><span data-stu-id="75929-102">Required.</span></span> <span data-ttu-id="75929-103">ODBC データ ストアへの接続に使用される認証の種類です。</span><span class="sxs-lookup"><span data-stu-id="75929-103">Type of authentication used to connect to the ODBC data store.</span></span> <span data-ttu-id="75929-104">Anonymous と Basic のいずれかの値になります。</span><span class="sxs-lookup"><span data-stu-id="75929-104">Possible values are: Anonymous and Basic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.ConnectionString" />
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
            <span data-ttu-id="75929-105">必須。</span><span class="sxs-lookup"><span data-stu-id="75929-105">Required.</span></span> <span data-ttu-id="75929-106">接続文字列と同様の省略可能な非アクセス資格情報の部分がなど、資格情報を暗号化"ドライバー {Sqlserver} を = です。サーバー = myserver; Database = mydb です。EncryptedCredential myencryptedcredential を ="です。</span><span class="sxs-lookup"><span data-stu-id="75929-106">The non-access credential portion of the connection string as well as an optional encrypted credential, e.g. "Driver={SQL Server};Server=myserver;Database=mydb;EncryptedCredential=myencryptedcredential".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credential">
      <MemberSignature Language="C#" Value="public string Credential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Credential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.Credential" />
      <MemberSignature Language="VB.NET" Value="Public Property Credential As String" />
      <MemberSignature Language="F#" Value="member this.Credential : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.Credential" />
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
            <span data-ttu-id="75929-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="75929-107">Optional.</span></span> <span data-ttu-id="75929-108">例: ドライバー固有のプロパティと値の形式で指定された接続文字列のアクセス資格情報の部分"Uid someusername; を =Pwd = somepassword です。RefreshToken = mytoken;"です。</span><span class="sxs-lookup"><span data-stu-id="75929-108">The access credential portion of the connection string specified in driver-specific property-value format, e.g. “Uid=someusername;Pwd=somepassword;RefreshToken=mytoken;”.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayName">
      <MemberSignature Language="C#" Value="public string GatewayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.GatewayName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayName As String" />
      <MemberSignature Language="F#" Value="member this.GatewayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.GatewayName" />
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
            <span data-ttu-id="75929-109">必須。</span><span class="sxs-lookup"><span data-stu-id="75929-109">Required.</span></span> <span data-ttu-id="75929-110">オンプレミス ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="75929-110">The on-premises gateway name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.Password" />
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
            <span data-ttu-id="75929-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="75929-111">Optional.</span></span> <span data-ttu-id="75929-112">基本認証または Windows 認証のパスワードです。</span><span class="sxs-lookup"><span data-stu-id="75929-112">Password for Basic or Windows authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesOdbcLinkedService.Username" />
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
            <span data-ttu-id="75929-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="75929-113">Optional.</span></span> <span data-ttu-id="75929-114">基本認証または Windows 認証のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="75929-114">User name for Basic or Windows authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>