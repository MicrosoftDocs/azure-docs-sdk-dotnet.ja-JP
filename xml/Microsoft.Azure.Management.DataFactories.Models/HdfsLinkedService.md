<Type Name="HdfsLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService">
  <TypeSignature Language="C#" Value="public class HdfsLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HdfsLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class HdfsLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type HdfsLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("Hdfs")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="0de9e-101">Hadoop 分散ファイル システム (HDFS) のデータ ソースのリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="0de9e-101">Linked Service for Hadoop Distributed File System (HDFS) data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HdfsLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.#ctor" />
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
      <MemberSignature Language="C#" Value="public HdfsLinkedService (string gatewayName, string url, string authenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string gatewayName, string url, string authenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (gatewayName As String, url As String, authenticationType As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService : string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService (gatewayName, url, authenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="gatewayName">To be added.</param>
        <param name="url">To be added.</param>
        <param name="authenticationType">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.AuthenticationType" />
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
            <span data-ttu-id="0de9e-102">必須。</span><span class="sxs-lookup"><span data-stu-id="0de9e-102">Required.</span></span> <span data-ttu-id="0de9e-103">HDFS への接続に使用される認証の種類です。</span><span class="sxs-lookup"><span data-stu-id="0de9e-103">Type of authentication used to connect to the HDFS.</span></span> <span data-ttu-id="0de9e-104">有効値は、: 匿名と Windows です。</span><span class="sxs-lookup"><span data-stu-id="0de9e-104">Possible values are: Anonymous, and Windows.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public string EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As String" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.EncryptedCredential" />
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
            <span data-ttu-id="0de9e-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0de9e-105">Optional.</span></span> <span data-ttu-id="0de9e-106">Windows 認証の暗号化された資格情報です。</span><span class="sxs-lookup"><span data-stu-id="0de9e-106">The encrypted credential for Windows authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayName">
      <MemberSignature Language="C#" Value="public string GatewayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.GatewayName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayName As String" />
      <MemberSignature Language="F#" Value="member this.GatewayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.GatewayName" />
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
            <span data-ttu-id="0de9e-107">必須。</span><span class="sxs-lookup"><span data-stu-id="0de9e-107">Required.</span></span> <span data-ttu-id="0de9e-108">オンプレミス ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="0de9e-108">The on-premises gateway name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.Password" />
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
            <span data-ttu-id="0de9e-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0de9e-109">Optional.</span></span> <span data-ttu-id="0de9e-110">Windows 認証のパスワード。</span><span class="sxs-lookup"><span data-stu-id="0de9e-110">Password for Windows authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.Url" />
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
            <span data-ttu-id="0de9e-111">必須。</span><span class="sxs-lookup"><span data-stu-id="0de9e-111">Required.</span></span> <span data-ttu-id="0de9e-112">HDFS の URL はサービス エンドポイント、例:"http://myhostname:50070/webhdfs/v1"です。</span><span class="sxs-lookup"><span data-stu-id="0de9e-112">The URL of the HDFS service endpoint, e.g. "http://myhostname:50070/webhdfs/v1".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HdfsLinkedService.Username" />
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
            <span data-ttu-id="0de9e-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="0de9e-113">Optional.</span></span> <span data-ttu-id="0de9e-114">Windows 認証のユーザー名。</span><span class="sxs-lookup"><span data-stu-id="0de9e-114">Username for Windows authentication.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>