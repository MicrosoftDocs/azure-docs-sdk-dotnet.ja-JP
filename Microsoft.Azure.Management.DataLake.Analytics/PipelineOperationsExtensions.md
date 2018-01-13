<Type Name="PipelineOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PipelineOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PipelineOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PipelineOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PipelineOperationsExtensions = class" />
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
            <span data-ttu-id="b3f76-101">PipelineOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="b3f76-101">Extension methods for PipelineOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation Get (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, Guid pipelineIdentity, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation Get(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, valuetype System.Guid pipelineIdentity, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String,System.Guid,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPipelineOperations, accountName As String, pipelineIdentity As Guid, Optional startDateTime As Nullable(Of DateTimeOffset) = null, Optional endDateTime As Nullable(Of DateTimeOffset) = null) As JobPipelineInformation" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string * Guid * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.Get (operations, accountName, pipelineIdentity, startDateTime, endDateTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="pipelineIdentity" Type="System.Guid" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b3f76-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b3f76-102">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b3f76-103">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="b3f76-103">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="pipelineIdentity">
            <span data-ttu-id="b3f76-104">パイプラインの id。</span><span class="sxs-lookup"><span data-stu-id="b3f76-104">Pipeline ID.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="b3f76-105">パイプラインを取得し、そのデータを集計する際の開始日です。</span><span class="sxs-lookup"><span data-stu-id="b3f76-105">The start date for when to get the pipeline and aggregate its data.</span></span> <span data-ttu-id="b3f76-106">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b3f76-106">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="b3f76-107">パイプラインを取得し、そのデータを集計する際の終了日。</span><span class="sxs-lookup"><span data-stu-id="b3f76-107">The end date for when to get the pipeline and aggregate its data.</span></span> <span data-ttu-id="b3f76-108">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b3f76-108">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3f76-109">パイプラインに情報を取得、指定したパイプラインの id です。</span><span class="sxs-lookup"><span data-stu-id="b3f76-109">Gets the Pipeline information for the specified pipeline ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, Guid pipelineIdentity, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, valuetype System.Guid pipelineIdentity, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String,System.Guid,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string * Guid * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.GetAsync (operations, accountName, pipelineIdentity, startDateTime, endDateTime, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="pipelineIdentity" Type="System.Guid" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b3f76-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b3f76-110">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b3f76-111">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="b3f76-111">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="pipelineIdentity">
            <span data-ttu-id="b3f76-112">パイプラインの id。</span><span class="sxs-lookup"><span data-stu-id="b3f76-112">Pipeline ID.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="b3f76-113">パイプラインを取得し、そのデータを集計する際の開始日です。</span><span class="sxs-lookup"><span data-stu-id="b3f76-113">The start date for when to get the pipeline and aggregate its data.</span></span> <span data-ttu-id="b3f76-114">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b3f76-114">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="b3f76-115">パイプラインを取得し、そのデータを集計する際の終了日。</span><span class="sxs-lookup"><span data-stu-id="b3f76-115">The end date for when to get the pipeline and aggregate its data.</span></span> <span data-ttu-id="b3f76-116">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b3f76-116">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b3f76-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b3f76-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3f76-118">パイプラインに情報を取得、指定したパイプラインの id です。</span><span class="sxs-lookup"><span data-stu-id="b3f76-118">Gets the Pipeline information for the specified pipeline ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; List (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; List(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.List(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IPipelineOperations, accountName As String, Optional startDateTime As Nullable(Of DateTimeOffset) = null, Optional endDateTime As Nullable(Of DateTimeOffset) = null) As IPage(Of JobPipelineInformation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.List (operations, accountName, startDateTime, endDateTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b3f76-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b3f76-119">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b3f76-120">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="b3f76-120">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="b3f76-121">パイプラインの一覧を取得する際の開始日です。</span><span class="sxs-lookup"><span data-stu-id="b3f76-121">The start date for when to get the list of pipelines.</span></span> <span data-ttu-id="b3f76-122">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b3f76-122">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="b3f76-123">パイプラインの一覧を取得する際の終了日。</span><span class="sxs-lookup"><span data-stu-id="b3f76-123">The end date for when to get the list of pipelines.</span></span> <span data-ttu-id="b3f76-124">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b3f76-124">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3f76-125">すべてのパイプラインの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="b3f76-125">Lists all pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt; ListAsync (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt; ListAsync(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string accountName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListAsync (operations, accountName, startDateTime, endDateTime, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b3f76-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b3f76-126">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b3f76-127">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="b3f76-127">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="b3f76-128">パイプラインの一覧を取得する際の開始日です。</span><span class="sxs-lookup"><span data-stu-id="b3f76-128">The start date for when to get the list of pipelines.</span></span> <span data-ttu-id="b3f76-129">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b3f76-129">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="b3f76-130">パイプラインの一覧を取得する際の終了日。</span><span class="sxs-lookup"><span data-stu-id="b3f76-130">The end date for when to get the list of pipelines.</span></span> <span data-ttu-id="b3f76-131">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b3f76-131">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b3f76-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b3f76-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3f76-133">すべてのパイプラインの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="b3f76-133">Lists all pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; ListNext (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt; ListNext(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListNext(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IPipelineOperations, nextPageLink As String) As IPage(Of JobPipelineInformation)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b3f76-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b3f76-134">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b3f76-135">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b3f76-135">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3f76-136">すべてのパイプラインの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="b3f76-136">Lists all pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.PipelineOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobPipelineInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IPipelineOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b3f76-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b3f76-137">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b3f76-138">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b3f76-138">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b3f76-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b3f76-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b3f76-140">すべてのパイプラインの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="b3f76-140">Lists all pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>