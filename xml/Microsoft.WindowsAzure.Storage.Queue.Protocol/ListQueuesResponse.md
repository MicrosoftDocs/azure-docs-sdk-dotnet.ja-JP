<Type Name="ListQueuesResponse" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse">
  <TypeSignature Language="C#" Value="public sealed class ListQueuesResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListQueuesResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListQueuesResponse&#xA;Inherits ResponseParsingBase(Of QueueEntry)" />
  <TypeSignature Language="F#" Value="type ListQueuesResponse = class&#xA;    inherit ResponseParsingBase&lt;QueueEntry&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="61e76-101">操作を一覧表示するキューからの応答を解析するためのメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="61e76-101">Provides methods for parsing the response from a queue listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListQueuesResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse" Usage="new Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="61e76-102">解析されるストリーム。</span><span class="sxs-lookup"><span data-stu-id="61e76-102">The stream to be parsed.</span></span></param>
        <summary>
            <span data-ttu-id="61e76-103"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="61e76-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListingContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext ListingContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext ListingContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.ListingContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListingContext As ListingContext" />
      <MemberSignature Language="F#" Value="member this.ListingContext : Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.ListingContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61e76-104">XML 応答からリスト コンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="61e76-104">Gets the listing context from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="61e76-105">一覧作成操作のパラメーターのセット。</span><span class="sxs-lookup"><span data-stu-id="61e76-105">A set of parameters for the listing operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Marker">
      <MemberSignature Language="C#" Value="public string Marker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Marker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Marker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Marker As String" />
      <MemberSignature Language="F#" Value="member this.Marker : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Marker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61e76-106">XML 応答の一覧作成操作に指定されたマーカー値を取得します。</span><span class="sxs-lookup"><span data-stu-id="61e76-106">Gets the Marker value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="61e76-107">マーカー値です。</span><span class="sxs-lookup"><span data-stu-id="61e76-107">The Marker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public int MaxResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResults As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61e76-108">XML 応答の一覧作成操作に指定された MaxResults 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="61e76-108">Gets the MaxResults value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="61e76-109">MaxResults の値です。</span><span class="sxs-lookup"><span data-stu-id="61e76-109">The MaxResults value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextMarker">
      <MemberSignature Language="C#" Value="public string NextMarker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextMarker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.NextMarker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextMarker As String" />
      <MemberSignature Language="F#" Value="member this.NextMarker : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.NextMarker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61e76-110">一覧が完了しなかった場合は、XML 応答から NextMarker 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="61e76-110">Gets the NextMarker value from the XML response, if the listing was not complete.</span></span>
            </summary>
        <value><span data-ttu-id="61e76-111">NextMarker 値です。</span><span class="sxs-lookup"><span data-stu-id="61e76-111">The NextMarker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of QueueEntry)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;" Usage="listQueuesResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61e76-112">操作を一覧表示するキューの応答に XML を解析します。</span><span class="sxs-lookup"><span data-stu-id="61e76-112">Parses the response XML for a queue listing operation.</span></span>
            </summary>
        <returns><span data-ttu-id="61e76-113">列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61e76-113">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Prefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61e76-114">XML 応答の一覧作成操作に指定されたプレフィックス値を取得します。</span><span class="sxs-lookup"><span data-stu-id="61e76-114">Gets the Prefix value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="61e76-115">プレフィックスの値です。</span><span class="sxs-lookup"><span data-stu-id="61e76-115">The Prefix value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Queues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt; Queues { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt; Queues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Queues" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Queues As IEnumerable(Of QueueEntry)" />
      <MemberSignature Language="F#" Value="member this.Queues : seq&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Queues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61e76-116">列挙可能なコレクションを取得<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry" />応答からのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61e76-116">Gets an enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry" /> objects from the response.</span></span>
            </summary>
        <value><span data-ttu-id="61e76-117">列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="61e76-117">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry" /> objects.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>