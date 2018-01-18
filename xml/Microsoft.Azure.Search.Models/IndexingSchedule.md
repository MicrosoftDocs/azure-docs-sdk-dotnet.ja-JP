<Type Name="IndexingSchedule" FullName="Microsoft.Azure.Search.Models.IndexingSchedule">
  <TypeSignature Language="C#" Value="public class IndexingSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexingSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexingSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexingSchedule" />
  <TypeSignature Language="F#" Value="type IndexingSchedule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a5a52-101">インデクサー実行のスケジュールを表します。</span><span class="sxs-lookup"><span data-stu-id="a5a52-101">Represents a schedule for indexer execution.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a5a52-102">IndexingSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5a52-102">Initializes a new instance of the IndexingSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingSchedule (TimeSpan interval, Nullable&lt;DateTimeOffset&gt; startTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan interval, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingSchedule.#ctor(System.TimeSpan,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (interval As TimeSpan, Optional startTime As Nullable(Of DateTimeOffset) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexingSchedule : TimeSpan * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Azure.Search.Models.IndexingSchedule" Usage="new Microsoft.Azure.Search.Models.IndexingSchedule (interval, startTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="interval" Type="System.TimeSpan" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="interval"><span data-ttu-id="a5a52-103">インデクサー実行間の時間間隔。</span><span class="sxs-lookup"><span data-stu-id="a5a52-103">The interval of time between indexer executions.</span></span></param>
        <param name="startTime"><span data-ttu-id="a5a52-104">インデクサーを開始する時刻を実行しています。</span><span class="sxs-lookup"><span data-stu-id="a5a52-104">The time when an indexer should start running.</span></span></param>
        <summary>
            <span data-ttu-id="a5a52-105">IndexingSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a5a52-105">Initializes a new instance of the IndexingSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public TimeSpan Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingSchedule.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Interval : TimeSpan with get, set" Usage="Microsoft.Azure.Search.Models.IndexingSchedule.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="interval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5a52-106">取得またはインデクサー実行間の時間間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="a5a52-106">Gets or sets the interval of time between indexer executions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingSchedule.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexingSchedule.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5a52-107">インデクサーを開始する時刻を取得またはを実行しています。</span><span class="sxs-lookup"><span data-stu-id="a5a52-107">Gets or sets the time when an indexer should start running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingSchedule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="indexingSchedule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a5a52-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a5a52-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a5a52-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a5a52-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>