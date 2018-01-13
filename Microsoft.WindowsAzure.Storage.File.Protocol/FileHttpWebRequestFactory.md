<Type Name="FileHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class FileHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FileHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class FileHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type FileHttpWebRequestFactory = class" />
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
            <span data-ttu-id="9381e-101">ファイル サービス内のファイルに対する操作の web 要求を構築するためのファクトリ クラスです。</span><span class="sxs-lookup"><span data-stu-id="9381e-101">A factory class for constructing web requests for operations on files in the File service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AbortCopy">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AbortCopy (Uri uri, Nullable&lt;int&gt; timeout, string copyId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AbortCopy(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string copyId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AbortCopy(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AbortCopy : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AbortCopy (uri, timeout, copyId, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="copyId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-102">A<see cref="T:System.Uri" />ファイルへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="9381e-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-103">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="9381e-103">An integer specifying the server timeout interval.</span></span></param>
        <param name="copyId"><span data-ttu-id="9381e-104">中止するコピー操作の ID 文字列です。</span><span class="sxs-lookup"><span data-stu-id="9381e-104">The ID string of the copy operation to be aborted.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-105"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-105">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="9381e-106">リース条件のみが、この操作でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="9381e-106">Only lease conditions are supported for this operation.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-107">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-107">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-108"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-108">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-109">コピー操作を中止する web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="9381e-109">Generates a web request to abort a copy operation.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-110"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-110">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
        <param name="request"><span data-ttu-id="9381e-111">Web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-111">The web request.</span></span></param>
        <param name="metadata"><span data-ttu-id="9381e-112">ユーザー定義のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="9381e-112">The user-defined metadata.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-113">ユーザー定義メタデータを要求に 1 つまたは複数の名前と値のペアとして追加します。</span><span class="sxs-lookup"><span data-stu-id="9381e-113">Adds user-defined metadata to the request as one or more name-value pairs.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
        <param name="request"><span data-ttu-id="9381e-114">Web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-114">The web request.</span></span></param>
        <param name="name"><span data-ttu-id="9381e-115">メタデータ名。</span><span class="sxs-lookup"><span data-stu-id="9381e-115">The metadata name.</span></span></param>
        <param name="value"><span data-ttu-id="9381e-116">メタデータ値。</span><span class="sxs-lookup"><span data-stu-id="9381e-116">The metadata value.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-117">ユーザー定義メタデータを要求に 1 つの名前と値のペアとして追加します。</span><span class="sxs-lookup"><span data-stu-id="9381e-117">Adds user-defined metadata to the request as a single name-value pair.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest CopyFrom (Uri uri, Nullable&lt;int&gt; timeout, Uri source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest CopyFrom(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class System.Uri source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.CopyFrom(System.Uri,System.Nullable{System.Int32},System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member CopyFrom : Uri * Nullable&lt;int&gt; * Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.CopyFrom (uri, timeout, source, sourceAccessCondition, destAccessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="source" Type="System.Uri" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-118">A<see cref="T:System.Uri" />出力先ファイルの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="9381e-118">A <see cref="T:System.Uri" /> specifying the absolute URI to the destination file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-119">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="9381e-119">An integer specifying the server timeout interval.</span></span></param>
        <param name="source"><span data-ttu-id="9381e-120">A<see cref="T:System.Uri" />絶対 URI は、ソース オブジェクトなど、必要な認証パラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="9381e-120">A <see cref="T:System.Uri" /> specifying the absolute URI to the source object, including any necessary authentication parameters.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="9381e-121"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、ソース オブジェクトで満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-121">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the source object in order for the request to proceed.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="9381e-122"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、変換先ファイルに満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-122">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the destination file in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-123">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-123">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-124"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-124">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-125">Blob またはファイルから別のファイルにコピーする web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="9381e-125">Generates a web request to copy from a blob or file to another file.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-126"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-126">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileProperties properties, long fileSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.FileProperties properties, int64 fileSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileProperties,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileProperties * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Create (uri, timeout, properties, fileSize, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.FileProperties" />
        <Parameter Name="fileSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-127">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-127">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-128">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-128">The server timeout interval.</span></span></param>
        <param name="properties"><span data-ttu-id="9381e-129">ファイルに対して設定するプロパティ。</span><span class="sxs-lookup"><span data-stu-id="9381e-129">The properties to set for the file.</span></span></param>
        <param name="fileSize"><span data-ttu-id="9381e-130">ファイルのサイズ。</span><span class="sxs-lookup"><span data-stu-id="9381e-130">The size of the file.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-131">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-131">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-132">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-132">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-133"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-133">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-134">新しいファイルを作成する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-134">Constructs a web request to create a new file.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-135"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-135">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Delete (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-136">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-136">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-137">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-137">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-138">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-138">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-139">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-139">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-140"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-140">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-141">ファイルを削除する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-141">Constructs a web request to delete a file.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-142"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-142">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-143">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-143">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-144">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-144">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-145">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-145">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-146">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-146">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-147"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-147">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-148">ファイルのコンテンツ、プロパティ、およびメタデータを取得する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-148">Constructs a web request to get the file's content, properties, and metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-149">操作を実行するための web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-149">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-150">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-150">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-151">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-151">The server timeout interval.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="9381e-152">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="9381e-152">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-153">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-153">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-154">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="9381e-154">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-155"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-155">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-156">ファイルのコンテンツ、プロパティ、およびメタデータを取得する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-156">Constructs a web request to get the file's content, properties, and metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-157">操作を実行するための web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-157">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, bool rangeContentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, bool rangeContentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * bool * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, offset, count, rangeContentMD5, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="rangeContentMD5" Type="System.Boolean" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-158">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-158">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-159">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="9381e-159">The server timeout interval, in seconds.</span></span></param>
        <param name="offset"><span data-ttu-id="9381e-160">コンテンツを返すを開始するバイト オフセットです。</span><span class="sxs-lookup"><span data-stu-id="9381e-160">The byte offset at which to begin returning content.</span></span></param>
        <param name="count"><span data-ttu-id="9381e-161">戻り値、またはファイルの末尾まですべてのバイトを返す null バイト数。</span><span class="sxs-lookup"><span data-stu-id="9381e-161">The number of bytes to return, or null to return all bytes through the end of the file.</span></span></param>
        <param name="rangeContentMD5"><span data-ttu-id="9381e-162">場合に設定<c>true</c>、指定した範囲に MD5 ヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9381e-162">If set to <c>true</c>, request an MD5 header for the specified range.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-163">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-163">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-164">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-164">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-165"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-165">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-166">指定された範囲のプロパティとメタデータと共に、ファイルの内容を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-166">Constructs a web request to return a specified range of the file's content, together with its properties and metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-167">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-167">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, bool rangeContentMD5, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, bool rangeContentMD5, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Boolean,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * bool * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Get (uri, timeout, offset, count, rangeContentMD5, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="rangeContentMD5" Type="System.Boolean" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-168">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-168">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-169">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="9381e-169">The server timeout interval, in seconds.</span></span></param>
        <param name="offset"><span data-ttu-id="9381e-170">コンテンツを返すを開始するバイト オフセットです。</span><span class="sxs-lookup"><span data-stu-id="9381e-170">The byte offset at which to begin returning content.</span></span></param>
        <param name="count"><span data-ttu-id="9381e-171">戻り値、またはファイルの末尾まですべてのバイトを返す null バイト数。</span><span class="sxs-lookup"><span data-stu-id="9381e-171">The number of bytes to return, or null to return all bytes through the end of the file.</span></span></param>
        <param name="rangeContentMD5"><span data-ttu-id="9381e-172">場合に設定<c>true</c>、指定した範囲に MD5 ヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9381e-172">If set to <c>true</c>, request an MD5 header for the specified range.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="9381e-173">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="9381e-173">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-174">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-174">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-175">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="9381e-175">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-176"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-176">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-177">指定された範囲のプロパティとメタデータと共に、ファイルの内容を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-177">Constructs a web request to return a specified range of the file's content, together with its properties and metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-178">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-178">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-179">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-179">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-180">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-180">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-181">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-181">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-182">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-182">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-183"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-183">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-184">ファイルのユーザー定義メタデータを返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-184">Constructs a web request to return the user-defined metadata for the file.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-185">操作を実行するための web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-185">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetMetadata (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-186">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-186">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-187">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-187">The server timeout interval.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="9381e-188">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="9381e-188">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-189">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-189">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-190">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="9381e-190">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-191"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-191">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-192">ファイルのユーザー定義メタデータを返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-192">Constructs a web request to return the user-defined metadata for the file.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-193">操作を実行するための web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-193">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-194">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-194">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-195">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-195">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-196">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-196">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-197">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-197">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-198"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-198">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-199">ファイルのシステム プロパティを返すための web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-199">Constructs a web request to return the file's system properties.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-200">操作を実行するための web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-200">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetProperties (uri, timeout, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-201">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-201">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-202">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-202">The server timeout interval.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="9381e-203">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="9381e-203">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-204">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-204">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-205">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="9381e-205">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-206"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-206">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-207">ファイルのシステム プロパティを返すための web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-207">Constructs a web request to return the file's system properties.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-208">操作を実行するための web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-208">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, useVersionHeader, operationContext)" />
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
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-209">A<see cref="T:System.Uri" />ファイル サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="9381e-209">A <see cref="T:System.Uri" /> specifying the File service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="9381e-210">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-210">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-211">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="9381e-211">The server timeout interval, in seconds.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-212">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-212">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-213"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-213">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-214">ファイル サービスのプロパティを取得する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="9381e-214">Creates a web request to get the properties of the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-215"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-215">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRanges">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ListRanges (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ListRanges(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ListRanges : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges (uri, timeout, offset, count, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-216">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-216">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-217">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-217">The server timeout interval.</span></span></param>
        <param name="offset"><span data-ttu-id="9381e-218">一覧のファイルにどのデータ範囲の範囲の開始オフセット (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="9381e-218">The starting offset of the data range over which to list file ranges, in bytes.</span></span></param>
        <param name="count"><span data-ttu-id="9381e-219">一覧のファイルにどのデータ範囲の範囲の長さ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="9381e-219">The length of the data range over which to list file ranges, in bytes.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-220">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-220">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-221">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-221">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-222"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-222">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-223">ファイルの有効な範囲の一覧を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-223">Constructs a web request to return the list of valid ranges for a file.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-224"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-224">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRanges">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest ListRanges (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Nullable&lt;DateTimeOffset&gt; shareSnapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest ListRanges(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; shareSnapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges(System.Uri,System.Nullable{System.Int32},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ListRanges : Uri * Nullable&lt;int&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.ListRanges (uri, timeout, offset, count, shareSnapshot, accessCondition, useVersionHeader, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="uri" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="shareSnapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-225">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-225">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-226">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-226">The server timeout interval.</span></span></param>
        <param name="offset"><span data-ttu-id="9381e-227">一覧のファイルにどのデータ範囲の範囲の開始オフセット (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="9381e-227">The starting offset of the data range over which to list file ranges, in bytes.</span></span></param>
        <param name="count"><span data-ttu-id="9381e-228">一覧のファイルにどのデータ範囲の範囲の長さ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="9381e-228">The length of the data range over which to list file ranges, in bytes.</span></span></param>
        <param name="shareSnapshot"><span data-ttu-id="9381e-229">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、共有のスナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="9381e-229">A <see cref="T:System.DateTimeOffset" /> specifying the share snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-230">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-230">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-231">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="9381e-231">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-232"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-232">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-233">ファイルの有効な範囲の一覧を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-233">Constructs a web request to return the list of valid ranges for a file.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-234">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-234">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutRange">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutRange (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileRange fileRange, Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite fileRangeWrite, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutRange(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.FileRange fileRange, valuetype Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite fileRangeWrite, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.PutRange(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileRange,Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutRange : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileRange * Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.PutRange (uri, timeout, fileRange, fileRangeWrite, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="fileRange" Type="Microsoft.WindowsAzure.Storage.File.FileRange" />
        <Parameter Name="fileRangeWrite" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileRangeWrite" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-235">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-235">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-236">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-236">The server timeout interval.</span></span></param>
        <param name="fileRange"><span data-ttu-id="9381e-237">開始時刻と終了オフセット。</span><span class="sxs-lookup"><span data-stu-id="9381e-237">The beginning and ending offsets.</span></span></param>
        <param name="fileRangeWrite"><span data-ttu-id="9381e-238">ファイルへの書き込みまたは一連の範囲をクリアするおかどうかが記述するアクション。</span><span class="sxs-lookup"><span data-stu-id="9381e-238">Action describing whether we are writing to a file or clearing a set of ranges.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-239">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-239">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-240">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-240">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-241"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-241">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-242">記述したり、ファイル内のページの範囲をクリアする web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-242">Constructs a web request to write or clear a range of pages in a file.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-243">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-243">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Resize (Uri uri, Nullable&lt;int&gt; timeout, long newFileSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Resize(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int64 newFileSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Resize(System.Uri,System.Nullable{System.Int32},System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Resize : Uri * Nullable&lt;int&gt; * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.Resize (uri, timeout, newFileSize, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="newFileSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-244">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-244">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-245">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-245">The server timeout interval.</span></span></param>
        <param name="newFileSize"><span data-ttu-id="9381e-246">新しいファイル サイズ。</span><span class="sxs-lookup"><span data-stu-id="9381e-246">The new file size.</span></span> <span data-ttu-id="9381e-247">このパラメーターに設定<c>null</c>既存のファイル サイズが維持されます。</span><span class="sxs-lookup"><span data-stu-id="9381e-247">Set this parameter to <c>null</c> to keep the existing file size.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-248">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-248">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-249">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-249">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-250"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-250">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-251">ファイルのサイズを変更する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-251">Constructs a web request to resize a file.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-252">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-252">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-253">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-253">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-254">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-254">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-255">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-255">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-256">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-256">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-257"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-257">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-258">ユーザー定義のメタデータ ファイルを設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-258">Constructs a web request to set user-defined metadata for the file.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-259">操作を実行するための web 要求。</span><span class="sxs-lookup"><span data-stu-id="9381e-259">A web request for performing the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.FileProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileProperties,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileProperties * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetProperties (uri, timeout, properties, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.FileProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-260">ファイルの絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="9381e-260">The absolute URI to the file.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-261">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="9381e-261">The server timeout interval.</span></span></param>
        <param name="properties"><span data-ttu-id="9381e-262">ファイルのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="9381e-262">The file's properties.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="9381e-263">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="9381e-263">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-264">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-264">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-265"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="9381e-265">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-266">ファイルのシステム プロパティを設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="9381e-266">Constructs a web request to set system properties for a file.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-267"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-267">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, useVersionHeader, operationContext)" />
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
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="9381e-268">A<see cref="T:System.Uri" />ファイル サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="9381e-268">A <see cref="T:System.Uri" /> specifying the File service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="9381e-269">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-269">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="9381e-270">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="9381e-270">The server timeout interval, in seconds.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="9381e-271">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="9381e-271">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9381e-272"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-272">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-273">ファイル サービスのプロパティを設定する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="9381e-273">Creates a web request to set the properties of the File service.</span></span>
            </summary>
        <returns><span data-ttu-id="9381e-274"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-274">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.WriteServiceProperties(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As FileServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.FileHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="9381e-275"><see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-275">A <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> object.</span></span></param>
        <param name="outputStream"><span data-ttu-id="9381e-276"><see cref="T:System.IO.Stream" />書式設定されたプロパティが書き込まれるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9381e-276">The <see cref="T:System.IO.Stream" /> object to which the formatted properties are to be written.</span></span></param>
        <summary>
            <span data-ttu-id="9381e-277">ファイル サービスのプロパティを XML 形式で、ストリームに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="9381e-277">Writes File service properties to a stream, formatted in XML.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>