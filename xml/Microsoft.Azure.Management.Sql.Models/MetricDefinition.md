<Type Name="MetricDefinition" FullName="Microsoft.Azure.Management.Sql.Models.MetricDefinition">
  <TypeSignature Language="C#" Value="public class MetricDefinition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricDefinition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.MetricDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricDefinition" />
  <TypeSignature Language="F#" Value="type MetricDefinition = class" />
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
            <span data-ttu-id="6c96f-101">データベースのメトリック定義します。</span><span class="sxs-lookup"><span data-stu-id="6c96f-101">A database metric definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MetricDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6c96f-102">MetricDefinition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6c96f-102">Initializes a new instance of the MetricDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricDefinition (Microsoft.Azure.Management.Sql.Models.MetricName name = null, string primaryAggregationType = null, string resourceUri = null, string unit = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricAvailability&gt; metricAvailabilities = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Sql.Models.MetricName name, string primaryAggregationType, string resourceUri, string unit, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.MetricAvailability&gt; metricAvailabilities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.MetricDefinition.#ctor(Microsoft.Azure.Management.Sql.Models.MetricName,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.MetricAvailability})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As MetricName = null, Optional primaryAggregationType As String = null, Optional resourceUri As String = null, Optional unit As String = null, Optional metricAvailabilities As IList(Of MetricAvailability) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.MetricDefinition : Microsoft.Azure.Management.Sql.Models.MetricName * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricAvailability&gt; -&gt; Microsoft.Azure.Management.Sql.Models.MetricDefinition" Usage="new Microsoft.Azure.Management.Sql.Models.MetricDefinition (name, primaryAggregationType, resourceUri, unit, metricAvailabilities)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.Sql.Models.MetricName" />
        <Parameter Name="primaryAggregationType" Type="System.String" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="metricAvailabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricAvailability&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="6c96f-103">メトリックの名前情報。</span><span class="sxs-lookup"><span data-stu-id="6c96f-103">The name information for the metric.</span></span></param>
        <param name="primaryAggregationType"><span data-ttu-id="6c96f-104">プライマリの集計では、どのメトリックの定義の値が表示されますを入力します。</span><span class="sxs-lookup"><span data-stu-id="6c96f-104">The primary aggregation type defining how metric values are displayed.</span></span> <span data-ttu-id="6c96f-105">使用可能な値が含まれます 'None'、'Average'、'Count'、'最小'、'最大'、'Total'。</span><span class="sxs-lookup"><span data-stu-id="6c96f-105">Possible values include: 'None', 'Average', 'Count', 'Minimum', 'Maximum', 'Total'</span></span></param>
        <param name="resourceUri"><span data-ttu-id="6c96f-106">データベースのリソース uri。</span><span class="sxs-lookup"><span data-stu-id="6c96f-106">The resource uri of the database.</span></span></param>
        <param name="unit"><span data-ttu-id="6c96f-107">メトリックの単位。</span><span class="sxs-lookup"><span data-stu-id="6c96f-107">The unit of the metric.</span></span> <span data-ttu-id="6c96f-108">使用可能な値が含まれます: 'Count'、'バイト'、'秒数'、'%'、'CountPerSecond'、'BytesPerSecond'</span><span class="sxs-lookup"><span data-stu-id="6c96f-108">Possible values include: 'Count', 'Bytes', 'Seconds', 'Percent', 'CountPerSecond', 'BytesPerSecond'</span></span></param>
        <param name="metricAvailabilities"><span data-ttu-id="6c96f-109">メトリックのメトリック availabities をデータベースの一覧。</span><span class="sxs-lookup"><span data-stu-id="6c96f-109">The list of database metric availabities for the metric.</span></span></param>
        <summary>
            <span data-ttu-id="6c96f-110">MetricDefinition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6c96f-110">Initializes a new instance of the MetricDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricAvailabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricAvailability&gt; MetricAvailabilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.MetricAvailability&gt; MetricAvailabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricDefinition.MetricAvailabilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MetricAvailabilities As IList(Of MetricAvailability)" />
      <MemberSignature Language="F#" Value="member this.MetricAvailabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricAvailability&gt;" Usage="Microsoft.Azure.Management.Sql.Models.MetricDefinition.MetricAvailabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricAvailabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.MetricAvailability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c96f-111">メトリックのメトリック availabities のデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6c96f-111">Gets the list of database metric availabities for the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.MetricName Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Models.MetricName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As MetricName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Sql.Models.MetricName" Usage="Microsoft.Azure.Management.Sql.Models.MetricDefinition.Name" />
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
        <ReturnType>Microsoft.Azure.Management.Sql.Models.MetricName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c96f-112">メトリックの名前情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="6c96f-112">Gets the name information for the metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAggregationType">
      <MemberSignature Language="C#" Value="public string PrimaryAggregationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryAggregationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricDefinition.PrimaryAggregationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryAggregationType As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryAggregationType : string" Usage="Microsoft.Azure.Management.Sql.Models.MetricDefinition.PrimaryAggregationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryAggregationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c96f-113">表示されるメトリックがどのように値を定義するプライマリの集計の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="6c96f-113">Gets the primary aggregation type defining how metric values are displayed.</span></span> <span data-ttu-id="6c96f-114">使用可能な値が含まれます 'None'、'Average'、'Count'、'最小'、'最大'、'Total'。</span><span class="sxs-lookup"><span data-stu-id="6c96f-114">Possible values include: 'None', 'Average', 'Count', 'Minimum', 'Maximum', 'Total'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceUri">
      <MemberSignature Language="C#" Value="public string ResourceUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricDefinition.ResourceUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceUri As String" />
      <MemberSignature Language="F#" Value="member this.ResourceUri : string" Usage="Microsoft.Azure.Management.Sql.Models.MetricDefinition.ResourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c96f-115">データベースのリソース uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="6c96f-115">Gets the resource uri of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.MetricDefinition.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Sql.Models.MetricDefinition.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c96f-116">メトリックの単位を取得します。</span><span class="sxs-lookup"><span data-stu-id="6c96f-116">Gets the unit of the metric.</span></span> <span data-ttu-id="6c96f-117">使用可能な値が含まれます: 'Count'、'バイト'、'秒数'、'%'、'CountPerSecond'、'BytesPerSecond'</span><span class="sxs-lookup"><span data-stu-id="6c96f-117">Possible values include: 'Count', 'Bytes', 'Seconds', 'Percent', 'CountPerSecond', 'BytesPerSecond'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>