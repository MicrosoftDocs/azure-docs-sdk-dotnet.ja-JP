<Type Name="ElasticPoolDtuCapability" FullName="Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability">
  <TypeSignature Language="C#" Value="public class ElasticPoolDtuCapability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPoolDtuCapability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPoolDtuCapability" />
  <TypeSignature Language="F#" Value="type ElasticPoolDtuCapability = class" />
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
            <span data-ttu-id="49b06-101">弾力性プール DTU 機能です。</span><span class="sxs-lookup"><span data-stu-id="49b06-101">The Elastic Pool DTU capability.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolDtuCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="49b06-102">ElasticPoolDtuCapability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="49b06-102">Initializes a new instance of the ElasticPoolDtuCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolDtuCapability (Nullable&lt;long&gt; limit = null, Nullable&lt;long&gt; maxDatabaseCount = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; supportedMaxSizes = null, Microsoft.Azure.Management.Sql.Models.MaxSizeCapability includedMaxSize = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; supportedPerDatabaseMaxSizes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability&gt; supportedPerDatabaseMaxDtus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; limit, valuetype System.Nullable`1&lt;int64&gt; maxDatabaseCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; status, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; supportedMaxSizes, class Microsoft.Azure.Management.Sql.Models.MaxSizeCapability includedMaxSize, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; supportedPerDatabaseMaxSizes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability&gt; supportedPerDatabaseMaxDtus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{Microsoft.Azure.Management.Sql.Models.CapabilityStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.MaxSizeCapability},Microsoft.Azure.Management.Sql.Models.MaxSizeCapability,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.MaxSizeCapability},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional limit As Nullable(Of Long) = null, Optional maxDatabaseCount As Nullable(Of Long) = null, Optional status As Nullable(Of CapabilityStatus) = null, Optional supportedMaxSizes As IList(Of MaxSizeCapability) = null, Optional includedMaxSize As MaxSizeCapability = null, Optional supportedPerDatabaseMaxSizes As IList(Of MaxSizeCapability) = null, Optional supportedPerDatabaseMaxDtus As IList(Of ElasticPoolPerDatabaseMaxDtuCapability) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; * Microsoft.Azure.Management.Sql.Models.MaxSizeCapability * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability" Usage="new Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability (limit, maxDatabaseCount, status, supportedMaxSizes, includedMaxSize, supportedPerDatabaseMaxSizes, supportedPerDatabaseMaxDtus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="limit" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="maxDatabaseCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" />
        <Parameter Name="supportedMaxSizes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt;" />
        <Parameter Name="includedMaxSize" Type="Microsoft.Azure.Management.Sql.Models.MaxSizeCapability" />
        <Parameter Name="supportedPerDatabaseMaxSizes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt;" />
        <Parameter Name="supportedPerDatabaseMaxDtus" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability&gt;" />
      </Parameters>
      <Docs>
        <param name="limit"><span data-ttu-id="49b06-103">データベースの最大サイズ (単位の ' unit' を参照してください)。</span><span class="sxs-lookup"><span data-stu-id="49b06-103">The maximum size of the database (see 'unit' for the units).</span></span></param>
        <param name="maxDatabaseCount"><span data-ttu-id="49b06-104">サポートされるデータベースの最大数。</span><span class="sxs-lookup"><span data-stu-id="49b06-104">The maximum number of databases supported.</span></span></param>
        <param name="status"><span data-ttu-id="49b06-105">機能の状態。</span><span class="sxs-lookup"><span data-stu-id="49b06-105">The status of the capability.</span></span> <span data-ttu-id="49b06-106">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="49b06-106">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span></param>
        <param name="supportedMaxSizes"><span data-ttu-id="49b06-107">サポートされている最大サイズの一覧。</span><span class="sxs-lookup"><span data-stu-id="49b06-107">The list of supported max sizes.</span></span></param>
        <param name="includedMaxSize"><span data-ttu-id="49b06-108">含まれる (無料) の最大サイズこのサービス レベル目標です。</span><span class="sxs-lookup"><span data-stu-id="49b06-108">The included (free) max size for this service level objective.</span></span></param>
        <param name="supportedPerDatabaseMaxSizes"><span data-ttu-id="49b06-109">サポートされている最大データベース サイズの一覧です。</span><span class="sxs-lookup"><span data-stu-id="49b06-109">The list of supported max database sizes.</span></span></param>
        <param name="supportedPerDatabaseMaxDtus"><span data-ttu-id="49b06-110">サポートされている最大データベース Dtu の一覧。</span><span class="sxs-lookup"><span data-stu-id="49b06-110">The list of supported max database DTUs.</span></span></param>
        <summary>
            <span data-ttu-id="49b06-111">ElasticPoolDtuCapability クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="49b06-111">Initializes a new instance of the ElasticPoolDtuCapability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludedMaxSize">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.MaxSizeCapability IncludedMaxSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.MaxSizeCapability IncludedMaxSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.IncludedMaxSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IncludedMaxSize As MaxSizeCapability" />
      <MemberSignature Language="F#" Value="member this.IncludedMaxSize : Microsoft.Azure.Management.Sql.Models.MaxSizeCapability" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.IncludedMaxSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="includedMaxSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.MaxSizeCapability</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49b06-112">このサービス レベル目標の含まれる (無料) の最大サイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="49b06-112">Gets the included (free) max size for this service level objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Limit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.Limit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Limit As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49b06-113">データベースの最大サイズを取得 ('unit' ユニットを参照してください)。</span><span class="sxs-lookup"><span data-stu-id="49b06-113">Gets the maximum size of the database (see 'unit' for the units).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDatabaseCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxDatabaseCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxDatabaseCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.MaxDatabaseCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxDatabaseCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxDatabaseCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.MaxDatabaseCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxDatabaseCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49b06-114">サポートされるデータベースの最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="49b06-114">Gets the maximum number of databases supported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CapabilityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Sql.Models.CapabilityStatus&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.Status" />
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
            <span data-ttu-id="49b06-115">機能の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="49b06-115">Gets the status of the capability.</span></span> <span data-ttu-id="49b06-116">使用可能な値が含まれます: 'Visible'、使用可能'、'Default'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="49b06-116">Possible values include: 'Visible', 'Available', 'Default', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedMaxSizes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; SupportedMaxSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; SupportedMaxSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.SupportedMaxSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedMaxSizes As IList(Of MaxSizeCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedMaxSizes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.SupportedMaxSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedMaxSizes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49b06-117">サポートされている最大サイズの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="49b06-117">Gets the list of supported max sizes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedPerDatabaseMaxDtus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability&gt; SupportedPerDatabaseMaxDtus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability&gt; SupportedPerDatabaseMaxDtus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.SupportedPerDatabaseMaxDtus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedPerDatabaseMaxDtus As IList(Of ElasticPoolPerDatabaseMaxDtuCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedPerDatabaseMaxDtus : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.SupportedPerDatabaseMaxDtus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedPerDatabaseMaxDtus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ElasticPoolPerDatabaseMaxDtuCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49b06-118">サポートされている最大データベース Dtu の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="49b06-118">Gets the list of supported max database DTUs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedPerDatabaseMaxSizes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; SupportedPerDatabaseMaxSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt; SupportedPerDatabaseMaxSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.SupportedPerDatabaseMaxSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SupportedPerDatabaseMaxSizes As IList(Of MaxSizeCapability)" />
      <MemberSignature Language="F#" Value="member this.SupportedPerDatabaseMaxSizes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDtuCapability.SupportedPerDatabaseMaxSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="supportedPerDatabaseMaxSizes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MaxSizeCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49b06-119">サポートされている最大データベース サイズの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="49b06-119">Gets the list of supported max database sizes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>