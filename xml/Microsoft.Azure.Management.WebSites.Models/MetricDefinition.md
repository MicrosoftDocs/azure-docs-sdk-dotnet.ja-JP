<Type Name="MetricDefinition" FullName="Microsoft.Azure.Management.WebSites.Models.MetricDefinition">
  <TypeSignature Language="C#" Value="public class MetricDefinition : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricDefinition extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.MetricDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricDefinition&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type MetricDefinition = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b4bcb-101">メトリックのメタデータ。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-101">Metadata for a metric.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MetricDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b4bcb-102">MetricDefinition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-102">Initializes a new instance of the MetricDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricDefinition (string id = null, string name = null, string kind = null, string type = null, string metricDefinitionName = null, string unit = null, string primaryAggregationType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily&gt; metricAvailabilities = null, string displayName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string metricDefinitionName, string unit, string primaryAggregationType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily&gt; metricAvailabilities, string displayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MetricDefinition.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional metricDefinitionName As String = null, Optional unit As String = null, Optional primaryAggregationType As String = null, Optional metricAvailabilities As IList(Of MetricAvailabilily) = null, Optional displayName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.MetricDefinition : string * string * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.MetricDefinition" Usage="new Microsoft.Azure.Management.WebSites.Models.MetricDefinition (id, name, kind, type, metricDefinitionName, unit, primaryAggregationType, metricAvailabilities, displayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="metricDefinitionName" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="primaryAggregationType" Type="System.String" />
        <Parameter Name="metricAvailabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily&gt;" />
        <Parameter Name="displayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="b4bcb-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="b4bcb-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="b4bcb-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="b4bcb-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-106">Resource type.</span></span></param>
        <param name="metricDefinitionName"><span data-ttu-id="b4bcb-107">メトリックの名前です。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-107">Name of the metric.</span></span></param>
        <param name="unit"><span data-ttu-id="b4bcb-108">メトリックの単位です。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-108">Unit of the metric.</span></span></param>
        <param name="primaryAggregationType"><span data-ttu-id="b4bcb-109">プライマリの集計の種類。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-109">Primary aggregation type.</span></span></param>
        <param name="metricAvailabilities"><span data-ttu-id="b4bcb-110">保有期間と共にメトリックに対してサポートされて時間結晶の一覧です。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-110">List of time grains supported for the metric together with retention period.</span></span></param>
        <param name="displayName"><span data-ttu-id="b4bcb-111">UI に表示されるフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-111">Friendly name shown in the UI.</span></span></param>
        <summary>
            <span data-ttu-id="b4bcb-112">MetricDefinition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-112">Initializes a new instance of the MetricDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MetricDefinition.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string" Usage="Microsoft.Azure.Management.WebSites.Models.MetricDefinition.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4bcb-113">UI に表示されるフレンドリ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-113">Gets friendly name shown in the UI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricAvailabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily&gt; MetricAvailabilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily&gt; MetricAvailabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MetricDefinition.MetricAvailabilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MetricAvailabilities As IList(Of MetricAvailabilily)" />
      <MemberSignature Language="F#" Value="member this.MetricAvailabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MetricDefinition.MetricAvailabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metricAvailabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MetricAvailabilily&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4bcb-114">保有期間と共にメトリックに対してサポートされて時間結晶の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-114">Gets list of time grains supported for the metric together with retention period.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricDefinitionName">
      <MemberSignature Language="C#" Value="public string MetricDefinitionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricDefinitionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MetricDefinition.MetricDefinitionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MetricDefinitionName As String" />
      <MemberSignature Language="F#" Value="member this.MetricDefinitionName : string" Usage="Microsoft.Azure.Management.WebSites.Models.MetricDefinition.MetricDefinitionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4bcb-115">メトリックの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-115">Gets name of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAggregationType">
      <MemberSignature Language="C#" Value="public string PrimaryAggregationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryAggregationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MetricDefinition.PrimaryAggregationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryAggregationType As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryAggregationType : string" Usage="Microsoft.Azure.Management.WebSites.Models.MetricDefinition.PrimaryAggregationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryAggregationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4bcb-116">プライマリの集計の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-116">Gets primary aggregation type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MetricDefinition.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.WebSites.Models.MetricDefinition.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4bcb-117">メトリックの単位を取得します。</span><span class="sxs-lookup"><span data-stu-id="b4bcb-117">Gets unit of the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>