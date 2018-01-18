<Type Name="ShareHttpResponseParsers" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers">
  <TypeSignature Language="C#" Value="public static class ShareHttpResponseParsers" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ShareHttpResponseParsers extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers" />
  <TypeSignature Language="VB.NET" Value="Public Class ShareHttpResponseParsers" />
  <TypeSignature Language="F#" Value="type ShareHttpResponseParsers = class" />
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
            <span data-ttu-id="649a6-101">ファイル サービスで共有での操作に対する応答を解析中のメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="649a6-101">Provides methods for parsing responses to operations on shares in the File service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,string&gt; GetMetadata (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, string&gt; GetMetadata(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetMetadata(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetMetadata (response As HttpWebResponse) As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="static member GetMetadata : System.Net.HttpWebResponse -&gt; System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetMetadata response" />
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
        <param name="response"><span data-ttu-id="649a6-102">サーバーからの応答。</span><span class="sxs-lookup"><span data-stu-id="649a6-102">The response from server.</span></span></param>
        <summary>
            <span data-ttu-id="649a6-103">ユーザー定義メタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="649a6-103">Gets the user-defined metadata.</span></span>
            </summary>
        <returns><span data-ttu-id="649a6-104">A<see cref="T:System.Collections.IDictionary" />のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="649a6-104">A <see cref="T:System.Collections.IDictionary" /> of the metadata.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.File.FileShareProperties GetProperties (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.File.FileShareProperties GetProperties(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetProperties(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetProperties (response As HttpWebResponse) As FileShareProperties" />
      <MemberSignature Language="F#" Value="static member GetProperties : System.Net.HttpWebResponse -&gt; Microsoft.WindowsAzure.Storage.File.FileShareProperties" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetProperties response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileShareProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="response"><span data-ttu-id="649a6-105">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="649a6-105">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="649a6-106">応答から共有のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="649a6-106">Gets the share's properties from the response.</span></span>
            </summary>
        <returns><span data-ttu-id="649a6-107">共有の属性です。</span><span class="sxs-lookup"><span data-stu-id="649a6-107">The share's attributes.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRequestId">
      <MemberSignature Language="C#" Value="public static string GetRequestId (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRequestId(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetRequestId(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetRequestId (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetRequestId : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetRequestId response" />
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
        <param name="response"><span data-ttu-id="649a6-108">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="649a6-108">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="649a6-109">応答からの要求 ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="649a6-109">Gets the request ID from the response.</span></span>
            </summary>
        <returns><span data-ttu-id="649a6-110">要求に関連付けられている一意の値。</span><span class="sxs-lookup"><span data-stu-id="649a6-110">A unique value associated with the request.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSnapshotTime">
      <MemberSignature Language="C#" Value="public static string GetSnapshotTime (System.Net.HttpWebResponse response);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetSnapshotTime(class System.Net.HttpWebResponse response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetSnapshotTime(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetSnapshotTime (response As HttpWebResponse) As String" />
      <MemberSignature Language="F#" Value="static member GetSnapshotTime : System.Net.HttpWebResponse -&gt; string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.GetSnapshotTime response" />
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
        <param name="response"><span data-ttu-id="649a6-111">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="649a6-111">The web response.</span></span></param>
        <summary>
            <span data-ttu-id="649a6-112">応答から、スナップショットのタイムスタンプを取得します。</span><span class="sxs-lookup"><span data-stu-id="649a6-112">Gets the snapshot timestamp from the response.</span></span>
            </summary>
        <returns><span data-ttu-id="649a6-113">スナップショットのタイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="649a6-113">The snapshot timestamp.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void ReadSharedAccessIdentifiers (System.IO.Stream inputStream, Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadSharedAccessIdentifiers(class System.IO.Stream inputStream, class Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadSharedAccessIdentifiers(System.IO.Stream,Microsoft.WindowsAzure.Storage.File.FileSharePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ReadSharedAccessIdentifiers (inputStream As Stream, permissions As FileSharePermissions)" />
      <MemberSignature Language="F#" Value="static member ReadSharedAccessIdentifiers : System.IO.Stream * Microsoft.WindowsAzure.Storage.File.FileSharePermissions -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadSharedAccessIdentifiers (inputStream, permissions)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="649a6-114">Xml 形式のポリシーのストリーム。</span><span class="sxs-lookup"><span data-stu-id="649a6-114">The stream of XML policies.</span></span></param>
        <param name="permissions"><span data-ttu-id="649a6-115">ポリシーが書き込まれるアクセス許可オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="649a6-115">The permissions object to which the policies are to be written.</span></span></param>
        <summary>
            <span data-ttu-id="649a6-116">共有アクセス ポリシーを xml ストリームから読み取ります。</span><span class="sxs-lookup"><span data-stu-id="649a6-116">Reads the share access policies from a stream in XML.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadShareStats">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats ReadShareStats (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats ReadShareStats(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadShareStats(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadShareStats (inputStream As Stream) As ShareStats" />
      <MemberSignature Language="F#" Value="static member ReadShareStats : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ShareHttpResponseParsers.ReadShareStats inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="649a6-117">共有の統計情報を読み取り元のストリーム。</span><span class="sxs-lookup"><span data-stu-id="649a6-117">The stream from which to read the share stats.</span></span></param>
        <summary>
            <span data-ttu-id="649a6-118">読み取り、ストリームからの統計情報を共有します。</span><span class="sxs-lookup"><span data-stu-id="649a6-118">Reads share stats from a stream.</span></span>
            </summary>
        <returns><span data-ttu-id="649a6-119">ストリームに格納されている共有の統計情報です。</span><span class="sxs-lookup"><span data-stu-id="649a6-119">The share stats stored in the stream.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>