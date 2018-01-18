<Type Name="ODataErrorHelper" FullName="Microsoft.WindowsAzure.Storage.ODataErrorHelper">
  <TypeSignature Language="C#" Value="public static class ODataErrorHelper" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ODataErrorHelper extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.ODataErrorHelper" />
  <TypeSignature Language="VB.NET" Value="Public Class ODataErrorHelper" />
  <TypeSignature Language="F#" Value="type ODataErrorHelper = class" />
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
            <span data-ttu-id="58159-101">テーブルの Windows Azure ストレージ サービスによって返される拡張エラー情報を処理するための他の機能を表します。</span><span class="sxs-lookup"><span data-stu-id="58159-101">Represents additional functionality for processing extended error information returned by the Windows Azure storage services for Tables.</span></span>
            <span data-ttu-id="58159-102">クラスは、OData ライブラリ ExtendedErrorInformation のテーブルを解析するために必要な場合にのみロードに作成されました。</span><span class="sxs-lookup"><span data-stu-id="58159-102">The class was created to only load the OData library when required for parsing the ExtendedErrorInformation of Tables.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ReadAndParseExtendedError">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ReadAndParseExtendedError (Microsoft.Data.OData.IODataResponseMessage responseMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ReadAndParseExtendedError(class Microsoft.Data.OData.IODataResponseMessage responseMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.ODataErrorHelper.ReadAndParseExtendedError(Microsoft.Data.OData.IODataResponseMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadAndParseExtendedError (responseMessage As IODataResponseMessage) As StorageExtendedErrorInformation" />
      <MemberSignature Language="F#" Value="static member ReadAndParseExtendedError : Microsoft.Data.OData.IODataResponseMessage -&gt; Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" Usage="Microsoft.WindowsAzure.Storage.ODataErrorHelper.ReadAndParseExtendedError responseMessage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="responseMessage" Type="Microsoft.Data.OData.IODataResponseMessage" />
      </Parameters>
      <Docs>
        <param name="responseMessage"><span data-ttu-id="58159-103">解析する IODataResponseMessage です。</span><span class="sxs-lookup"><span data-stu-id="58159-103">The IODataResponseMessage to parse.</span></span></param>
        <summary>
            <span data-ttu-id="58159-104">OData ライブラリを使用して、ストリームからエラーの詳細を解析します。</span><span class="sxs-lookup"><span data-stu-id="58159-104">Parses the error details from the stream using OData library.</span></span>
            </summary>
        <returns><span data-ttu-id="58159-105">エラーの詳細です。</span><span class="sxs-lookup"><span data-stu-id="58159-105">The error details.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDataServiceResponseFromStream">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ReadDataServiceResponseFromStream (System.IO.Stream inputStream, System.Collections.Generic.IDictionary&lt;string,string&gt; responseHeaders, string contentType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ReadDataServiceResponseFromStream(class System.IO.Stream inputStream, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; responseHeaders, string contentType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.ODataErrorHelper.ReadDataServiceResponseFromStream(System.IO.Stream,System.Collections.Generic.IDictionary{System.String,System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadDataServiceResponseFromStream (inputStream As Stream, responseHeaders As IDictionary(Of String, String), contentType As String) As StorageExtendedErrorInformation" />
      <MemberSignature Language="F#" Value="static member ReadDataServiceResponseFromStream : System.IO.Stream * System.Collections.Generic.IDictionary&lt;string, string&gt; * string -&gt; Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" Usage="Microsoft.WindowsAzure.Storage.ODataErrorHelper.ReadDataServiceResponseFromStream (inputStream, responseHeaders, contentType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
        <Parameter Name="responseHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="contentType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="58159-106">入力ストリーム。</span><span class="sxs-lookup"><span data-stu-id="58159-106">The input stream.</span></span></param>
        <param name="responseHeaders"><span data-ttu-id="58159-107">Web 応答ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="58159-107">The web response headers.</span></span></param>
        <param name="contentType"><span data-ttu-id="58159-108">応答コンテンツの種類です。</span><span class="sxs-lookup"><span data-stu-id="58159-108">The response Content-Type.</span></span></param>
        <summary>
            <span data-ttu-id="58159-109">OData ライブラリを使用して、ストリームからのエラーの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="58159-109">Gets the error details from the stream using OData library.</span></span>
            </summary>
        <returns><span data-ttu-id="58159-110">エラーの詳細です。</span><span class="sxs-lookup"><span data-stu-id="58159-110">The error details.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadFromStreamUsingODataLib">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ReadFromStreamUsingODataLib (System.IO.Stream inputStream, System.Net.HttpWebResponse response, string contentType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation ReadFromStreamUsingODataLib(class System.IO.Stream inputStream, class System.Net.HttpWebResponse response, string contentType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.ODataErrorHelper.ReadFromStreamUsingODataLib(System.IO.Stream,System.Net.HttpWebResponse,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadFromStreamUsingODataLib (inputStream As Stream, response As HttpWebResponse, contentType As String) As StorageExtendedErrorInformation" />
      <MemberSignature Language="F#" Value="static member ReadFromStreamUsingODataLib : System.IO.Stream * System.Net.HttpWebResponse * string -&gt; Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation" Usage="Microsoft.WindowsAzure.Storage.ODataErrorHelper.ReadFromStreamUsingODataLib (inputStream, response, contentType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
        <Parameter Name="contentType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="58159-111">入力ストリーム。</span><span class="sxs-lookup"><span data-stu-id="58159-111">The input stream.</span></span></param>
        <param name="response"><span data-ttu-id="58159-112">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="58159-112">The web response.</span></span></param>
        <param name="contentType"><span data-ttu-id="58159-113">応答コンテンツの種類です。</span><span class="sxs-lookup"><span data-stu-id="58159-113">The response Content-Type.</span></span></param>
        <summary>
            <span data-ttu-id="58159-114">OData ライブラリを使用して、ストリームからのエラーの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="58159-114">Gets the error details from the stream using OData library.</span></span>
            </summary>
        <returns><span data-ttu-id="58159-115">エラーの詳細です。</span><span class="sxs-lookup"><span data-stu-id="58159-115">The error details.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>