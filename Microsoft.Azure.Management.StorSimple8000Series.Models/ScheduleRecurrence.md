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
            スケジュールの繰り返しです。
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
            ScheduleRecurrence クラスの新しいインスタンスを初期化します。
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
        <param name="recurrenceType">繰り返しの種類。 使用可能な値が含まれます: '時間 (分)'、'毎時'、'毎日'、'毎週'</param>
        <param name="recurrenceValue">定期的な値です。</param>
        <param name="weeklyDaysList">週の日 ボックスの一覧です。 スケジュールの定期的なパターン '毎週' にのみ適用できます。</param>
        <summary>
            ScheduleRecurrence クラスの新しいインスタンスを初期化します。
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
            取得または繰り返しの種類を設定します。 使用可能な値が含まれます: '時間 (分)'、'毎時'、'毎日'、'毎週'
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
            取得または繰り返し値を設定します。
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
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
            取得または週の日の一覧を設定します。 スケジュールの定期的なパターン '毎週' にのみ適用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>