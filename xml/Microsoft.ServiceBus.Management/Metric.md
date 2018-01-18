<Type Name="Metric" FullName="Microsoft.ServiceBus.Management.Metric">
  <TypeSignature Language="C#" Value="public class Metric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Metric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Management.Metric" />
  <TypeSignature Language="VB.NET" Value="Public Class Metric" />
  <TypeSignature Language="F#" Value="type Metric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="51161-101">Service Bus の状態を監視するために使用するメトリックを表します。</span><span class="sxs-lookup"><span data-stu-id="51161-101">Represents the metric used to monitor the Service Bus status.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Metric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Management.Metric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Metric.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.ServiceBus.Management.Metric.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="51161-102">取得またはメトリックの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="51161-102">Gets or sets the display name of the metric.</span></span></summary>
        <value><span data-ttu-id="51161-103">メトリックの表示名。</span><span class="sxs-lookup"><span data-stu-id="51161-103">The display name of the metric.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Metric.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceBus.Management.Metric.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DataAnnotations.Key</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="51161-104">取得またはメトリックの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="51161-104">Gets or sets the name of the metric.</span></span></summary>
        <value><span data-ttu-id="51161-105">メトリックの名前。</span><span class="sxs-lookup"><span data-stu-id="51161-105">The name of the metric.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAggregation">
      <MemberSignature Language="C#" Value="public string PrimaryAggregation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryAggregation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Metric.PrimaryAggregation" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryAggregation As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryAggregation : string with get, set" Usage="Microsoft.ServiceBus.Management.Metric.PrimaryAggregation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="51161-106">取得またはこのメトリックの集計をプライマリを設定します。</span><span class="sxs-lookup"><span data-stu-id="51161-106">Gets or sets the primary aggregation for this metric.</span></span></summary>
        <value><span data-ttu-id="51161-107">このメトリックの集計をプライマリです。</span><span class="sxs-lookup"><span data-stu-id="51161-107">The primary aggregation for this metric.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rollups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Management.MetricRollup&gt; Rollups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class Microsoft.ServiceBus.Management.MetricRollup&gt; Rollups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Metric.Rollups" />
      <MemberSignature Language="VB.NET" Value="Public Property Rollups As ICollection(Of MetricRollup)" />
      <MemberSignature Language="F#" Value="member this.Rollups : System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Management.MetricRollup&gt; with get, set" Usage="Microsoft.ServiceBus.Management.Metric.Rollups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Management.MetricRollup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="51161-108">取得またはメトリックのロールアップのコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="51161-108">Gets or sets the collection of metric rollup.</span></span></summary>
        <value><span data-ttu-id="51161-109">メトリック ロールアップのコレクション。</span><span class="sxs-lookup"><span data-stu-id="51161-109">The collection of metric rollup.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Management.Metric.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.ServiceBus.Management.Metric.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="51161-110">取得またはメトリックの単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="51161-110">Gets or sets the metric unit.</span></span></summary>
        <value><span data-ttu-id="51161-111">メトリックの単位です。</span><span class="sxs-lookup"><span data-stu-id="51161-111">The metric unit.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>