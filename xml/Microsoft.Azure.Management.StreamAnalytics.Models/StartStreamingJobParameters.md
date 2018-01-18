<Type Name="StartStreamingJobParameters" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters">
  <TypeSignature Language="C#" Value="public class StartStreamingJobParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StartStreamingJobParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class StartStreamingJobParameters" />
  <TypeSignature Language="F#" Value="type StartStreamingJobParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="779ef-101">パラメーターは、ストリーミング ジョブの開始操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="779ef-101">Parameters supplied to the Start Streaming Job operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartStreamingJobParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="779ef-102">StartStreamingJobParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="779ef-102">Initializes a new instance of the StartStreamingJobParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartStreamingJobParameters (string outputStartMode = null, Nullable&lt;DateTime&gt; outputStartTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string outputStartMode, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; outputStartTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.#ctor(System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional outputStartMode As String = null, Optional outputStartTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters : string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters (outputStartMode, outputStartTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="outputStartMode" Type="System.String" />
        <Parameter Name="outputStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="outputStartMode"><span data-ttu-id="779ef-103">値は JobStartTime、CustomTime、または lastoutputeventtime ですジョブを起動するたびに、出力イベント ストリームの開始位置を開始する必要がありますかどうかを示すためにあります outputStartTime プロパティを介して指定されたカスタム ユーザー タイムスタンプで開始 またはから開始します。最後のイベントは、時間を出力します。</span><span class="sxs-lookup"><span data-stu-id="779ef-103">Value may be JobStartTime, CustomTime, or LastOutputEventTime to indicate whether the starting point of the output event stream should start whenever the job is started, start at a custom user time stamp specified via the outputStartTime property, or start from the last event output time.</span></span>
            <span data-ttu-id="779ef-104">使用可能な値が含まれます: 'JobStartTime'、'CustomTime'、'LastOutputEventTime'</span><span class="sxs-lookup"><span data-stu-id="779ef-104">Possible values include: 'JobStartTime', 'CustomTime', 'LastOutputEventTime'</span></span></param>
        <param name="outputStartTime"><span data-ttu-id="779ef-105">値がいずれか、ISO 8601 形式のタイムスタンプを出力イベント ストリームの開始位置を示すか、出力イベント ストリームが開始されていることを示す null をするたびに、ストリーミング ジョブが開始します。</span><span class="sxs-lookup"><span data-stu-id="779ef-105">Value is either an ISO-8601 formatted time stamp that indicates the starting point of the output event stream, or null to indicate that the output event stream will start whenever the streaming job is started.</span></span> <span data-ttu-id="779ef-106">このプロパティは、outputStartMode が CustomTime に設定されている場合、値にすることが必要です。</span><span class="sxs-lookup"><span data-stu-id="779ef-106">This property must have a value if outputStartMode is set to CustomTime.</span></span></param>
        <summary>
            <span data-ttu-id="779ef-107">StartStreamingJobParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="779ef-107">Initializes a new instance of the StartStreamingJobParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartMode">
      <MemberSignature Language="C#" Value="public string OutputStartMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputStartMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartMode" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartMode As String" />
      <MemberSignature Language="F#" Value="member this.OutputStartMode : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputStartMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="779ef-108">取得または設定の値は JobStartTime、CustomTime、または lastoutputeventtime ですジョブを起動するたびに、出力イベント ストリームの開始位置を開始する必要がありますかどうかを示す可能性がありますが、outputStartTime プロパティを介して指定されたカスタム ユーザー タイムスタンプで開始または。最後のイベント出力時刻から開始します。</span><span class="sxs-lookup"><span data-stu-id="779ef-108">Gets or sets value may be JobStartTime, CustomTime, or LastOutputEventTime to indicate whether the starting point of the output event stream should start whenever the job is started, start at a custom user time stamp specified via the outputStartTime property, or start from the last event output time.</span></span> <span data-ttu-id="779ef-109">使用可能な値が含まれます: 'JobStartTime'、'CustomTime'、'LastOutputEventTime'</span><span class="sxs-lookup"><span data-stu-id="779ef-109">Possible values include: 'JobStartTime', 'CustomTime', 'LastOutputEventTime'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OutputStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OutputStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OutputStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="779ef-110">取得または設定の値がいずれか、ISO 8601 形式のタイムスタンプを出力イベント ストリームの開始位置を示すか、出力イベント ストリームが開始されていることを示す null をするたびに、ストリーミング ジョブが開始します。</span><span class="sxs-lookup"><span data-stu-id="779ef-110">Gets or sets value is either an ISO-8601 formatted time stamp that indicates the starting point of the output event stream, or null to indicate that the output event stream will start whenever the streaming job is started.</span></span> <span data-ttu-id="779ef-111">このプロパティは、outputStartMode が CustomTime に設定されている場合、値にすることが必要です。</span><span class="sxs-lookup"><span data-stu-id="779ef-111">This property must have a value if outputStartMode is set to CustomTime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>