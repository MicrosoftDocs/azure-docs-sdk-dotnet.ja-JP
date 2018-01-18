<Type Name="QueueHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class QueueHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueueHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type QueueHttpWebRequestFactory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="24b2b-101">キュー サービスでキューを管理する web 要求を構築するためのファクトリ クラスです。</span><span class="sxs-lookup"><span data-stu-id="24b2b-101">A factory class for constructing a web request to manage queues in the Queue service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AddMessage (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;int&gt; timeToLiveInSeconds, Nullable&lt;int&gt; visibilityTimeoutInSeconds, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AddMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int32&gt; timeToLiveInSeconds, valuetype System.Nullable`1&lt;int32&gt; visibilityTimeoutInSeconds, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AddMessage : Uri * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage (uri, timeout, timeToLiveInSeconds, visibilityTimeoutInSeconds, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeToLiveInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-102">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-103">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-103">An integer specifying the server timeout interval.</span></span></param>
        <param name="timeToLiveInSeconds"><span data-ttu-id="24b2b-104">有効期限を秒単位でメッセージです。</span><span class="sxs-lookup"><span data-stu-id="24b2b-104">The message time-to-live, in seconds.</span></span></param>
        <param name="visibilityTimeoutInSeconds"><span data-ttu-id="24b2b-105">によってメッセージが表示されなくなります、秒単位で時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="24b2b-105">The length of time during which the message will be invisible, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-106"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-106">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-107">キューのメッセージを追加する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-107">Constructs a web request to add a message for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-108"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-108">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AddMessage (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;int&gt; timeToLiveInSeconds, Nullable&lt;int&gt; visibilityTimeoutInSeconds, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AddMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int32&gt; timeToLiveInSeconds, valuetype System.Nullable`1&lt;int32&gt; visibilityTimeoutInSeconds, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AddMessage : Uri * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMessage (uri, timeout, timeToLiveInSeconds, visibilityTimeoutInSeconds, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeToLiveInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-109">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-109">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-110">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-110">An integer specifying the server timeout interval.</span></span></param>
        <param name="timeToLiveInSeconds"><span data-ttu-id="24b2b-111">有効期限を秒単位でメッセージです。</span><span class="sxs-lookup"><span data-stu-id="24b2b-111">The message time-to-live, in seconds.</span></span></param>
        <param name="visibilityTimeoutInSeconds"><span data-ttu-id="24b2b-112">によってメッセージが表示されなくなります、秒単位で時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="24b2b-112">The length of time during which the message will be invisible, in seconds.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-113">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-113">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-114"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-114">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-115">キューのメッセージを追加する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-115">Constructs a web request to add a message for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-116"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-116">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata (request, metadata)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="24b2b-117"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-117">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></param>
        <param name="metadata"><span data-ttu-id="24b2b-118">A<see cref="T:System.Collections.Generic.Dictionary`2" />ユーザー定義メタデータを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-118">A <see cref="T:System.Collections.Generic.Dictionary`2" /> object containing the user-defined metadata.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-119">ユーザー定義メタデータを要求に 1 つまたは複数の名前と値のペアとして追加します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-119">Adds user-defined metadata to the request as one or more name-value pairs.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.AddMetadata (request, name, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="24b2b-120"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-120">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></param>
        <param name="name"><span data-ttu-id="24b2b-121">メタデータ名を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="24b2b-121">A string containing the metadata name.</span></span></param>
        <param name="value"><span data-ttu-id="24b2b-122">メタデータ値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="24b2b-122">A string containing the metadata value.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-123">ユーザー定義メタデータを要求に 1 つの名前と値のペアとして追加します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-123">Adds user-defined metadata to the request as a single name-value pair.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ClearMessages (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ClearMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ClearMessages : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages (uri, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-124">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-124">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-125">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-125">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-126"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-126">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-127">キュー内のすべてのメッセージを消去する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-127">Constructs a web request to clear all messages in the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-128"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-128">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ClearMessages (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ClearMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ClearMessages : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.ClearMessages (uri, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-129">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-129">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-130">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-130">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-131">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-131">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-132"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-132">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-133">キュー内のすべてのメッセージを消去する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-133">Constructs a web request to clear all messages in the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-134"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-134">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create (uri, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-135">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-135">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-136">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-136">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-137"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-137">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-138">新しいキューを作成する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-138">Constructs a web request to create a new queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-139"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-139">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-140">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-140">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-141">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-141">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-142">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-142">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-143"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-143">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-144">新しいキューを作成する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-144">Constructs a web request to create a new queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-145"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-145">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete (uri, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-146">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-146">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-147">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-147">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-148"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-148">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-149">キューおよびすべての内部にメッセージを削除する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-149">Constructs a web request to delete the queue and all of the messages within it.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-150"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-150">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.Delete (uri, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-151">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-151">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-152">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-152">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-153">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-153">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-154"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-154">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-155">キューおよびすべての内部にメッセージを削除する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-155">Constructs a web request to delete the queue and all of the messages within it.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-156"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-156">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest DeleteMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest DeleteMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member DeleteMessage : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage (uri, timeout, popReceipt, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-157">A<see cref="T:System.Uri" />更新メッセージへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-157">A <see cref="T:System.Uri" /> specifying the absolute URI to the message to update.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-158">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="24b2b-158">The server timeout interval, in seconds.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="24b2b-159">メッセージの popreceipt を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="24b2b-159">A string specifying the pop receipt of the message.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-160"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-160">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-161">メッセージを更新する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-161">Constructs a web request to update a message.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-162"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-162">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest DeleteMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest DeleteMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member DeleteMessage : Uri * Nullable&lt;int&gt; * string * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.DeleteMessage (uri, timeout, popReceipt, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-163">A<see cref="T:System.Uri" />更新メッセージへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-163">A <see cref="T:System.Uri" /> specifying the absolute URI to the message to update.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-164">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="24b2b-164">The server timeout interval, in seconds.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="24b2b-165">メッセージの popreceipt を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="24b2b-165">A string specifying the pop receipt of the message.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-166">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-166">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-167"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-167">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-168">メッセージを更新する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-168">Constructs a web request to update a message.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-169"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-169">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl (uri, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-170">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-170">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-171">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-171">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-172"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-172">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-173">キューの ACL を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-173">Constructs a web request to return the ACL for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-174"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-174">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetAcl (uri, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-175">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-175">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-176">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-176">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-177">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-177">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-178"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-178">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-179">キューの ACL を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-179">Constructs a web request to return the ACL for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-180"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-180">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMessages : Uri * Nullable&lt;int&gt; * int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages (uri, timeout, numberOfMessages, visibilityTimeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-181">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-181">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-182">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-182">An integer specifying the server timeout interval.</span></span></param>
        <param name="numberOfMessages"><span data-ttu-id="24b2b-183">取得するメッセージの数を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-183">An integer specifying the number of messages to get.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="24b2b-184">A<see cref="T:System.TimeSpan" />表示タイムアウトを指定する値。</span><span class="sxs-lookup"><span data-stu-id="24b2b-184">A <see cref="T:System.TimeSpan" /> value specifying the visibility timeout.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-185"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-185">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-186">キューからメッセージを取得する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-186">Constructs a web request to get messages from a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-187"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-187">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Nullable&lt;TimeSpan&gt; visibilityTimeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Nullable{System.TimeSpan},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMessages : Uri * Nullable&lt;int&gt; * int * Nullable&lt;TimeSpan&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMessages (uri, timeout, numberOfMessages, visibilityTimeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-188">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-188">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-189">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-189">An integer specifying the server timeout interval.</span></span></param>
        <param name="numberOfMessages"><span data-ttu-id="24b2b-190">取得するメッセージの数を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-190">An integer specifying the number of messages to get.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="24b2b-191">A<see cref="T:System.TimeSpan" />表示タイムアウトを指定する値。</span><span class="sxs-lookup"><span data-stu-id="24b2b-191">A <see cref="T:System.TimeSpan" /> value specifying the visibility timeout.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-192">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-192">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-193"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-193">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-194">キューからメッセージを取得する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-194">Constructs a web request to get messages from a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-195"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-195">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata (uri, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-196">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-196">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-197">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-197">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-198"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-198">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-199">このキューのユーザー定義メタデータを返す web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-199">Generates a web request to return the user-defined metadata for this queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-200"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-200">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetMetadata (uri, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-201">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-201">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-202">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-202">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-203">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-203">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-204"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-204">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-205">このキューのユーザー定義メタデータを返す web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-205">Generates a web request to return the user-defined metadata for this queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-206"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-206">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-207">A<see cref="T:System.Uri" />キュー サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-207">A <see cref="T:System.Uri" /> specifying the Queue service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="24b2b-208">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-208">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-209">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="24b2b-209">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-210"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-210">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-211">キュー サービスのプロパティを取得する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-211">Creates a web request to get the properties of the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-212"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-212">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceStats (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceStats(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceStats(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceStats : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.GetServiceStats (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-213">A<see cref="T:System.Uri" />キュー サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-213">A <see cref="T:System.Uri" /> specifying the Queue service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="24b2b-214">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-214">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-215">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="24b2b-215">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-216"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-216">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-217">キュー サービスの統計情報を取得する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-217">Creates a web request to get Queue service stats.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-218"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-218">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-219">A<see cref="T:System.Uri" />キュー サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-219">A <see cref="T:System.Uri" /> specifying the Queue service endpoint.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-220">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-220">An integer specifying the server timeout interval.</span></span></param>
        <param name="listingContext"><span data-ttu-id="24b2b-221"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-221">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> object.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="24b2b-222">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />リスト、キューのメタデータを返すかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="24b2b-222">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration value that indicates whether to return queue metadata with the listing.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-223"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-223">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-224">このストレージ アカウント内のすべてのキューの一覧が返されますへの web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-224">Constructs a web request to return a listing of all queues in this storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-225"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-225">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails detailsIncluded, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="listingContext" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-226">A<see cref="T:System.Uri" />キュー サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-226">A <see cref="T:System.Uri" /> specifying the Queue service endpoint.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-227">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-227">An integer specifying the server timeout interval.</span></span></param>
        <param name="listingContext"><span data-ttu-id="24b2b-228"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-228">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" /> object.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="24b2b-229">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />リスト、キューのメタデータを返すかどうかを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="24b2b-229">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> enumeration value that indicates whether to return queue metadata with the listing.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-230">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-230">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-231"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-231">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-232">このストレージ アカウント内のすべてのキューの一覧が返されますへの web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-232">Constructs a web request to return a listing of all queues in this storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-233"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-233">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PeekMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PeekMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages(System.Uri,System.Nullable{System.Int32},System.Int32,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PeekMessages : Uri * Nullable&lt;int&gt; * int * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages (uri, timeout, numberOfMessages, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-234">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-234">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-235">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-235">An integer specifying the server timeout interval.</span></span></param>
        <param name="numberOfMessages"><span data-ttu-id="24b2b-236">ここに表示するメッセージの数を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-236">An integer specifying the number of messages to peek.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-237"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-237">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-238">キューからメッセージをピークする web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-238">Constructs a web request to peek messages from a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-239"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-239">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessages">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PeekMessages (Uri uri, Nullable&lt;int&gt; timeout, int numberOfMessages, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PeekMessages(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int32 numberOfMessages, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages(System.Uri,System.Nullable{System.Int32},System.Int32,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PeekMessages : Uri * Nullable&lt;int&gt; * int * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.PeekMessages (uri, timeout, numberOfMessages, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numberOfMessages" Type="System.Int32" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-240">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-240">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-241">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-241">An integer specifying the server timeout interval.</span></span></param>
        <param name="numberOfMessages"><span data-ttu-id="24b2b-242">ここに表示するメッセージの数を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-242">An integer specifying the number of messages to peek.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-243">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-243">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-244"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-244">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-245">キューからメッセージをピークする web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-245">Constructs a web request to peek messages from a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-246"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-246">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl (uri, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-247">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-247">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-248">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-248">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-249"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-249">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-250">キューの ACL を設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-250">Constructs a web request to set the ACL for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-251"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-251">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetAcl (uri, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-252">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-252">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-253">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-253">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-254">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-254">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-255"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-255">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-256">キューの ACL を設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-256">Constructs a web request to set the ACL for a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-257"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-257">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata (uri, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-258">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-258">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-259">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-259">An integer specifying the server timeout interval.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-260"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-260">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-261">キューのユーザー定義メタデータを設定する web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-261">Generates a web request to set user-defined metadata for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-262"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-262">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetMetadata (uri, timeout, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-263">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-263">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-264">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="24b2b-264">An integer specifying the server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-265">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-265">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-266"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-266">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-267">キューのユーザー定義メタデータを設定する web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-267">Generates a web request to set user-defined metadata for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-268"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-268">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="builder" Type="Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-269">A<see cref="T:System.Uri" />キュー サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-269">A <see cref="T:System.Uri" /> specifying the Queue service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="24b2b-270">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-270">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-271">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="24b2b-271">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-272"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-272">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-273">キュー サービスのプロパティを設定する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-273">Creates a web request to set the properties of the Queue service.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-274"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-274">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest UpdateMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, int visibilityTimeoutInSeconds, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest UpdateMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, int32 visibilityTimeoutInSeconds, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Int32,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member UpdateMessage : Uri * Nullable&lt;int&gt; * string * int * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage (uri, timeout, popReceipt, visibilityTimeoutInSeconds, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Int32" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-275">A<see cref="T:System.Uri" />更新メッセージへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-275">A <see cref="T:System.Uri" /> specifying the absolute URI to the message to update.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-276">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="24b2b-276">The server timeout interval, in seconds.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="24b2b-277">メッセージの popreceipt を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="24b2b-277">A string specifying the pop receipt of the message.</span></span></param>
        <param name="visibilityTimeoutInSeconds"><span data-ttu-id="24b2b-278">によってメッセージが表示されなくなります、秒単位で時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="24b2b-278">The length of time during which the message will be invisible, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-279"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-279">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-280">メッセージを更新する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-280">Constructs a web request to update a message.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-281"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-281">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest UpdateMessage (Uri uri, Nullable&lt;int&gt; timeout, string popReceipt, int visibilityTimeoutInSeconds, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest UpdateMessage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string popReceipt, int32 visibilityTimeoutInSeconds, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage(System.Uri,System.Nullable{System.Int32},System.String,System.Int32,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member UpdateMessage : Uri * Nullable&lt;int&gt; * string * int * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.UpdateMessage (uri, timeout, popReceipt, visibilityTimeoutInSeconds, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="visibilityTimeoutInSeconds" Type="System.Int32" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="24b2b-282">A<see cref="T:System.Uri" />更新メッセージへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-282">A <see cref="T:System.Uri" /> specifying the absolute URI to the message to update.</span></span></param>
        <param name="timeout"><span data-ttu-id="24b2b-283">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="24b2b-283">The server timeout interval, in seconds.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="24b2b-284">メッセージの popreceipt を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="24b2b-284">A string specifying the pop receipt of the message.</span></span></param>
        <param name="visibilityTimeoutInSeconds"><span data-ttu-id="24b2b-285">によってメッセージが表示されなくなります、秒単位で時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="24b2b-285">The length of time during which the message will be invisible, in seconds.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="24b2b-286">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="24b2b-286">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="24b2b-287"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-287">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-288">メッセージを更新する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="24b2b-288">Constructs a web request to update a message.</span></span>
            </summary>
        <returns><span data-ttu-id="24b2b-289"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-289">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.WriteServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As ServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="24b2b-290"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-290">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="outputStream"><span data-ttu-id="24b2b-291"><see cref="T:System.IO.Stream" />書式設定されたプロパティが書き込まれるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="24b2b-291">The <see cref="T:System.IO.Stream" /> object to which the formatted properties are to be written.</span></span></param>
        <summary>
            <span data-ttu-id="24b2b-292">キュー サービス プロパティを XML 形式で、ストリームに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="24b2b-292">Writes Queue service properties to a stream, formatted in XML.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>