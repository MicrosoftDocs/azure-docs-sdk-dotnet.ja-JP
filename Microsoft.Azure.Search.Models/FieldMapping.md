<Type Name="FieldMapping" FullName="Microsoft.Azure.Search.Models.FieldMapping">
  <TypeSignature Language="C#" Value="public class FieldMapping" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FieldMapping extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.FieldMapping" />
  <TypeSignature Language="VB.NET" Value="Public Class FieldMapping" />
  <TypeSignature Language="F#" Value="type FieldMapping = class" />
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
            <span data-ttu-id="d40fc-101">インデックスのデータ ソースのフィールドと対象のフィールド間のマッピングを定義します。</span><span class="sxs-lookup"><span data-stu-id="d40fc-101">Defines a mapping between a field in a data source and a target field in an index.</span></span>
            <see href="https://docs.microsoft.com/azure/search/search-indexer-field-mappings" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FieldMapping ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMapping.#ctor" />
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
            <span data-ttu-id="d40fc-102">フィールド マッピングのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d40fc-102">Initializes a new instance of the FieldMapping class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FieldMapping (string sourceFieldName, Microsoft.Azure.Search.Models.FieldMappingFunction mappingFunction);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sourceFieldName, class Microsoft.Azure.Search.Models.FieldMappingFunction mappingFunction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMapping.#ctor(System.String,Microsoft.Azure.Search.Models.FieldMappingFunction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceFieldName As String, mappingFunction As FieldMappingFunction)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.FieldMapping : string * Microsoft.Azure.Search.Models.FieldMappingFunction -&gt; Microsoft.Azure.Search.Models.FieldMapping" Usage="new Microsoft.Azure.Search.Models.FieldMapping (sourceFieldName, mappingFunction)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceFieldName" Type="System.String" />
        <Parameter Name="mappingFunction" Type="Microsoft.Azure.Search.Models.FieldMappingFunction" />
      </Parameters>
      <Docs>
        <param name="sourceFieldName"><span data-ttu-id="d40fc-103">データ ソースのフィールドの名前。</span><span class="sxs-lookup"><span data-stu-id="d40fc-103">The name of the field in the data source.</span></span></param>
        <param name="mappingFunction"><span data-ttu-id="d40fc-104">インデックスを作成する前に、各ソース フィールドの値に適用する関数。</span><span class="sxs-lookup"><span data-stu-id="d40fc-104">A function to apply to each source field value before indexing.</span></span></param>
        <summary>
            <span data-ttu-id="d40fc-105">フィールド マッピングのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d40fc-105">Initializes a new instance of the FieldMapping class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FieldMapping (string sourceFieldName, string targetFieldName = null, Microsoft.Azure.Search.Models.FieldMappingFunction mappingFunction = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sourceFieldName, string targetFieldName, class Microsoft.Azure.Search.Models.FieldMappingFunction mappingFunction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMapping.#ctor(System.String,System.String,Microsoft.Azure.Search.Models.FieldMappingFunction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sourceFieldName As String, Optional targetFieldName As String = null, Optional mappingFunction As FieldMappingFunction = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.FieldMapping : string * string * Microsoft.Azure.Search.Models.FieldMappingFunction -&gt; Microsoft.Azure.Search.Models.FieldMapping" Usage="new Microsoft.Azure.Search.Models.FieldMapping (sourceFieldName, targetFieldName, mappingFunction)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceFieldName" Type="System.String" />
        <Parameter Name="targetFieldName" Type="System.String" />
        <Parameter Name="mappingFunction" Type="Microsoft.Azure.Search.Models.FieldMappingFunction" />
      </Parameters>
      <Docs>
        <param name="sourceFieldName"><span data-ttu-id="d40fc-106">データ ソースのフィールドの名前。</span><span class="sxs-lookup"><span data-stu-id="d40fc-106">The name of the field in the data source.</span></span></param>
        <param name="targetFieldName"><span data-ttu-id="d40fc-107">インデックスで対象のフィールドの名前。</span><span class="sxs-lookup"><span data-stu-id="d40fc-107">The name of the target field in the index.</span></span> <span data-ttu-id="d40fc-108">既定では、ソース フィールド名と同じです。</span><span class="sxs-lookup"><span data-stu-id="d40fc-108">Same as the source field name by default.</span></span></param>
        <param name="mappingFunction"><span data-ttu-id="d40fc-109">インデックスを作成する前に、各ソース フィールドの値に適用する関数。</span><span class="sxs-lookup"><span data-stu-id="d40fc-109">A function to apply to each source field value before indexing.</span></span></param>
        <summary>
            <span data-ttu-id="d40fc-110">フィールド マッピングのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d40fc-110">Initializes a new instance of the FieldMapping class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MappingFunction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.FieldMappingFunction MappingFunction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.FieldMappingFunction MappingFunction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FieldMapping.MappingFunction" />
      <MemberSignature Language="VB.NET" Value="Public Property MappingFunction As FieldMappingFunction" />
      <MemberSignature Language="F#" Value="member this.MappingFunction : Microsoft.Azure.Search.Models.FieldMappingFunction with get, set" Usage="Microsoft.Azure.Search.Models.FieldMapping.MappingFunction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mappingFunction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FieldMappingFunction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d40fc-111">取得またはインデックスを作成する前に、各ソース フィールドの値に適用する関数を設定します。</span><span class="sxs-lookup"><span data-stu-id="d40fc-111">Gets or sets a function to apply to each source field value before indexing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceFieldName">
      <MemberSignature Language="C#" Value="public string SourceFieldName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FieldMapping.SourceFieldName" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceFieldName As String" />
      <MemberSignature Language="F#" Value="member this.SourceFieldName : string with get, set" Usage="Microsoft.Azure.Search.Models.FieldMapping.SourceFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceFieldName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d40fc-112">取得またはデータ ソースのフィールドの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="d40fc-112">Gets or sets the name of the field in the data source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetFieldName">
      <MemberSignature Language="C#" Value="public string TargetFieldName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FieldMapping.TargetFieldName" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetFieldName As String" />
      <MemberSignature Language="F#" Value="member this.TargetFieldName : string with get, set" Usage="Microsoft.Azure.Search.Models.FieldMapping.TargetFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetFieldName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d40fc-113">取得またはインデックスで対象のフィールドの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="d40fc-113">Gets or sets the name of the target field in the index.</span></span> <span data-ttu-id="d40fc-114">既定では、ソース フィールド名と同じです。</span><span class="sxs-lookup"><span data-stu-id="d40fc-114">Same as the source field name by default.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMapping.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fieldMapping.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d40fc-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="d40fc-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d40fc-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d40fc-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>