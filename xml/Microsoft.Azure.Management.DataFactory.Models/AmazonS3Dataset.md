<Type Name="AmazonS3Dataset" FullName="Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset">
  <TypeSignature Language="C#" Value="public class AmazonS3Dataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AmazonS3Dataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset" />
  <TypeSignature Language="VB.NET" Value="Public Class AmazonS3Dataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type AmazonS3Dataset = class&#xA;    inherit Dataset" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.Dataset</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("AmazonS3Object")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="17ac7-101">単一の Amazon 単純な記憶域サービス (S3) オブジェクトまたは S3 オブジェクトのセット。</span><span class="sxs-lookup"><span data-stu-id="17ac7-101">A single Amazon Simple Storage Service (S3) object or a set of S3 objects.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonS3Dataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="17ac7-102">AmazonS3Dataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="17ac7-102">Initializes a new instance of the AmazonS3Dataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmazonS3Dataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object bucketName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null, object key = null, object prefix = null, object version = null, Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format = null, Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object bucketName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters, object key, object prefix, object version, class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format, class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification},System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat,Microsoft.Azure.Management.DataFactory.Models.DatasetCompression)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, bucketName As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null, Optional key As Object = null, Optional prefix As Object = null, Optional version As Object = null, Optional format As DatasetStorageFormat = null, Optional compression As DatasetCompression = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat * Microsoft.Azure.Management.DataFactory.Models.DatasetCompression -&gt; Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset (linkedServiceName, bucketName, additionalProperties, description, structure, parameters, key, prefix, version, format, compression)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="bucketName" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="structure" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt;" />
        <Parameter Name="key" Type="System.Object" />
        <Parameter Name="prefix" Type="System.Object" />
        <Parameter Name="version" Type="System.Object" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
        <Parameter Name="compression" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetCompression" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName"><span data-ttu-id="17ac7-103">リンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="17ac7-103">Linked service reference.</span></span></param>
        <param name="bucketName"><span data-ttu-id="17ac7-104">Amazon S3 バケットの名前。</span><span class="sxs-lookup"><span data-stu-id="17ac7-104">The name of the Amazon S3 bucket.</span></span> <span data-ttu-id="17ac7-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="17ac7-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="17ac7-106">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="17ac7-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="17ac7-107">データセットの説明。</span><span class="sxs-lookup"><span data-stu-id="17ac7-107">Dataset description.</span></span></param>
        <param name="structure"><span data-ttu-id="17ac7-108">データセットの構造を定義する列。</span><span class="sxs-lookup"><span data-stu-id="17ac7-108">Columns that define the structure of the dataset.</span></span> <span data-ttu-id="17ac7-109">型: 配列 (または配列の resultType を含む式)、itemType: DatasetDataElement です。</span><span class="sxs-lookup"><span data-stu-id="17ac7-109">Type: array (or Expression with resultType array), itemType: DatasetDataElement.</span></span></param>
        <param name="parameters"><span data-ttu-id="17ac7-110">データセットのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="17ac7-110">Parameters for dataset.</span></span></param>
        <param name="key"><span data-ttu-id="17ac7-111">Amazon S3 オブジェクトのキー。</span><span class="sxs-lookup"><span data-stu-id="17ac7-111">The key of the Amazon S3 object.</span></span> <span data-ttu-id="17ac7-112">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="17ac7-112">Type: string (or Expression with resultType string).</span></span></param>
        <param name="prefix"><span data-ttu-id="17ac7-113">S3 オブジェクト名のプレフィックス フィルター。</span><span class="sxs-lookup"><span data-stu-id="17ac7-113">The prefix filter for the S3 object name.</span></span>
            <span data-ttu-id="17ac7-114">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="17ac7-114">Type: string (or Expression with resultType string).</span></span></param>
        <param name="version"><span data-ttu-id="17ac7-115">S3 オブジェクトのバージョンです。</span><span class="sxs-lookup"><span data-stu-id="17ac7-115">The version for the S3 object.</span></span> <span data-ttu-id="17ac7-116">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="17ac7-116">Type: string (or Expression with resultType string).</span></span></param>
        <param name="format"><span data-ttu-id="17ac7-117">ファイルの形式です。</span><span class="sxs-lookup"><span data-stu-id="17ac7-117">The format of files.</span></span></param>
        <param name="compression"><span data-ttu-id="17ac7-118">データの圧縮方法は、Amazon S3 オブジェクトの使用します。</span><span class="sxs-lookup"><span data-stu-id="17ac7-118">The data compression method used for the Amazon S3 object.</span></span></param>
        <summary>
            <span data-ttu-id="17ac7-119">AmazonS3Dataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="17ac7-119">Initializes a new instance of the AmazonS3Dataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BucketName">
      <MemberSignature Language="C#" Value="public object BucketName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object BucketName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.BucketName" />
      <MemberSignature Language="VB.NET" Value="Public Property BucketName As Object" />
      <MemberSignature Language="F#" Value="member this.BucketName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.BucketName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.bucketName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17ac7-120">取得または Amazon S3 バケットの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="17ac7-120">Gets or sets the name of the Amazon S3 bucket.</span></span> <span data-ttu-id="17ac7-121">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="17ac7-121">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Compression">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.Compression" />
      <MemberSignature Language="VB.NET" Value="Public Property Compression As DatasetCompression" />
      <MemberSignature Language="F#" Value="member this.Compression : Microsoft.Azure.Management.DataFactory.Models.DatasetCompression with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.Compression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.compression")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DatasetCompression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17ac7-122">取得または Amazon S3 オブジェクトに対して使用されるデータの圧縮方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="17ac7-122">Gets or sets the data compression method used for the Amazon S3 object.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As DatasetStorageFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17ac7-123">取得またはファイルの形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="17ac7-123">Gets or sets the format of files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public object Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As Object" />
      <MemberSignature Language="F#" Value="member this.Key : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17ac7-124">取得または Amazon S3 オブジェクトのキーを設定します。</span><span class="sxs-lookup"><span data-stu-id="17ac7-124">Gets or sets the key of the Amazon S3 object.</span></span> <span data-ttu-id="17ac7-125">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="17ac7-125">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public object Prefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public Property Prefix As Object" />
      <MemberSignature Language="F#" Value="member this.Prefix : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.Prefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.prefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17ac7-126">取得または S3 オブジェクト名のプレフィックス フィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="17ac7-126">Gets or sets the prefix filter for the S3 object name.</span></span> <span data-ttu-id="17ac7-127">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="17ac7-127">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="amazonS3Dataset.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="17ac7-128">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="17ac7-128">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="17ac7-129">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="17ac7-129">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public object Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Object" />
      <MemberSignature Language="F#" Value="member this.Version : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AmazonS3Dataset.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17ac7-130">取得または S3 オブジェクトのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="17ac7-130">Gets or sets the version for the S3 object.</span></span> <span data-ttu-id="17ac7-131">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="17ac7-131">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>