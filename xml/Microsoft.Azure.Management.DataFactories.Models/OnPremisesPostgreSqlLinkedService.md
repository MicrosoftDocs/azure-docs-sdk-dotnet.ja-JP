<Type Name="OnPremisesPostgreSqlLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService">
  <TypeSignature Language="C#" Value="public class OnPremisesPostgreSqlLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OnPremisesPostgreSqlLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class OnPremisesPostgreSqlLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type OnPremisesPostgreSqlLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("OnPremisesPostgreSql")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e6de0-101">PostgreSql データ ソースのリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="e6de0-101">Linked Service for PostgreSql data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OnPremisesPostgreSqlLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.#ctor" />
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
      <MemberSignature Language="C#" Value="public OnPremisesPostgreSqlLinkedService (string gatewayName, string server, string database, string authenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string gatewayName, string server, string database, string authenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (gatewayName As String, server As String, database As String, authenticationType As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService : string * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService (gatewayName, server, database, authenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="server" Type="System.String" />
        <Parameter Name="database" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="gatewayName">To be added.</param>
        <param name="server">To be added.</param>
        <param name="database">To be added.</param>
        <param name="authenticationType">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.AuthenticationType" />
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
            <span data-ttu-id="e6de0-102">必須。</span><span class="sxs-lookup"><span data-stu-id="e6de0-102">Required.</span></span> <span data-ttu-id="e6de0-103">接続に使用される AuthenticationType。</span><span class="sxs-lookup"><span data-stu-id="e6de0-103">AuthenticationType to be used for connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Database">
      <MemberSignature Language="C#" Value="public string Database { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Database" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.Database" />
      <MemberSignature Language="VB.NET" Value="Public Property Database As String" />
      <MemberSignature Language="F#" Value="member this.Database : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.Database" />
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
            <span data-ttu-id="e6de0-104">必須。</span><span class="sxs-lookup"><span data-stu-id="e6de0-104">Required.</span></span> <span data-ttu-id="e6de0-105">接続のデータベース名。</span><span class="sxs-lookup"><span data-stu-id="e6de0-105">Database name for connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public string EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As String" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="e6de0-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="e6de0-106">Optional.</span></span> <span data-ttu-id="e6de0-107">認証の暗号化された資格情報です。</span><span class="sxs-lookup"><span data-stu-id="e6de0-107">The encrypted credential for authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayName">
      <MemberSignature Language="C#" Value="public string GatewayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.GatewayName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayName As String" />
      <MemberSignature Language="F#" Value="member this.GatewayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.GatewayName" />
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
            <span data-ttu-id="e6de0-108">必須。</span><span class="sxs-lookup"><span data-stu-id="e6de0-108">Required.</span></span> <span data-ttu-id="e6de0-109">オンプレミス ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="e6de0-109">The on-premises gateway name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.Password" />
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
            <span data-ttu-id="e6de0-110">省略可能。</span><span class="sxs-lookup"><span data-stu-id="e6de0-110">Optional.</span></span> <span data-ttu-id="e6de0-111">認証のパスワードです。</span><span class="sxs-lookup"><span data-stu-id="e6de0-111">Password for authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schema">
      <MemberSignature Language="C#" Value="public string Schema { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Schema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.Schema" />
      <MemberSignature Language="VB.NET" Value="Public Property Schema As String" />
      <MemberSignature Language="F#" Value="member this.Schema : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.Schema" />
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
            <span data-ttu-id="e6de0-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="e6de0-112">Optional.</span></span> <span data-ttu-id="e6de0-113">接続のスキーマ名。</span><span class="sxs-lookup"><span data-stu-id="e6de0-113">Schema name for connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Server">
      <MemberSignature Language="C#" Value="public string Server { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Server" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.Server" />
      <MemberSignature Language="VB.NET" Value="Public Property Server As String" />
      <MemberSignature Language="F#" Value="member this.Server : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.Server" />
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
            <span data-ttu-id="e6de0-114">必須。</span><span class="sxs-lookup"><span data-stu-id="e6de0-114">Required.</span></span> <span data-ttu-id="e6de0-115">接続のサーバー名。</span><span class="sxs-lookup"><span data-stu-id="e6de0-115">Server name for connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OnPremisesPostgreSqlLinkedService.Username" />
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
            <span data-ttu-id="e6de0-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="e6de0-116">Optional.</span></span> <span data-ttu-id="e6de0-117">認証のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="e6de0-117">Username for authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>