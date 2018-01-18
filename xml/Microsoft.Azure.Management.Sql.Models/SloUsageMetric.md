<Type Name="SloUsageMetric" FullName="Microsoft.Azure.Management.Sql.Models.SloUsageMetric">
  <TypeSignature Language="C#" Value="public class SloUsageMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SloUsageMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SloUsageMetric" />
  <TypeSignature Language="VB.NET" Value="Public Class SloUsageMetric" />
  <TypeSignature Language="F#" Value="type SloUsageMetric = class" />
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
            <span data-ttu-id="ab50e-101">Slo の使用状況メトリック。</span><span class="sxs-lookup"><span data-stu-id="ab50e-101">A Slo Usage Metric.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SloUsageMetric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SloUsageMetric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ab50e-102">SloUsageMetric クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ab50e-102">Initializes a new instance of the SloUsageMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SloUsageMetric (string serviceLevelObjective = null, Guid serviceLevelObjectiveId = null, double inRangeTimeRatio = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceLevelObjective, valuetype System.Guid serviceLevelObjectiveId, float64 inRangeTimeRatio) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SloUsageMetric.#ctor(System.String,System.Guid,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceLevelObjective As String = null, Optional serviceLevelObjectiveId As Guid = null, Optional inRangeTimeRatio As Double = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SloUsageMetric : string * Guid * double -&gt; Microsoft.Azure.Management.Sql.Models.SloUsageMetric" Usage="new Microsoft.Azure.Management.Sql.Models.SloUsageMetric (serviceLevelObjective, serviceLevelObjectiveId, inRangeTimeRatio)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceLevelObjective" Type="System.String" />
        <Parameter Name="serviceLevelObjectiveId" Type="System.Guid" />
        <Parameter Name="inRangeTimeRatio" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="serviceLevelObjective"><span data-ttu-id="ab50e-103">サービス レベル目標の SLO の使用状況メトリック。</span><span class="sxs-lookup"><span data-stu-id="ab50e-103">The serviceLevelObjective for SLO usage metric.</span></span> <span data-ttu-id="ab50e-104">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</span><span class="sxs-lookup"><span data-stu-id="ab50e-104">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span></param>
        <param name="serviceLevelObjectiveId"><span data-ttu-id="ab50e-105">SLO の使用状況メトリックの serviceLevelObjectiveId します。</span><span class="sxs-lookup"><span data-stu-id="ab50e-105">The serviceLevelObjectiveId for SLO usage metric.</span></span></param>
        <param name="inRangeTimeRatio"><span data-ttu-id="ab50e-106">取得または inRangeTimeRatio の SLO の使用状況メトリックを設定します。</span><span class="sxs-lookup"><span data-stu-id="ab50e-106">Gets or sets inRangeTimeRatio for SLO usage metric.</span></span></param>
        <summary>
            <span data-ttu-id="ab50e-107">SloUsageMetric クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ab50e-107">Initializes a new instance of the SloUsageMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InRangeTimeRatio">
      <MemberSignature Language="C#" Value="public double InRangeTimeRatio { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 InRangeTimeRatio" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SloUsageMetric.InRangeTimeRatio" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InRangeTimeRatio As Double" />
      <MemberSignature Language="F#" Value="member this.InRangeTimeRatio : double" Usage="Microsoft.Azure.Management.Sql.Models.SloUsageMetric.InRangeTimeRatio" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="inRangeTimeRatio")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab50e-108">取得または inRangeTimeRatio の SLO の使用状況メトリックを設定します。</span><span class="sxs-lookup"><span data-stu-id="ab50e-108">Gets or sets inRangeTimeRatio for SLO usage metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string ServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SloUsageMetric.ServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.SloUsageMetric.ServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="ab50e-109">SLO の使用状況メトリックのサービス レベル目標を取得します。</span><span class="sxs-lookup"><span data-stu-id="ab50e-109">Gets the serviceLevelObjective for SLO usage metric.</span></span> <span data-ttu-id="ab50e-110">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</span><span class="sxs-lookup"><span data-stu-id="ab50e-110">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjectiveId">
      <MemberSignature Language="C#" Value="public Guid ServiceLevelObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid ServiceLevelObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SloUsageMetric.ServiceLevelObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjectiveId As Guid" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjectiveId : Guid" Usage="Microsoft.Azure.Management.Sql.Models.SloUsageMetric.ServiceLevelObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceLevelObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ab50e-111">SLO の使用状況メトリックの serviceLevelObjectiveId を取得します。</span><span class="sxs-lookup"><span data-stu-id="ab50e-111">Gets the serviceLevelObjectiveId for SLO usage metric.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>