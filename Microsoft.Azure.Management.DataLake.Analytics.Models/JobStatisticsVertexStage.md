<Type Name="JobStatisticsVertexStage" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage">
  <TypeSignature Language="C#" Value="public class JobStatisticsVertexStage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobStatisticsVertexStage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage" />
  <TypeSignature Language="VB.NET" Value="Public Class JobStatisticsVertexStage" />
  <TypeSignature Language="F#" Value="type JobStatisticsVertexStage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bd128-101">Data Lake Analytics ジョブの頂点のステージの統計情報。</span><span class="sxs-lookup"><span data-stu-id="bd128-101">The Data Lake Analytics job statistics vertex stage information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStatisticsVertexStage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bd128-102">JobStatisticsVertexStage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bd128-102">Initializes a new instance of the JobStatisticsVertexStage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStatisticsVertexStage (Nullable&lt;long&gt; dataRead = null, Nullable&lt;long&gt; dataReadCrossPod = null, Nullable&lt;long&gt; dataReadIntraPod = null, Nullable&lt;long&gt; dataToRead = null, Nullable&lt;long&gt; dataWritten = null, Nullable&lt;int&gt; duplicateDiscardCount = null, Nullable&lt;int&gt; failedCount = null, Nullable&lt;long&gt; maxVertexDataRead = null, Nullable&lt;long&gt; minVertexDataRead = null, Nullable&lt;int&gt; readFailureCount = null, Nullable&lt;int&gt; revocationCount = null, Nullable&lt;int&gt; runningCount = null, Nullable&lt;int&gt; scheduledCount = null, string stageName = null, Nullable&lt;int&gt; succeededCount = null, Nullable&lt;long&gt; tempDataWritten = null, Nullable&lt;int&gt; totalCount = null, Nullable&lt;TimeSpan&gt; totalFailedTime = null, Nullable&lt;int&gt; totalProgress = null, Nullable&lt;TimeSpan&gt; totalSucceededTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; dataRead, valuetype System.Nullable`1&lt;int64&gt; dataReadCrossPod, valuetype System.Nullable`1&lt;int64&gt; dataReadIntraPod, valuetype System.Nullable`1&lt;int64&gt; dataToRead, valuetype System.Nullable`1&lt;int64&gt; dataWritten, valuetype System.Nullable`1&lt;int32&gt; duplicateDiscardCount, valuetype System.Nullable`1&lt;int32&gt; failedCount, valuetype System.Nullable`1&lt;int64&gt; maxVertexDataRead, valuetype System.Nullable`1&lt;int64&gt; minVertexDataRead, valuetype System.Nullable`1&lt;int32&gt; readFailureCount, valuetype System.Nullable`1&lt;int32&gt; revocationCount, valuetype System.Nullable`1&lt;int32&gt; runningCount, valuetype System.Nullable`1&lt;int32&gt; scheduledCount, string stageName, valuetype System.Nullable`1&lt;int32&gt; succeededCount, valuetype System.Nullable`1&lt;int64&gt; tempDataWritten, valuetype System.Nullable`1&lt;int32&gt; totalCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; totalFailedTime, valuetype System.Nullable`1&lt;int32&gt; totalProgress, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; totalSucceededTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dataRead As Nullable(Of Long) = null, Optional dataReadCrossPod As Nullable(Of Long) = null, Optional dataReadIntraPod As Nullable(Of Long) = null, Optional dataToRead As Nullable(Of Long) = null, Optional dataWritten As Nullable(Of Long) = null, Optional duplicateDiscardCount As Nullable(Of Integer) = null, Optional failedCount As Nullable(Of Integer) = null, Optional maxVertexDataRead As Nullable(Of Long) = null, Optional minVertexDataRead As Nullable(Of Long) = null, Optional readFailureCount As Nullable(Of Integer) = null, Optional revocationCount As Nullable(Of Integer) = null, Optional runningCount As Nullable(Of Integer) = null, Optional scheduledCount As Nullable(Of Integer) = null, Optional stageName As String = null, Optional succeededCount As Nullable(Of Integer) = null, Optional tempDataWritten As Nullable(Of Long) = null, Optional totalCount As Nullable(Of Integer) = null, Optional totalFailedTime As Nullable(Of TimeSpan) = null, Optional totalProgress As Nullable(Of Integer) = null, Optional totalSucceededTime As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage (dataRead, dataReadCrossPod, dataReadIntraPod, dataToRead, dataWritten, duplicateDiscardCount, failedCount, maxVertexDataRead, minVertexDataRead, readFailureCount, revocationCount, runningCount, scheduledCount, stageName, succeededCount, tempDataWritten, totalCount, totalFailedTime, totalProgress, totalSucceededTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataRead" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="dataReadCrossPod" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="dataReadIntraPod" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="dataToRead" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="dataWritten" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="duplicateDiscardCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="failedCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxVertexDataRead" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="minVertexDataRead" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="readFailureCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="revocationCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="runningCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="scheduledCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="stageName" Type="System.String" />
        <Parameter Name="succeededCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="tempDataWritten" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="totalCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="totalFailedTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="totalProgress" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="totalSucceededTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="dataRead"><span data-ttu-id="bd128-103">データの量は、バイト単位で読み取られます。</span><span class="sxs-lookup"><span data-stu-id="bd128-103">the amount of data read, in bytes.</span></span></param>
        <param name="dataReadCrossPod"><span data-ttu-id="bd128-104">データの量は、(バイト単位) の複数のポッド全体で読み取る。</span><span class="sxs-lookup"><span data-stu-id="bd128-104">the amount of data read across multiple pods, in bytes.</span></span></param>
        <param name="dataReadIntraPod"><span data-ttu-id="bd128-105">データの量は、(バイト単位) の 1 つの pod で読み取られます。</span><span class="sxs-lookup"><span data-stu-id="bd128-105">the amount of data read in one pod, in bytes.</span></span></param>
        <param name="dataToRead"><span data-ttu-id="bd128-106">残りのバイト単位で読み取られるデータの量。</span><span class="sxs-lookup"><span data-stu-id="bd128-106">the amount of data remaining to be read, in bytes.</span></span></param>
        <param name="dataWritten"><span data-ttu-id="bd128-107">(バイト単位)、書き込まれたデータの量。</span><span class="sxs-lookup"><span data-stu-id="bd128-107">the amount of data written, in bytes.</span></span></param>
        <param name="duplicateDiscardCount"><span data-ttu-id="bd128-108">破棄された重複部分の数。</span><span class="sxs-lookup"><span data-stu-id="bd128-108">the number of duplicates that were discarded.</span></span></param>
        <param name="failedCount"><span data-ttu-id="bd128-109">この段階で発生したエラーの数。</span><span class="sxs-lookup"><span data-stu-id="bd128-109">the number of failures that occured in this stage.</span></span></param>
        <param name="maxVertexDataRead"><span data-ttu-id="bd128-110">最大データ量は、(バイト単位) の 1 つの頂点で読み取られます。</span><span class="sxs-lookup"><span data-stu-id="bd128-110">the maximum amount of data read in a single vertex, in bytes.</span></span></param>
        <param name="minVertexDataRead"><span data-ttu-id="bd128-111">最小限のデータは、(バイト単位) の 1 つの頂点で読み取られます。</span><span class="sxs-lookup"><span data-stu-id="bd128-111">the minimum amount of data read in a single vertex, in bytes.</span></span></param>
        <param name="readFailureCount"><span data-ttu-id="bd128-112">この段階での読み取りエラーの数。</span><span class="sxs-lookup"><span data-stu-id="bd128-112">the number of read failures in this stage.</span></span></param>
        <param name="revocationCount"><span data-ttu-id="bd128-113">この段階で取り消された頂点の数。</span><span class="sxs-lookup"><span data-stu-id="bd128-113">the number of vertices that were revoked during this stage.</span></span></param>
        <param name="runningCount"><span data-ttu-id="bd128-114">この段階では、実行中の頂点の数。</span><span class="sxs-lookup"><span data-stu-id="bd128-114">the number of currently running vertices in this stage.</span></span></param>
        <param name="scheduledCount"><span data-ttu-id="bd128-115">この段階で現在のスケジュール済みの頂点の数</span><span class="sxs-lookup"><span data-stu-id="bd128-115">the number of currently scheduled vertices in this stage</span></span></param>
        <param name="stageName"><span data-ttu-id="bd128-116">ジョブの実行のこの段階での名前。</span><span class="sxs-lookup"><span data-stu-id="bd128-116">the name of this stage in job execution.</span></span></param>
        <param name="succeededCount"><span data-ttu-id="bd128-117">この段階で成功したことの頂点の数。</span><span class="sxs-lookup"><span data-stu-id="bd128-117">the number of vertices that succeeded in this stage.</span></span></param>
        <param name="tempDataWritten"><span data-ttu-id="bd128-118">バイト単位で記述された一時データの量。</span><span class="sxs-lookup"><span data-stu-id="bd128-118">the amount of temporary data written, in bytes.</span></span></param>
        <param name="totalCount"><span data-ttu-id="bd128-119">このステージの合計頂点の数。</span><span class="sxs-lookup"><span data-stu-id="bd128-119">the total vertex count for this stage.</span></span></param>
        <param name="totalFailedTime"><span data-ttu-id="bd128-120">頂点を失敗した時間は、この段階かかりました。</span><span class="sxs-lookup"><span data-stu-id="bd128-120">the amount of time that failed vertices took up in this stage.</span></span></param>
        <param name="totalProgress"><span data-ttu-id="bd128-121">この段階で、割合としての現在の進行状況。</span><span class="sxs-lookup"><span data-stu-id="bd128-121">the current progress of this stage, as a percentage.</span></span></param>
        <param name="totalSucceededTime"><span data-ttu-id="bd128-122">この段階で成功したすべての頂点にかかった時間の量。</span><span class="sxs-lookup"><span data-stu-id="bd128-122">the amount of time all successful vertices took in this stage.</span></span></param>
        <summary>
            <span data-ttu-id="bd128-123">JobStatisticsVertexStage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bd128-123">Initializes a new instance of the JobStatisticsVertexStage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataRead">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DataRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DataRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DataRead" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataRead As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DataRead : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DataRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataRead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-124">バイト単位で読み取られるデータの量を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-124">Gets the amount of data read, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataReadCrossPod">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DataReadCrossPod { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DataReadCrossPod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DataReadCrossPod" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataReadCrossPod As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DataReadCrossPod : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DataReadCrossPod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataReadCrossPod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-125">(バイト単位) の複数のポッド全体で読み取るデータの量を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-125">Gets the amount of data read across multiple pods, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataReadIntraPod">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DataReadIntraPod { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DataReadIntraPod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DataReadIntraPod" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataReadIntraPod As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DataReadIntraPod : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DataReadIntraPod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataReadIntraPod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-126">(バイト単位) の 1 つの pod で読み取られるデータの量を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-126">Gets the amount of data read in one pod, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataToRead">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DataToRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DataToRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DataToRead" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataToRead As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DataToRead : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DataToRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataToRead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-127">残りのバイト単位で読み取られるデータの量を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-127">Gets the amount of data remaining to be read, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataWritten">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DataWritten { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DataWritten" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DataWritten" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataWritten As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DataWritten : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DataWritten" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataWritten")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-128">(バイト単位)、書き込まれたデータの量を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-128">Gets the amount of data written, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDiscardCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DuplicateDiscardCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DuplicateDiscardCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DuplicateDiscardCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DuplicateDiscardCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DuplicateDiscardCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.DuplicateDiscardCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="duplicateDiscardCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-129">破棄された重複の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-129">Gets the number of duplicates that were discarded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailedCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FailedCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FailedCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.FailedCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FailedCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.FailedCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failedCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-130">この段階で発生したエラーの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-130">Gets the number of failures that occured in this stage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxVertexDataRead">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxVertexDataRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxVertexDataRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.MaxVertexDataRead" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxVertexDataRead As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxVertexDataRead : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.MaxVertexDataRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxVertexDataRead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-131">最大量 (バイト単位) の 1 つの頂点で読み取られるデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-131">Gets the maximum amount of data read in a single vertex, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinVertexDataRead">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MinVertexDataRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MinVertexDataRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.MinVertexDataRead" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinVertexDataRead As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MinVertexDataRead : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.MinVertexDataRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minVertexDataRead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-132">(バイト単位) の 1 つの頂点で読み取られるデータの最小量を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-132">Gets the minimum amount of data read in a single vertex, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadFailureCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ReadFailureCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ReadFailureCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.ReadFailureCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadFailureCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ReadFailureCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.ReadFailureCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="readFailureCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-133">この段階で読み取りエラーの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-133">Gets the number of read failures in this stage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevocationCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RevocationCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RevocationCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.RevocationCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RevocationCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RevocationCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.RevocationCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="revocationCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-134">この段階で取り消された頂点の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-134">Gets the number of vertices that were revoked during this stage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunningCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RunningCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RunningCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.RunningCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RunningCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RunningCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.RunningCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runningCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-135">この段階では、実行中の頂点の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-135">Gets the number of currently running vertices in this stage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ScheduledCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ScheduledCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.ScheduledCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ScheduledCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.ScheduledCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scheduledCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-136">この段階で現在のスケジュール済みの頂点の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-136">Gets the number of currently scheduled vertices in this stage</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StageName">
      <MemberSignature Language="C#" Value="public string StageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StageName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.StageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StageName As String" />
      <MemberSignature Language="F#" Value="member this.StageName : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.StageName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stageName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-137">ジョブの実行では、この段階の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-137">Gets the name of this stage in job execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SucceededCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SucceededCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SucceededCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.SucceededCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SucceededCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SucceededCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.SucceededCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="succeededCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-138">この段階で成功したことの頂点の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-138">Gets the number of vertices that succeeded in this stage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TempDataWritten">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TempDataWritten { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TempDataWritten" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.TempDataWritten" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TempDataWritten As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TempDataWritten : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.TempDataWritten" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tempDataWritten")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-139">バイト単位で記述された一時データの量を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-139">Gets the amount of temporary data written, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.TotalCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-140">このステージの合計頂点の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-140">Gets the total vertex count for this stage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalFailedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TotalFailedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TotalFailedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.TotalFailedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalFailedTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TotalFailedTime : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.TotalFailedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalFailedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-141">頂点を失敗した時間は取得この段階でかかりました。</span><span class="sxs-lookup"><span data-stu-id="bd128-141">Gets the amount of time that failed vertices took up in this stage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalProgress">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.TotalProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalProgress As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalProgress : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.TotalProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalProgress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-142">このステージの現在の進行状況をパーセンテージとして取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-142">Gets the current progress of this stage, as a percentage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalSucceededTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TotalSucceededTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TotalSucceededTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.TotalSucceededTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalSucceededTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TotalSucceededTime : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatisticsVertexStage.TotalSucceededTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalSucceededTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd128-143">この段階で成功したすべての頂点にかかった時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd128-143">Gets the amount of time all successful vertices took in this stage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>