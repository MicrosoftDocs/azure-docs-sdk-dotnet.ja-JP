<Type Name="QueueHttpResponseParsers" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers">
  <TypeSignature Language="C#" Value="public static class QueueHttpResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueueHttpResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueHttpResponseParsers" />
  <TypeSignature Language="F#" Value="type QueueHttpResponseParsers = class" />
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
            <span data-ttu-id="b9983-101">キュー サービスのキュー データを含む応答を解析するためのメソッドのセットを提供します。</span><span class="sxs-lookup"><span data-stu-id="b9983-101">Provides a set of methods for parsing a response containing queue data from the Queue service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetApproximateMessageCount">
      <MemberSignature Language="C#" Value="public static string GetApproximateMessageCount (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetApproximateMessageCount(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetApproximateMessageCount(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetApproximateMessageCount (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetApproximateMessageCount : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetApproximateMessageCount response" />
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
        <param name="response"><span data-ttu-id="b9983-102">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="b9983-102">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="b9983-103">キューのおおよそのメッセージ数を取得します。</span><span class="sxs-lookup"><span data-stu-id="b9983-103">Gets the approximate message count for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="b9983-104">キューのおおよその数。</span><span class="sxs-lookup"><span data-stu-id="b9983-104">The approximate count for the queue.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,string&gt; GetMetadata (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GetMetadata(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetMetadata(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMetadata (response As HttpWebResponse) As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : System.Net.HttpWebResponse -&gt; System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetMetadata response" />
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
        <param name="response"><span data-ttu-id="b9983-105">サーバーからの応答。</span><span class="sxs-lookup"><span data-stu-id="b9983-105">The response from server.</span></span></param>
        <summary>
            <span data-ttu-id="b9983-106">ユーザー定義メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="b9983-106">Gets the user-defined metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="b9983-107">型のオブジェクト<see cref="T:System.Collections.IDictionary" />メタデータを含むです。</span><span class="sxs-lookup"><span data-stu-id="b9983-107">An object of type <see cref="T:System.Collections.IDictionary" /> containing the metadata.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextVisibleTime">
      <MemberSignature Language="C#" Value="public static DateTime GetNextVisibleTime (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype System.DateTime GetNextVisibleTime(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetNextVisibleTime(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetNextVisibleTime (response As HttpWebResponse) As DateTime" />
      <MemberSignature Language="F#" Value="static member GetNextVisibleTime : System.Net.HttpWebResponse -&gt; DateTime" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetNextVisibleTime response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="b9983-108">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="b9983-108">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="b9983-109">Web 応答ヘッダーから、次回の可視性を抽出します。</span><span class="sxs-lookup"><span data-stu-id="b9983-109">Extracts the next visibility time from a web response header.</span></span>
            </summary>
        <returns><span data-ttu-id="b9983-110">応答のヘッダーに格納されている次の可視性の時刻。</span><span class="sxs-lookup"><span data-stu-id="b9983-110">The time of next visibility stored in the header of the response.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPopReceipt">
      <MemberSignature Language="C#" Value="public static string GetPopReceipt (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetPopReceipt(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetPopReceipt(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetPopReceipt (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetPopReceipt : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetPopReceipt response" />
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
        <param name="response"><span data-ttu-id="b9983-111">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="b9983-111">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="b9983-112">Popreceipt は、web 応答ヘッダーから抽出します。</span><span class="sxs-lookup"><span data-stu-id="b9983-112">Extracts the pop receipt from a web response header.</span></span>
            </summary>
        <returns><span data-ttu-id="b9983-113">応答のヘッダーに格納されている popreceipt。</span><span class="sxs-lookup"><span data-stu-id="b9983-113">The pop receipt stored in the header of the response.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.GetRequestId response" />
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
        <param name="response"><span data-ttu-id="b9983-114">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="b9983-114">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="b9983-115">応答からの要求 ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="b9983-115">Gets the request ID from the response.</span></span>
            </summary>
        <returns><span data-ttu-id="b9983-116">要求に関連付けられている一意の値。</span><span class="sxs-lookup"><span data-stu-id="b9983-116">A unique value associated with the request.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties ReadServiceProperties(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceProperties(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceProperties (inputStream As Stream) As ServiceProperties" />
      <MemberSignature Language="F#" Value="static member ReadServiceProperties : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceProperties inputStream" />
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
        <param name="inputStream"><span data-ttu-id="b9983-117">サービスのプロパティが読み取り元のストリーム。</span><span class="sxs-lookup"><span data-stu-id="b9983-117">The stream from which to read the service properties.</span></span></param>
        <summary>
            <span data-ttu-id="b9983-118">サービスのプロパティをストリームから読み取ります。</span><span class="sxs-lookup"><span data-stu-id="b9983-118">Reads service properties from a stream.</span></span>
            </summary>
        <returns><span data-ttu-id="b9983-119">ストリームに格納されているサービスのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="b9983-119">The service properties stored in the stream.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadServiceStats">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats ReadServiceStats (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats ReadServiceStats(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceStats(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadServiceStats (inputStream As Stream) As ServiceStats" />
      <MemberSignature Language="F#" Value="static member ReadServiceStats : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadServiceStats inputStream" />
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
        <param name="inputStream"><span data-ttu-id="b9983-120">サービスの統計情報を読み取り元のストリーム。</span><span class="sxs-lookup"><span data-stu-id="b9983-120">The stream from which to read the service stats.</span></span></param>
        <summary>
            <span data-ttu-id="b9983-121">ストリームからサービスの統計情報を読み取ります。</span><span class="sxs-lookup"><span data-stu-id="b9983-121">Reads service stats from a stream.</span></span>
            </summary>
        <returns><span data-ttu-id="b9983-122">ストリームに格納されているサービスの統計情報です。</span><span class="sxs-lookup"><span data-stu-id="b9983-122">The service stats stored in the stream.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void ReadSharedAccessIdentifiers (System.IO.Stream inputStream, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadSharedAccessIdentifiers(class System.IO.Stream inputStream, class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadSharedAccessIdentifiers(System.IO.Stream,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ReadSharedAccessIdentifiers (inputStream As Stream, permissions As QueuePermissions)" />
      <MemberSignature Language="F#" Value="static member ReadSharedAccessIdentifiers : System.IO.Stream * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueHttpResponseParsers.ReadSharedAccessIdentifiers (inputStream, permissions)" />
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
        <Parameter Name="inputStream" Type="System.IO.Stream" />
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="b9983-123">Xml 形式のポリシーのストリーム。</span><span class="sxs-lookup"><span data-stu-id="b9983-123">The stream of XML policies.</span></span></param>
        <param name="permissions"><span data-ttu-id="b9983-124">ポリシーが書き込まれるアクセス許可オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b9983-124">The permissions object to which the policies are to be written.</span></span></param>
        <summary>
            <span data-ttu-id="b9983-125">共有アクセス ポリシーを xml ストリームから読み取ります。</span><span class="sxs-lookup"><span data-stu-id="b9983-125">Reads the share access policies from a stream in XML.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>