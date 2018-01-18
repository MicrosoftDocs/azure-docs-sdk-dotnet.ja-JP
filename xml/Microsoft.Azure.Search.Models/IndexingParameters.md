<Type Name="IndexingParameters" FullName="Microsoft.Azure.Search.Models.IndexingParameters">
  <TypeSignature Language="C#" Value="public class IndexingParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexingParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexingParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexingParameters" />
  <TypeSignature Language="F#" Value="type IndexingParameters = class" />
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
            <span data-ttu-id="b3304-101">インデクサー実行のパラメーターを表します。</span><span class="sxs-lookup"><span data-stu-id="b3304-101">Represents parameters for indexer execution.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b3304-102">IndexingParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b3304-102">Initializes a new instance of the IndexingParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingParameters (Nullable&lt;int&gt; batchSize = null, Nullable&lt;int&gt; maxFailedItems = null, Nullable&lt;int&gt; maxFailedItemsPerBatch = null, System.Collections.Generic.IDictionary&lt;string,object&gt; configuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; batchSize, valuetype System.Nullable`1&lt;int32&gt; maxFailedItems, valuetype System.Nullable`1&lt;int32&gt; maxFailedItemsPerBatch, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingParameters.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional batchSize As Nullable(Of Integer) = null, Optional maxFailedItems As Nullable(Of Integer) = null, Optional maxFailedItemsPerBatch As Nullable(Of Integer) = null, Optional configuration As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexingParameters : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Search.Models.IndexingParameters" Usage="new Microsoft.Azure.Search.Models.IndexingParameters (batchSize, maxFailedItems, maxFailedItemsPerBatch, configuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="batchSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxFailedItems" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxFailedItemsPerBatch" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="configuration" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="batchSize">To be added.</param>
        <param name="maxFailedItems">To be added.</param>
        <param name="maxFailedItemsPerBatch">To be added.</param>
        <param name="configuration">To be added.</param>
        <summary>
            <span data-ttu-id="b3304-103">IndexingParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b3304-103">Initializes a new instance of the IndexingParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Base64EncodeKeys">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Base64EncodeKeys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Base64EncodeKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingParameters.Base64EncodeKeys" />
      <MemberSignature Language="VB.NET" Value="Public Property Base64EncodeKeys As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Base64EncodeKeys : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexingParameters.Base64EncodeKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="base64EncodeKeys")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("This property is obsolete. Please create a field mapping using 'FieldMapping.Base64Encode' instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3304-104">インデクサーがあるかどうかの設定を取得または base64-ターゲット インデックスのキー フィールドに挿入されるすべての値をエンコードします。</span><span class="sxs-lookup"><span data-stu-id="b3304-104">Gets or sets whether indexer will base64-encode all values that are inserted into key field of the target index.</span></span> <span data-ttu-id="b3304-105">これはキーがキーで無効な文字を含めることができる場合必要 (ドットなど '.')。</span><span class="sxs-lookup"><span data-stu-id="b3304-105">This is needed if keys can contain characters that are invalid in keys (such as dot '.').</span></span> <span data-ttu-id="b3304-106">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="b3304-106">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BatchSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BatchSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingParameters.BatchSize" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BatchSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexingParameters.BatchSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="batchSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3304-107">取得またはパフォーマンスを向上するために単一のバッチとしてデータ ソースから読み取られたされ、インデックスが作成される項目の数を設定します。</span><span class="sxs-lookup"><span data-stu-id="b3304-107">Gets or sets the number of items that are read from the data source and indexed as a single batch in order to improve performance.</span></span> <span data-ttu-id="b3304-108">既定値は、データ ソースの種類によって異なります。</span><span class="sxs-lookup"><span data-stu-id="b3304-108">The default depends on the data source type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configuration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Configuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Configuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingParameters.Configuration" />
      <MemberSignature Language="VB.NET" Value="Public Property Configuration As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Configuration : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexingParameters.Configuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="configuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3304-109">取得またはインデクサーに固有の構成プロパティのディクショナリを設定します。</span><span class="sxs-lookup"><span data-stu-id="b3304-109">Gets or sets a dictionary of indexer-specific configuration properties.</span></span> <span data-ttu-id="b3304-110">それぞれの名前は、特定のプロパティの名前です。</span><span class="sxs-lookup"><span data-stu-id="b3304-110">Each name is the name of a specific property.</span></span> <span data-ttu-id="b3304-111">各値は、プリミティブ型でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="b3304-111">Each value must be of a primitive type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxFailedItems">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxFailedItems { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxFailedItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingParameters.MaxFailedItems" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxFailedItems As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxFailedItems : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexingParameters.MaxFailedItems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxFailedItems")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3304-112">取得またはまだ成功と見なせるをインデクサー実行のインデックス作成に失敗できる項目の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="b3304-112">Gets or sets the maximum number of items that can fail indexing for indexer execution to still be considered successful.</span></span> <span data-ttu-id="b3304-113">-1 は無制限を意味します。</span><span class="sxs-lookup"><span data-stu-id="b3304-113">-1 means no limit.</span></span> <span data-ttu-id="b3304-114">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="b3304-114">Default is 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxFailedItemsPerBatch">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxFailedItemsPerBatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxFailedItemsPerBatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingParameters.MaxFailedItemsPerBatch" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxFailedItemsPerBatch As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxFailedItemsPerBatch : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.IndexingParameters.MaxFailedItemsPerBatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxFailedItemsPerBatch")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b3304-115">取得またはまだと見なされるに成功したバッチのインデックス作成に失敗できる単一のバッチ内の項目の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="b3304-115">Gets or sets the maximum number of items in a single batch that can fail indexing for the batch to still be considered successful.</span></span> <span data-ttu-id="b3304-116">-1 は無制限を意味します。</span><span class="sxs-lookup"><span data-stu-id="b3304-116">-1 means no limit.</span></span> <span data-ttu-id="b3304-117">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="b3304-117">Default is 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>