<Type Name="BlobHttpResponseParsers" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers">
  <TypeSignature Language="C#" Value="public static class BlobHttpResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BlobHttpResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobHttpResponseParsers" />
  <TypeSignature Language="F#" Value="type BlobHttpResponseParsers = class" />
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
            <span data-ttu-id="28a71-101">一連の Blob サービスから応答を含む blob データを解析するためのメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="28a71-101">Provides a set of methods for parsing a response containing blob data from the Blob service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCopyAttributes">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.CopyState GetCopyAttributes (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Blob.CopyState GetCopyAttributes(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetCopyAttributes(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetCopyAttributes (response As HttpWebResponse) As CopyState" />
      <MemberSignature Language="F#" Value="static member GetCopyAttributes : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.CopyState" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetCopyAttributes response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CopyState</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="28a71-102">HTTP web 応答です。</span><span class="sxs-lookup"><span data-stu-id="28a71-102">The HTTP web response.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-103">抽出、 <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CopyState" /> web 応答のヘッダーからのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="28a71-103">Extracts a <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CopyState" /> object from the headers of a web response.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-104">A<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CopyState" />オブジェクト、または<c>null</c> web 応答に状態コピーにはが含まれていない場合。</span><span class="sxs-lookup"><span data-stu-id="28a71-104">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CopyState" /> object, or <c>null</c> if the web response does not include copy state.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetIncrementalCopyStatus">
      <MemberSignature Language="C#" Value="public static bool GetIncrementalCopyStatus (string incrementalCopyHeader);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool GetIncrementalCopyStatus(string incrementalCopyHeader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetIncrementalCopyStatus(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetIncrementalCopyStatus (incrementalCopyHeader As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member GetIncrementalCopyStatus : string -&gt; bool" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetIncrementalCopyStatus incrementalCopyHeader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="incrementalCopyHeader" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="incrementalCopyHeader"><span data-ttu-id="28a71-105">Blob の増分のコピーのステータスを示す文字列します。</span><span class="sxs-lookup"><span data-stu-id="28a71-105">String giving the incremental copy status of the blob</span></span></param>
        <summary>
            <span data-ttu-id="28a71-106">場合差分コピー内の blob を決定します。</span><span class="sxs-lookup"><span data-stu-id="28a71-106">Determines if a blob in an incremental copy.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="28a71-107"><c>true</c> blob が増分のコピーである場合または<c>false</c>しない場合。</span><span class="sxs-lookup"><span data-stu-id="28a71-107"><c>true</c> if blob is an incremental copy or <c>false</c> if not.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseDuration">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.LeaseDuration GetLeaseDuration (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseDuration GetLeaseDuration(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseDuration(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetLeaseDuration (response As HttpWebResponse) As LeaseDuration" />
      <MemberSignature Language="F#" Value="static member GetLeaseDuration : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.LeaseDuration" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseDuration response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseDuration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="28a71-108">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="28a71-108">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-109">リース期間は、web 応答から抽出します。</span><span class="sxs-lookup"><span data-stu-id="28a71-109">Extracts the lease duration from a web response.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-110">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseDuration" /> web 応答からの列挙。</span><span class="sxs-lookup"><span data-stu-id="28a71-110">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseDuration" /> enumeration from the web response.</span></span></returns>
        <remarks><span data-ttu-id="28a71-111">適切なヘッダーが存在しない場合のステータス<see cref="F:Microsoft.WindowsAzure.Storage.Blob.LeaseDuration.Unspecified" />が返されます。</span><span class="sxs-lookup"><span data-stu-id="28a71-111">If the appropriate header is not present, a status of <see cref="F:Microsoft.WindowsAzure.Storage.Blob.LeaseDuration.Unspecified" /> is returned.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="28a71-112">ヘッダーには、認識されない値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="28a71-112">The header contains an unrecognized value.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseId">
      <MemberSignature Language="C#" Value="public static string GetLeaseId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetLeaseId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetLeaseId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetLeaseId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseId response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="28a71-113">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="28a71-113">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-114">Web 応答からのリース ID ヘッダーを抽出します。</span><span class="sxs-lookup"><span data-stu-id="28a71-114">Extracts the lease ID header from a web response.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-115">リース id です。</span><span class="sxs-lookup"><span data-stu-id="28a71-115">The lease ID.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseState">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.LeaseState GetLeaseState (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseState GetLeaseState(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseState(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetLeaseState (response As HttpWebResponse) As LeaseState" />
      <MemberSignature Language="F#" Value="static member GetLeaseState : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.LeaseState" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseState response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseState</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="28a71-116">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="28a71-116">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-117">リースの状態は、web 応答から抽出します。</span><span class="sxs-lookup"><span data-stu-id="28a71-117">Extracts the lease state from a web response.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-118">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseState" /> web 応答からの列挙。</span><span class="sxs-lookup"><span data-stu-id="28a71-118">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseState" /> enumeration from the web response.</span></span></returns>
        <remarks><span data-ttu-id="28a71-119">適切なヘッダーが存在しない場合のステータス<see cref="F:Microsoft.WindowsAzure.Storage.Blob.LeaseState.Unspecified" />が返されます。</span><span class="sxs-lookup"><span data-stu-id="28a71-119">If the appropriate header is not present, a status of <see cref="F:Microsoft.WindowsAzure.Storage.Blob.LeaseState.Unspecified" /> is returned.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="28a71-120">ヘッダーには、認識されない値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="28a71-120">The header contains an unrecognized value.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.LeaseStatus GetLeaseStatus (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.WindowsAzure.Storage.Blob.LeaseStatus GetLeaseStatus(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseStatus(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetLeaseStatus (response As HttpWebResponse) As LeaseStatus" />
      <MemberSignature Language="F#" Value="static member GetLeaseStatus : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.LeaseStatus" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetLeaseStatus response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.LeaseStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="28a71-121">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="28a71-121">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-122">リースの状態は、web 応答から抽出します。</span><span class="sxs-lookup"><span data-stu-id="28a71-122">Extracts the lease status from a web response.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-123">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseStatus" /> web 応答からの列挙。</span><span class="sxs-lookup"><span data-stu-id="28a71-123">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.LeaseStatus" /> enumeration from the web response.</span></span></returns>
        <remarks><span data-ttu-id="28a71-124">適切なヘッダーが存在しない場合のステータス<see cref="F:Microsoft.WindowsAzure.Storage.Blob.LeaseStatus.Unspecified" />が返されます。</span><span class="sxs-lookup"><span data-stu-id="28a71-124">If the appropriate header is not present, a status of <see cref="F:Microsoft.WindowsAzure.Storage.Blob.LeaseStatus.Unspecified" /> is returned.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="28a71-125">ヘッダーには、認識されない値が含まれています。</span><span class="sxs-lookup"><span data-stu-id="28a71-125">The header contains an unrecognized value.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,string&gt; GetMetadata (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GetMetadata(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetMetadata(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMetadata (response As HttpWebResponse) As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : System.Net.HttpWebResponse -&gt; System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetMetadata response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="28a71-126">サーバーからの応答。</span><span class="sxs-lookup"><span data-stu-id="28a71-126">The response from server.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-127">ユーザー定義メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="28a71-127">Gets the user-defined metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-128">A<see cref="T:System.Collections.IDictionary" />のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="28a71-128">A <see cref="T:System.Collections.IDictionary" /> of the metadata.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Blob.BlobProperties GetProperties (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Blob.BlobProperties GetProperties(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetProperties(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetProperties (response As HttpWebResponse) As BlobProperties" />
      <MemberSignature Language="F#" Value="static member GetProperties : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobProperties" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetProperties response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="28a71-129">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="28a71-129">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-130">応答から blob のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="28a71-130">Gets the blob's properties from the response.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-131">Blob のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="28a71-131">The blob's properties.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemainingLeaseTime">
      <MemberSignature Language="C#" Value="public static Nullable&lt;int&gt; GetRemainingLeaseTime (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype System.Nullable`1&lt;int32&gt; GetRemainingLeaseTime(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetRemainingLeaseTime(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRemainingLeaseTime (response As HttpWebResponse) As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="static member GetRemainingLeaseTime : System.Net.HttpWebResponse -&gt; Nullable&lt;int&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetRemainingLeaseTime response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="28a71-132">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="28a71-132">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-133">残りのリース期間は、web 応答から抽出します。</span><span class="sxs-lookup"><span data-stu-id="28a71-133">Extracts the remaining lease time from a web response.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-134">残りのリース時間 (秒)。</span><span class="sxs-lookup"><span data-stu-id="28a71-134">The remaining lease time, in seconds.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetRequestId response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="28a71-135">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="28a71-135">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-136">応答からの要求 ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="28a71-136">Gets the request ID from the response.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-137">要求に関連付けられている一意の値。</span><span class="sxs-lookup"><span data-stu-id="28a71-137">A unique value associated with the request.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServerEncrypted">
      <MemberSignature Language="C#" Value="public static bool GetServerEncrypted (string encryptionHeader);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool GetServerEncrypted(string encryptionHeader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetServerEncrypted(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetServerEncrypted (encryptionHeader As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member GetServerEncrypted : string -&gt; bool" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetServerEncrypted encryptionHeader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptionHeader" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="encryptionHeader"><span data-ttu-id="28a71-138">サーバーの暗号化の状態を与える文字列。</span><span class="sxs-lookup"><span data-stu-id="28a71-138">String giving the status of server encryption.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-139">Blob がサーバー側暗号化として表示されているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="28a71-139">Determines if a blob is listed as server-side encypted.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="28a71-140"><c>true</c> blob が暗号化されている場合または<c>false</c>しない場合。</span><span class="sxs-lookup"><span data-stu-id="28a71-140"><c>true</c> if blob encrypted or <c>false</c> if not.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSnapshotTime">
      <MemberSignature Language="C#" Value="public static string GetSnapshotTime (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetSnapshotTime(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetSnapshotTime(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetSnapshotTime (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetSnapshotTime : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.GetSnapshotTime response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="28a71-141">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="28a71-141">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-142">応答から、スナップショットのタイムスタンプを取得します。</span><span class="sxs-lookup"><span data-stu-id="28a71-142">Gets the snapshot timestamp from the response.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-143">スナップショットのタイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="28a71-143">The snapshot timestamp.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.ReadServiceProperties(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceProperties (inputStream As Stream) As ServiceProperties" />
      <MemberSignature Language="F#" Value="static member ReadServiceProperties : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.ReadServiceProperties inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="28a71-144">サービスのプロパティが読み取り元のストリーム。</span><span class="sxs-lookup"><span data-stu-id="28a71-144">The stream from which to read the service properties.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-145">サービスのプロパティをストリームから読み取ります。</span><span class="sxs-lookup"><span data-stu-id="28a71-145">Reads service properties from a stream.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-146">ストリームに格納されているサービスのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="28a71-146">The service properties stored in the stream.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceStats">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats ReadServiceStats (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats ReadServiceStats(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.ReadServiceStats(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceStats (inputStream As Stream) As ServiceStats" />
      <MemberSignature Language="F#" Value="static member ReadServiceStats : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobHttpResponseParsers.ReadServiceStats inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="28a71-147">サービスの統計情報を読み取り元のストリーム。</span><span class="sxs-lookup"><span data-stu-id="28a71-147">The stream from which to read the service stats.</span></span></param>
        <summary>
            <span data-ttu-id="28a71-148">ストリームからサービスの統計情報を読み取ります。</span><span class="sxs-lookup"><span data-stu-id="28a71-148">Reads service stats from a stream.</span></span>
            </summary>
        <returns><span data-ttu-id="28a71-149">ストリームに格納されているサービスの統計情報です。</span><span class="sxs-lookup"><span data-stu-id="28a71-149">The service stats stored in the stream.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>