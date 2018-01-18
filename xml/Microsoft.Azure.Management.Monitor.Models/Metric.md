<Type Name="Metric" FullName="Microsoft.Azure.Management.Monitor.Models.Metric">
  <TypeSignature Language="C#" Value="public class Metric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Metric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.Metric" />
  <TypeSignature Language="VB.NET" Value="Public Class Metric" />
  <TypeSignature Language="F#" Value="type Metric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="96080-101">クエリの結果データです。</span><span class="sxs-lookup"><span data-stu-id="96080-101">The result data of a query.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Metric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Metric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="96080-102">メトリックのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="96080-102">Initializes a new instance of the Metric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Metric (string id, string type, Microsoft.Azure.Management.Monitor.Models.LocalizableString name, Microsoft.Azure.Management.Monitor.Models.Unit unit, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; timeseries);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string type, class Microsoft.Azure.Management.Monitor.Models.LocalizableString name, valuetype Microsoft.Azure.Management.Monitor.Models.Unit unit, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; timeseries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Metric.#ctor(System.String,System.String,Microsoft.Azure.Management.Monitor.Models.LocalizableString,Microsoft.Azure.Management.Monitor.Models.Unit,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.Metric : string * string * Microsoft.Azure.Management.Monitor.Models.LocalizableString * Microsoft.Azure.Management.Monitor.Models.Unit * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; -&gt; Microsoft.Azure.Management.Monitor.Models.Metric" Usage="new Microsoft.Azure.Management.Monitor.Models.Metric (id, type, name, unit, timeseries)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="unit" Type="Microsoft.Azure.Management.Monitor.Models.Unit" />
        <Parameter Name="timeseries" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="96080-103">メトリックの id。</span><span class="sxs-lookup"><span data-stu-id="96080-103">the metric Id.</span></span></param>
        <param name="type"><span data-ttu-id="96080-104">メトリック リソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="96080-104">the resource type of the metric resource.</span></span></param>
        <param name="name"><span data-ttu-id="96080-105">名前とメトリックの表示名がローカライズ可能な文字列など。</span><span class="sxs-lookup"><span data-stu-id="96080-105">the name and the display name of the metric, i.e. it is localizable string.</span></span></param>
        <param name="unit"><span data-ttu-id="96080-106">メトリックの単位。</span><span class="sxs-lookup"><span data-stu-id="96080-106">the unit of the metric.</span></span> <span data-ttu-id="96080-107">使用可能な値が含まれます: 'Count'、'バイト'、'秒数'、'CountPerSecond'、'BytesPerSecond'、'%'、'(ミリ秒)'、'ByteSeconds'、'指定されていない'</span><span class="sxs-lookup"><span data-stu-id="96080-107">Possible values include: 'Count', 'Bytes', 'Seconds', 'CountPerSecond', 'BytesPerSecond', 'Percent', 'MilliSeconds', 'ByteSeconds', 'Unspecified'</span></span></param>
        <param name="timeseries"><span data-ttu-id="96080-108">タイム シリーズは、データのクエリが実行されるときに返されます。</span><span class="sxs-lookup"><span data-stu-id="96080-108">the time series returned when a data query is performed.</span></span></param>
        <summary>
            <span data-ttu-id="96080-109">メトリックのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="96080-109">Initializes a new instance of the Metric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Metric.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Metric.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96080-110">取得または設定、メトリックの id です。</span><span class="sxs-lookup"><span data-stu-id="96080-110">Gets or sets the metric Id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Metric.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Metric.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96080-111">名前と表示名をメトリックの取得または設定がローカライズ可能な文字列など。</span><span class="sxs-lookup"><span data-stu-id="96080-111">Gets or sets the name and the display name of the metric, i.e. it is localizable string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeseries">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; Timeseries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; Timeseries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Metric.Timeseries" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeseries As IList(Of TimeSeriesElement)" />
      <MemberSignature Language="F#" Value="member this.Timeseries : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Metric.Timeseries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeseries")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96080-112">取得または設定とデータのクエリに返されるタイム シリーズが実行されます。</span><span class="sxs-lookup"><span data-stu-id="96080-112">Gets or sets the time series returned when a data query is performed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Metric.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Metric.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96080-113">取得またはメトリック リソースのリソースの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="96080-113">Gets or sets the resource type of the metric resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.Unit Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Models.Unit Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Metric.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As Unit" />
      <MemberSignature Language="F#" Value="member this.Unit : Microsoft.Azure.Management.Monitor.Models.Unit with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Metric.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.Unit</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96080-114">取得またはメトリックの単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="96080-114">Gets or sets the unit of the metric.</span></span> <span data-ttu-id="96080-115">使用可能な値が含まれます: 'Count'、'バイト'、'秒数'、'CountPerSecond'、'BytesPerSecond'、'%'、'(ミリ秒)'、'ByteSeconds'、'指定されていない'</span><span class="sxs-lookup"><span data-stu-id="96080-115">Possible values include: 'Count', 'Bytes', 'Seconds', 'CountPerSecond', 'BytesPerSecond', 'Percent', 'MilliSeconds', 'ByteSeconds', 'Unspecified'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Metric.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="metric.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="96080-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="96080-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="96080-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="96080-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>