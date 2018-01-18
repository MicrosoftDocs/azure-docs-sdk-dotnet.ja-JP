<Type Name="ServerCommunicationLink" FullName="Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink">
  <TypeSignature Language="C#" Value="public class ServerCommunicationLink : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServerCommunicationLink extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink" />
  <TypeSignature Language="VB.NET" Value="Public Class ServerCommunicationLink&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type ServerCommunicationLink = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4dc8f-101">サーバーの通信リンクです。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-101">Server communication link.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerCommunicationLink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4dc8f-102">ServerCommunicationLink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-102">Initializes a new instance of the ServerCommunicationLink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerCommunicationLink (string partnerServer, string id = null, string name = null, string type = null, string state = null, string location = null, string kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partnerServer, string id, string name, string type, string state, string location, string kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partnerServer As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional state As String = null, Optional location As String = null, Optional kind As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink" Usage="new Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink (partnerServer, id, name, type, state, location, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partnerServer" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partnerServer"><span data-ttu-id="4dc8f-103">パートナー サーバーの名前です。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-103">The name of the partner server.</span></span></param>
        <param name="id"><span data-ttu-id="4dc8f-104">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="4dc8f-104">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="4dc8f-105">リソース名。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-105">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="4dc8f-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-106">Resource type.</span></span></param>
        <param name="state"><span data-ttu-id="4dc8f-107">状態。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-107">The state.</span></span></param>
        <param name="location"><span data-ttu-id="4dc8f-108">通信リンクの場所です。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-108">Communication link location.</span></span></param>
        <param name="kind"><span data-ttu-id="4dc8f-109">通信リンクの種類。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-109">Communication link kind.</span></span>  <span data-ttu-id="4dc8f-110">このプロパティは、Azure ポータルのメタデータに使用されます。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-110">This property is used for Azure Portal metadata.</span></span></param>
        <summary>
            <span data-ttu-id="4dc8f-111">ServerCommunicationLink クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-111">Initializes a new instance of the ServerCommunicationLink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4dc8f-112">通信リンクの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-112">Gets communication link kind.</span></span>  <span data-ttu-id="4dc8f-113">このプロパティは、Azure ポータルのメタデータに使用されます。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-113">This property is used for Azure Portal metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4dc8f-114">通信リンクの場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-114">Gets communication link location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerServer">
      <MemberSignature Language="C#" Value="public string PartnerServer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink.PartnerServer" />
      <MemberSignature Language="VB.NET" Value="Public Property PartnerServer As String" />
      <MemberSignature Language="F#" Value="member this.PartnerServer : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink.PartnerServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4dc8f-115">取得またはパートナー サーバーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-115">Gets or sets the name of the partner server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4dc8f-116">状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-116">Gets the state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="serverCommunicationLink.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4dc8f-117">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-117">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4dc8f-118">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4dc8f-118">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>