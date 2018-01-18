<Type Name="Index" FullName="Microsoft.Azure.Documents.Index">
  <TypeSignature Language="C#" Value="public abstract class Index : Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Index extends Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Index" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Index&#xA;Inherits JsonSerializable" />
  <TypeSignature Language="F#" Value="type Index = class&#xA;    inherit JsonSerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.IndexJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8196f-101">Azure Cosmos DB サービス IndexingPolicy インデックスの基本クラスは、HashIndex または RangeIndex のように具体的なインデックスを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8196f-101">Base class for IndexingPolicy Indexes in the Azure Cosmos DB service, you should use a concrete Index like HashIndex or RangeIndex.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Index (Microsoft.Azure.Documents.IndexKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Documents.IndexKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.#ctor(Microsoft.Azure.Documents.IndexKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kind As IndexKind)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Index : Microsoft.Azure.Documents.IndexKind -&gt; Microsoft.Azure.Documents.Index" Usage="new Microsoft.Azure.Documents.Index kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Documents.IndexKind" />
      </Parameters>
      <Docs>
        <param name="kind">To be added.</param>
        <summary>
            <span data-ttu-id="8196f-102">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Index" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="8196f-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Index" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hash">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.HashIndex Hash (Microsoft.Azure.Documents.DataType dataType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.HashIndex Hash(valuetype Microsoft.Azure.Documents.DataType dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.Hash(Microsoft.Azure.Documents.DataType)" />
      <MemberSignature Language="F#" Value="static member Hash : Microsoft.Azure.Documents.DataType -&gt; Microsoft.Azure.Documents.HashIndex" Usage="Microsoft.Azure.Documents.Index.Hash dataType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.HashIndex</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
      </Parameters>
      <Docs>
        <param name="dataType"><span data-ttu-id="8196f-103">インデックスのパス指定の対象のデータ型を指定します。</span><span class="sxs-lookup"><span data-stu-id="8196f-103">Specifies the target data type for the index path specification.</span></span></param>
        <summary>
            <span data-ttu-id="8196f-104">インスタンスを返します、 <see cref="T:Microsoft.Azure.Documents.HashIndex" /> Azure Cosmos DB サービスのデータ型が指定したクラスです。</span><span class="sxs-lookup"><span data-stu-id="8196f-104">Returns an instance of the <see cref="T:Microsoft.Azure.Documents.HashIndex" /> class with specified DataType for the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="8196f-105">インスタンス<see cref="T:Microsoft.Azure.Documents.HashIndex" />型です。</span><span class="sxs-lookup"><span data-stu-id="8196f-105">An instance of <see cref="T:Microsoft.Azure.Documents.HashIndex" /> type.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DataType" />
        <example>
            <span data-ttu-id="8196f-106">データ型を渡して HashIndex インスタンスを作成する例を次に示します。</span><span class="sxs-lookup"><span data-stu-id="8196f-106">Here is an example to create HashIndex instance passing in the DataType:</span></span>
            <code language="c#"><![CDATA[
            HashIndex hashIndex = Index.Hash(DataType.String);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Hash">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.HashIndex Hash (Microsoft.Azure.Documents.DataType dataType, short precision);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.HashIndex Hash(valuetype Microsoft.Azure.Documents.DataType dataType, int16 precision) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.Hash(Microsoft.Azure.Documents.DataType,System.Int16)" />
      <MemberSignature Language="F#" Value="static member Hash : Microsoft.Azure.Documents.DataType * int16 -&gt; Microsoft.Azure.Documents.HashIndex" Usage="Microsoft.Azure.Documents.Index.Hash (dataType, precision)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.HashIndex</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
        <Parameter Name="precision" Type="System.Int16" />
      </Parameters>
      <Docs>
        <param name="dataType"><span data-ttu-id="8196f-107">インデックスのパス指定の対象のデータ型を指定します。</span><span class="sxs-lookup"><span data-stu-id="8196f-107">Specifies the target data type for the index path specification.</span></span></param>
        <param name="precision"><span data-ttu-id="8196f-108">このインデックスに関連付けられているデータ型に使用される有効桁数を指定します。</span><span class="sxs-lookup"><span data-stu-id="8196f-108">Specifies the precision to be used for the data type associated with this index.</span></span></param>
        <summary>
            <span data-ttu-id="8196f-109">インスタンスを返します、<see cref="T:Microsoft.Azure.Documents.HashIndex" />指定のデータ型と Azure Cosmos DB サービスの有効桁数を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="8196f-109">Returns an instance of the <see cref="T:Microsoft.Azure.Documents.HashIndex" /> class with specified DataType and precision for the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="8196f-110">インスタンス<see cref="T:Microsoft.Azure.Documents.HashIndex" />型です。</span><span class="sxs-lookup"><span data-stu-id="8196f-110">An instance of <see cref="T:Microsoft.Azure.Documents.HashIndex" /> type.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DataType" />
        <example>
            <span data-ttu-id="8196f-111">データ型および有効桁数を渡します HashIndex インスタンスを作成する例を次に示します。</span><span class="sxs-lookup"><span data-stu-id="8196f-111">Here is an example to create HashIndex instance passing in the DataType and precision:</span></span>
            <code language="c#"><![CDATA[
            HashIndex hashIndex = Index.Hash(DataType.String, 3);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.IndexKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.IndexKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Index.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As IndexKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.Azure.Documents.IndexKind" Usage="Microsoft.Azure.Documents.Index.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.IndexKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8196f-112">取得または Azure Cosmos DB サービスで適用されるインデックスの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="8196f-112">Gets or sets the kind of indexing to be applied in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="8196f-113">値のいずれか、<see cref="T:Microsoft.Azure.Documents.IndexKind" />列挙します。</span><span class="sxs-lookup"><span data-stu-id="8196f-113">One of the values of the <see cref="T:Microsoft.Azure.Documents.IndexKind" /> enumeration.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Range">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.RangeIndex Range (Microsoft.Azure.Documents.DataType dataType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.RangeIndex Range(valuetype Microsoft.Azure.Documents.DataType dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.Range(Microsoft.Azure.Documents.DataType)" />
      <MemberSignature Language="F#" Value="static member Range : Microsoft.Azure.Documents.DataType -&gt; Microsoft.Azure.Documents.RangeIndex" Usage="Microsoft.Azure.Documents.Index.Range dataType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.RangeIndex</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
      </Parameters>
      <Docs>
        <param name="dataType"><span data-ttu-id="8196f-114">インデックスのパス指定の対象のデータ型を指定します。</span><span class="sxs-lookup"><span data-stu-id="8196f-114">Specifies the target data type for the index path specification.</span></span></param>
        <summary>
            <span data-ttu-id="8196f-115">インスタンスを返します、 <see cref="T:Microsoft.Azure.Documents.RangeIndex" /> Azure Cosmos DB サービスのデータ型が指定したクラスです。</span><span class="sxs-lookup"><span data-stu-id="8196f-115">Returns an instance of the <see cref="T:Microsoft.Azure.Documents.RangeIndex" /> class with specified DataType for the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="8196f-116">インスタンス<see cref="T:Microsoft.Azure.Documents.RangeIndex" />型です。</span><span class="sxs-lookup"><span data-stu-id="8196f-116">An instance of <see cref="T:Microsoft.Azure.Documents.RangeIndex" /> type.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DataType" />
        <example>
            <span data-ttu-id="8196f-117">データ型を渡して RangeIndex インスタンスを作成する例を次に示します。</span><span class="sxs-lookup"><span data-stu-id="8196f-117">Here is an example to create RangeIndex instance passing in the DataType:</span></span>
            <code language="c#"><![CDATA[
            RangeIndex rangeIndex = Index.Range(DataType.Number);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Range">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.RangeIndex Range (Microsoft.Azure.Documents.DataType dataType, short precision);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.RangeIndex Range(valuetype Microsoft.Azure.Documents.DataType dataType, int16 precision) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.Range(Microsoft.Azure.Documents.DataType,System.Int16)" />
      <MemberSignature Language="F#" Value="static member Range : Microsoft.Azure.Documents.DataType * int16 -&gt; Microsoft.Azure.Documents.RangeIndex" Usage="Microsoft.Azure.Documents.Index.Range (dataType, precision)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.RangeIndex</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
        <Parameter Name="precision" Type="System.Int16" />
      </Parameters>
      <Docs>
        <param name="dataType"><span data-ttu-id="8196f-118">インデックスのパス指定の対象のデータ型を指定します。</span><span class="sxs-lookup"><span data-stu-id="8196f-118">Specifies the target data type for the index path specification.</span></span></param>
        <param name="precision"><span data-ttu-id="8196f-119">このインデックスに関連付けられているデータ型に使用される有効桁数を指定します。</span><span class="sxs-lookup"><span data-stu-id="8196f-119">Specifies the precision to be used for the data type associated with this index.</span></span></param>
        <summary>
            <span data-ttu-id="8196f-120">インスタンスを返します、<see cref="T:Microsoft.Azure.Documents.RangeIndex" />指定のデータ型と Azure Cosmos DB サービスの有効桁数を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="8196f-120">Returns an instance of the <see cref="T:Microsoft.Azure.Documents.RangeIndex" /> class with specified DataType and precision for the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="8196f-121">インスタンス<see cref="T:Microsoft.Azure.Documents.RangeIndex" />型です。</span><span class="sxs-lookup"><span data-stu-id="8196f-121">An instance of <see cref="T:Microsoft.Azure.Documents.RangeIndex" /> type.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DataType" />
        <example>
            <span data-ttu-id="8196f-122">データ型および有効桁数を渡します RangeIndex インスタンスを作成する例を次に示します。</span><span class="sxs-lookup"><span data-stu-id="8196f-122">Here is an example to create RangeIndex instance passing in the DataType and precision:</span></span>
            <code language="c#"><![CDATA[
            RangeIndex rangeIndex = Index.Range(DataType.Number, -1);
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="Spatial">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.SpatialIndex Spatial (Microsoft.Azure.Documents.DataType dataType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.SpatialIndex Spatial(valuetype Microsoft.Azure.Documents.DataType dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Index.Spatial(Microsoft.Azure.Documents.DataType)" />
      <MemberSignature Language="F#" Value="static member Spatial : Microsoft.Azure.Documents.DataType -&gt; Microsoft.Azure.Documents.SpatialIndex" Usage="Microsoft.Azure.Documents.Index.Spatial dataType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.SpatialIndex</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dataType" Type="Microsoft.Azure.Documents.DataType" />
      </Parameters>
      <Docs>
        <param name="dataType"><span data-ttu-id="8196f-123">インデックスのパス指定の対象のデータ型を指定します。</span><span class="sxs-lookup"><span data-stu-id="8196f-123">Specifies the target data type for the index path specification.</span></span></param>
        <summary>
            <span data-ttu-id="8196f-124">インスタンスを返します、 <see cref="T:Microsoft.Azure.Documents.SpatialIndex" /> Azure Cosmos DB サービスのデータ型が指定したクラスです。</span><span class="sxs-lookup"><span data-stu-id="8196f-124">Returns an instance of the <see cref="T:Microsoft.Azure.Documents.SpatialIndex" /> class with specified DataType for the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="8196f-125">インスタンス<see cref="T:Microsoft.Azure.Documents.SpatialIndex" />型です。</span><span class="sxs-lookup"><span data-stu-id="8196f-125">An instance of <see cref="T:Microsoft.Azure.Documents.SpatialIndex" /> type.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DataType" />
        <example>
            <span data-ttu-id="8196f-126">データ型を渡して SpatialIndex インスタンスを作成する例を次に示します。</span><span class="sxs-lookup"><span data-stu-id="8196f-126">Here is an example to create SpatialIndex instance passing in the DataType:</span></span>
            <code language="c#"><![CDATA[
            SpatialIndex spatialIndex = Index.Spatial(DataType.Point);
            ]]></code></example>
      </Docs>
    </Member>
  </Members>
</Type>