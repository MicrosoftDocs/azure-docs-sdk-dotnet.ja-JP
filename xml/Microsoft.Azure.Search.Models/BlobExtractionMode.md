<Type Name="BlobExtractionMode" FullName="Microsoft.Azure.Search.Models.BlobExtractionMode">
  <TypeSignature Language="C#" Value="public sealed class BlobExtractionMode : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.BlobExtractionMode&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BlobExtractionMode extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.BlobExtractionMode&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.BlobExtractionMode" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BlobExtractionMode&#xA;Inherits ExtensibleEnum(Of BlobExtractionMode)" />
  <TypeSignature Language="F#" Value="type BlobExtractionMode = class&#xA;    inherit ExtensibleEnum&lt;BlobExtractionMode&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.BlobExtractionMode&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.BlobExtractionMode</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.BlobExtractionMode&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="542c3-101">Blob ストレージ インデクサーによってインデックスが作成される blob のどの部分を定義します。</span><span class="sxs-lookup"><span data-stu-id="542c3-101">Defines which parts of a blob will be indexed by the blob storage indexer.</span></span> 
            <see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllMetadata">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.BlobExtractionMode AllMetadata;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.BlobExtractionMode AllMetadata" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.BlobExtractionMode.AllMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly AllMetadata As BlobExtractionMode " />
      <MemberSignature Language="F#" Value=" staticval mutable AllMetadata : Microsoft.Azure.Search.Models.BlobExtractionMode" Usage="Microsoft.Azure.Search.Models.BlobExtractionMode.AllMetadata" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.BlobExtractionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="542c3-102">ストレージ メタデータと blob のコンテンツから抽出されたコンテンツの種類固有のメタデータのインデックスはことを指定します。</span><span class="sxs-lookup"><span data-stu-id="542c3-102">Specifies that storage metadata and the content-type specific metadata extracted from the blob content will be indexed.</span></span>
            <see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage#content-type-specific-metadata-properties" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentAndMetadata">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.BlobExtractionMode ContentAndMetadata;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.BlobExtractionMode ContentAndMetadata" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.BlobExtractionMode.ContentAndMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly ContentAndMetadata As BlobExtractionMode " />
      <MemberSignature Language="F#" Value=" staticval mutable ContentAndMetadata : Microsoft.Azure.Search.Models.BlobExtractionMode" Usage="Microsoft.Azure.Search.Models.BlobExtractionMode.ContentAndMetadata" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.BlobExtractionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="542c3-103">すべてのメタデータと blob から抽出されたテキストのコンテンツのインデックスはことを指定します。</span><span class="sxs-lookup"><span data-stu-id="542c3-103">Specifies that all metadata and textual content extracted from the blob will be indexed.</span></span> <span data-ttu-id="542c3-104">これが既定値です。</span><span class="sxs-lookup"><span data-stu-id="542c3-104">This is the default value.</span></span>  
            <see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage#document-extraction-process" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.BlobExtractionMode Create (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.BlobExtractionMode Create(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.BlobExtractionMode.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (name As String) As BlobExtractionMode" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.BlobExtractionMode" Usage="Microsoft.Azure.Search.Models.BlobExtractionMode.Create name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.BlobExtractionMode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="542c3-105">Blob の抽出モードの名前です。</span><span class="sxs-lookup"><span data-stu-id="542c3-105">Name of the blob extraction mode.</span></span></param>
        <summary>
            <span data-ttu-id="542c3-106">新しい BlobExtractionMode インスタンスを作成または指定された名前と一致する既知の blob の抽出モードの場合は、既存のインスタンスを返します。</span><span class="sxs-lookup"><span data-stu-id="542c3-106">Creates a new BlobExtractionMode instance, or returns an existing instance if the given name matches that of a known blob extraction mode.</span></span>
            </summary>
        <returns><span data-ttu-id="542c3-107">指定した名前の BlobExtractionMode インスタンス。</span><span class="sxs-lookup"><span data-stu-id="542c3-107">A BlobExtractionMode instance with the given name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.BlobExtractionMode (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.BlobExtractionMode op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.BlobExtractionMode.op_Implicit(System.String)~Microsoft.Azure.Search.Models.BlobExtractionMode" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As BlobExtractionMode" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.BlobExtractionMode" Usage="Microsoft.Azure.Search.Models.BlobExtractionMode.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.BlobExtractionMode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="542c3-108">変換する文字列。</span><span class="sxs-lookup"><span data-stu-id="542c3-108">string to convert.</span></span></param>
        <summary>
            <span data-ttu-id="542c3-109">文字列から BlobExtractionMode への暗黙的な変換を定義します。</span><span class="sxs-lookup"><span data-stu-id="542c3-109">Defines implicit conversion from string to BlobExtractionMode.</span></span>
            </summary>
        <returns><span data-ttu-id="542c3-110">BlobExtractionMode として文字列です。</span><span class="sxs-lookup"><span data-stu-id="542c3-110">The string as a BlobExtractionMode.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageMetadata">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.BlobExtractionMode StorageMetadata;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.BlobExtractionMode StorageMetadata" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.BlobExtractionMode.StorageMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly StorageMetadata As BlobExtractionMode " />
      <MemberSignature Language="F#" Value=" staticval mutable StorageMetadata : Microsoft.Azure.Search.Models.BlobExtractionMode" Usage="Microsoft.Azure.Search.Models.BlobExtractionMode.StorageMetadata" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.BlobExtractionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="542c3-111">標準的な blob のプロパティとユーザー指定のメタデータのみがインデックス付けることを指定します。</span><span class="sxs-lookup"><span data-stu-id="542c3-111">Specifies that only the standard blob properties and user-specified metadata will be indexed.</span></span> 
            <see href="https://docs.microsoft.com/azure/storage/storage-properties-metadata" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>