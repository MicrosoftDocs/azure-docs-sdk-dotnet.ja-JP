<Type Name="ScheduleEntryInner" FullName="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner">
  <TypeSignature Language="C#" Value="public class ScheduleEntryInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduleEntryInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduleEntryInner" />
  <TypeSignature Language="F#" Value="type ScheduleEntryInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Premium Redis Cache のパッチ スケジュール エントリです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleEntryInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ScheduleEntryInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleEntryInner (Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int startHourUtc, Nullable&lt;TimeSpan&gt; maintenanceWindow = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek dayOfWeek, int32 startHourUtc, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maintenanceWindow) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.#ctor(Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek,System.Int32,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner : Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek * int * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner" Usage="new Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner (dayOfWeek, startHourUtc, maintenanceWindow)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dayOfWeek" Type="Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek" />
        <Parameter Name="startHourUtc" Type="System.Int32" />
        <Parameter Name="maintenanceWindow" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="dayOfWeek">曜日、キャッシュにパッチできるとします。 使用可能な値が含まれます: '月曜日'、'火曜日'、'水曜日'、'木曜日'、'金曜日'、'土曜日'、'日曜日'、'毎日'、'週末'</param>
        <param name="startHourUtc">開始時刻がどのキャッシュ後に修正プログラムの適用開始できます。</param>
        <param name="maintenanceWindow">ISO8601 timespan をどの程度時間キャッシュ修正プログラムの適用を指定することがかかることができます。 </param>
        <summary>
            ScheduleEntryInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DayOfWeek">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek DayOfWeek { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek DayOfWeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.DayOfWeek" />
      <MemberSignature Language="VB.NET" Value="Public Property DayOfWeek As DayOfWeek" />
      <MemberSignature Language="F#" Value="member this.DayOfWeek : Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.DayOfWeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dayOfWeek")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはの場合、キャッシュにパッチできる曜日を設定します。 使用可能な値が含まれます: '月曜日'、'火曜日'、'水曜日'、'木曜日'、'金曜日'、'土曜日'、'日曜日'、'毎日'、'週末'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaintenanceWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaintenanceWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaintenanceWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.MaintenanceWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property MaintenanceWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaintenanceWindow : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.MaintenanceWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maintenanceWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または ISO8601 timespan がかかることがどの程度時間キャッシュ修正プログラムの適用を指定することを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartHourUtc">
      <MemberSignature Language="C#" Value="public int StartHourUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StartHourUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.StartHourUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property StartHourUtc As Integer" />
      <MemberSignature Language="F#" Value="member this.StartHourUtc : int with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.StartHourUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startHourUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の開始時刻がどのキャッシュ後に修正プログラムの適用開始できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scheduleEntryInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
  </Members>
</Type>