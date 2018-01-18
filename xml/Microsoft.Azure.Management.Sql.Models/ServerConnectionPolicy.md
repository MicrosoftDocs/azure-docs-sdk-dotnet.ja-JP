<Type Name="ServerConnectionPolicy" FullName="Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy">
  <TypeSignature Language="C#" Value="public class ServerConnectionPolicy : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServerConnectionPolicy extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ServerConnectionPolicy&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type ServerConnectionPolicy = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="b2327-101">サーバーのセキュリティで保護された接続ポリシー。</span><span class="sxs-lookup"><span data-stu-id="b2327-101">A server secure connection policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerConnectionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b2327-102">ServerConnectionPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b2327-102">Initializes a new instance of the ServerConnectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServerConnectionPolicy (Microsoft.Azure.Management.Sql.Models.ServerConnectionType connectionType, string id = null, string name = null, string type = null, string kind = null, string location = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.ServerConnectionType connectionType, string id, string name, string type, string kind, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy.#ctor(Microsoft.Azure.Management.Sql.Models.ServerConnectionType,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionType As ServerConnectionType, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As String = null, Optional location As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy : Microsoft.Azure.Management.Sql.Models.ServerConnectionType * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy" Usage="new Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy (connectionType, id, name, type, kind, location)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionType" Type="Microsoft.Azure.Management.Sql.Models.ServerConnectionType" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionType"><span data-ttu-id="b2327-103">サーバー接続の種類。</span><span class="sxs-lookup"><span data-stu-id="b2327-103">The server connection type.</span></span> <span data-ttu-id="b2327-104">使用可能な値が含まれます: 'Default'、'Proxy'、'リダイレクト'</span><span class="sxs-lookup"><span data-stu-id="b2327-104">Possible values include: 'Default', 'Proxy', 'Redirect'</span></span></param>
        <param name="id"><span data-ttu-id="b2327-105">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="b2327-105">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="b2327-106">リソース名。</span><span class="sxs-lookup"><span data-stu-id="b2327-106">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="b2327-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="b2327-107">Resource type.</span></span></param>
        <param name="kind"><span data-ttu-id="b2327-108">Azure ポータルのエクスペリエンスで使用されるメタデータ。</span><span class="sxs-lookup"><span data-stu-id="b2327-108">Metadata used for the Azure portal experience.</span></span></param>
        <param name="location"><span data-ttu-id="b2327-109">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="b2327-109">Resource location.</span></span></param>
        <summary>
            <span data-ttu-id="b2327-110">ServerConnectionPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b2327-110">Initializes a new instance of the ServerConnectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.ServerConnectionType ConnectionType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.ServerConnectionType ConnectionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy.ConnectionType" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionType As ServerConnectionType" />
      <MemberSignature Language="F#" Value="member this.ConnectionType : Microsoft.Azure.Management.Sql.Models.ServerConnectionType with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy.ConnectionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.connectionType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerConnectionType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b2327-111">取得またはサーバー接続の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2327-111">Gets or sets the server connection type.</span></span> <span data-ttu-id="b2327-112">使用可能な値が含まれます: 'Default'、'Proxy'、'リダイレクト'</span><span class="sxs-lookup"><span data-stu-id="b2327-112">Possible values include: 'Default', 'Proxy', 'Redirect'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy.Kind" />
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
            <span data-ttu-id="b2327-113">Azure ポータルのエクスペリエンスで使用されるメタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="b2327-113">Gets metadata used for the Azure portal experience.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy.Location" />
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
            <span data-ttu-id="b2327-114">リソースの場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="b2327-114">Gets resource location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServerConnectionPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="serverConnectionPolicy.Validate " />
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
            <span data-ttu-id="b2327-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="b2327-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b2327-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b2327-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>