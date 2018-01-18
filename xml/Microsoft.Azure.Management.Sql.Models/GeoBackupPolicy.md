<Type Name="GeoBackupPolicy" FullName="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy">
  <TypeSignature Language="C#" Value="public class GeoBackupPolicy : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GeoBackupPolicy extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class GeoBackupPolicy&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type GeoBackupPolicy = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="8ab94-101">データベース geo バックアップ ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="8ab94-101">A database geo backup policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeoBackupPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8ab94-102">GeoBackupPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8ab94-102">Initializes a new instance of the GeoBackupPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GeoBackupPolicy (Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState state, string id = null, string name = null, string type = null, string storageType = null, string kind = null, string location = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState state, string id, string name, string type, string storageType, string kind, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.#ctor(Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As GeoBackupPolicyState, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional storageType As String = null, Optional kind As String = null, Optional location As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy : Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy" Usage="new Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy (state, id, name, type, storageType, kind, location)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="storageType" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="state"><span data-ttu-id="8ab94-103">Geo バックアップ ポリシーの状態。</span><span class="sxs-lookup"><span data-stu-id="8ab94-103">The state of the geo backup policy.</span></span> <span data-ttu-id="8ab94-104">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="8ab94-104">Possible values include: 'Disabled', 'Enabled'</span></span></param>
        <param name="id"><span data-ttu-id="8ab94-105">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="8ab94-105">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="8ab94-106">リソース名。</span><span class="sxs-lookup"><span data-stu-id="8ab94-106">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="8ab94-107">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="8ab94-107">Resource type.</span></span></param>
        <param name="storageType"><span data-ttu-id="8ab94-108">Geo バックアップ ポリシーの記憶域の種類。</span><span class="sxs-lookup"><span data-stu-id="8ab94-108">The storage type of the geo backup policy.</span></span></param>
        <param name="kind"><span data-ttu-id="8ab94-109">Geo バックアップ ポリシーの種類。</span><span class="sxs-lookup"><span data-stu-id="8ab94-109">Kind of geo backup policy.</span></span>  <span data-ttu-id="8ab94-110">これは、Azure ポータルのエクスペリエンスで使用されるメタデータです。</span><span class="sxs-lookup"><span data-stu-id="8ab94-110">This is metadata used for the Azure portal experience.</span></span></param>
        <param name="location"><span data-ttu-id="8ab94-111">バックアップ ポリシーの場所です。</span><span class="sxs-lookup"><span data-stu-id="8ab94-111">Backup policy location.</span></span></param>
        <summary>
            <span data-ttu-id="8ab94-112">GeoBackupPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8ab94-112">Initializes a new instance of the GeoBackupPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.Kind" />
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
            <span data-ttu-id="8ab94-113">Geo バックアップ ポリシーの種類を取得。</span><span class="sxs-lookup"><span data-stu-id="8ab94-113">Gets kind of geo backup policy.</span></span>  <span data-ttu-id="8ab94-114">これは、Azure ポータルのエクスペリエンスで使用されるメタデータです。</span><span class="sxs-lookup"><span data-stu-id="8ab94-114">This is metadata used for the Azure portal experience.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.Location" />
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
            <span data-ttu-id="8ab94-115">バックアップ ポリシーの場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ab94-115">Gets backup policy location.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As GeoBackupPolicyState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState with get, set" Usage="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.State" />
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
        <ReturnType>Microsoft.Azure.Management.Sql.Models.GeoBackupPolicyState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ab94-116">取得または geo バックアップ ポリシーの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ab94-116">Gets or sets the state of the geo backup policy.</span></span> <span data-ttu-id="8ab94-117">使用可能な値が含まれます: '無効'、'Enabled'</span><span class="sxs-lookup"><span data-stu-id="8ab94-117">Possible values include: 'Disabled', 'Enabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageType">
      <MemberSignature Language="C#" Value="public string StorageType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.StorageType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageType As String" />
      <MemberSignature Language="F#" Value="member this.StorageType : string" Usage="Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.StorageType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ab94-118">Geo バックアップ ポリシーの記憶域の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ab94-118">Gets the storage type of the geo backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.GeoBackupPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="geoBackupPolicy.Validate " />
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
            <span data-ttu-id="8ab94-119">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="8ab94-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8ab94-120">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8ab94-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>