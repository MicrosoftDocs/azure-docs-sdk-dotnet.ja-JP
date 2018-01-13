<Type Name="ListBlobsResponse" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse">
  <TypeSignature Language="C#" Value="public sealed class ListBlobsResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListBlobsResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListBlobsResponse&#xA;Inherits ResponseParsingBase(Of IListBlobEntry)" />
  <TypeSignature Language="F#" Value="type ListBlobsResponse = class&#xA;    inherit ResponseParsingBase&lt;IListBlobEntry&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="10466-101">Blob の一覧作成操作からの応答を解析するためのメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="10466-101">Provides methods for parsing the response from a blob listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListBlobsResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse" Usage="new Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse stream" />
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
        <param name="stream"><span data-ttu-id="10466-102">解析されるストリーム。</span><span class="sxs-lookup"><span data-stu-id="10466-102">The stream to be parsed.</span></span></param>
        <summary>
            <span data-ttu-id="10466-103"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="10466-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Blobs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; Blobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; Blobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Blobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Blobs As IEnumerable(Of IListBlobEntry)" />
      <MemberSignature Language="F#" Value="member this.Blobs : seq&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Blobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10466-104">実装するオブジェクトの列挙可能なコレクションを取得<see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />応答からです。</span><span class="sxs-lookup"><span data-stu-id="10466-104">Gets an enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" /> from the response.</span></span>
            </summary>
        <value><span data-ttu-id="10466-105">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />です。</span><span class="sxs-lookup"><span data-stu-id="10466-105">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public string Delimiter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Delimiter As String" />
      <MemberSignature Language="F#" Value="member this.Delimiter : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Delimiter" />
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
            <span data-ttu-id="10466-106">XML 応答の一覧作成操作に指定された区切り記号値を取得します。</span><span class="sxs-lookup"><span data-stu-id="10466-106">Gets the Delimiter value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="10466-107">区切り記号の値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="10466-107">A string containing the Delimiter value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListingContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext ListingContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext ListingContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.ListingContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListingContext As BlobListingContext" />
      <MemberSignature Language="F#" Value="member this.ListingContext : Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.ListingContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="10466-108">XML 応答からリスト コンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="10466-108">Gets the listing context from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="10466-109"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="10466-109">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Marker">
      <MemberSignature Language="C#" Value="public string Marker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Marker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Marker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Marker As String" />
      <MemberSignature Language="F#" Value="member this.Marker : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Marker" />
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
            <span data-ttu-id="10466-110">XML 応答の一覧作成操作に指定されたマーカー値を取得します。</span><span class="sxs-lookup"><span data-stu-id="10466-110">Gets the Marker value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="10466-111">マーカー値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="10466-111">A string containing the Marker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public int MaxResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResults As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.MaxResults" />
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
            <span data-ttu-id="10466-112">XML 応答の一覧作成操作に指定された MaxResults 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="10466-112">Gets the MaxResults value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="10466-113">MaxResults の値を格納する整数。</span><span class="sxs-lookup"><span data-stu-id="10466-113">An integer containing the MaxResults value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextMarker">
      <MemberSignature Language="C#" Value="public string NextMarker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextMarker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.NextMarker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextMarker As String" />
      <MemberSignature Language="F#" Value="member this.NextMarker : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.NextMarker" />
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
            <span data-ttu-id="10466-114">取得または一覧が完了しなかった場合に、XML 応答から NextMarker 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="10466-114">Gets or sets the NextMarker value from the XML response, if the listing was not complete.</span></span>
            </summary>
        <value><span data-ttu-id="10466-115">NextMarker 値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="10466-115">A string containing the NextMarker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of IListBlobEntry)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" Usage="listBlobsResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="10466-116">Blob の一覧作成操作の応答 XML を解析します。</span><span class="sxs-lookup"><span data-stu-id="10466-116">Parses the response XML for a blob listing operation.</span></span>
            </summary>
        <returns><span data-ttu-id="10466-117">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />です。</span><span class="sxs-lookup"><span data-stu-id="10466-117">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Prefix" />
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
            <span data-ttu-id="10466-118">XML 応答の一覧作成操作に指定されたプレフィックス値を取得します。</span><span class="sxs-lookup"><span data-stu-id="10466-118">Gets the Prefix value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="10466-119">プレフィックスの値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="10466-119">A string containing the Prefix value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>