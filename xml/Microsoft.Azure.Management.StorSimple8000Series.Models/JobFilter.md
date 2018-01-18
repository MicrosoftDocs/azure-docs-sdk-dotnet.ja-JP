<Type Name="JobFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter">
  <TypeSignature Language="C#" Value="public class JobFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobFilter" />
  <TypeSignature Language="F#" Value="type JobFilter = class" />
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
            <span data-ttu-id="23907-101">ジョブに使用する OData フィルターです。</span><span class="sxs-lookup"><span data-stu-id="23907-101">The OData filter to be used for jobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23907-102">JobFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23907-102">Initializes a new instance of the JobFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobFilter (string status = null, string jobType = null, Nullable&lt;DateTime&gt; startTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string status, string jobType, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.#ctor(System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As String = null, Optional jobType As String = null, Optional startTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter : string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter (status, jobType, startTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="23907-103">フィルター処理するジョブの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="23907-103">Specifies the status of the jobs to be filtered.</span></span> <span data-ttu-id="23907-104">たとえば、"Running"、「成功」、「失敗」や「キャンセル」です。</span><span class="sxs-lookup"><span data-stu-id="23907-104">For e.g., "Running", "Succeeded", "Failed" or "Canceled".</span></span>
            <span data-ttu-id="23907-105">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="23907-105">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="jobType"><span data-ttu-id="23907-106">フィルター処理するジョブの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="23907-106">Specifies the type of the jobs to be filtered.</span></span> <span data-ttu-id="23907-107">例:"ScheduledBackup"、"ManualBackup"、"RestoreBackup"、"CloneVolume"、"FailoverVolumeContainers"、"CreateLocallyPinnedVolume"、"ModifyVolume"、"InstallUpdates"、"SupportPackageLogs"または"CreateCloudAppliance"です。</span><span class="sxs-lookup"><span data-stu-id="23907-107">For e.g., "ScheduledBackup", "ManualBackup", "RestoreBackup", "CloneVolume", "FailoverVolumeContainers", "CreateLocallyPinnedVolume", "ModifyVolume", "InstallUpdates", "SupportPackageLogs", or "CreateCloudAppliance".</span></span> <span data-ttu-id="23907-108">このプロパティの唯一の 'Equality' 演算子を使用できます。</span><span class="sxs-lookup"><span data-stu-id="23907-108">Only 'Equality' operator can be used for this property.</span></span></param>
        <param name="startTime"><span data-ttu-id="23907-109">フィルター処理するジョブの開始時刻を指定します。</span><span class="sxs-lookup"><span data-stu-id="23907-109">Specifies the start time of the jobs to be filtered.</span></span>  <span data-ttu-id="23907-110">のみ 'より大きいまたは等しい' および 'より小さいまたは等しいに' 演算子は、このプロパティに対してサポートされています。</span><span class="sxs-lookup"><span data-stu-id="23907-110">Only 'Greater Than or Equal To' and 'Lesser Than or Equal To' operators are supported for this property.</span></span></param>
        <summary>
            <span data-ttu-id="23907-111">JobFilter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="23907-111">Initializes a new instance of the JobFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobType">
      <MemberSignature Language="C#" Value="public string JobType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.JobType" />
      <MemberSignature Language="VB.NET" Value="Public Property JobType As String" />
      <MemberSignature Language="F#" Value="member this.JobType : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.JobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23907-112">取得または設定は、フィルター処理するジョブの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="23907-112">Gets or sets specifies the type of the jobs to be filtered.</span></span> <span data-ttu-id="23907-113">例:"ScheduledBackup"、"ManualBackup"、"RestoreBackup"、"CloneVolume"、"FailoverVolumeContainers"、"CreateLocallyPinnedVolume"、"ModifyVolume"、"InstallUpdates"、"SupportPackageLogs"または"CreateCloudAppliance"です。</span><span class="sxs-lookup"><span data-stu-id="23907-113">For e.g., "ScheduledBackup", "ManualBackup", "RestoreBackup", "CloneVolume", "FailoverVolumeContainers", "CreateLocallyPinnedVolume", "ModifyVolume", "InstallUpdates", "SupportPackageLogs", or "CreateCloudAppliance".</span></span> <span data-ttu-id="23907-114">このプロパティの唯一の 'Equality' 演算子を使用できます。</span><span class="sxs-lookup"><span data-stu-id="23907-114">Only 'Equality' operator can be used for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23907-115">取得または設定は、フィルター処理するジョブの開始時刻を指定します。</span><span class="sxs-lookup"><span data-stu-id="23907-115">Gets or sets specifies the start time of the jobs to be filtered.</span></span>
            <span data-ttu-id="23907-116">のみ 'より大きいまたは等しい' および 'より小さいまたは等しいに' 演算子は、このプロパティに対してサポートされています。</span><span class="sxs-lookup"><span data-stu-id="23907-116">Only 'Greater Than or Equal To' and 'Lesser Than or Equal To' operators are supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23907-117">取得または設定は、フィルター処理するジョブの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="23907-117">Gets or sets specifies the status of the jobs to be filtered.</span></span> <span data-ttu-id="23907-118">たとえば、"Running"、「成功」、「失敗」や「キャンセル」です。</span><span class="sxs-lookup"><span data-stu-id="23907-118">For e.g., "Running", "Succeeded", "Failed" or "Canceled".</span></span> <span data-ttu-id="23907-119">唯一の 'Equality' 演算子については、このプロパティのサポートします。</span><span class="sxs-lookup"><span data-stu-id="23907-119">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>