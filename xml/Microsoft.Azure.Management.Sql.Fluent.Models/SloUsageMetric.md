<Type Name="SloUsageMetric" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric">
  <TypeSignature Language="C#" Value="public class SloUsageMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SloUsageMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric" />
  <TypeSignature Language="VB.NET" Value="Public Class SloUsageMetric" />
  <TypeSignature Language="F#" Value="type SloUsageMetric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="df4ba-101">Slo の使用状況メトリックを表します。</span><span class="sxs-lookup"><span data-stu-id="df4ba-101">Represents a Slo Usage Metric.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SloUsageMetric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="df4ba-102">SloUsageMetric クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="df4ba-102">Initializes a new instance of the SloUsageMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SloUsageMetric (string serviceLevelObjective = null, Nullable&lt;Guid&gt; serviceLevelObjectiveId = null, Nullable&lt;double&gt; inRangeTimeRatio = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceLevelObjective, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; serviceLevelObjectiveId, valuetype System.Nullable`1&lt;float64&gt; inRangeTimeRatio) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.#ctor(System.String,System.Nullable{System.Guid},System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceLevelObjective As String = null, Optional serviceLevelObjectiveId As Nullable(Of Guid) = null, Optional inRangeTimeRatio As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric : string * Nullable&lt;Guid&gt; * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric (serviceLevelObjective, serviceLevelObjectiveId, inRangeTimeRatio)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceLevelObjective" Type="System.String" />
        <Parameter Name="serviceLevelObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="inRangeTimeRatio" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceLevelObjective"><span data-ttu-id="df4ba-103">サービス レベル目標の SLO の使用状況メトリック。</span><span class="sxs-lookup"><span data-stu-id="df4ba-103">The serviceLevelObjective for SLO usage metric.</span></span> <span data-ttu-id="df4ba-104">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'</span><span class="sxs-lookup"><span data-stu-id="df4ba-104">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3'</span></span></param>
        <param name="serviceLevelObjectiveId"><span data-ttu-id="df4ba-105">SLO の使用状況メトリックの serviceLevelObjectiveId します。</span><span class="sxs-lookup"><span data-stu-id="df4ba-105">The serviceLevelObjectiveId for SLO usage metric.</span></span></param>
        <param name="inRangeTimeRatio"><span data-ttu-id="df4ba-106">取得または inRangeTimeRatio の SLO の使用状況メトリックを設定します。</span><span class="sxs-lookup"><span data-stu-id="df4ba-106">Gets or sets inRangeTimeRatio for SLO usage metric.</span></span></param>
        <summary>
            <span data-ttu-id="df4ba-107">SloUsageMetric クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="df4ba-107">Initializes a new instance of the SloUsageMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InRangeTimeRatio">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; InRangeTimeRatio { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; InRangeTimeRatio" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.InRangeTimeRatio" />
      <MemberSignature Language="VB.NET" Value="Public Property InRangeTimeRatio As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.InRangeTimeRatio : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.InRangeTimeRatio" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inRangeTimeRatio")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="df4ba-108">取得または inRangeTimeRatio の SLO の使用状況メトリックを設定します。</span><span class="sxs-lookup"><span data-stu-id="df4ba-108">Gets or sets inRangeTimeRatio for SLO usage metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string ServiceLevelObjective { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.ServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjective : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.ServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="df4ba-109">取得または使用状況メトリックの SLO のサービス レベル目標を設定します。</span><span class="sxs-lookup"><span data-stu-id="df4ba-109">Gets or sets the serviceLevelObjective for SLO usage metric.</span></span>
            <span data-ttu-id="df4ba-110">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'</span><span class="sxs-lookup"><span data-stu-id="df4ba-110">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ServiceLevelObjectiveId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.ServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceLevelObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjectiveId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.SloUsageMetric.ServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceLevelObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="df4ba-111">取得または使用状況メトリックの SLO の serviceLevelObjectiveId を設定します。</span><span class="sxs-lookup"><span data-stu-id="df4ba-111">Gets or sets the serviceLevelObjectiveId for SLO usage metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>