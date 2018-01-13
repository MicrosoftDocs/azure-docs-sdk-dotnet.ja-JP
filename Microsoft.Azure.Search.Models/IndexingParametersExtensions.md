<Type Name="IndexingParametersExtensions" FullName="Microsoft.Azure.Search.Models.IndexingParametersExtensions">
  <TypeSignature Language="C#" Value="public static class IndexingParametersExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IndexingParametersExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexingParametersExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IndexingParametersExtensions" />
  <TypeSignature Language="F#" Value="type IndexingParametersExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            IndexingParameters クラスの拡張メソッドを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DoNotFailOnUnsupportedContentType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters DoNotFailOnUnsupportedContentType (this Microsoft.Azure.Search.Models.IndexingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters DoNotFailOnUnsupportedContentType(class Microsoft.Azure.Search.Models.IndexingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.DoNotFailOnUnsupportedContentType(Microsoft.Azure.Search.Models.IndexingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DoNotFailOnUnsupportedContentType (parameters As IndexingParameters) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member DoNotFailOnUnsupportedContentType : Microsoft.Azure.Search.Models.IndexingParameters -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.DoNotFailOnUnsupportedContentType parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
      </Parameters>
      <Docs>
        <param name="parameters">IndexingParameters を構成します。</param>
        <summary>
            指定する<c cref="F:Microsoft.Azure.Search.Models.BlobExtractionMode.StorageMetadata">BlobExtractionMode.StorageMetadata</c> blob 抽出モードがサポートされていないコンテンツの種類の blob を自動的に使用されます。 既定値は false です。
            </summary>
        <returns />
        <remarks>
            このオプションにのみ適用されますインデクサーそのインデックスの Azure Blob ストレージです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeFileNameExtensions">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters ExcludeFileNameExtensions (this Microsoft.Azure.Search.Models.IndexingParameters parameters, params string[] extensions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters ExcludeFileNameExtensions(class Microsoft.Azure.Search.Models.IndexingParameters parameters, string[] extensions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.ExcludeFileNameExtensions(Microsoft.Azure.Search.Models.IndexingParameters,System.String[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ExcludeFileNameExtensions (parameters As IndexingParameters, ParamArray extensions As String()) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member ExcludeFileNameExtensions : Microsoft.Azure.Search.Models.IndexingParameters * string[] -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.ExcludeFileNameExtensions (parameters, extensions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
        <Parameter Name="extensions" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="parameters">IndexingParameters を構成します。</param>
        <param name="extensions">インデックス作成から除外するファイル拡張子。</param>
        <summary>
            インデクサーはないインデックスを設定するを指定するファイル名拡張子を持つ blob を指定します。 各文字列は、先頭のドット付きのファイル拡張子です。 たとえば、".pdf"、".docx"などです。このメソッドと IndexFileNameExtensions に同じファイル拡張子を渡すと、その拡張子を持つ blob がインデックス作成から除外されます (つまり、このメソッドが優先されます)。
            詳細については、「<see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage" />」を参照してください。
            </summary>
        <returns>IndexingParameters インスタンス。</returns>
        <remarks>
            このオプションにのみ適用されますインデクサーそのインデックスの Azure Blob ストレージです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexFileNameExtensions">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters IndexFileNameExtensions (this Microsoft.Azure.Search.Models.IndexingParameters parameters, params string[] extensions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters IndexFileNameExtensions(class Microsoft.Azure.Search.Models.IndexingParameters parameters, string[] extensions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.IndexFileNameExtensions(Microsoft.Azure.Search.Models.IndexingParameters,System.String[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IndexFileNameExtensions (parameters As IndexingParameters, ParamArray extensions As String()) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member IndexFileNameExtensions : Microsoft.Azure.Search.Models.IndexingParameters * string[] -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.IndexFileNameExtensions (parameters, extensions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
        <Parameter Name="extensions" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="parameters">IndexingParameters を構成します。</param>
        <param name="extensions">インデックスに含めるファイル拡張子。</param>
        <summary>
            インデクサーを指定するファイル名拡張子を持つ blob のみのインデックスはことを指定します。 各文字列は、先頭のドット付きのファイル拡張子です。 たとえば、".pdf"、".docx"などです。このメソッドと ExcludeFileNameExtensions に同じファイル拡張子を渡すと、その拡張子を持つ blob がインデックス作成から除外されます (つまり、ExcludeFileNameExtensions が優先されます)。
            詳細については、「<see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage" />」を参照してください。
            </summary>
        <returns>IndexingParameters インスタンス。</returns>
        <remarks>
            このオプションにのみ適用されますインデクサーそのインデックスの Azure Blob ストレージです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexStorageMetadataOnly">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters IndexStorageMetadataOnly (this Microsoft.Azure.Search.Models.IndexingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters IndexStorageMetadataOnly(class Microsoft.Azure.Search.Models.IndexingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.IndexStorageMetadataOnly(Microsoft.Azure.Search.Models.IndexingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IndexStorageMetadataOnly (parameters As IndexingParameters) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member IndexStorageMetadataOnly : Microsoft.Azure.Search.Models.IndexingParameters -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.IndexStorageMetadataOnly parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This method is obsolete. Please use SetBlobExtractionMode(BlobExtractionMode.StorageMetadata).")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
      </Parameters>
      <Docs>
        <param name="parameters">IndexingParameters を構成します。</param>
        <summary> 
            インデクサーがストレージ メタデータのみのインデックスをドキュメントの抽出プロセスを完全にスキップするを指定します。 これは、ドキュメントのコンテンツも不要で、コンテンツの種類に固有のメタデータ プロパティも不要な場合に便利です。 詳細については、「<see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage" />」を参照してください。 
            </summary>
        <returns>IndexingParameters インスタンス。</returns>
        <remarks> 
            このオプションにのみ適用されますインデクサーそのインデックスの Azure Blob ストレージです。 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseDelimitedTextFiles">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters ParseDelimitedTextFiles (this Microsoft.Azure.Search.Models.IndexingParameters parameters, params string[] headers);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters ParseDelimitedTextFiles(class Microsoft.Azure.Search.Models.IndexingParameters parameters, string[] headers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseDelimitedTextFiles(Microsoft.Azure.Search.Models.IndexingParameters,System.String[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ParseDelimitedTextFiles (parameters As IndexingParameters, ParamArray headers As String()) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member ParseDelimitedTextFiles : Microsoft.Azure.Search.Models.IndexingParameters * string[] -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseDelimitedTextFiles (parameters, headers)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
        <Parameter Name="headers" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="parameters">IndexingParameters を構成します。</param>
        <param name="headers">
            インデクサーが Azure Search インデックス内の特定のフィールドに値をマップに使用する列ヘッダーを指定します。 すべてのヘッダーを指定しない場合、インデクサーでは、各 blob の最初の空白行にコンマ区切りのヘッダーが含まれている前提としています。
            </param>
        <summary>
            すべての blob が区切られたテキスト ファイルであると想定するインデクサーを指示します。 現在のみコンマ区切り値 (CSV) テキスト ファイルがサポートされます。
            詳細については、「<see href="https://docs.microsoft.com/azure/search/search-howto-index-csv-blobs" />」を参照してください。
            </summary>
        <returns>IndexingParameters インスタンス。</returns>
        <remarks>
            このオプションにのみ適用されますインデクサーそのインデックスの Azure Blob ストレージです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseJson">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters ParseJson (this Microsoft.Azure.Search.Models.IndexingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters ParseJson(class Microsoft.Azure.Search.Models.IndexingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseJson(Microsoft.Azure.Search.Models.IndexingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ParseJson (parameters As IndexingParameters) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member ParseJson : Microsoft.Azure.Search.Models.IndexingParameters -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseJson parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
      </Parameters>
      <Docs>
        <param name="parameters">IndexingParameters を構成します。</param>
        <summary>
            すべての blob には、各 blob の JSON が Azure Search インデックスに 1 つのドキュメントに対応するようを解析して、JSON が含まれていると仮定するインデクサーを指示します。
            詳細については、「<see href="https://docs.microsoft.com/azure/search/search-howto-index-json-blobs/" />」を参照してください。
            </summary>
        <returns>IndexingParameters インスタンス。</returns>
        <remarks>
            このオプションにのみ適用されますインデクサーそのインデックスの Azure Blob ストレージです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseJsonArrays">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters ParseJsonArrays (this Microsoft.Azure.Search.Models.IndexingParameters parameters, string documentRoot = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters ParseJsonArrays(class Microsoft.Azure.Search.Models.IndexingParameters parameters, string documentRoot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseJsonArrays(Microsoft.Azure.Search.Models.IndexingParameters,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ParseJsonArrays (parameters As IndexingParameters, Optional documentRoot As String = null) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member ParseJsonArrays : Microsoft.Azure.Search.Models.IndexingParameters * string -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.ParseJsonArrays (parameters, documentRoot)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
        <Parameter Name="documentRoot" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parameters">IndexingParameters を構成します。</param>
        <param name="documentRoot">
            インデクサーの各 blob の最上位の JSON プロパティではない場合は、JSON 配列を検索する方法を説明するために省略可能な JSON ポインター。 このパラメーターが null または空の場合は、インデクサーが JSON 配列を各 blob の最上位の JSON プロパティに含まれることを想定します。
            既定値は Null です。
            </param>
        <summary>
            すべての blob にファイルが解析されますが、各配列内の各 JSON オブジェクトを Azure Search インデックスに 1 つのドキュメントに対応するよう、JSON 配列が含まれていると仮定するインデクサーを指示します。
            詳細については、「<see href="https://docs.microsoft.com/azure/search/search-howto-index-json-blobs" />」を参照してください。
            </summary>
        <returns>IndexingParameters インスタンス。</returns>
        <remarks>
            このオプションにのみ適用されますインデクサーそのインデックスの Azure Blob ストレージです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetBlobExtractionMode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters SetBlobExtractionMode (this Microsoft.Azure.Search.Models.IndexingParameters parameters, Microsoft.Azure.Search.Models.BlobExtractionMode extractionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters SetBlobExtractionMode(class Microsoft.Azure.Search.Models.IndexingParameters parameters, class Microsoft.Azure.Search.Models.BlobExtractionMode extractionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.SetBlobExtractionMode(Microsoft.Azure.Search.Models.IndexingParameters,Microsoft.Azure.Search.Models.BlobExtractionMode)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetBlobExtractionMode (parameters As IndexingParameters, extractionMode As BlobExtractionMode) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member SetBlobExtractionMode : Microsoft.Azure.Search.Models.IndexingParameters * Microsoft.Azure.Search.Models.BlobExtractionMode -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.SetBlobExtractionMode (parameters, extractionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
        <Parameter Name="extractionMode" Type="Microsoft.Azure.Search.Models.BlobExtractionMode" />
      </Parameters>
      <Docs>
        <param name="parameters">IndexingParameters を構成します。</param>
        <param name="extractionMode">A <c cref="T:Microsoft.Azure.Search.Models.BlobExtractionMode">BlobExtractionMode</c>インデックスを指定する値。</param>
        <summary>
            Blob ストレージ インデクサーによってインデックスが作成される blob のどの部分を指定します。 
            </summary>
        <returns>IndexingParameters インスタンス。</returns>
        <remarks>
            このオプションにのみ適用されますインデクサーそのインデックスの Azure Blob ストレージです。
            <see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexingParameters SkipContent (this Microsoft.Azure.Search.Models.IndexingParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexingParameters SkipContent(class Microsoft.Azure.Search.Models.IndexingParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParametersExtensions.SkipContent(Microsoft.Azure.Search.Models.IndexingParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SkipContent (parameters As IndexingParameters) As IndexingParameters" />
      <MemberSignature Language="F#" Value="static member SkipContent : Microsoft.Azure.Search.Models.IndexingParameters -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="Microsoft.Azure.Search.Models.IndexingParametersExtensions.SkipContent parameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This method is obsolete. Please use SetBlobExtractionMode(BlobExtractionMode.AllMetadata).")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" RefType="this" />
      </Parameters>
      <Docs>
        <param name="parameters">IndexingParameters を構成します。</param>
        <summary>
            インデクサーはメタデータの抽出がすべての blob のコンテンツの抽出をスキップすることを指定します。 一部の blob のコンテンツの抽出をスキップする場合は、このオプションを使用する代わりに、個別にそれらの blob に AzureSearch_SkipContent メタデータを追加します。 詳細については、「<see href="https://docs.microsoft.com/azure/search/search-howto-indexing-azure-blob-storage" />」を参照してください。 
            </summary>
        <returns>IndexingParameters インスタンス。</returns>
        <remarks> 
            このオプションにのみ適用されますインデクサーそのインデックスの Azure Blob ストレージです。 
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>