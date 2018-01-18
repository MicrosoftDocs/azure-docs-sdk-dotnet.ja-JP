<Type Name="SynonymMap" FullName="Microsoft.Azure.Search.Models.SynonymMap">
  <TypeSignature Language="C#" Value="public class SynonymMap : Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SynonymMap extends System.Object implements class Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SynonymMap" />
  <TypeSignature Language="VB.NET" Value="Public Class SynonymMap&#xA;Implements IResourceWithETag" />
  <TypeSignature Language="F#" Value="type SynonymMap = class&#xA;    interface IResourceWithETag" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Search.Models.IResourceWithETag</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="7a1ac-101">Azure Search でシノニム マップの定義を表します。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-101">Represents a synonym map definition in Azure Search.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SynonymMap ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymMap.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7a1ac-102">SynonymMap クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-102">Initializes a new instance of the SynonymMap class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SynonymMap (string name, Microsoft.Azure.Search.Models.SynonymMapFormat format, string synonyms, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.SynonymMapFormat format, string synonyms, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymMap.#ctor(System.String,Microsoft.Azure.Search.Models.SynonymMapFormat,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, format As SynonymMapFormat, synonyms As String, Optional eTag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SynonymMap : string * Microsoft.Azure.Search.Models.SynonymMapFormat * string * string -&gt; Microsoft.Azure.Search.Models.SynonymMap" Usage="new Microsoft.Azure.Search.Models.SynonymMap (name, format, synonyms, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="format" Type="Microsoft.Azure.Search.Models.SynonymMapFormat" />
        <Parameter Name="synonyms" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7a1ac-103">シノニムのマップの名前。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-103">The name of the synonym map.</span></span></param>
        <param name="format"><span data-ttu-id="7a1ac-104">シノニムのマップの形式です。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-104">The format of the synonym map.</span></span> <span data-ttu-id="7a1ac-105">'Solr' 形式のみが現在サポートされています。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-105">Only the 'solr' format is currently supported.</span></span></param>
        <param name="synonyms"><span data-ttu-id="7a1ac-106">一連のシノニムの指定したマップ形式のシノニム ルール。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-106">A series of synonym rules in the specified synonym map format.</span></span> <span data-ttu-id="7a1ac-107">ルールは、改行で区切る必要があります。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-107">The rules must be separated by newlines.</span></span></param>
        <param name="eTag"><span data-ttu-id="7a1ac-108">シノニムのマップの ETag。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-108">The ETag of the synonym map.</span></span></param>
        <summary>
            <span data-ttu-id="7a1ac-109">SynonymMap クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-109">Initializes a new instance of the SynonymMap class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymMap.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Search.Models.SynonymMap.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="@odata.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a1ac-110">取得またはシノニム マップの ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-110">Gets or sets the ETag of the synonym map.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.SynonymMapFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.SynonymMapFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymMap.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As SynonymMapFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Search.Models.SynonymMapFormat with get, set" Usage="Microsoft.Azure.Search.Models.SynonymMap.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMapFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a1ac-111">取得またはシノニム マップの形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-111">Gets or sets the format of the synonym map.</span></span> <span data-ttu-id="7a1ac-112">'Solr' 形式のみが現在サポートされています。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-112">Only the 'solr' format is currently supported.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymMap.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.SynonymMap.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a1ac-113">取得またはシノニム マップの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-113">Gets or sets the name of the synonym map.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Synonyms">
      <MemberSignature Language="C#" Value="public string Synonyms { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Synonyms" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymMap.Synonyms" />
      <MemberSignature Language="VB.NET" Value="Public Property Synonyms As String" />
      <MemberSignature Language="F#" Value="member this.Synonyms : string with get, set" Usage="Microsoft.Azure.Search.Models.SynonymMap.Synonyms" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="synonyms")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a1ac-114">取得または一連のシノニムの規則をシノニムの指定したマップ形式に設定します。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-114">Gets or sets a series of synonym rules in the specified synonym map format.</span></span> <span data-ttu-id="7a1ac-115">ルールは、改行で区切る必要があります。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-115">The rules must be separated by newlines.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymMap.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="synonymMap.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7a1ac-116">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7a1ac-117">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7a1ac-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>