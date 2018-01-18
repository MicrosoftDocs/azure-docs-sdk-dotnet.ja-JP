<Type Name="ODataErrorHelper" FullName="Microsoft.Azure.CosmosDB.Table.ODataErrorHelper">
  <TypeSignature Language="C#" Value="public static class ODataErrorHelper" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ODataErrorHelper extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.ODataErrorHelper" />
  <TypeSignature Language="VB.NET" Value="Public Class ODataErrorHelper" />
  <TypeSignature Language="F#" Value="type ODataErrorHelper = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="68a82-101">テーブルの Windows Azure ストレージ サービスによって返される拡張エラー情報を処理するための他の機能を表します。</span><span class="sxs-lookup"><span data-stu-id="68a82-101">Represents additional functionality for processing extended error information returned by the Windows Azure storage services for Tables.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ReadAndParseExtendedError">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Storage.StorageExtendedErrorInformation ReadAndParseExtendedError (System.IO.Stream inputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Storage.StorageExtendedErrorInformation ReadAndParseExtendedError(class System.IO.Stream inputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadAndParseExtendedError(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadAndParseExtendedError (inputStream As Stream) As StorageExtendedErrorInformation" />
      <MemberSignature Language="F#" Value="static member ReadAndParseExtendedError : System.IO.Stream -&gt; Microsoft.Azure.Storage.StorageExtendedErrorInformation" Usage="Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadAndParseExtendedError inputStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.StorageExtendedErrorInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="68a82-102">解析するストリーム。</span><span class="sxs-lookup"><span data-stu-id="68a82-102">The stream to parse.</span></span></param>
        <summary>
            <span data-ttu-id="68a82-103">ストリームからエラーの詳細を解析してください。</span><span class="sxs-lookup"><span data-stu-id="68a82-103">Parses the error details from the stream</span></span>
            </summary>
        <returns><span data-ttu-id="68a82-104">エラーの詳細です。</span><span class="sxs-lookup"><span data-stu-id="68a82-104">The error details.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAndParseExtendedErrorAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.StorageExtendedErrorInformation&gt; ReadAndParseExtendedErrorAsync (System.IO.Stream responseStream, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.StorageExtendedErrorInformation&gt; ReadAndParseExtendedErrorAsync(class System.IO.Stream responseStream, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadAndParseExtendedErrorAsync(System.IO.Stream,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReadAndParseExtendedErrorAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.StorageExtendedErrorInformation&gt;" Usage="Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadAndParseExtendedErrorAsync (responseStream, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.CosmosDB.Table.ODataErrorHelper/&lt;ReadAndParseExtendedErrorAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.StorageExtendedErrorInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="responseStream" Type="System.IO.Stream" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="responseStream"><span data-ttu-id="68a82-105">解析するストリーム。</span><span class="sxs-lookup"><span data-stu-id="68a82-105">The stream to parse.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="68a82-106">キャンセル トークンが要求を取り消すために使用します。</span><span class="sxs-lookup"><span data-stu-id="68a82-106">Cancellation token used to cancel the request.</span></span></param>
        <summary>
            <span data-ttu-id="68a82-107">ストリームからエラーの詳細を解析します。</span><span class="sxs-lookup"><span data-stu-id="68a82-107">Parses the error details from the stream.</span></span>
            </summary>
        <returns><span data-ttu-id="68a82-108">エラーの詳細です。</span><span class="sxs-lookup"><span data-stu-id="68a82-108">The error details.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadFromStreamUsingODataLib">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Storage.StorageExtendedErrorInformation ReadFromStreamUsingODataLib (System.IO.Stream inputStream, System.Net.HttpWebResponse response, string contentType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Storage.StorageExtendedErrorInformation ReadFromStreamUsingODataLib(class System.IO.Stream inputStream, class System.Net.HttpWebResponse response, string contentType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadFromStreamUsingODataLib(System.IO.Stream,System.Net.HttpWebResponse,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReadFromStreamUsingODataLib (inputStream As Stream, response As HttpWebResponse, contentType As String) As StorageExtendedErrorInformation" />
      <MemberSignature Language="F#" Value="static member ReadFromStreamUsingODataLib : System.IO.Stream * System.Net.HttpWebResponse * string -&gt; Microsoft.Azure.Storage.StorageExtendedErrorInformation" Usage="Microsoft.Azure.CosmosDB.Table.ODataErrorHelper.ReadFromStreamUsingODataLib (inputStream, response, contentType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.StorageExtendedErrorInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="inputStream" Type="System.IO.Stream" />
        <Parameter Name="response" Type="System.Net.HttpWebResponse" />
        <Parameter Name="contentType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="inputStream"><span data-ttu-id="68a82-109">入力ストリーム。</span><span class="sxs-lookup"><span data-stu-id="68a82-109">The input stream.</span></span></param>
        <param name="response"><span data-ttu-id="68a82-110">Web 応答です。</span><span class="sxs-lookup"><span data-stu-id="68a82-110">The web response.</span></span></param>
        <param name="contentType"><span data-ttu-id="68a82-111">応答コンテンツの種類です。</span><span class="sxs-lookup"><span data-stu-id="68a82-111">The response Content-Type.</span></span></param>
        <summary>
            <span data-ttu-id="68a82-112">ストリームからのエラーの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="68a82-112">Gets the error details from the stream.</span></span>
            </summary>
        <returns><span data-ttu-id="68a82-113">エラーの詳細です。</span><span class="sxs-lookup"><span data-stu-id="68a82-113">The error details.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>