<Type Name="AmazonRedshiftLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService">
  <TypeSignature Language="C#" Value="public class AmazonRedshiftLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AmazonRedshiftLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AmazonRedshiftLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type AmazonRedshiftLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AmazonRedshift")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="59b2a-101">Amazon Redshift コネクタのリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="59b2a-101">Linked service for Amazon Redshift connector.</span></span>
            <span data-ttu-id="59b2a-102">Amazon Redshift は、完全に管理されたペタバイト スケール データ ウェアハウス サービス、Amazon Web Services クラウド プラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="59b2a-102">Amazon Redshift is a fully managed, petabyte-scale data warehouse service for the Amazon Web Services cloud platform.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonRedshiftLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="59b2a-103"><see cref="T:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="59b2a-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonRedshiftLinkedService (string server, string username, string password, string database);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string server, string username, string password, string database) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (server As String, username As String, password As String, database As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService : string * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService (server, username, password, database)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="server" Type="System.String" />
        <Parameter Name="username" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="database" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="server">To be added.</param>
        <param name="username">To be added.</param>
        <param name="password">To be added.</param>
        <param name="database">To be added.</param>
        <summary>
            <span data-ttu-id="59b2a-104">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService" />必須の引数を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="59b2a-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Database">
      <MemberSignature Language="C#" Value="public string Database { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Database" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.Database" />
      <MemberSignature Language="VB.NET" Value="Public Property Database As String" />
      <MemberSignature Language="F#" Value="member this.Database : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.Database" />
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
            <span data-ttu-id="59b2a-105">必須。</span><span class="sxs-lookup"><span data-stu-id="59b2a-105">Required.</span></span> <span data-ttu-id="59b2a-106">Amazon Redshift サーバーのデータベース名。</span><span class="sxs-lookup"><span data-stu-id="59b2a-106">The database name of the Amazon Redshift server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.Password" />
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
            <span data-ttu-id="59b2a-107">必須。</span><span class="sxs-lookup"><span data-stu-id="59b2a-107">Required.</span></span> <span data-ttu-id="59b2a-108">Amazon Redshift サーバーのパスワードです。</span><span class="sxs-lookup"><span data-stu-id="59b2a-108">The password of the Amazon Redshift server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59b2a-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="59b2a-109">Optional.</span></span> <span data-ttu-id="59b2a-110">Amazon Redshift サーバーがクライアント接続をリッスンするように使用する TCP ポート番号。</span><span class="sxs-lookup"><span data-stu-id="59b2a-110">The TCP port number that the Amazon Redshift server uses to listen for client connections.</span></span> <span data-ttu-id="59b2a-111">既定値は、5439 です。</span><span class="sxs-lookup"><span data-stu-id="59b2a-111">The default value is 5439.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Server">
      <MemberSignature Language="C#" Value="public string Server { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Server" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.Server" />
      <MemberSignature Language="VB.NET" Value="Public Property Server As String" />
      <MemberSignature Language="F#" Value="member this.Server : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.Server" />
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
            <span data-ttu-id="59b2a-112">必須。</span><span class="sxs-lookup"><span data-stu-id="59b2a-112">Required.</span></span> <span data-ttu-id="59b2a-113">Amazon Redshift サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="59b2a-113">The name of the Amazon Redshift server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AmazonRedshiftLinkedService.Username" />
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
            <span data-ttu-id="59b2a-114">必須。</span><span class="sxs-lookup"><span data-stu-id="59b2a-114">Required.</span></span> <span data-ttu-id="59b2a-115">Amazon Redshift サーバーのユーザー名。</span><span class="sxs-lookup"><span data-stu-id="59b2a-115">The username of the Amazon Redshift server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>