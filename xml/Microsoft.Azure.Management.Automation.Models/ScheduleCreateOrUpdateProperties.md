<Type Name="ScheduleCreateOrUpdateProperties" FullName="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties">
  <TypeSignature Language="C#" Value="public class ScheduleCreateOrUpdateProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduleCreateOrUpdateProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduleCreateOrUpdateProperties" />
  <TypeSignature Language="F#" Value="type ScheduleCreateOrUpdateProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2f024-101">作成または更新のスケジュール操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="2f024-101">The parameters supplied to the create or update schedule operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleCreateOrUpdateProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2f024-102">ScheduleCreateOrUpdateProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2f024-102">Initializes a new instance of the ScheduleCreateOrUpdateProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleCreateOrUpdateProperties (DateTimeOffset startTime, string frequency);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTimeOffset startTime, string frequency) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.#ctor(System.DateTimeOffset,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startTime As DateTimeOffset, frequency As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties : DateTimeOffset * string -&gt; Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties" Usage="new Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties (startTime, frequency)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="frequency" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startTime">To be added.</param>
        <param name="frequency">To be added.</param>
        <summary>
            <span data-ttu-id="2f024-103">必須の引数で ScheduleCreateOrUpdateProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2f024-103">Initializes a new instance of the ScheduleCreateOrUpdateProperties class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdvancedSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.AdvancedSchedule AdvancedSchedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.AdvancedSchedule AdvancedSchedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.AdvancedSchedule" />
      <MemberSignature Language="VB.NET" Value="Public Property AdvancedSchedule As AdvancedSchedule" />
      <MemberSignature Language="F#" Value="member this.AdvancedSchedule : Microsoft.Azure.Management.Automation.Models.AdvancedSchedule with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.AdvancedSchedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AdvancedSchedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f024-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2f024-104">Optional.</span></span> <span data-ttu-id="2f024-105">取得または、AdvancedSchedule を設定します。</span><span class="sxs-lookup"><span data-stu-id="2f024-105">Gets or sets the AdvancedSchedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f024-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2f024-106">Optional.</span></span> <span data-ttu-id="2f024-107">取得またはスケジュールの説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="2f024-107">Gets or sets the description of the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; ExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; ExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.ExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpiryTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.ExpiryTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.ExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f024-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2f024-108">Optional.</span></span> <span data-ttu-id="2f024-109">取得またはスケジュールの終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="2f024-109">Gets or sets the end time of the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frequency">
      <MemberSignature Language="C#" Value="public string Frequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Frequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.Frequency" />
      <MemberSignature Language="VB.NET" Value="Public Property Frequency As String" />
      <MemberSignature Language="F#" Value="member this.Frequency : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.Frequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f024-110">必須。</span><span class="sxs-lookup"><span data-stu-id="2f024-110">Required.</span></span> <span data-ttu-id="2f024-111">取得またはスケジュールの頻度を設定します。</span><span class="sxs-lookup"><span data-stu-id="2f024-111">Gets or sets the frequency of the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public Nullable&lt;byte&gt; Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;unsigned int8&gt; Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As Nullable(Of Byte)" />
      <MemberSignature Language="F#" Value="member this.Interval : Nullable&lt;byte&gt; with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Byte&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f024-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2f024-112">Optional.</span></span> <span data-ttu-id="2f024-113">取得またはスケジュールの間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="2f024-113">Gets or sets the interval of the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTimeOffset StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTimeOffset with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f024-114">必須。</span><span class="sxs-lookup"><span data-stu-id="2f024-114">Required.</span></span> <span data-ttu-id="2f024-115">取得またはスケジュールの開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="2f024-115">Gets or sets the start time of the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ScheduleCreateOrUpdateProperties.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2f024-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2f024-116">Optional.</span></span> <span data-ttu-id="2f024-117">取得またはスケジュールのタイム ゾーンを設定します。</span><span class="sxs-lookup"><span data-stu-id="2f024-117">Gets or sets the time zone of the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>