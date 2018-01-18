<Type Name="ShareHttpWebRequestFactory" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory">
  <TypeSignature Language="C#" Value="public static class ShareHttpWebRequestFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ShareHttpWebRequestFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ShareHttpWebRequestFactory" />
  <TypeSignature Language="F#" Value="type ShareHttpWebRequestFactory = class" />
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
            <span data-ttu-id="3684b-101">操作の web 要求を構築するためのファクトリ クラスは、ファイル サービスで共有します。</span><span class="sxs-lookup"><span data-stu-id="3684b-101">A factory class for constructing web requests for operations on shares in the File service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, System.Collections.Generic.IDictionary&lt;string,string&gt; metadata);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, metadata As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.AddMetadata (request, metadata)" />
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
        <param name="request"><span data-ttu-id="3684b-102">Web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-102">The web request.</span></span></param>
        <param name="metadata"><span data-ttu-id="3684b-103">ユーザー定義のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="3684b-103">The user-defined metadata.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-104">ユーザー定義メタデータを要求に 1 つまたは複数の名前と値のペアとして追加します。</span><span class="sxs-lookup"><span data-stu-id="3684b-104">Adds user-defined metadata to the request as one or more name-value pairs.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMetadata">
      <MemberSignature Language="C#" Value="public static void AddMetadata (System.Net.HttpWebRequest request, string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void AddMetadata(class System.Net.HttpWebRequest request, string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.AddMetadata(System.Net.HttpWebRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub AddMetadata (request As HttpWebRequest, name As String, value As String)" />
      <MemberSignature Language="F#" Value="static member AddMetadata : System.Net.HttpWebRequest * string * string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.AddMetadata (request, name, value)" />
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
        <param name="request"><span data-ttu-id="3684b-105">Web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-105">The web request.</span></span></param>
        <param name="name"><span data-ttu-id="3684b-106">メタデータ名。</span><span class="sxs-lookup"><span data-stu-id="3684b-106">The metadata name.</span></span></param>
        <param name="value"><span data-ttu-id="3684b-107">メタデータ値。</span><span class="sxs-lookup"><span data-stu-id="3684b-107">The metadata value.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-108">ユーザー定義メタデータを要求に 1 つの名前と値のペアとして追加します。</span><span class="sxs-lookup"><span data-stu-id="3684b-108">Adds user-defined metadata to the request as a single name-value pair.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Create(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Create (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3684b-109">共有の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="3684b-109">The absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-110">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="3684b-110">The server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-111">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3684b-111">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-112"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="3684b-112">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-113">新しい共有を作成する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3684b-113">Constructs a web request to create a new share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-114">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-114">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Create (Uri uri, Microsoft.WindowsAzure.Storage.File.FileShareProperties properties, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Create(class System.Uri uri, class Microsoft.WindowsAzure.Storage.File.FileShareProperties properties, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Create(System.Uri,Microsoft.WindowsAzure.Storage.File.FileShareProperties,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.WindowsAzure.Storage.File.FileShareProperties * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Create (uri, properties, timeout, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.FileShareProperties" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3684b-115">共有の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="3684b-115">The absolute URI to the share.</span></span></param>
        <param name="properties"><span data-ttu-id="3684b-116">共有に設定するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="3684b-116">Properties to set on the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-117">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="3684b-117">The server timeout interval.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-118">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3684b-118">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-119"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="3684b-119">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-120">新しい共有を作成する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3684b-120">Constructs a web request to create a new share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-121">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-121">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Delete (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3684b-122">共有の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="3684b-122">The absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-123">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="3684b-123">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3684b-124">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="3684b-124">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-125">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3684b-125">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-126"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="3684b-126">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-127">共有とその中のファイルをすべて削除する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3684b-127">Constructs a web request to delete the share and all of the files within it.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-128">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-128">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Delete (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Delete(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, valuetype Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Delete(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Delete : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Delete (uri, timeout, snapshot, deleteSnapshotsOption, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3684b-129">共有の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="3684b-129">The absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-130">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="3684b-130">The server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3684b-131">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3684b-131">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="deleteSnapshotsOption"><span data-ttu-id="3684b-132">A<see cref="T:Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />のみ、共有を削除するか、共有とすべてのスナップショットを削除するかどうかを示すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-132">A <see cref="T:Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" /> object indicating whether to only delete the share or delete the share and all snapshots.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3684b-133">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="3684b-133">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-134">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="3684b-134">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-135"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="3684b-135">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-136">共有とその中のファイルをすべて削除する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3684b-136">Constructs a web request to delete the share and all of the files within it.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-137">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-137">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetAcl (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3684b-138">A<see cref="T:System.Uri" />共有への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3684b-138">A <see cref="T:System.Uri" /> specifying the absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-139">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3684b-139">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3684b-140"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-140">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-141">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3684b-141">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-142"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-142">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-143">共有の ACL を返す web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3684b-143">Constructs a web request to return the ACL for a share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-144"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-144">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3684b-145">共有の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="3684b-145">The absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-146">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="3684b-146">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3684b-147">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="3684b-147">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-148">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3684b-148">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-149"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="3684b-149">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-150">この共有のユーザー定義メタデータを返す web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3684b-150">Generates a web request to return the user-defined metadata for this share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-151">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-151">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetMetadata(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetMetadata (uri, timeout, snapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3684b-152">共有の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="3684b-152">The absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-153">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="3684b-153">The server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3684b-154">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3684b-154">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3684b-155">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="3684b-155">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-156">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="3684b-156">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-157"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="3684b-157">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-158">この共有のユーザー定義メタデータを返す web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3684b-158">Generates a web request to return the user-defined metadata for this share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-159">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-159">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetProperties (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3684b-160">共有の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="3684b-160">The absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-161">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="3684b-161">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3684b-162">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="3684b-162">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-163">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3684b-163">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-164"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="3684b-164">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-165">この共有のユーザー定義のメタデータとプロパティを返す web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3684b-165">Generates a web request to return the properties and user-defined metadata for this share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-166">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-166">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetProperties (Uri uri, Nullable&lt;int&gt; timeout, Nullable&lt;DateTimeOffset&gt; snapshot, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshot, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetProperties(System.Uri,System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetProperties : Uri * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetProperties (uri, timeout, snapshot, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="snapshot" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3684b-167">共有の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="3684b-167">The absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-168">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="3684b-168">The server timeout interval.</span></span></param>
        <param name="snapshot"><span data-ttu-id="3684b-169">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、スナップショットのタイムスタンプを指定します。</span><span class="sxs-lookup"><span data-stu-id="3684b-169">A <see cref="T:System.DateTimeOffset" /> specifying the snapshot timestamp, if the share is a snapshot.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3684b-170">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="3684b-170">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-171">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="3684b-171">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-172"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="3684b-172">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-173">この共有のユーザー定義のメタデータとプロパティを返す web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3684b-173">Generates a web request to return the properties and user-defined metadata for this share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-174">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-174">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStats">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest GetStats (Uri uri, Nullable&lt;int&gt; timeout, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest GetStats(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetStats(System.Uri,System.Nullable{System.Int32},System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member GetStats : Uri * Nullable&lt;int&gt; * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.GetStats (uri, timeout, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3684b-175">A<see cref="T:System.Uri" />共有を指定します。</span><span class="sxs-lookup"><span data-stu-id="3684b-175">A <see cref="T:System.Uri" /> specifying the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-176">サーバー タイムアウト間隔 (秒)。</span><span class="sxs-lookup"><span data-stu-id="3684b-176">The server timeout interval, in seconds.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-177">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3684b-177">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-178"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-178">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-179">共有の統計情報を取得する web 要求を作成します。</span><span class="sxs-lookup"><span data-stu-id="3684b-179">Creates a web request to get the stats of the share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-180"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-180">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest List (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest List(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext listingContext, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.List(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member List : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.List (uri, timeout, listingContext, detailsIncluded, useVersionHeader, operationContext)" />
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
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3684b-181">アカウントの絶対 URI。</span><span class="sxs-lookup"><span data-stu-id="3684b-181">The absolute URI for the account.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-182">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="3684b-182">The server timeout interval.</span></span></param>
        <param name="listingContext"><span data-ttu-id="3684b-183">一覧作成操作のパラメーターのセット。</span><span class="sxs-lookup"><span data-stu-id="3684b-183">A set of parameters for the listing operation.</span></span></param>
        <param name="detailsIncluded"><span data-ttu-id="3684b-184">一覧を返す追加の詳細。</span><span class="sxs-lookup"><span data-stu-id="3684b-184">Additional details to return with the listing.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-185">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3684b-185">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-186"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="3684b-186">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-187">このストレージ アカウント内のすべての共有の一覧が返されますへの web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3684b-187">Constructs a web request to return a listing of all shares in this storage account.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-188">指定された操作の web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-188">A web request for the specified operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAcl">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetAcl (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileSharePublicAccessType publicAccess, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetAcl(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype Microsoft.WindowsAzure.Storage.File.FileSharePublicAccessType publicAccess, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetAcl(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileSharePublicAccessType,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetAcl : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileSharePublicAccessType * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetAcl (uri, timeout, publicAccess, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="publicAccess" Type="Microsoft.WindowsAzure.Storage.File.FileSharePublicAccessType" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3684b-189">A<see cref="T:System.Uri" />共有への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3684b-189">A <see cref="T:System.Uri" /> specifying the absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-190">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3684b-190">An integer specifying the server timeout interval.</span></span></param>
        <param name="publicAccess"><span data-ttu-id="3684b-191">共有のようにパブリック アクセスの種類。</span><span class="sxs-lookup"><span data-stu-id="3684b-191">The type of public access to allow for the share.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3684b-192"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-192">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-193">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3684b-193">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-194"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-194">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-195">共有の ACL を設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3684b-195">Constructs a web request to set the ACL for a share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-196"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-196">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetMetadata (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetMetadata(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetMetadata(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetMetadata : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetMetadata (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <param name="uri"><span data-ttu-id="3684b-197">共有の絶対 URI です。</span><span class="sxs-lookup"><span data-stu-id="3684b-197">The absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-198">サーバー タイムアウト間隔。</span><span class="sxs-lookup"><span data-stu-id="3684b-198">The server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3684b-199">要求に適用するアクセス条件。</span><span class="sxs-lookup"><span data-stu-id="3684b-199">The access condition to apply to the request.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-200">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3684b-200">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-201"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />オブジェクトの現在の操作を追跡します。</span><span class="sxs-lookup"><span data-stu-id="3684b-201">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-202">共有のユーザー定義メタデータを設定する web 要求を生成します。</span><span class="sxs-lookup"><span data-stu-id="3684b-202">Generates a web request to set user-defined metadata for the share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-203">使用して、操作を実行する web 要求。</span><span class="sxs-lookup"><span data-stu-id="3684b-203">A web request to use to perform the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetProperties">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest SetProperties (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.File.FileShareProperties properties, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest SetProperties(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.File.FileShareProperties properties, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetProperties(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileShareProperties,Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member SetProperties : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileShareProperties * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.SetProperties (uri, timeout, properties, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.FileShareProperties" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3684b-204">A<see cref="T:System.Uri" />共有への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3684b-204">A <see cref="T:System.Uri" /> specifying the absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-205">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3684b-205">An integer specifying the server timeout interval.</span></span></param>
        <param name="properties"><span data-ttu-id="3684b-206">共有のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="3684b-206">The share's properties.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3684b-207"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-207">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-208">設定するかどうかを示すブール値、 <i>- x-ms-version</i> HTTP ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3684b-208">A boolean value indicating whether to set the <i>x-ms-version</i> HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-209"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-209">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-210">共有のシステム プロパティを設定する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3684b-210">Constructs a web request to set system properties for a share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-211"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-211">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public static System.Net.HttpWebRequest Snapshot (Uri uri, Nullable&lt;int&gt; timeout, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.HttpWebRequest Snapshot(class System.Uri uri, valuetype System.Nullable`1&lt;int32&gt; timeout, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, bool useVersionHeader, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Snapshot(System.Uri,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.AccessCondition,System.Boolean,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Snapshot : Uri * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * bool * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpWebRequestFactory.Snapshot (uri, timeout, accessCondition, useVersionHeader, operationContext)" />
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
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="useVersionHeader" Type="System.Boolean" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="uri"><span data-ttu-id="3684b-212">A<see cref="T:System.Uri" />共有への絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="3684b-212">A <see cref="T:System.Uri" /> specifying the absolute URI to the share.</span></span></param>
        <param name="timeout"><span data-ttu-id="3684b-213">サーバー タイムアウト間隔を指定する整数。</span><span class="sxs-lookup"><span data-stu-id="3684b-213">An integer specifying the server timeout interval.</span></span></param>
        <param name="accessCondition"><span data-ttu-id="3684b-214"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-214">An <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the condition that must be met in order for the request to proceed.</span></span></param>
        <param name="useVersionHeader"><span data-ttu-id="3684b-215">X-ms-version - HTTP ヘッダーを設定するかどうかを示すフラグ。</span><span class="sxs-lookup"><span data-stu-id="3684b-215">A flag indicating whether to set the x-ms-version HTTP header.</span></span></param>
        <param name="operationContext"><span data-ttu-id="3684b-216"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-216">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="3684b-217">共有のスナップショットを作成する web 要求を構築します。</span><span class="sxs-lookup"><span data-stu-id="3684b-217">Constructs a web request to create a snapshot of a share.</span></span>
            </summary>
        <returns><span data-ttu-id="3684b-218"><see cref="T:System.Net.HttpWebRequest" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3684b-218">A <see cref="T:System.Net.HttpWebRequest" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>