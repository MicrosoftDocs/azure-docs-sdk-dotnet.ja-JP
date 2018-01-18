<Type Name="ScheduleRecurrence" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence">
  <TypeSignature Language="C#" Value="public class ScheduleRecurrence" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduleRecurrence extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduleRecurrence" />
  <TypeSignature Language="F#" Value="type ScheduleRecurrence = class" />
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
            <span data-ttu-id="81090-101">スケジュールの繰り返しです。</span><span class="sxs-lookup"><span data-stu-id="81090-101">The schedule recurrence.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleRecurrence ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="81090-102">ScheduleRecurrence クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="81090-102">Initializes a new instance of the ScheduleRecurrence class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleRecurrence (Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType recurrenceType, int recurrenceValue, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; weeklyDaysList = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType recurrenceType, int32 recurrenceValue, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; weeklyDaysList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType,System.Int32,System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek}})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence : Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType * int * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence (recurrenceType, recurrenceValue, weeklyDaysList)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recurrenceType" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType" />
        <Parameter Name="recurrenceValue" Type="System.Int32" />
        <Parameter Name="weeklyDaysList" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="recurrenceType"><span data-ttu-id="81090-103">繰り返しの種類。</span><span class="sxs-lookup"><span data-stu-id="81090-103">The recurrence type.</span></span> <span data-ttu-id="81090-104">使用可能な値が含まれます: '時間 (分)'、'毎時'、'毎日'、'毎週'</span><span class="sxs-lookup"><span data-stu-id="81090-104">Possible values include: 'Minutes', 'Hourly', 'Daily', 'Weekly'</span></span></param>
        <param name="recurrenceValue"><span data-ttu-id="81090-105">定期的な値です。</span><span class="sxs-lookup"><span data-stu-id="81090-105">The recurrence value.</span></span></param>
        <param name="weeklyDaysList"><span data-ttu-id="81090-106">週の日 ボックスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="81090-106">The week days list.</span></span> <span data-ttu-id="81090-107">スケジュールの定期的なパターン '毎週' にのみ適用できます。</span><span class="sxs-lookup"><span data-stu-id="81090-107">Applicable only for schedules of recurrence type 'weekly'.</span></span></param>
        <summary>
            <span data-ttu-id="81090-108">ScheduleRecurrence クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="81090-108">Initializes a new instance of the ScheduleRecurrence class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType RecurrenceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType RecurrenceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.RecurrenceType" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceType As RecurrenceType" />
      <MemberSignature Language="F#" Value="member this.RecurrenceType : Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.RecurrenceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrenceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.RecurrenceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81090-109">取得または繰り返しの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="81090-109">Gets or sets the recurrence type.</span></span> <span data-ttu-id="81090-110">使用可能な値が含まれます: '時間 (分)'、'毎時'、'毎日'、'毎週'</span><span class="sxs-lookup"><span data-stu-id="81090-110">Possible values include: 'Minutes', 'Hourly', 'Daily', 'Weekly'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceValue">
      <MemberSignature Language="C#" Value="public int RecurrenceValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RecurrenceValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.RecurrenceValue" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceValue As Integer" />
      <MemberSignature Language="F#" Value="member this.RecurrenceValue : int with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.RecurrenceValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrenceValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81090-111">取得または繰り返し値を設定します。</span><span class="sxs-lookup"><span data-stu-id="81090-111">Gets or sets the recurrence value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scheduleRecurrence.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="81090-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="81090-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="81090-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="81090-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WeeklyDaysList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; WeeklyDaysList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; WeeklyDaysList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.WeeklyDaysList" />
      <MemberSignature Language="VB.NET" Value="Public Property WeeklyDaysList As IList(Of Nullable(Of DayOfWeek))" />
      <MemberSignature Language="F#" Value="member this.WeeklyDaysList : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence.WeeklyDaysList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="weeklyDaysList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81090-114">取得または週の日の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="81090-114">Gets or sets the week days list.</span></span> <span data-ttu-id="81090-115">スケジュールの定期的なパターン '毎週' にのみ適用できます。</span><span class="sxs-lookup"><span data-stu-id="81090-115">Applicable only for schedules of recurrence type 'weekly'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>