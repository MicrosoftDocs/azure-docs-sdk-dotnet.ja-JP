<Type Name="ElasticPoolEditionCapability" FullName="Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability">
  <TypeSignature Language="C#" Value="public class ElasticPoolEditionCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPoolEditionCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPoolEditionCapability" />
  <TypeSignature Language="F#" Value="type ElasticPoolEditionCapability = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dc470-101">弾力性プール エディションの機能です。</span><span class="sxs-lookup"><span data-stu-id="dc470-101">The elastic pool edition capabilities.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolEditionCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc470-102">ElasticPoolEditionCapability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc470-102">Initializes a new instance of the ElasticPoolEditionCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolEditionCapability (string name = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt; supportedElasticPoolDtus = null, Nullable&lt;bool&gt; zoneRedundant = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt; supportedElasticPoolDtus, valuetype System.Nullable`1&lt;bool&gt; zoneRedundant) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional status As Nullable(Of CapabilityStatus) = null, Optional supportedElasticPoolDtus As IList(Of ElasticPoolDtuCapability) = null, Optional zoneRedundant As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability : string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability" Usage="new Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability (name, status, supportedElasticPoolDtus, zoneRedundant)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
        <Parameter Name="supportedElasticPoolDtus" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt;" />
        <Parameter Name="zoneRedundant" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="dc470-103">弾力性プールのエディション名。</span><span class="sxs-lookup"><span data-stu-id="dc470-103">The elastic pool edition name.</span></span></param>
        <param name="status"><span data-ttu-id="dc470-104">弾力性プール エディションの状態です。</span><span class="sxs-lookup"><span data-stu-id="dc470-104">The status of the elastic pool edition.</span></span>
            <span data-ttu-id="dc470-105">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="dc470-105">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span></param>
        <param name="supportedElasticPoolDtus"><span data-ttu-id="dc470-106">エディションのサポートされている弾力性プールの DTU レベルの一覧。</span><span class="sxs-lookup"><span data-stu-id="dc470-106">The list of supported elastic pool DTU levels for the edition.</span></span></param>
        <param name="zoneRedundant"><span data-ttu-id="dc470-107">かどうかエディションのゾーンの冗長性がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="dc470-107">Whether or not zone redundancy is supported for the edition.</span></span></param>
        <summary>
            <span data-ttu-id="dc470-108">ElasticPoolEditionCapability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc470-108">Initializes a new instance of the ElasticPoolEditionCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc470-109">弾力性プールのエディション名を取得します。</span><span class="sxs-lookup"><span data-stu-id="dc470-109">Gets the elastic pool edition name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc470-110">弾力性プール エディションのステータスを取得します。</span><span class="sxs-lookup"><span data-stu-id="dc470-110">Gets the status of the elastic pool edition.</span></span> <span data-ttu-id="dc470-111">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="dc470-111">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedElasticPoolDtus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt; SupportedElasticPoolDtus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt; SupportedElasticPoolDtus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.SupportedElasticPoolDtus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedElasticPoolDtus As IList(Of ElasticPoolDtuCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedElasticPoolDtus : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.SupportedElasticPoolDtus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedElasticPoolDtus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc470-112">エディションのサポートされている弾力性プールの一覧の DTU レベルを取得します。</span><span class="sxs-lookup"><span data-stu-id="dc470-112">Gets the list of supported elastic pool DTU levels for the edition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ZoneRedundant">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ZoneRedundant { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ZoneRedundant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.ZoneRedundant" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ZoneRedundant As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ZoneRedundant : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolEditionCapability.ZoneRedundant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zoneRedundant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc470-113">エディションのゾーンの冗長性がサポートされているかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="dc470-113">Gets whether or not zone redundancy is supported for the edition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>