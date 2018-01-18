<Type Name="SapCloudForCustomerResourceDataset" FullName="Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerResourceDataset">
  <TypeSignature Language="C#" Value="public class SapCloudForCustomerResourceDataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SapCloudForCustomerResourceDataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerResourceDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class SapCloudForCustomerResourceDataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type SapCloudForCustomerResourceDataset = class&#xA;    inherit Dataset" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
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
      <AttributeName>Newtonsoft.Json.JsonObject("SapCloudForCustomerResource")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5bdc3-101">顧客の OData エンティティ用クラウドの SAP のパス。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-101">The path of the SAP Cloud for Customer OData entity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SapCloudForCustomerResourceDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerResourceDataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5bdc3-102">SapCloudForCustomerResourceDataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-102">Initializes a new instance of the SapCloudForCustomerResourceDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SapCloudForCustomerResourceDataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object path, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object path, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerResourceDataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, path As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerResourceDataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerResourceDataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerResourceDataset (linkedServiceName, path, additionalProperties, description, structure, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="path" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="structure" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt;" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName"><span data-ttu-id="5bdc3-103">リンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-103">Linked service reference.</span></span></param>
        <param name="path"><span data-ttu-id="5bdc3-104">顧客の OData エンティティ用クラウドの SAP のパス。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-104">The path of the SAP Cloud for Customer OData entity.</span></span> <span data-ttu-id="5bdc3-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="5bdc3-106">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="5bdc3-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="5bdc3-107">データセットの説明。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-107">Dataset description.</span></span></param>
        <param name="structure"><span data-ttu-id="5bdc3-108">データセットの構造を定義する列。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-108">Columns that define the structure of the dataset.</span></span> <span data-ttu-id="5bdc3-109">型: 配列 (または配列の resultType を含む式)、itemType: DatasetDataElement です。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-109">Type: array (or Expression with resultType array), itemType: DatasetDataElement.</span></span></param>
        <param name="parameters"><span data-ttu-id="5bdc3-110">データセットのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-110">Parameters for dataset.</span></span></param>
        <summary>
            <span data-ttu-id="5bdc3-111">SapCloudForCustomerResourceDataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-111">Initializes a new instance of the SapCloudForCustomerResourceDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public object Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerResourceDataset.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As Object" />
      <MemberSignature Language="F#" Value="member this.Path : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerResourceDataset.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5bdc3-112">取得または顧客の OData エンティティ用クラウドの SAP のパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-112">Gets or sets the path of the SAP Cloud for Customer OData entity.</span></span>
            <span data-ttu-id="5bdc3-113">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-113">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SapCloudForCustomerResourceDataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sapCloudForCustomerResourceDataset.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5bdc3-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5bdc3-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5bdc3-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>