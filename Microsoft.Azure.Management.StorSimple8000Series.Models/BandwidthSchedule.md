<Type Name="BandwidthSchedule" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule">
  <TypeSignature Language="C#" Value="public class BandwidthSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BandwidthSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class BandwidthSchedule" />
  <TypeSignature Language="F#" Value="type BandwidthSchedule = class" />
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
            <span data-ttu-id="ead09-101">帯域幅の設定のスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="ead09-101">The schedule for bandwidth setting.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BandwidthSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ead09-102">BandwidthSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ead09-102">Initializes a new instance of the BandwidthSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BandwidthSchedule (Microsoft.Azure.Management.StorSimple8000Series.Models.Time start, Microsoft.Azure.Management.StorSimple8000Series.Models.Time stop, int rateInMbps, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; days);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.Time start, class Microsoft.Azure.Management.StorSimple8000Series.Models.Time stop, int32 rateInMbps, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; days) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.Time,Microsoft.Azure.Management.StorSimple8000Series.Models.Time,System.Int32,System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (start As Time, stop As Time, rateInMbps As Integer, days As IList(Of Nullable(Of DayOfWeek)))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule : Microsoft.Azure.Management.StorSimple8000Series.Models.Time * Microsoft.Azure.Management.StorSimple8000Series.Models.Time * int * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule (start, stop, rateInMbps, days)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Time" />
        <Parameter Name="stop" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Time" />
        <Parameter Name="rateInMbps" Type="System.Int32" />
        <Parameter Name="days" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="start"><span data-ttu-id="ead09-103">Schdule の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="ead09-103">The start time of the schdule.</span></span></param>
        <param name="stop"><span data-ttu-id="ead09-104">スケジュールの終了時刻。</span><span class="sxs-lookup"><span data-stu-id="ead09-104">The stop time of the schedule.</span></span></param>
        <param name="rateInMbps"><span data-ttu-id="ead09-105">Mbps レートです。</span><span class="sxs-lookup"><span data-stu-id="ead09-105">The rate in Mbps.</span></span></param>
        <param name="days"><span data-ttu-id="ead09-106">このスケジュールは該当する場合、週の日です。</span><span class="sxs-lookup"><span data-stu-id="ead09-106">The days of the week when this schedule is applicable.</span></span></param>
        <summary>
            <span data-ttu-id="ead09-107">BandwidthSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ead09-107">Initializes a new instance of the BandwidthSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Days">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; Days { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; Days" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule.Days" />
      <MemberSignature Language="VB.NET" Value="Public Property Days As IList(Of Nullable(Of DayOfWeek))" />
      <MemberSignature Language="F#" Value="member this.Days : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule.Days" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="days")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.DayOfWeek&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ead09-108">取得または、このスケジュールは該当するときに曜日を設定します。</span><span class="sxs-lookup"><span data-stu-id="ead09-108">Gets or sets the days of the week when this schedule is applicable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RateInMbps">
      <MemberSignature Language="C#" Value="public int RateInMbps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RateInMbps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule.RateInMbps" />
      <MemberSignature Language="VB.NET" Value="Public Property RateInMbps As Integer" />
      <MemberSignature Language="F#" Value="member this.RateInMbps : int with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule.RateInMbps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rateInMbps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ead09-109">取得または mbps、レートを設定します。</span><span class="sxs-lookup"><span data-stu-id="ead09-109">Gets or sets the rate in Mbps.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.Time Start { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.Time Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule.Start" />
      <MemberSignature Language="VB.NET" Value="Public Property Start As Time" />
      <MemberSignature Language="F#" Value="member this.Start : Microsoft.Azure.Management.StorSimple8000Series.Models.Time with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="start")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Time</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ead09-110">取得または、schdule の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="ead09-110">Gets or sets the start time of the schdule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.Time Stop { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.Time Stop" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule.Stop" />
      <MemberSignature Language="VB.NET" Value="Public Property Stop As Time" />
      <MemberSignature Language="F#" Value="member this.Stop : Microsoft.Azure.Management.StorSimple8000Series.Models.Time with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule.Stop" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stop")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Time</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ead09-111">取得またはスケジュールの終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="ead09-111">Gets or sets the stop time of the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BandwidthSchedule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="bandwidthSchedule.Validate " />
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
            <span data-ttu-id="ead09-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ead09-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ead09-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ead09-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>