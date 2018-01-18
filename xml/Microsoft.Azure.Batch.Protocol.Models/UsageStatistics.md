<Type Name="UsageStatistics" FullName="Microsoft.Azure.Batch.Protocol.Models.UsageStatistics">
  <TypeSignature Language="C#" Value="public class UsageStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UsageStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class UsageStatistics" />
  <TypeSignature Language="F#" Value="type UsageStatistics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="66aef-101">プールの利用状況情報に関連する統計。</span><span class="sxs-lookup"><span data-stu-id="66aef-101">Statistics related to pool usage information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66aef-102">UsageStatistics クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="66aef-102">Initializes a new instance of the UsageStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UsageStatistics (DateTime startTime, DateTime lastUpdateTime, TimeSpan dedicatedCoreTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime startTime, valuetype System.DateTime lastUpdateTime, valuetype System.TimeSpan dedicatedCoreTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.#ctor(System.DateTime,System.DateTime,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (startTime As DateTime, lastUpdateTime As DateTime, dedicatedCoreTime As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.UsageStatistics : DateTime * DateTime * TimeSpan -&gt; Microsoft.Azure.Batch.Protocol.Models.UsageStatistics" Usage="new Microsoft.Azure.Batch.Protocol.Models.UsageStatistics (startTime, lastUpdateTime, dedicatedCoreTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="lastUpdateTime" Type="System.DateTime" />
        <Parameter Name="dedicatedCoreTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="startTime"><span data-ttu-id="66aef-103">統計情報の時間範囲の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="66aef-103">The start time of the time range covered by the statistics.</span></span></param>
        <param name="lastUpdateTime"><span data-ttu-id="66aef-104">これで、統計の最終更新時刻。</span><span class="sxs-lookup"><span data-stu-id="66aef-104">The time at which the statistics were last updated.</span></span> <span data-ttu-id="66aef-105">すべての統計情報は、startTime と lastUpdateTime 間の範囲に制限されます。</span><span class="sxs-lookup"><span data-stu-id="66aef-105">All statistics are limited to the range between startTime and lastUpdateTime.</span></span></param>
        <param name="dedicatedCoreTime"><span data-ttu-id="66aef-106">専用の集計されたウォール クロック時間は、プールの一部であるノードのコアを計算します。</span><span class="sxs-lookup"><span data-stu-id="66aef-106">The aggregated wall-clock time of the dedicated compute node cores being part of the pool.</span></span></param>
        <summary>
            <span data-ttu-id="66aef-107">UsageStatistics クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="66aef-107">Initializes a new instance of the UsageStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DedicatedCoreTime">
      <MemberSignature Language="C#" Value="public TimeSpan DedicatedCoreTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DedicatedCoreTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.DedicatedCoreTime" />
      <MemberSignature Language="VB.NET" Value="Public Property DedicatedCoreTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DedicatedCoreTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.DedicatedCoreTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dedicatedCoreTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66aef-108">取得またはノード コアのプールの一部である専用のコンピューティングの集計されたウォール クロック時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="66aef-108">Gets or sets the aggregated wall-clock time of the dedicated compute node cores being part of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66aef-109">取得または設定する、統計の最終更新時刻。</span><span class="sxs-lookup"><span data-stu-id="66aef-109">Gets or sets the time at which the statistics were last updated.</span></span>
            <span data-ttu-id="66aef-110">すべての統計情報は、startTime と lastUpdateTime 間の範囲に制限されます。</span><span class="sxs-lookup"><span data-stu-id="66aef-110">All statistics are limited to the range between startTime and lastUpdateTime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66aef-111">取得または統計の時間範囲の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="66aef-111">Gets or sets the start time of the time range covered by the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.UsageStatistics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="usageStatistics.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66aef-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="66aef-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="66aef-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="66aef-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>