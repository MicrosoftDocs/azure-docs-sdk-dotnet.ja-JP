<Type Name="RecurrenceScheduleOccurrence" FullName="Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence">
  <TypeSignature Language="C#" Value="public class RecurrenceScheduleOccurrence" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecurrenceScheduleOccurrence extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence" />
  <TypeSignature Language="VB.NET" Value="Public Class RecurrenceScheduleOccurrence" />
  <TypeSignature Language="F#" Value="type RecurrenceScheduleOccurrence = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="841f5-101">定期的なスケジュールの実行です。</span><span class="sxs-lookup"><span data-stu-id="841f5-101">The recurrence schedule occurence.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecurrenceScheduleOccurrence ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="841f5-102">RecurrenceScheduleOccurrence クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="841f5-102">Initializes a new instance of the RecurrenceScheduleOccurrence class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecurrenceScheduleOccurrence (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DayOfWeek&gt; day = null, Nullable&lt;int&gt; occurrence = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataFactory.Models.DayOfWeek&gt; day, valuetype System.Nullable`1&lt;int32&gt; occurrence) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Nullable{Microsoft.Azure.Management.DataFactory.Models.DayOfWeek},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional day As Nullable(Of DayOfWeek) = null, Optional occurrence As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence : System.Collections.Generic.IDictionary&lt;string, obj&gt; * Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DayOfWeek&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence" Usage="new Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence (additionalProperties, day, occurrence)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="day" Type="System.Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DayOfWeek&gt;" />
        <Parameter Name="occurrence" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="841f5-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="841f5-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="day"><span data-ttu-id="841f5-104">週の日です。</span><span class="sxs-lookup"><span data-stu-id="841f5-104">The day of the week.</span></span> <span data-ttu-id="841f5-105">使用可能な値が含まれます: '日曜日'、'月曜日'、'火曜日'、'水曜日'、'木曜日'、'金曜日'、'土曜日'</span><span class="sxs-lookup"><span data-stu-id="841f5-105">Possible values include: 'Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'</span></span></param>
        <param name="occurrence"><span data-ttu-id="841f5-106">出現します。</span><span class="sxs-lookup"><span data-stu-id="841f5-106">The occurrence.</span></span></param>
        <summary>
            <span data-ttu-id="841f5-107">RecurrenceScheduleOccurrence クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="841f5-107">Initializes a new instance of the RecurrenceScheduleOccurrence class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="841f5-108">メッセージから一致しないプロパティを取得または設定は、このコレクションを逆シリアル化</span><span class="sxs-lookup"><span data-stu-id="841f5-108">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Day">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DayOfWeek&gt; Day { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataFactory.Models.DayOfWeek&gt; Day" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence.Day" />
      <MemberSignature Language="VB.NET" Value="Public Property Day As Nullable(Of DayOfWeek)" />
      <MemberSignature Language="F#" Value="member this.Day : Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DayOfWeek&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence.Day" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="day")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataFactory.Models.DayOfWeek&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="841f5-109">取得または週の曜日を設定します。</span><span class="sxs-lookup"><span data-stu-id="841f5-109">Gets or sets the day of the week.</span></span> <span data-ttu-id="841f5-110">使用可能な値が含まれます: '日曜日'、'月曜日'、'火曜日'、'水曜日'、'木曜日'、'金曜日'、'土曜日'</span><span class="sxs-lookup"><span data-stu-id="841f5-110">Possible values include: 'Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Occurrence">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Occurrence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Occurrence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence.Occurrence" />
      <MemberSignature Language="VB.NET" Value="Public Property Occurrence As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Occurrence : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RecurrenceScheduleOccurrence.Occurrence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="occurrence")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="841f5-111">取得または、出現する位置を設定します。</span><span class="sxs-lookup"><span data-stu-id="841f5-111">Gets or sets the occurrence.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>