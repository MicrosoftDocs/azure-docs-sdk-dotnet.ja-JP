<Type Name="LocationThresholdRuleCondition" FullName="Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition">
  <TypeSignature Language="C#" Value="public class LocationThresholdRuleCondition : Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LocationThresholdRuleCondition extends Microsoft.Azure.Management.Monitor.Management.Models.RuleCondition" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class LocationThresholdRuleCondition&#xA;Inherits RuleCondition" />
  <TypeSignature Language="F#" Value="type LocationThresholdRuleCondition = class&#xA;    inherit RuleCondition" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Azure.Management.Insights.Models.LocationThresholdRuleCondition")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e3fb1-101">失敗した場所の特定の数に基づいてルールの条件。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-101">A rule condition based on a certain number of locations failing.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocationThresholdRuleCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.#ctor" />
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
            <span data-ttu-id="e3fb1-102">LocationThresholdRuleCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-102">Initializes a new instance of the LocationThresholdRuleCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocationThresholdRuleCondition (int failedLocationCount, Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource = null, Nullable&lt;TimeSpan&gt; windowSize = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 failedLocationCount, class Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource dataSource, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; windowSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.#ctor(System.Int32,Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (failedLocationCount As Integer, Optional dataSource As RuleDataSource = null, Optional windowSize As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition : int * Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition (failedLocationCount, dataSource, windowSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="failedLocationCount" Type="System.Int32" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Management.Monitor.Management.Models.RuleDataSource" />
        <Parameter Name="windowSize" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="failedLocationCount"><span data-ttu-id="e3fb1-103">アラートをアクティブ化に失敗する場所の数。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-103">the number of locations that must fail to activate the alert.</span></span></param>
        <param name="dataSource"><span data-ttu-id="e3fb1-104">ルールがそのデータを収集元となるリソースです。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-104">the resource from which the rule collects its data.</span></span> <span data-ttu-id="e3fb1-105">この種類のデータ ソースが必ず型 RuleMetricDataSource の。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-105">For this type dataSource will always be of type RuleMetricDataSource.</span></span></param>
        <param name="windowSize"><span data-ttu-id="e3fb1-106">期間 (ISO 8601 期間形式) でのしきい値に基づいてアラート アクティビティを監視するために使用します。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-106">the period of time (in ISO 8601 duration format) that is used to monitor alert activity based on the threshold.</span></span> <span data-ttu-id="e3fb1-107">5 分から 1 日の間でなければなりませんし、指定されている場合。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-107">If specified then it must be between 5 minutes and 1 day.</span></span></param>
        <summary>
            <span data-ttu-id="e3fb1-108">LocationThresholdRuleCondition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-108">Initializes a new instance of the LocationThresholdRuleCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedLocationCount">
      <MemberSignature Language="C#" Value="public int FailedLocationCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FailedLocationCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.FailedLocationCount" />
      <MemberSignature Language="VB.NET" Value="Public Property FailedLocationCount As Integer" />
      <MemberSignature Language="F#" Value="member this.FailedLocationCount : int with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.FailedLocationCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failedLocationCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3fb1-109">取得またはアラートをアクティブ化に失敗する場所の数を設定します。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-109">Gets or sets the number of locations that must fail to activate the alert.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="locationThresholdRuleCondition.Validate " />
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
            <span data-ttu-id="e3fb1-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e3fb1-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WindowSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; WindowSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; WindowSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.WindowSize" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowSize As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.WindowSize : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.LocationThresholdRuleCondition.WindowSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3fb1-112">取得または設定の時間 (ISO 8601 期間形式) のしきい値に基づいてアラート アクティビティを監視するために使用します。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-112">Gets or sets the period of time (in ISO 8601 duration format) that is used to monitor alert activity based on the threshold.</span></span> <span data-ttu-id="e3fb1-113">5 分から 1 日の間でなければなりませんし、指定されている場合。</span><span class="sxs-lookup"><span data-stu-id="e3fb1-113">If specified then it must be between 5 minutes and 1 day.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>