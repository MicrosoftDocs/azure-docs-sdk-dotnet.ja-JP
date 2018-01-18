<Type Name="ArmDisasterRecovery" FullName="Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery">
  <TypeSignature Language="C#" Value="public class ArmDisasterRecovery : Microsoft.Azure.Management.EventHub.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ArmDisasterRecovery extends Microsoft.Azure.Management.EventHub.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery" />
  <TypeSignature Language="VB.NET" Value="Public Class ArmDisasterRecovery&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ArmDisasterRecovery = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.EventHub.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="57135-101">1 つの項目リストまたは取得 Alias(Disaster Recovery configuration) 操作</span><span class="sxs-lookup"><span data-stu-id="57135-101">Single item in List or Get Alias(Disaster Recovery configuration) operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ArmDisasterRecovery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="57135-102">ArmDisasterRecovery クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="57135-102">Initializes a new instance of the ArmDisasterRecovery class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ArmDisasterRecovery (string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.EventHub.Models.ProvisioningStateDR&gt; provisioningState = null, string partnerNamespace = null, string alternateName = null, Nullable&lt;Microsoft.Azure.Management.EventHub.Models.RoleDisasterRecovery&gt; role = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.EventHub.Models.ProvisioningStateDR&gt; provisioningState, string partnerNamespace, string alternateName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.EventHub.Models.RoleDisasterRecovery&gt; role) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery.#ctor(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.EventHub.Models.ProvisioningStateDR},System.String,System.String,System.Nullable{Microsoft.Azure.Management.EventHub.Models.RoleDisasterRecovery})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional provisioningState As Nullable(Of ProvisioningStateDR) = null, Optional partnerNamespace As String = null, Optional alternateName As String = null, Optional role As Nullable(Of RoleDisasterRecovery) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery : string * string * string * Nullable&lt;Microsoft.Azure.Management.EventHub.Models.ProvisioningStateDR&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.EventHub.Models.RoleDisasterRecovery&gt; -&gt; Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery" Usage="new Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery (id, name, type, provisioningState, partnerNamespace, alternateName, role)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.EventHub.Models.ProvisioningStateDR&gt;" />
        <Parameter Name="partnerNamespace" Type="System.String" />
        <Parameter Name="alternateName" Type="System.String" />
        <Parameter Name="role" Type="System.Nullable&lt;Microsoft.Azure.Management.EventHub.Models.RoleDisasterRecovery&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="57135-103">リソース Id</span><span class="sxs-lookup"><span data-stu-id="57135-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="57135-104">リソース名</span><span class="sxs-lookup"><span data-stu-id="57135-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="57135-105">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="57135-105">Resource type</span></span></param>
        <param name="provisioningState"><span data-ttu-id="57135-106">プロビジョニングの状態の別名 (障害回復の構成) - の値のいずれか '承諾' または '成功' または '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="57135-106">Provisioning state of the Alias(Disaster Recovery configuration) - possible values 'Accepted' or 'Succeeded' or 'Failed'.</span></span> <span data-ttu-id="57135-107">使用可能な値が含まれます: '受理'、'成功'、'失敗'</span><span class="sxs-lookup"><span data-stu-id="57135-107">Possible values include: 'Accepted', 'Succeeded', 'Failed'</span></span></param>
        <param name="partnerNamespace"><span data-ttu-id="57135-108">プライマリ/セカンダリの eventhub 名前空間名、GEO DR pairning の一部の ARM Id</span><span class="sxs-lookup"><span data-stu-id="57135-108">ARM Id of the Primary/Secondary eventhub namespace name, which is part of GEO DR pairning</span></span></param>
        <param name="alternateName"><span data-ttu-id="57135-109">別の名前は、エイリアスと名前空間の名前が同じ場合を指定します。</span><span class="sxs-lookup"><span data-stu-id="57135-109">Alternate name specified when alias and namespace names are same.</span></span></param>
        <param name="role"><span data-ttu-id="57135-110">値 'プライマリ' または 'PrimaryNotReplicating' または 'セカンダリ' の GEO DR の考えられる 名前空間の役割です。</span><span class="sxs-lookup"><span data-stu-id="57135-110">role of namespace in GEO DR - possible values 'Primary' or 'PrimaryNotReplicating' or 'Secondary'.</span></span> <span data-ttu-id="57135-111">使用可能な値が含まれます 'Primary'、'PrimaryNotReplicating'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="57135-111">Possible values include: 'Primary', 'PrimaryNotReplicating', 'Secondary'</span></span></param>
        <summary>
            <span data-ttu-id="57135-112">ArmDisasterRecovery クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="57135-112">Initializes a new instance of the ArmDisasterRecovery class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlternateName">
      <MemberSignature Language="C#" Value="public string AlternateName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AlternateName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery.AlternateName" />
      <MemberSignature Language="VB.NET" Value="Public Property AlternateName As String" />
      <MemberSignature Language="F#" Value="member this.AlternateName : string with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery.AlternateName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.alternateName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57135-113">取得または別名と名前空間の名前が同じ場合に指定された代替名を設定します。</span><span class="sxs-lookup"><span data-stu-id="57135-113">Gets or sets alternate name specified when alias and namespace names are same.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerNamespace">
      <MemberSignature Language="C#" Value="public string PartnerNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery.PartnerNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property PartnerNamespace As String" />
      <MemberSignature Language="F#" Value="member this.PartnerNamespace : string with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery.PartnerNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57135-114">ARM Id GEO DR pairning の一部であるプライマリ/セカンダリ eventhub 名前空間名の取得または設定</span><span class="sxs-lookup"><span data-stu-id="57135-114">Gets or sets ARM Id of the Primary/Secondary eventhub namespace name, which is part of GEO DR pairning</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.EventHub.Models.ProvisioningStateDR&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.EventHub.Models.ProvisioningStateDR&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningStateDR)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.EventHub.Models.ProvisioningStateDR&gt;" Usage="Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.EventHub.Models.ProvisioningStateDR&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57135-115">プロビジョニングの状態を取得 (障害回復の構成) - の別名の値のいずれか '承諾' または '成功' または '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="57135-115">Gets provisioning state of the Alias(Disaster Recovery configuration) - possible values 'Accepted' or 'Succeeded' or 'Failed'.</span></span> <span data-ttu-id="57135-116">使用可能な値が含まれます: '受理'、'成功'、'失敗'</span><span class="sxs-lookup"><span data-stu-id="57135-116">Possible values include: 'Accepted', 'Succeeded', 'Failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Role">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.EventHub.Models.RoleDisasterRecovery&gt; Role { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.EventHub.Models.RoleDisasterRecovery&gt; Role" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery.Role" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Role As Nullable(Of RoleDisasterRecovery)" />
      <MemberSignature Language="F#" Value="member this.Role : Nullable&lt;Microsoft.Azure.Management.EventHub.Models.RoleDisasterRecovery&gt;" Usage="Microsoft.Azure.Management.EventHub.Models.ArmDisasterRecovery.Role" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.role")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.EventHub.Models.RoleDisasterRecovery&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57135-117">GEO DR に使用可能な値 'プライマリ' または 'PrimaryNotReplicating' または 'セカンダリ' で名前空間の役割を取得します。</span><span class="sxs-lookup"><span data-stu-id="57135-117">Gets role of namespace in GEO DR - possible values 'Primary' or 'PrimaryNotReplicating' or 'Secondary'.</span></span> <span data-ttu-id="57135-118">使用可能な値が含まれます 'Primary'、'PrimaryNotReplicating'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="57135-118">Possible values include: 'Primary', 'PrimaryNotReplicating', 'Secondary'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>