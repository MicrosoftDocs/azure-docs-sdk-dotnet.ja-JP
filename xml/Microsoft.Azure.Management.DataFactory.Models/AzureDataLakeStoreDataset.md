<Type Name="AzureDataLakeStoreDataset" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset">
  <TypeSignature Language="C#" Value="public class AzureDataLakeStoreDataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureDataLakeStoreDataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureDataLakeStoreDataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type AzureDataLakeStoreDataset = class&#xA;    inherit Dataset" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureDataLakeStoreFile")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8c175-101">Azure Data Lake Store データセットです。</span><span class="sxs-lookup"><span data-stu-id="8c175-101">Azure Data Lake Store dataset.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset.#ctor" />
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
            <span data-ttu-id="8c175-102">AzureDataLakeStoreDataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8c175-102">Initializes a new instance of the AzureDataLakeStoreDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureDataLakeStoreDataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object folderPath, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null, object fileName = null, Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format = null, Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object folderPath, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters, object fileName, class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format, class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification},System.Object,Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat,Microsoft.Azure.Management.DataFactory.Models.DatasetCompression)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, folderPath As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null, Optional fileName As Object = null, Optional format As DatasetStorageFormat = null, Optional compression As DatasetCompression = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; * obj * Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat * Microsoft.Azure.Management.DataFactory.Models.DatasetCompression -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset (linkedServiceName, folderPath, additionalProperties, description, structure, parameters, fileName, format, compression)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="folderPath" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="structure" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt;" />
        <Parameter Name="fileName" Type="System.Object" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
        <Parameter Name="compression" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetCompression" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName"><span data-ttu-id="8c175-103">リンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="8c175-103">Linked service reference.</span></span></param>
        <param name="folderPath"><span data-ttu-id="8c175-104">Azure Data Lake Store フォルダーへのパス。</span><span class="sxs-lookup"><span data-stu-id="8c175-104">Path to the folder in the Azure Data Lake Store.</span></span> <span data-ttu-id="8c175-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="8c175-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="8c175-106">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="8c175-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="8c175-107">データセットの説明。</span><span class="sxs-lookup"><span data-stu-id="8c175-107">Dataset description.</span></span></param>
        <param name="structure"><span data-ttu-id="8c175-108">データセットの構造を定義する列。</span><span class="sxs-lookup"><span data-stu-id="8c175-108">Columns that define the structure of the dataset.</span></span> <span data-ttu-id="8c175-109">型: 配列 (または配列の resultType を含む式)、itemType: DatasetDataElement です。</span><span class="sxs-lookup"><span data-stu-id="8c175-109">Type: array (or Expression with resultType array), itemType: DatasetDataElement.</span></span></param>
        <param name="parameters"><span data-ttu-id="8c175-110">データセットのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8c175-110">Parameters for dataset.</span></span></param>
        <param name="fileName"><span data-ttu-id="8c175-111">Azure Data Lake Store 内のファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="8c175-111">The name of the file in the Azure Data Lake Store.</span></span> <span data-ttu-id="8c175-112">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="8c175-112">Type: string (or Expression with resultType string).</span></span></param>
        <param name="format"><span data-ttu-id="8c175-113">Data Lake Store の形式です。</span><span class="sxs-lookup"><span data-stu-id="8c175-113">The format of the Data Lake Store.</span></span></param>
        <param name="compression"><span data-ttu-id="8c175-114">データの圧縮方法は Azure Data Lake Store、その項目に使用します。</span><span class="sxs-lookup"><span data-stu-id="8c175-114">The data compression method used for the item(s) in the Azure Data Lake Store.</span></span></param>
        <summary>
            <span data-ttu-id="8c175-115">AzureDataLakeStoreDataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8c175-115">Initializes a new instance of the AzureDataLakeStoreDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Compression">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset.Compression" />
      <MemberSignature Language="VB.NET" Value="Public Property Compression As DatasetCompression" />
      <MemberSignature Language="F#" Value="member this.Compression : Microsoft.Azure.Management.DataFactory.Models.DatasetCompression with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset.Compression" />
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
            <span data-ttu-id="8c175-116">取得または Azure Data Lake Store、その項目に使用するデータの圧縮方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="8c175-116">Gets or sets the data compression method used for the item(s) in the Azure Data Lake Store.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileName">
      <MemberSignature Language="C#" Value="public object FileName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset.FileName" />
      <MemberSignature Language="VB.NET" Value="Public Property FileName As Object" />
      <MemberSignature Language="F#" Value="member this.FileName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset.FileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.fileName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c175-117">取得または Azure Data Lake Store のファイルの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="8c175-117">Gets or sets the name of the file in the Azure Data Lake Store.</span></span>
            <span data-ttu-id="8c175-118">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="8c175-118">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FolderPath">
      <MemberSignature Language="C#" Value="public object FolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset.FolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property FolderPath As Object" />
      <MemberSignature Language="F#" Value="member this.FolderPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset.FolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.folderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c175-119">取得または Azure Data Lake Store フォルダーへのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="8c175-119">Gets or sets path to the folder in the Azure Data Lake Store.</span></span> <span data-ttu-id="8c175-120">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="8c175-120">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As DatasetStorageFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset.Format" />
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
            <span data-ttu-id="8c175-121">取得または Data Lake Store の形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="8c175-121">Gets or sets the format of the Data Lake Store.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureDataLakeStoreDataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureDataLakeStoreDataset.Validate " />
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
            <span data-ttu-id="8c175-122">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="8c175-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8c175-123">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8c175-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>