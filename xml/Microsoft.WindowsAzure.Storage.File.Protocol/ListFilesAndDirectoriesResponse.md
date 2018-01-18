<Type Name="ListFilesAndDirectoriesResponse" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse">
  <TypeSignature Language="C#" Value="public sealed class ListFilesAndDirectoriesResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListFilesAndDirectoriesResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListFilesAndDirectoriesResponse&#xA;Inherits ResponseParsingBase(Of IListFileEntry)" />
  <TypeSignature Language="F#" Value="type ListFilesAndDirectoriesResponse = class&#xA;    inherit ResponseParsingBase&lt;IListFileEntry&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="45a4d-101">ファイルの一覧作成操作からの応答を解析するためのメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="45a4d-101">Provides methods for parsing the response from a file listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListFilesAndDirectoriesResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse" Usage="new Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse stream" />
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
        <param name="stream"><span data-ttu-id="45a4d-102">解析されるストリーム。</span><span class="sxs-lookup"><span data-stu-id="45a4d-102">The stream to be parsed.</span></span></param>
        <summary>
            <span data-ttu-id="45a4d-103"><see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="45a4d-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Files">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt; Files { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt; Files" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.Files" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Files As IEnumerable(Of IListFileEntry)" />
      <MemberSignature Language="F#" Value="member this.Files : seq&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.Files" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45a4d-104">実装するオブジェクトの列挙可能なコレクションを取得<see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" />応答からです。</span><span class="sxs-lookup"><span data-stu-id="45a4d-104">Gets an enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" /> from the response.</span></span>
            </summary>
        <value><span data-ttu-id="45a4d-105">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" />です。</span><span class="sxs-lookup"><span data-stu-id="45a4d-105">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListingContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext ListingContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext ListingContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.ListingContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListingContext As FileListingContext" />
      <MemberSignature Language="F#" Value="member this.ListingContext : Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.ListingContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="45a4d-106">XML 応答からリスト コンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="45a4d-106">Gets the listing context from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="45a4d-107">一覧作成操作のパラメーターのセット。</span><span class="sxs-lookup"><span data-stu-id="45a4d-107">A set of parameters for the listing operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Marker">
      <MemberSignature Language="C#" Value="public string Marker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Marker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.Marker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Marker As String" />
      <MemberSignature Language="F#" Value="member this.Marker : string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.Marker" />
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
            <span data-ttu-id="45a4d-108">XML 応答の一覧作成操作に指定されたマーカー値を取得します。</span><span class="sxs-lookup"><span data-stu-id="45a4d-108">Gets the Marker value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="45a4d-109">マーカー値です。</span><span class="sxs-lookup"><span data-stu-id="45a4d-109">The Marker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public int MaxResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResults As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.MaxResults" />
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
            <span data-ttu-id="45a4d-110">XML 応答の一覧作成操作に指定された MaxResults 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="45a4d-110">Gets the MaxResults value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="45a4d-111">MaxResults の値です。</span><span class="sxs-lookup"><span data-stu-id="45a4d-111">The MaxResults value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextMarker">
      <MemberSignature Language="C#" Value="public string NextMarker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextMarker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.NextMarker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextMarker As String" />
      <MemberSignature Language="F#" Value="member this.NextMarker : string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.NextMarker" />
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
            <span data-ttu-id="45a4d-112">一覧が完了しなかった場合は、XML 応答から NextMarker 値を取得します。</span><span class="sxs-lookup"><span data-stu-id="45a4d-112">Gets the NextMarker value from the XML response, if the listing was not complete.</span></span>
            </summary>
        <value><span data-ttu-id="45a4d-113">NextMarker 値です。</span><span class="sxs-lookup"><span data-stu-id="45a4d-113">The NextMarker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of IListFileEntry)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;" Usage="listFilesAndDirectoriesResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="45a4d-114">ファイルの一覧作成操作の応答に XML を解析します。</span><span class="sxs-lookup"><span data-stu-id="45a4d-114">Parses the response XML for a file listing operation.</span></span>
            </summary>
        <returns><span data-ttu-id="45a4d-115">実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" />です。</span><span class="sxs-lookup"><span data-stu-id="45a4d-115">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>