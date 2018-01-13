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
            Blob ストレージ インデクサーによってインデックスが作成される blob のどの部分を定義します。 
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
            ストレージ メタデータと blob のコンテンツから抽出されたコンテンツの種類固有のメタデータのインデックスはことを指定します。
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
            すべてのメタデータと blob から抽出されたテキストのコンテンツのインデックスはことを指定します。 これが既定値です。  
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
        <param name="name">Blob の抽出モードの名前です。</param>
        <summary>
            新しい BlobExtractionMode インスタンスを作成または指定された名前と一致する既知の blob の抽出モードの場合は、既存のインスタンスを返します。
            </summary>
        <returns>指定した名前の BlobExtractionMode インスタンス。</returns>
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
        <param name="name">変換する文字列。</param>
        <summary>
            文字列から BlobExtractionMode への暗黙的な変換を定義します。
            </summary>
        <returns>BlobExtractionMode として文字列です。</returns>
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
            標準的な blob のプロパティとユーザー指定のメタデータのみがインデックス付けることを指定します。 
            <see href="https://docs.microsoft.com/azure/storage/storage-properties-metadata" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>