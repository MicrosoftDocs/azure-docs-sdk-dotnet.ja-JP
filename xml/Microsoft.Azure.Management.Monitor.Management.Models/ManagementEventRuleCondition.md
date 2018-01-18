<Type Name="ManagementEventRuleCondition" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventRuleCondition">
  <TypeSignature Language="C#" Value="public class ManagementEventRuleCondition : Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementEventRuleCondition extends Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventRuleCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementEventRuleCondition&#xA;Inherits RuleCondition" />
  <TypeSignature Language="F#" Value="type ManagementEventRuleCondition = class&#xA;    inherit RuleCondition" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Azure.Management.Insights.Models.ManagementEventRuleCondition")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="092c6-101">管理イベント ルールの条件。</span><span class="sxs-lookup"><span data-stu-id="092c6-101">A management event rule condition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementEventRuleCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventRuleCondition.#ctor" />
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
            <span data-ttu-id="092c6-102">ManagementEventRuleCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="092c6-102">Initializes a new instance of the ManagementEventRuleCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementEventRuleCondition (Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource = null, Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition aggregation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource, class Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition aggregation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventRuleCondition.#ctor(Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource,Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dataSource As RuleDataSource = null, Optional aggregation As ManagementEventAggregationCondition = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventRuleCondition : Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource * Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventRuleCondition" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventRuleCondition (dataSource, aggregation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataSource" Type="Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource" />
        <Parameter Name="aggregation" Type="Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition" />
      </Parameters>
      <Docs>
        <param name="dataSource"><span data-ttu-id="092c6-103">ルールがそのデータを収集元となるリソースです。</span><span class="sxs-lookup"><span data-stu-id="092c6-103">the resource from which the rule collects its data.</span></span> <span data-ttu-id="092c6-104">この種類のデータ ソースが必ず型 RuleMetricDataSource の。</span><span class="sxs-lookup"><span data-stu-id="092c6-104">For this type dataSource will always be of type RuleMetricDataSource.</span></span></param>
        <param name="aggregation"><span data-ttu-id="092c6-105">方法と、アラートが有効な場合は、収集されるデータを組み合わせる必要があります。</span><span class="sxs-lookup"><span data-stu-id="092c6-105">How the data that is collected should be combined over time and when the alert is activated.</span></span> <span data-ttu-id="092c6-106">管理イベントのアラートの集計の省略可能 – すべてのイベントが指定されていない場合は、アラートがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="092c6-106">Note that for management event alerts aggregation is optional – if it is not provided then any event will cause the alert to activate.</span></span></param>
        <summary>
            <span data-ttu-id="092c6-107">ManagementEventRuleCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="092c6-107">Initializes a new instance of the ManagementEventRuleCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Aggregation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition Aggregation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition Aggregation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventRuleCondition.Aggregation" />
      <MemberSignature Language="VB.NET" Value="Public Property Aggregation As ManagementEventAggregationCondition" />
      <MemberSignature Language="F#" Value="member this.Aggregation : Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventRuleCondition.Aggregation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aggregation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="092c6-108">取得または時間の経過と共に収集されるデータを結合する方法と、アラートがアクティブになったときに設定します。</span><span class="sxs-lookup"><span data-stu-id="092c6-108">Gets or sets how the data that is collected should be combined over time and when the alert is activated.</span></span> <span data-ttu-id="092c6-109">管理イベントのアラートの集計の省略可能 – すべてのイベントが指定されていない場合は、アラートがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="092c6-109">Note that for management event alerts aggregation is optional – if it is not provided then any event will cause the alert to activate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>