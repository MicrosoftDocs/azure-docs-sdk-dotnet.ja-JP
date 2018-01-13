<Type Name="ManagementGroupDetailsProperties" FullName="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties">
  <TypeSignature Language="C#" Value="public class ManagementGroupDetailsProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementGroupDetailsProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementGroupDetailsProperties" />
  <TypeSignature Language="F#" Value="type ManagementGroupDetailsProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fe105-101">管理グループの詳細プロパティです。</span><span class="sxs-lookup"><span data-stu-id="fe105-101">The details properties of a management group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroupDetailsProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fe105-102">ManagementGroupDetailsProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fe105-102">Initializes a new instance of the ManagementGroupDetailsProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroupDetailsProperties (Nullable&lt;double&gt; version = null, Nullable&lt;DateTime&gt; updatedTime = null, string updatedBy = null, Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo parent = null, string managementGroupType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;float64&gt; version, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedTime, string updatedBy, class Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo parent, string managementGroupType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.#ctor(System.Nullable{System.Double},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional version As Nullable(Of Double) = null, Optional updatedTime As Nullable(Of DateTime) = null, Optional updatedBy As String = null, Optional parent As ParentGroupInfo = null, Optional managementGroupType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties : Nullable&lt;double&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties (version, updatedTime, updatedBy, parent, managementGroupType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="version" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="updatedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedBy" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo" />
        <Parameter Name="managementGroupType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="fe105-103">オブジェクトのバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="fe105-103">The version number of the object.</span></span></param>
        <param name="updatedTime"><span data-ttu-id="fe105-104">日付と、このオブジェクトが最後に更新された日時。</span><span class="sxs-lookup"><span data-stu-id="fe105-104">The date and time when this object was last updated.</span></span></param>
        <param name="updatedBy"><span data-ttu-id="fe105-105">プリンシパルまたはオブジェクトを更新するプロセスの id。</span><span class="sxs-lookup"><span data-stu-id="fe105-105">The identity of the principal or process that updated the object.</span></span></param>
        <param name="parent"><span data-ttu-id="fe105-106">親</span><span class="sxs-lookup"><span data-stu-id="fe105-106">Parent</span></span></param>
        <param name="managementGroupType"><span data-ttu-id="fe105-107">管理グループの種類</span><span class="sxs-lookup"><span data-stu-id="fe105-107">Management Group Type</span></span></param>
        <summary>
            <span data-ttu-id="fe105-108">ManagementGroupDetailsProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fe105-108">Initializes a new instance of the ManagementGroupDetailsProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagementGroupType">
      <MemberSignature Language="C#" Value="public string ManagementGroupType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ManagementGroupType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.ManagementGroupType" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagementGroupType As String" />
      <MemberSignature Language="F#" Value="member this.ManagementGroupType : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.ManagementGroupType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managementGroupType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe105-109">取得または設定の管理グループの種類</span><span class="sxs-lookup"><span data-stu-id="fe105-109">Gets or sets management Group Type</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fe105-110">使用可能な値が含まれます: '登録', 'Department'、'Account', 'Subscription'</span><span class="sxs-lookup"><span data-stu-id="fe105-110">Possible values include: 'Enrollment', 'Department', 'Account', 'Subscription'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo Parent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo Parent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.Parent" />
      <MemberSignature Language="VB.NET" Value="Public Property Parent As ParentGroupInfo" />
      <MemberSignature Language="F#" Value="member this.Parent : Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.Parent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe105-111">取得または親の設定</span><span class="sxs-lookup"><span data-stu-id="fe105-111">Gets or sets parent</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedBy">
      <MemberSignature Language="C#" Value="public string UpdatedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpdatedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.UpdatedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdatedBy As String" />
      <MemberSignature Language="F#" Value="member this.UpdatedBy : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.UpdatedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="updatedBy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe105-112">取得またはプリンシパルまたはオブジェクトを更新するプロセスの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="fe105-112">Gets or sets the identity of the principal or process that updated the object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.UpdatedTime" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdatedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.UpdatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="updatedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe105-113">取得またはこのオブジェクトが最後に更新された日時を設定します。</span><span class="sxs-lookup"><span data-stu-id="fe105-113">Gets or sets the date and time when this object was last updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Version : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe105-114">取得またはオブジェクトのバージョン番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="fe105-114">Gets or sets the version number of the object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>