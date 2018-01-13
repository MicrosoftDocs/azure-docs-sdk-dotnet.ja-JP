<Type Name="IRecurrenceOperations" FullName="Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations">
  <TypeSignature Language="C#" Value="public interface IRecurrenceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecurrenceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecurrenceOperations" />
  <TypeSignature Language="F#" Value="type IRecurrenceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dafe3-101">RecurrenceOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="dafe3-101">RecurrenceOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt; GetWithHttpMessagesAsync (string accountName, Guid recurrenceIdentity, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt; GetWithHttpMessagesAsync(string accountName, valuetype System.Guid recurrenceIdentity, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations.GetWithHttpMessagesAsync(System.String,System.Guid,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Guid * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;" Usage="iRecurrenceOperations.GetWithHttpMessagesAsync (accountName, recurrenceIdentity, startDateTime, endDateTime, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="recurrenceIdentity" Type="System.Guid" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="dafe3-102">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="dafe3-102">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="recurrenceIdentity">
            <span data-ttu-id="dafe3-103">定期的なアイテムの id。</span><span class="sxs-lookup"><span data-stu-id="dafe3-103">Recurrence ID.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="dafe3-104">定期的なアイテムを取得し、そのデータを集計する際の開始日です。</span><span class="sxs-lookup"><span data-stu-id="dafe3-104">The start date for when to get the recurrence and aggregate its data.</span></span> <span data-ttu-id="dafe3-105">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-105">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="dafe3-106">定期的なアイテムを取得し、そのデータを集計する際の終了日。</span><span class="sxs-lookup"><span data-stu-id="dafe3-106">The end date for when to get recurrence and aggregate its data.</span></span> <span data-ttu-id="dafe3-107">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-107">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="dafe3-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="dafe3-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dafe3-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dafe3-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dafe3-110">指定された繰り返し ID の定期実行情報を取得します</span><span class="sxs-lookup"><span data-stu-id="dafe3-110">Gets the recurrence information for the specified recurrence ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="dafe3-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="dafe3-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dafe3-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;&gt;" Usage="iRecurrenceOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="dafe3-114">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="dafe3-114">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="dafe3-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="dafe3-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dafe3-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dafe3-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dafe3-117">すべての繰り返しを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="dafe3-117">Lists all recurrences.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="dafe3-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="dafe3-119">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-119">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dafe3-120">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;&gt; ListWithHttpMessagesAsync (string accountName, Nullable&lt;DateTimeOffset&gt; startDateTime = null, Nullable&lt;DateTimeOffset&gt; endDateTime = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;&gt; ListWithHttpMessagesAsync(string accountName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startDateTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endDateTime, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IRecurrenceOperations.ListWithHttpMessagesAsync(System.String,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;&gt;" Usage="iRecurrenceOperations.ListWithHttpMessagesAsync (accountName, startDateTime, endDateTime, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="startDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endDateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="dafe3-121">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="dafe3-121">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="startDateTime">
            <span data-ttu-id="dafe3-122">定期的なアイテムの一覧を取得する際の開始日です。</span><span class="sxs-lookup"><span data-stu-id="dafe3-122">The start date for when to get the list of recurrences.</span></span> <span data-ttu-id="dafe3-123">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-123">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="endDateTime">
            <span data-ttu-id="dafe3-124">定期的なアイテムの一覧を取得する際の終了日。</span><span class="sxs-lookup"><span data-stu-id="dafe3-124">The end date for when to get the list of recurrences.</span></span> <span data-ttu-id="dafe3-125">%Startdatetime と、endDateTime は、30 日以内の間隔を指定できます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-125">The startDateTime and endDateTime can be no more than 30 days apart.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="dafe3-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="dafe3-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dafe3-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="dafe3-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dafe3-128">すべての繰り返しを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="dafe3-128">Lists all recurrences.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="dafe3-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="dafe3-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dafe3-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dafe3-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>