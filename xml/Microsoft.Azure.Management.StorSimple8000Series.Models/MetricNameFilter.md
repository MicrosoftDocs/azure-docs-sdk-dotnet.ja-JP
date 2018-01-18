<Type Name="MetricNameFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter">
  <TypeSignature Language="C#" Value="public class MetricNameFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricNameFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricNameFilter" />
  <TypeSignature Language="F#" Value="type MetricNameFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="aadde-101">フィルター選択するメトリックの名前を指定するメトリックの名前フィルターです。</span><span class="sxs-lookup"><span data-stu-id="aadde-101">The metric name filter, specifying the name of the metric to be filtered on.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricNameFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="aadde-102">MetricNameFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="aadde-102">Initializes a new instance of the MetricNameFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricNameFilter (string value = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional value As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter : string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter value" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="aadde-103">フィルター選択されるメトリック名を指定します。</span><span class="sxs-lookup"><span data-stu-id="aadde-103">Specifies the metric name to be filtered on.</span></span>
            <span data-ttu-id="aadde-104">たとえば、CloudStorageUsed です。</span><span class="sxs-lookup"><span data-stu-id="aadde-104">E.g., CloudStorageUsed.</span></span> <span data-ttu-id="aadde-105">有効な値は、ListMetricDefinitions 呼び出しの"name"というフィールドに返されるものです。</span><span class="sxs-lookup"><span data-stu-id="aadde-105">Valid values are the ones returned in the field "name" in the ListMetricDefinitions call.</span></span> <span data-ttu-id="aadde-106">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="aadde-106">Only 'Equality' operator is supported for this property.</span></span></param>
        <summary>
            <span data-ttu-id="aadde-107">MetricNameFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="aadde-107">Initializes a new instance of the MetricNameFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aadde-108">取得または設定で、フィルター選択するメトリックの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="aadde-108">Gets or sets specifies the metric name to be filtered on.</span></span> <span data-ttu-id="aadde-109">たとえば、CloudStorageUsed です。</span><span class="sxs-lookup"><span data-stu-id="aadde-109">E.g., CloudStorageUsed.</span></span> <span data-ttu-id="aadde-110">有効な値は、ListMetricDefinitions 呼び出しの"name"というフィールドに返されるものです。</span><span class="sxs-lookup"><span data-stu-id="aadde-110">Valid values are the ones returned in the field "name" in the ListMetricDefinitions call.</span></span> <span data-ttu-id="aadde-111">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="aadde-111">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>