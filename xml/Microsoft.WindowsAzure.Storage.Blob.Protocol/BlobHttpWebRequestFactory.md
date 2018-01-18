<Type Name="BlobHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class BlobHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BlobHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type BlobHttpWebRequestFactory = class" />
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
            <span data-ttu-id="3f765-101">Blob サービスの HTTP web 要求を構築するためのファクトリ クラスです。</span><span class="sxs-lookup"><span data-stu-id="3f765-101">A factory class for constructing HTTP web requests for the Blob service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AbortCopy">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AbortCopy (Uri uri, Nullable&lt;int&gt; timeout, string copyId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AbortCopy(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string copyId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AbortCopy(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AbortCopy : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AbortCopy (uri, timeout, copyId, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-102">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-103">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-103">An integer specifying the server timeout interval.</span></span></param>
        <param name="copyId"><span data-ttu-id="3f765-104">中止するコピー操作の ID 文字列です。</span><span class="sxs-lookup"><span data-stu-id="3f765-104">The ID string of the copy operation to be aborted.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-105"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-105">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="3f765-106">リース条件のみが、この操作でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="3f765-106">Only lease conditions are supported for this operation.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-107"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-107">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-108">コピー操作を中止する web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-108">Generates a web request to abort a copy operation.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-109"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-109">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortCopy">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AbortCopy (Uri uri, Nullable&lt;int&gt; timeout, string copyId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AbortCopy(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string copyId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AbortCopy(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AbortCopy : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AbortCopy (uri, timeout, copyId, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3f765-110">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-110">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-111">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-111">An integer specifying the server timeout interval.</span></span></param>
        <param name="copyId"><span data-ttu-id="3f765-112">中止するコピー操作の ID 文字列です。</span><span class="sxs-lookup"><span data-stu-id="3f765-112">The ID string of the copy operation to be aborted.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-113"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-113">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span> <span data-ttu-id="3f765-114">リース条件のみが、この操作でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="3f765-114">Only lease conditions are supported for this operation.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-115">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-115">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-116"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-116">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-117">コピー操作を中止する web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-117">Generates a web request to abort a copy operation.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-118"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-118">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
        <param name="request"><span data-ttu-id="3f765-119"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-119">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></param>
        <param name="metadata"><span data-ttu-id="3f765-120">A<see cref="T:System.Collections.Generic.Dictionary`2" />ユーザー定義メタデータを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-120">A <see cref="T:System.Collections.Generic.Dictionary`2" /> object containing the user-defined metadata.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-121">ユーザー定義メタデータを要求に 1 つまたは複数の名前と値のペアとして追加します。</span><span class="sxs-lookup"><span data-stu-id="3f765-121">Adds user-defined metadata to the request as one or more name-value pairs.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
        <param name="request"><span data-ttu-id="3f765-122"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-122">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></param>
        <param name="name"><span data-ttu-id="3f765-123">メタデータ名を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="3f765-123">A string containing the metadata name.</span></span></param>
        <param name="value"><span data-ttu-id="3f765-124">メタデータ値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="3f765-124">A string containing the metadata value.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-125">ユーザー定義メタデータを要求に 1 つの名前と値のペアとして追加します。</span><span class="sxs-lookup"><span data-stu-id="3f765-125">Adds user-defined metadata to the request as a single name-value pair.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlock">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AppendBlock (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AppendBlock(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AppendBlock(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AppendBlock : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AppendBlock (uri, timeout, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-126">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-126">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-127">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-127">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-128"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-128">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-129"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-129">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-130">追加 blob にブロックをコミットする web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-130">Constructs a web request to commit a block to an append blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-131"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-131">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppendBlock">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest AppendBlock (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest AppendBlock(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AppendBlock(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member AppendBlock : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.AppendBlock (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3f765-132">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-132">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-133">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-133">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-134"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-134">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-135">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-135">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-136"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-136">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-137">追加 blob にブロックをコミットする web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-137">Constructs a web request to commit a block to an append blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-138"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-138">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest CopyFrom (Uri uri, Nullable&lt;int&gt; timeout, Uri source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest CopyFrom(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class System.Uri source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom(System.Uri,System.Nullable{System.Int32},System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member CopyFrom : Uri * Nullable&lt;int&gt; * Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom (uri, timeout, source, sourceAccessCondition, destAccessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-139">A<see cref="T:System.Uri" />のコピー先 blob の絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-139">A <see cref="T:System.Uri" /> specifying the absolute URI to the destination blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-140">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-140">An integer specifying the server timeout interval.</span></span></param>
        <param name="source"><span data-ttu-id="3f765-141">A<see cref="T:System.Uri" />絶対 URI は、ソース オブジェクトなど、必要な認証パラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-141">A <see cref="T:System.Uri" /> specifying the absolute URI to the source object, including any necessary authentication parameters.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="3f765-142"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、ソース オブジェクトで満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-142">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the source object in order for the request to proceed.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="3f765-143"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、コピー先 blob に満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-143">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the destination blob in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-144"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-144">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-145">Blob またはファイルを別の blob にコピーする web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-145">Generates a web request to copy a blob or file to another blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-146"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-146">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest CopyFrom (Uri uri, Nullable&lt;int&gt; timeout, Uri source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest CopyFrom(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class System.Uri source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom(System.Uri,System.Nullable{System.Int32},System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member CopyFrom : Uri * Nullable&lt;int&gt; * Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom (uri, timeout, source, sourceAccessCondition, destAccessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3f765-147">A<see cref="T:System.Uri" />のコピー先 blob の絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-147">A <see cref="T:System.Uri" /> specifying the absolute URI to the destination blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-148">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-148">An integer specifying the server timeout interval.</span></span></param>
        <param name="source"><span data-ttu-id="3f765-149">A<see cref="T:System.Uri" />絶対 URI は、ソース オブジェクトなど、必要な認証パラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-149">A <see cref="T:System.Uri" /> specifying the absolute URI to the source object, including any necessary authentication parameters.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="3f765-150"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、ソース オブジェクトで満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-150">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the source object in order for the request to proceed.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="3f765-151"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、コピー先 blob に満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-151">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the destination blob in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-152">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-152">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-153"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-153">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-154">Blob またはファイルを別の blob にコピーする web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-154">Generates a web request to copy a blob or file to another blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-155"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-155">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest CopyFrom (Uri uri, Nullable&lt;int&gt; timeout, Uri source, bool incrementalCopy, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest CopyFrom(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class System.Uri source, bool incrementalCopy, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom(System.Uri,System.Nullable{System.Int32},System.Uri,System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member CopyFrom : Uri * Nullable&lt;int&gt; * Uri * bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom (uri, timeout, source, incrementalCopy, sourceAccessCondition, destAccessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="incrementalCopy" Type="System.Boolean" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-156">A<see cref="T:System.Uri" />のコピー先 blob の絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-156">A <see cref="T:System.Uri" /> specifying the absolute URI to the destination blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-157">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-157">An integer specifying the server timeout interval.</span></span></param>
        <param name="source"><span data-ttu-id="3f765-158">A<see cref="T:System.Uri" />絶対 URI は、ソース オブジェクトなど、必要な認証パラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-158">A <see cref="T:System.Uri" /> specifying the absolute URI to the source object, including any necessary authentication parameters.</span></span></param>
        <param name="incrementalCopy"><span data-ttu-id="3f765-159">これは、増分のコピーであるかどうかを示すブール値。</span><span class="sxs-lookup"><span data-stu-id="3f765-159">A boolean indicating whether or not this is an incremental copy.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="3f765-160"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、ソース オブジェクトで満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-160">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the source object in order for the request to proceed.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="3f765-161"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、コピー先 blob に満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-161">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the destination blob in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-162">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-162">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-163"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-163">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-164">Blob またはファイルを別の blob にコピーする web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-164">Generates a web request to copy a blob or file to another blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-165"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-165">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest CopyFrom (Uri uri, Nullable&lt;int&gt; timeout, Uri source, bool incrementalCopy, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest CopyFrom(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class System.Uri source, bool incrementalCopy, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom(System.Uri,System.Nullable{System.Int32},System.Uri,System.Boolean,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member CopyFrom : Uri * Nullable&lt;int&gt; * Uri * bool * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.CopyFrom (uri, timeout, source, incrementalCopy, premiumPageBlobTier, sourceAccessCondition, destAccessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="incrementalCopy" Type="System.Boolean" />
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-166">A<see cref="T:System.Uri" />のコピー先 blob の絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-166">A <see cref="T:System.Uri" /> specifying the absolute URI to the destination blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-167">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-167">An integer specifying the server timeout interval.</span></span></param>
        <param name="source"><span data-ttu-id="3f765-168">A<see cref="T:System.Uri" />絶対 URI は、ソース オブジェクトなど、必要な認証パラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-168">A <see cref="T:System.Uri" /> specifying the absolute URI to the source object, including any necessary authentication parameters.</span></span></param>
        <param name="incrementalCopy"><span data-ttu-id="3f765-169">これは、増分のコピーであるかどうかを示すブール値。</span><span class="sxs-lookup"><span data-stu-id="3f765-169">A boolean indicating whether or not this is an incremental copy.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="3f765-170">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="3f765-170">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="sourceAccessCondition"><span data-ttu-id="3f765-171"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、ソース オブジェクトで満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-171">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the source object in order for the request to proceed.</span></span></param>
        <param name="destAccessCondition"><span data-ttu-id="3f765-172"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために、コピー先 blob に満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-172">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met on the destination blob in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-173">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-173">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-174"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-174">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-175">Blob またはファイルを別の blob にコピーする web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-175">Generates a web request to copy a blob or file to another blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-176"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-176">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Delete (uri, timeout, snapshot, deleteSnapshotsOption, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-177">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-177">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-178">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-178">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-179">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-179">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="deleteSnapshotsOption"><span data-ttu-id="3f765-180">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />かどうかのみを削除する blob のスナップショットのみ、またはその両方を示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-180">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" /> object indicating whether to delete only blobs, only snapshots, or both.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-181"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-181">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-182"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-182">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-183">Blob を削除する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-183">Constructs a web request to delete a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-184"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-184">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Delete (uri, timeout, snapshot, deleteSnapshotsOption, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-185">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-185">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-186">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-186">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-187">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-187">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="deleteSnapshotsOption"><span data-ttu-id="3f765-188">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />かどうかのみを削除する blob のスナップショットのみ、またはその両方を示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-188">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" /> object indicating whether to delete only blobs, only snapshots, or both.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-189"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-189">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-190">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-190">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-191"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-191">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-192">Blob を削除する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-192">Constructs a web request to delete a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-193"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-193">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get (uri, timeout, snapshot, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-194">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-194">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-195">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-195">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-196">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのバージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-196">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot version, if the blob is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-197"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-197">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-198"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-198">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-199">Blob のコンテンツ、プロパティ、およびメタデータを取得する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-199">Constructs a web request to get the blob's content, properties, and metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-200"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-200">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get (uri, timeout, snapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-201">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-201">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-202">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-202">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-203">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのバージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-203">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot version, if the blob is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-204"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-204">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-205">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-205">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-206"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-206">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-207">Blob のコンテンツ、プロパティ、およびメタデータを取得する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-207">Constructs a web request to get the blob's content, properties, and metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-208"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-208">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, bool rangeContentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, bool rangeContentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * bool * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get (uri, timeout, snapshot, offset, count, rangeContentMD5, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="rangeContentMD5" Type="System.Boolean" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-209">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-209">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-210">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-210">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-211">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのバージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-211">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot version, if the blob is a snapshot.</span></span></param>
        <param name="offset"><span data-ttu-id="3f765-212">コンテンツを返すを開始するバイト オフセットです。</span><span class="sxs-lookup"><span data-stu-id="3f765-212">The byte offset at which to begin returning content.</span></span></param>
        <param name="count"><span data-ttu-id="3f765-213">戻るには、バイト数または<c>null</c>を blob の末尾までのすべてのバイトを返します。</span><span class="sxs-lookup"><span data-stu-id="3f765-213">The number of bytes to return, or <c>null</c> to return all bytes through the end of the blob.</span></span></param>
        <param name="rangeContentMD5"><span data-ttu-id="3f765-214">場合に設定<c>true</c>、指定した範囲の MD5 ヘッダーが要求されました。</span><span class="sxs-lookup"><span data-stu-id="3f765-214">If set to <c>true</c>, an MD5 header is requested for the specified range.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-215"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-215">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-216"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-216">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-217">そのプロパティおよびメタデータの blob のコンテンツの指定された範囲を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-217">Constructs a web request to return a specified range of the blob's content, together with its properties and metadata.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3f765-218">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3f765-218">A web request to use to perform the operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Get (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, bool rangeContentMD5, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Get(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, bool rangeContentMD5, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Boolean,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Get : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * bool * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Get (uri, timeout, snapshot, offset, count, rangeContentMD5, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="rangeContentMD5" Type="System.Boolean" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-219">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-219">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-220">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-220">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-221">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのバージョンを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-221">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot version, if the blob is a snapshot.</span></span></param>
        <param name="offset"><span data-ttu-id="3f765-222">コンテンツを返すを開始するバイト オフセットです。</span><span class="sxs-lookup"><span data-stu-id="3f765-222">The byte offset at which to begin returning content.</span></span></param>
        <param name="count"><span data-ttu-id="3f765-223">戻るには、バイト数または<c>null</c>を blob の末尾までのすべてのバイトを返します。</span><span class="sxs-lookup"><span data-stu-id="3f765-223">The number of bytes to return, or <c>null</c> to return all bytes through the end of the blob.</span></span></param>
        <param name="rangeContentMD5"><span data-ttu-id="3f765-224">場合に設定<c>true</c>、指定した範囲の MD5 ヘッダーが要求されました。</span><span class="sxs-lookup"><span data-stu-id="3f765-224">If set to <c>true</c>, an MD5 header is requested for the specified range.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-225"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-225">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-226">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-226">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-227"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-227">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-228">そのプロパティおよびメタデータの blob のコンテンツの指定された範囲を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-228">Constructs a web request to return a specified range of the blob's content, together with its properties and metadata.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3f765-229">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3f765-229">A web request to use to perform the operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlockList">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetBlockList (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter typesOfBlocks, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetBlockList(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter typesOfBlocks, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetBlockList(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetBlockList : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetBlockList (uri, timeout, snapshot, typesOfBlocks, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="typesOfBlocks" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-230">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-230">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-231">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-231">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-232">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-232">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="typesOfBlocks"><span data-ttu-id="3f765-233"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="3f765-233">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> enumeration value.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-234"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-234">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-235"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-235">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-236">ブロック blob のブロックの一覧を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-236">Constructs a web request to return the list of blocks for a block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-237"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-237">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBlockList">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetBlockList (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter typesOfBlocks, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetBlockList(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter typesOfBlocks, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetBlockList(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetBlockList : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetBlockList (uri, timeout, snapshot, typesOfBlocks, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="typesOfBlocks" Type="Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-238">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-238">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-239">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-239">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-240">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-240">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="typesOfBlocks"><span data-ttu-id="3f765-241"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="3f765-241">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlockListingFilter" /> enumeration value.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-242"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-242">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-243">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-243">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-244"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-244">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-245">ブロック blob のブロックの一覧を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-245">Constructs a web request to return the list of blocks for a block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-246"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-246">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetMetadata (uri, timeout, snapshot, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-247">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-247">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-248">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-248">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-249">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-249">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-250"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-250">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-251"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-251">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-252">Blob のユーザー定義メタデータを返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-252">Constructs a web request to return the user-defined metadata for the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-253"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-253">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetMetadata (uri, timeout, snapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-254">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-254">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-255">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-255">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-256">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-256">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-257"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-257">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-258">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-258">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-259"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-259">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-260">Blob のユーザー定義メタデータを返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-260">Constructs a web request to return the user-defined metadata for the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-261"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-261">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRanges">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetPageRanges (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetPageRanges(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRanges(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetPageRanges : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRanges (uri, timeout, snapshot, offset, count, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-262">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-262">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-263">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-263">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-264">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-264">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="offset"><span data-ttu-id="3f765-265">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="3f765-265">The starting offset of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="3f765-266">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="3f765-266">Must be a multiple of 512.</span></span></param>
        <param name="count"><span data-ttu-id="3f765-267">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="3f765-267">The length of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="3f765-268">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="3f765-268">Must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-269"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-269">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-270"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-270">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-271">ページ blob の有効なページ範囲の一覧を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-271">Constructs a web request to return the list of valid page ranges for a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-272"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-272">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRanges">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetPageRanges (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetPageRanges(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRanges(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetPageRanges : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRanges (uri, timeout, snapshot, offset, count, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-273">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-273">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-274">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-274">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-275">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-275">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="offset"><span data-ttu-id="3f765-276">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="3f765-276">The starting offset of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="3f765-277">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="3f765-277">Must be a multiple of 512.</span></span></param>
        <param name="count"><span data-ttu-id="3f765-278">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="3f765-278">The length of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="3f765-279">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="3f765-279">Must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-280"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-280">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-281">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-281">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-282"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-282">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-283">ページ blob の有効なページ範囲の一覧を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-283">Constructs a web request to return the list of valid page ranges for a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-284"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-284">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPageRangesDiff">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetPageRangesDiff (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, DateTimeOffset previousSnapshotTime, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; count, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetPageRangesDiff(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype System.DateTimeOffset previousSnapshotTime, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; count, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRangesDiff(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.DateTimeOffset,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetPageRangesDiff : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * DateTimeOffset * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetPageRangesDiff (uri, timeout, snapshot, previousSnapshotTime, offset, count, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="previousSnapshotTime" Type="System.DateTimeOffset" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-285">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-285">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-286">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-286">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-287">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-287">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="previousSnapshotTime"><span data-ttu-id="3f765-288">A <see cref="T:System.DateTimeOffset" /> diff の開始点として使用する、スナップショットのタイムスタンプを表すこの CloudPageBlob を表す場合、スナップショット、previousSnapshotTime パラメーターは、現在のスナップショットのタイムスタンプより前でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="3f765-288">A <see cref="T:System.DateTimeOffset" /> representing the snapshot timestamp to use as the starting point for the diff. If this CloudPageBlob represents a snapshot, the previousSnapshotTime parameter must be prior to the current snapshot timestamp.</span></span></param>
        <param name="offset"><span data-ttu-id="3f765-289">するデータ範囲のリスト ページの範囲の開始オフセット (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="3f765-289">The starting offset of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="3f765-290">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="3f765-290">Must be a multiple of 512.</span></span></param>
        <param name="count"><span data-ttu-id="3f765-291">リスト ページにどのデータ範囲の範囲の長さ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="3f765-291">The length of the data range over which to list page ranges, in bytes.</span></span> <span data-ttu-id="3f765-292">512 の倍数である必要があります。</span><span class="sxs-lookup"><span data-stu-id="3f765-292">Must be a multiple of 512.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-293"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-293">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-294">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-294">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-295"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-295">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-296">指定したスナップショットとこのオブジェクトの間で異なるページ範囲のリストを返すための web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-296">Constructs a web request to return the list of page ranges that differ between a specified snapshot and this object.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-297"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-297">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetProperties (uri, timeout, snapshot, accessCondition, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-298">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-298">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-299">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-299">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-300">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-300">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-301"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-301">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-302"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-302">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-303">Blob のシステム プロパティを返すための web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-303">Constructs a web request to return the blob's system properties.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-304"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-304">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetProperties (uri, timeout, snapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-305">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-305">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-306">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-306">An integer specifying the server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3f765-307">A <see cref="T:System.DateTimeOffset" /> blob がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-307">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the blob is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-308"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-308">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-309">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-309">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-310"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-310">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-311">Blob のシステム プロパティを返すための web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-311">Constructs a web request to return the blob's system properties.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-312"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-312">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetServiceProperties (uri, builder, timeout, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3f765-313">A <see cref="T:System.Uri" /> Blob サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-313">A <see cref="T:System.Uri" /> specifying the Blob service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="3f765-314">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-314">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-315">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="3f765-315">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-316"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-316">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-317">Blob サービスのプロパティを取得する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-317">Creates a web request to get the properties of the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-318"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-318">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetServiceStats (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetServiceStats(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetServiceStats(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetServiceStats : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.GetServiceStats (uri, builder, timeout, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3f765-319">A <see cref="T:System.Uri" /> Blob サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-319">A <see cref="T:System.Uri" /> specifying the Blob service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="3f765-320">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-320">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-321">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="3f765-321">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-322"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-322">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-323">Blob サービスの統計情報を取得する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-323">Creates a web request to get the stats of the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-324"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-324">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lease">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Lease (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, Nullable&lt;int&gt; leaseDuration, Nullable&lt;int&gt; leaseBreakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Lease(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, valuetype System.Nullable`1&lt;int32&gt; leaseDuration, valuetype System.Nullable`1&lt;int32&gt; leaseBreakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Lease(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.LeaseAction,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Lease : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.LeaseAction * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Lease (uri, timeout, action, proposedLeaseId, leaseDuration, leaseBreakPeriod, accessCondition, operationContext)" />
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
        <Parameter Name="action" Type="Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="leaseDuration" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="leaseBreakPeriod" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-325">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-325">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-326">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="3f765-326">The server timeout interval, in seconds.</span></span></param>
        <param name="action"><span data-ttu-id="3f765-327">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />リース操作を実行することを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="3f765-327">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" /> enumeration value indicating the lease action to perform.</span></span></param>
        <param name="proposedLeaseId"><span data-ttu-id="3f765-328">取得の結果の提案または操作を変更するには、リース ID を指定する文字列または<c>null</c>取得操作の ID が推奨されていない場合。</span><span class="sxs-lookup"><span data-stu-id="3f765-328">A string specifying the lease ID to propose for the result of an acquire or change operation, or <c>null</c> if no ID is proposed for an acquire operation.</span></span> <span data-ttu-id="3f765-329">このパラメーターを指定する必要があります<c>null</c>の書き換え、リリース、および中断操作。</span><span class="sxs-lookup"><span data-stu-id="3f765-329">This parameter should be <c>null</c> for renew, release, and break operations.</span></span></param>
        <param name="leaseDuration"><span data-ttu-id="3f765-330">リース期間を秒単位での操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="3f765-330">The lease duration, in seconds, for acquire operations.</span></span>
            <span data-ttu-id="3f765-331">-1 は無限の期間が指定されます。</span><span class="sxs-lookup"><span data-stu-id="3f765-331">If this is -1 then an infinite duration is specified.</span></span> <span data-ttu-id="3f765-332">これは、値には<c>null</c>更新、変更、リリース、および操作を中断します。</span><span class="sxs-lookup"><span data-stu-id="3f765-332">This should be <c>null</c> for renew, change, release, and break operations.</span></span></param>
        <param name="leaseBreakPeriod"><span data-ttu-id="3f765-333">秒単位、リースを中断する前に中断操作の後で、待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="3f765-333">The amount of time to wait, in seconds, after a break operation before the lease is broken.</span></span>
            <span data-ttu-id="3f765-334">これは、する場合<c>null</c>既定の時間が使用されます。</span><span class="sxs-lookup"><span data-stu-id="3f765-334">If this is <c>null</c> then the default time is used.</span></span> <span data-ttu-id="3f765-335">これは、値には<c>null</c>の取得、更新、変更、および操作を解放します。</span><span class="sxs-lookup"><span data-stu-id="3f765-335">This should be <c>null</c> for acquire, renew, change, and release operations.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-336"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-336">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-337"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-337">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-338">使用して取得、更新、変更、リリース、または blob のリースを中断する web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-338">Generates a web request to use to acquire, renew, change, release or break the lease for the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-339"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-339">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lease">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Lease (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, Nullable&lt;int&gt; leaseDuration, Nullable&lt;int&gt; leaseBreakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Lease(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseAction action, string proposedLeaseId, valuetype System.Nullable`1&lt;int32&gt; leaseDuration, valuetype System.Nullable`1&lt;int32&gt; leaseBreakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Lease(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.LeaseAction,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Lease : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.LeaseAction * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Lease (uri, timeout, action, proposedLeaseId, leaseDuration, leaseBreakPeriod, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="action" Type="Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="leaseDuration" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="leaseBreakPeriod" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-340">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-340">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-341">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="3f765-341">The server timeout interval, in seconds.</span></span></param>
        <param name="action"><span data-ttu-id="3f765-342">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" />リース操作を実行することを示す列挙値。</span><span class="sxs-lookup"><span data-stu-id="3f765-342">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseAction" /> enumeration value indicating the lease action to perform.</span></span></param>
        <param name="proposedLeaseId"><span data-ttu-id="3f765-343">取得の結果の提案または操作を変更するには、リース ID を指定する文字列または<c>null</c>取得操作の ID が推奨されていない場合。</span><span class="sxs-lookup"><span data-stu-id="3f765-343">A string specifying the lease ID to propose for the result of an acquire or change operation, or <c>null</c> if no ID is proposed for an acquire operation.</span></span> <span data-ttu-id="3f765-344">このパラメーターを指定する必要があります<c>null</c>の書き換え、リリース、および中断操作。</span><span class="sxs-lookup"><span data-stu-id="3f765-344">This parameter should be <c>null</c> for renew, release, and break operations.</span></span></param>
        <param name="leaseDuration"><span data-ttu-id="3f765-345">リース期間を秒単位での操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="3f765-345">The lease duration, in seconds, for acquire operations.</span></span>
            <span data-ttu-id="3f765-346">-1 は無限の期間が指定されます。</span><span class="sxs-lookup"><span data-stu-id="3f765-346">If this is -1 then an infinite duration is specified.</span></span> <span data-ttu-id="3f765-347">これは、値には<c>null</c>更新、変更、リリース、および操作を中断します。</span><span class="sxs-lookup"><span data-stu-id="3f765-347">This should be <c>null</c> for renew, change, release, and break operations.</span></span></param>
        <param name="leaseBreakPeriod"><span data-ttu-id="3f765-348">秒単位、リースを中断する前に中断操作の後で、待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="3f765-348">The amount of time to wait, in seconds, after a break operation before the lease is broken.</span></span>
            <span data-ttu-id="3f765-349">これは、する場合<c>null</c>既定の時間が使用されます。</span><span class="sxs-lookup"><span data-stu-id="3f765-349">If this is <c>null</c> then the default time is used.</span></span> <span data-ttu-id="3f765-350">これは、値には<c>null</c>の取得、更新、変更、および操作を解放します。</span><span class="sxs-lookup"><span data-stu-id="3f765-350">This should be <c>null</c> for acquire, renew, change, and release operations.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-351"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-351">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-352">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-352">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-353"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-353">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-354">使用して取得、更新、変更、リリース、または blob のリースを中断する web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-354">Generates a web request to use to acquire, renew, change, release or break the lease for the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-355"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-355">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Put">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Put (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.Blob.BlobType blobType, long pageBlobSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Put(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobType blobType, int64 pageBlobSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Put(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.Blob.BlobType,System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Put : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.Blob.BlobType * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Put (uri, timeout, properties, blobType, pageBlobSize, accessCondition, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="blobType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobType" />
        <Parameter Name="pageBlobSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-356">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-356">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-357">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-357">An integer specifying the server timeout interval.</span></span></param>
        <param name="properties"><span data-ttu-id="3f765-358"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-358">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> object.</span></span></param>
        <param name="blobType"><span data-ttu-id="3f765-359"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobType" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="3f765-359">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobType" /> enumeration value.</span></span></param>
        <param name="pageBlobSize"><span data-ttu-id="3f765-360">ページ blob の場合、blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="3f765-360">For a page blob, the size of the blob.</span></span> <span data-ttu-id="3f765-361">ブロック blob では、このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="3f765-361">This parameter is ignored for block blobs.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-362"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-362">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-363"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-363">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-364">新しいブロック blob またはページ blob を作成または既存のブロック blob のコンテンツを更新する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-364">Constructs a web request to create a new block blob or page blob, or to update the content of an existing block blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="3f765-365"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-365">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Put">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Put (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.Blob.BlobType blobType, long pageBlobSize, Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Put(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobType blobType, int64 pageBlobSize, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; premiumPageBlobTier, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Put(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.Blob.BlobType,System.Int64,System.Nullable{Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Put : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.Blob.BlobType * int64 * Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Put (uri, timeout, properties, blobType, pageBlobSize, premiumPageBlobTier, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="blobType" Type="Microsoft.WindowsAzure.Storage.Blob.BlobType" />
        <Parameter Name="pageBlobSize" Type="System.Int64" />
        <Parameter Name="premiumPageBlobTier" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-366">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-366">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-367">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-367">An integer specifying the server timeout interval.</span></span></param>
        <param name="properties"><span data-ttu-id="3f765-368"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-368">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> object.</span></span></param>
        <param name="blobType"><span data-ttu-id="3f765-369"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobType" /> 列挙値。</span><span class="sxs-lookup"><span data-stu-id="3f765-369">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobType" /> enumeration value.</span></span></param>
        <param name="pageBlobSize"><span data-ttu-id="3f765-370">ページ blob の場合、blob のサイズ。</span><span class="sxs-lookup"><span data-stu-id="3f765-370">For a page blob, the size of the blob.</span></span> <span data-ttu-id="3f765-371">ブロック blob では、このパラメーターは無視されます。</span><span class="sxs-lookup"><span data-stu-id="3f765-371">This parameter is ignored for block blobs.</span></span></param>
        <param name="premiumPageBlobTier"><span data-ttu-id="3f765-372">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" />を設定する層を表すです。</span><span class="sxs-lookup"><span data-stu-id="3f765-372">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PremiumPageBlobTier" /> representing the tier to set.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-373"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-373">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-374">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-374">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-375"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-375">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-376">新しいブロック blob またはページ blob を作成または既存のブロック blob のコンテンツを更新する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-376">Constructs a web request to create a new block blob or page blob, or to update the content of an existing block blob.</span></span> 
            </summary>
        <returns><span data-ttu-id="3f765-377"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-377">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlock">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutBlock (Uri uri, Nullable&lt;int&gt; timeout, string blockId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutBlock(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string blockId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlock(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutBlock : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlock (uri, timeout, blockId, accessCondition, operationContext)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-378">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-378">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-379">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-379">An integer specifying the server timeout interval.</span></span></param>
        <param name="blockId"><span data-ttu-id="3f765-380">このブロックのブロック ID を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="3f765-380">A string specifying the block ID for this block.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-381"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-381">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-382"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-382">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-383">ブロック blob に書き込み、ブロックへの web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-383">Constructs a web request to write a block to a block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-384"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-384">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlock">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutBlock (Uri uri, Nullable&lt;int&gt; timeout, string blockId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutBlock(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string blockId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlock(System.Uri,System.Nullable{System.Int32},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutBlock : Uri * Nullable&lt;int&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlock (uri, timeout, blockId, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="blockId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-385">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-385">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-386">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-386">An integer specifying the server timeout interval.</span></span></param>
        <param name="blockId"><span data-ttu-id="3f765-387">このブロックのブロック ID を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="3f765-387">A string specifying the block ID for this block.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-388"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-388">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-389">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-389">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-390"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-390">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-391">ブロック blob に書き込み、ブロックへの web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-391">Constructs a web request to write a block to a block blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-392"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-392">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockList">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutBlockList (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutBlockList(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlockList(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutBlockList : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlockList (uri, timeout, properties, accessCondition, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-393">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-393">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-394">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-394">An integer specifying the server timeout interval.</span></span></param>
        <param name="properties"><span data-ttu-id="3f765-395">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> blob に対して設定するプロパティを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-395">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> object specifying the properties to set for the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-396"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-396">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-397"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-397">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-398">作成またはブロック リストをコミットすることによって blob を更新する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-398">Constructs a web request to create or update a blob by committing a block list.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-399"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-399">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutBlockList">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutBlockList (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutBlockList(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlockList(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutBlockList : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutBlockList (uri, timeout, properties, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-400">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-400">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-401">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-401">An integer specifying the server timeout interval.</span></span></param>
        <param name="properties"><span data-ttu-id="3f765-402">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> blob に対して設定するプロパティを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-402">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" /> object specifying the properties to set for the blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-403"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-403">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-404">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-404">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-405"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-405">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-406">作成またはブロック リストをコミットすることによって blob を更新する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-406">Constructs a web request to create or update a blob by committing a block list.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-407"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-407">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutPage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutPage (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.PageRange pageRange, Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite pageWrite, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutPage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.PageRange pageRange, valuetype Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite pageWrite, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutPage(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.PageRange,Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutPage : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.PageRange * Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutPage (uri, timeout, pageRange, pageWrite, accessCondition, operationContext)" />
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
        <Parameter Name="pageRange" Type="Microsoft.WindowsAzure.Storage.Blob.PageRange" />
        <Parameter Name="pageWrite" Type="Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-408">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-408">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-409">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-409">An integer specifying the server timeout interval.</span></span></param>
        <param name="pageRange"><span data-ttu-id="3f765-410"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-410">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> object.</span></span></param>
        <param name="pageWrite"><span data-ttu-id="3f765-411">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite" />ページ blob に対して実行する操作を表す列挙値。</span><span class="sxs-lookup"><span data-stu-id="3f765-411">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite" /> enumeration value indicating the operation to perform on the page blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-412"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-412">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-413"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-413">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-414">記述したり、ページ blob のページの範囲をクリアする web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-414">Constructs a web request to write or clear a range of pages in a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-415"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-415">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PutPage">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest PutPage (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.PageRange pageRange, Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite pageWrite, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest PutPage(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.PageRange pageRange, valuetype Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite pageWrite, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutPage(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.PageRange,Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member PutPage : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.PageRange * Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.PutPage (uri, timeout, pageRange, pageWrite, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="pageRange" Type="Microsoft.WindowsAzure.Storage.Blob.PageRange" />
        <Parameter Name="pageWrite" Type="Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-416">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-416">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-417">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-417">An integer specifying the server timeout interval.</span></span></param>
        <param name="pageRange"><span data-ttu-id="3f765-418"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-418">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> object.</span></span></param>
        <param name="pageWrite"><span data-ttu-id="3f765-419">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite" />ページ blob に対して実行する操作を表す列挙値。</span><span class="sxs-lookup"><span data-stu-id="3f765-419">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PageWrite" /> enumeration value indicating the operation to perform on the page blob.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-420"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-420">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-421">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-421">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-422"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-422">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-423">記述したり、ページ blob のページの範囲をクリアする web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-423">Constructs a web request to write or clear a range of pages in a page blob.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3f765-424">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3f765-424">A web request to use to perform the operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Resize (Uri uri, Nullable&lt;int&gt; timeout, long newBlobSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Resize(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int64 newBlobSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Resize(System.Uri,System.Nullable{System.Int32},System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Resize : Uri * Nullable&lt;int&gt; * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Resize (uri, timeout, newBlobSize, accessCondition, operationContext)" />
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
        <Parameter Name="newBlobSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-425">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-425">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-426">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-426">An integer specifying the server timeout interval.</span></span></param>
        <param name="newBlobSize"><span data-ttu-id="3f765-427">新しい blob のサイズ、ページ blob の場合。</span><span class="sxs-lookup"><span data-stu-id="3f765-427">The new blob size, if the blob is a page blob.</span></span> <span data-ttu-id="3f765-428">このパラメーターに設定<c>null</c>既存の blob のサイズを保持します。</span><span class="sxs-lookup"><span data-stu-id="3f765-428">Set this parameter to <c>null</c> to keep the existing blob size.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-429"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-429">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-430"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-430">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-431">ページ blob のサイズを変更する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-431">Constructs a web request to resize a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-432"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-432">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Resize (Uri uri, Nullable&lt;int&gt; timeout, long newBlobSize, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Resize(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, int64 newBlobSize, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Resize(System.Uri,System.Nullable{System.Int32},System.Int64,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Resize : Uri * Nullable&lt;int&gt; * int64 * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Resize (uri, timeout, newBlobSize, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="newBlobSize" Type="System.Int64" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-433">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-433">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-434">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-434">An integer specifying the server timeout interval.</span></span></param>
        <param name="newBlobSize"><span data-ttu-id="3f765-435">新しい blob のサイズ、ページ blob の場合。</span><span class="sxs-lookup"><span data-stu-id="3f765-435">The new blob size, if the blob is a page blob.</span></span> <span data-ttu-id="3f765-436">このパラメーターに設定<c>null</c>既存の blob のサイズを保持します。</span><span class="sxs-lookup"><span data-stu-id="3f765-436">Set this parameter to <c>null</c> to keep the existing blob size.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-437"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-437">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-438">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-438">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-439"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-439">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-440">ページ blob のサイズを変更する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-440">Constructs a web request to resize a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-441"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-441">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetBlobTier">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetBlobTier (Uri uri, Nullable&lt;int&gt; timeout, string blobTier, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetBlobTier(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, string blobTier, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetBlobTier(System.Uri,System.Nullable{System.Int32},System.String,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetBlobTier : Uri * Nullable&lt;int&gt; * string * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetBlobTier (uri, timeout, blobTier, useVersionHeader, operationContext)" />
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
        <Parameter Name="blobTier" Type="System.String" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-442">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-442">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-443">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="3f765-443">The server timeout interval, in seconds.</span></span></param>
        <param name="blobTier"><span data-ttu-id="3f765-444">文字列として設定する blob 層です。</span><span class="sxs-lookup"><span data-stu-id="3f765-444">The blob tier to set as a string.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-445">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-445">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-446"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-446">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-447">Blob の層に設定する web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-447">Generates a web request to set the tier for a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-448"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-448">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-449">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-449">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-450">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-450">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-451"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-451">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-452"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-452">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-453">Blob のユーザー定義メタデータを設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-453">Constructs a web request to set user-defined metadata for the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-454"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-454">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3f765-455">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-455">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-456">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-456">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-457"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-457">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-458">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-458">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-459"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-459">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-460">Blob のユーザー定義メタデータを設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-460">Constructs a web request to set user-defined metadata for the blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-461"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-461">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetProperties (uri, timeout, properties, accessCondition, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-462">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-462">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-463">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-463">An integer specifying the server timeout interval.</span></span></param>
        <param name="properties"><span data-ttu-id="3f765-464">Blob のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="3f765-464">The blob's properties.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-465"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-465">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-466"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-466">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-467">Blob のシステム プロパティを設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-467">Constructs a web request to set system properties for a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-468"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-468">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Blob.BlobProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.BlobProperties,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobProperties * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetProperties (uri, timeout, properties, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-469">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-469">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-470">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-470">An integer specifying the server timeout interval.</span></span></param>
        <param name="properties"><span data-ttu-id="3f765-471">Blob のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="3f765-471">The blob's properties.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-472"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-472">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-473">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-473">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-474"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-474">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-475">Blob のシステム プロパティを設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-475">Constructs a web request to set system properties for a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-476"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-476">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSequenceNumber">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetSequenceNumber (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, Nullable&lt;long&gt; sequenceNumber, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetSequenceNumber(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, valuetype System.Nullable`1&lt;int64&gt; sequenceNumber, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetSequenceNumber(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction,System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetSequenceNumber : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetSequenceNumber (uri, timeout, sequenceNumberAction, sequenceNumber, accessCondition, operationContext)" />
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
        <Parameter Name="sequenceNumberAction" Type="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
        <Parameter Name="sequenceNumber" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-477">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-477">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-478">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-478">An integer specifying the server timeout interval.</span></span></param>
        <param name="sequenceNumberAction"><span data-ttu-id="3f765-479">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</span><span class="sxs-lookup"><span data-stu-id="3f765-479">A value of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />, indicating the operation to perform on the sequence number.</span></span></param>
        <param name="sequenceNumber"><span data-ttu-id="3f765-480">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="3f765-480">The sequence number.</span></span> <span data-ttu-id="3f765-481">このパラメーターに設定<c>null</c>場合、この操作は、増分処理します。</span><span class="sxs-lookup"><span data-stu-id="3f765-481">Set this parameter to <c>null</c> if this operation is an increment action.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-482"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-482">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-483"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-483">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-484">ページ blob のシーケンス番号を設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-484">Constructs a web request to set a page blob's sequence number.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-485"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-485">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSequenceNumber">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetSequenceNumber (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, Nullable&lt;long&gt; sequenceNumber, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetSequenceNumber(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction sequenceNumberAction, valuetype System.Nullable`1&lt;int64&gt; sequenceNumber, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetSequenceNumber(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction,System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetSequenceNumber : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetSequenceNumber (uri, timeout, sequenceNumberAction, sequenceNumber, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="sequenceNumberAction" Type="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
        <Parameter Name="sequenceNumber" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-486">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-486">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-487">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-487">An integer specifying the server timeout interval.</span></span></param>
        <param name="sequenceNumberAction"><span data-ttu-id="3f765-488">型の値<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />、シーケンス番号に対して実行する操作を示すです。</span><span class="sxs-lookup"><span data-stu-id="3f765-488">A value of type <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />, indicating the operation to perform on the sequence number.</span></span></param>
        <param name="sequenceNumber"><span data-ttu-id="3f765-489">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="3f765-489">The sequence number.</span></span> <span data-ttu-id="3f765-490">このパラメーターに設定<c>null</c>場合、この操作は、増分処理します。</span><span class="sxs-lookup"><span data-stu-id="3f765-490">Set this parameter to <c>null</c> if this operation is an increment action.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-491"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-491">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-492">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-492">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-493"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-493">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-494">ページ blob のシーケンス番号を設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-494">Constructs a web request to set a page blob's sequence number.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-495"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-495">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetServiceProperties (Uri uri, Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetServiceProperties(class System.Uri uri, class Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder builder, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetServiceProperties(System.Uri,Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetServiceProperties : Uri * Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.SetServiceProperties (uri, builder, timeout, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3f765-496">A <see cref="T:System.Uri" /> Blob サービスのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-496">A <see cref="T:System.Uri" /> specifying the Blob service endpoint.</span></span></param>
        <param name="builder"><span data-ttu-id="3f765-497">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> URI クエリ文字列を追加する追加のパラメーターを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-497">A <see cref="T:Microsoft.WindowsAzure.Storage.Core.UriQueryBuilder" /> object specifying additional parameters to add to the URI query string.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-498">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="3f765-498">The server timeout interval, in seconds.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-499"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-499">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-500">Blob サービスのプロパティを設定する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="3f765-500">Creates a web request to set the properties of the Blob service.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-501"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-501">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Snapshot (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Snapshot(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Snapshot(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Snapshot : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Snapshot (uri, timeout, accessCondition, operationContext)" />
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
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3f765-502">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-502">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-503">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-503">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-504"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-504">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-505"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-505">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-506">Blob のスナップショットを作成する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-506">Constructs a web request to create a snapshot of a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-507"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-507">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Snapshot (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Snapshot(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Snapshot(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Snapshot : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.Snapshot (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3f765-508">A <see cref="T:System.Uri" /> blob への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3f765-508">A <see cref="T:System.Uri" /> specifying the absolute URI to the blob.</span></span></param>
        <param name="timeout"><span data-ttu-id="3f765-509">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3f765-509">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3f765-510"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-510">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3f765-511">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3f765-511">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3f765-512"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-512">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-513">Blob のスナップショットを作成する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3f765-513">Constructs a web request to create a snapshot of a blob.</span></span>
            </summary>
        <returns><span data-ttu-id="3f765-514"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-514">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteServiceProperties">
      <MemberSignature Language="C#" Value="public static void WriteServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.WriteServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteServiceProperties (properties As ServiceProperties, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpWebRequestFactory.WriteServiceProperties (properties, outputStream)" />
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
        <param name="properties"><span data-ttu-id="3f765-515"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-515">A <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> object.</span></span></param>
        <param name="outputStream"><span data-ttu-id="3f765-516"><see cref="T:System.IO.Stream" />書式設定されたプロパティが書き込まれるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3f765-516">The <see cref="T:System.IO.Stream" /> object to which the formatted properties are to be written.</span></span></param>
        <summary>
            <span data-ttu-id="3f765-517">Blob サービスのプロパティを XML 形式で、ストリームに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="3f765-517">Writes Blob service properties to a stream, formatted in XML.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>