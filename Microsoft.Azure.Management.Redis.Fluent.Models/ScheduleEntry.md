<Type Name="ScheduleEntry" FullName="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry">
  <TypeSignature Language="C#" Value="public class ScheduleEntry : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Wrapper&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScheduleEntry extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.Wrapper`1&lt;class Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry" />
  <TypeSignature Language="VB.NET" Value="Public Class ScheduleEntry&#xA;Inherits Wrapper(Of ScheduleEntryInner)" />
  <TypeSignature Language="F#" Value="type ScheduleEntry = class&#xA;    inherit Wrapper&lt;ScheduleEntryInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Wrapper&lt;Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5dac3-101">Premium Redis Cache のパッチ スケジュール エントリです。</span><span class="sxs-lookup"><span data-stu-id="5dac3-101">Patch schedule entry for a Premium Redis Cache.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScheduleEntry (Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry.#ctor(Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inner As ScheduleEntryInner)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry : Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner -&gt; Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry" Usage="new Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry inner" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inner" Type="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntryInner" />
      </Parameters>
      <Docs>
        <param name="inner">To be added.</param>
        <summary>
            <span data-ttu-id="5dac3-102">ScheduleEntry クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5dac3-102">Initializes a new instance of the ScheduleEntry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DayOfWeek">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek DayOfWeek { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek DayOfWeek" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry.DayOfWeek" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DayOfWeek As DayOfWeek" />
      <MemberSignature Language="F#" Value="member this.DayOfWeek : Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry.DayOfWeek" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.Models.DayOfWeek</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5dac3-103">取得またはの場合、キャッシュにパッチできる曜日を設定します。</span><span class="sxs-lookup"><span data-stu-id="5dac3-103">Gets or sets day of the week when a cache can be patched.</span></span> <span data-ttu-id="5dac3-104">使用可能な値が含まれます: '月曜日'、'火曜日'、'水曜日'、'木曜日'、'金曜日'、'土曜日'、'日曜日'、'毎日'、'週末'</span><span class="sxs-lookup"><span data-stu-id="5dac3-104">Possible values include: 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday', 'Sunday', 'Everyday', 'Weekend'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaintenanceWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaintenanceWindow { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaintenanceWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry.MaintenanceWindow" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaintenanceWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaintenanceWindow : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry.MaintenanceWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5dac3-105">取得または ISO8601 timespan がかかることがどの程度時間キャッシュ修正プログラムの適用を指定することを設定します。</span><span class="sxs-lookup"><span data-stu-id="5dac3-105">Gets or sets ISO8601 timespan specifying how much time cache patching can take.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartHourUtc">
      <MemberSignature Language="C#" Value="public int StartHourUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StartHourUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry.StartHourUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartHourUtc As Integer" />
      <MemberSignature Language="F#" Value="member this.StartHourUtc : int" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ScheduleEntry.StartHourUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5dac3-106">取得または設定の開始時刻がどのキャッシュ後に修正プログラムの適用開始できます。</span><span class="sxs-lookup"><span data-stu-id="5dac3-106">Gets or sets start hour after which cache patching can start.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>