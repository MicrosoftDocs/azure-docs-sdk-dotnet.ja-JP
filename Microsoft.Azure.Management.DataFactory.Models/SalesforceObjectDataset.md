<Type Name="SalesforceObjectDataset" FullName="Microsoft.Azure.Management.DataFactory.Models.SalesforceObjectDataset">
  <TypeSignature Language="C#" Value="public class SalesforceObjectDataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SalesforceObjectDataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SalesforceObjectDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class SalesforceObjectDataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type SalesforceObjectDataset = class&#xA;    inherit Dataset" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("SalesforceObject")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d9e51-101">Salesforce オブジェクト データセットです。</span><span class="sxs-lookup"><span data-stu-id="d9e51-101">The Salesforce object dataset.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SalesforceObjectDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SalesforceObjectDataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d9e51-102">SalesforceObjectDataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d9e51-102">Initializes a new instance of the SalesforceObjectDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SalesforceObjectDataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null, object objectApiName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters, object objectApiName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SalesforceObjectDataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification},System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null, Optional objectApiName As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SalesforceObjectDataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.SalesforceObjectDataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.SalesforceObjectDataset (linkedServiceName, additionalProperties, description, structure, parameters, objectApiName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="structure" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt;" />
        <Parameter Name="objectApiName" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName"><span data-ttu-id="d9e51-103">リンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="d9e51-103">Linked service reference.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="d9e51-104">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="d9e51-104">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="d9e51-105">データセットの説明。</span><span class="sxs-lookup"><span data-stu-id="d9e51-105">Dataset description.</span></span></param>
        <param name="structure"><span data-ttu-id="d9e51-106">データセットの構造を定義する列。</span><span class="sxs-lookup"><span data-stu-id="d9e51-106">Columns that define the structure of the dataset.</span></span> <span data-ttu-id="d9e51-107">型: 配列 (または配列の resultType を含む式)、itemType: DatasetDataElement です。</span><span class="sxs-lookup"><span data-stu-id="d9e51-107">Type: array (or Expression with resultType array), itemType: DatasetDataElement.</span></span></param>
        <param name="parameters"><span data-ttu-id="d9e51-108">データセットのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d9e51-108">Parameters for dataset.</span></span></param>
        <param name="objectApiName"><span data-ttu-id="d9e51-109">Salesforce オブジェクト API の名前。</span><span class="sxs-lookup"><span data-stu-id="d9e51-109">The Salesforce object API name.</span></span> <span data-ttu-id="d9e51-110">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="d9e51-110">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="d9e51-111">SalesforceObjectDataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d9e51-111">Initializes a new instance of the SalesforceObjectDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectApiName">
      <MemberSignature Language="C#" Value="public object ObjectApiName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ObjectApiName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SalesforceObjectDataset.ObjectApiName" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectApiName As Object" />
      <MemberSignature Language="F#" Value="member this.ObjectApiName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SalesforceObjectDataset.ObjectApiName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.objectApiName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9e51-112">取得または Salesforce オブジェクト API の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="d9e51-112">Gets or sets the Salesforce object API name.</span></span> <span data-ttu-id="d9e51-113">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="d9e51-113">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SalesforceObjectDataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="salesforceObjectDataset.Validate " />
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
            <span data-ttu-id="d9e51-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="d9e51-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d9e51-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d9e51-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>