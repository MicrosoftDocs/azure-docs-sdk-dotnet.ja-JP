<Type Name="HubspotObjectDataset" FullName="Microsoft.Azure.Management.DataFactory.Models.HubspotObjectDataset">
  <TypeSignature Language="C#" Value="public class HubspotObjectDataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HubspotObjectDataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HubspotObjectDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class HubspotObjectDataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type HubspotObjectDataset = class&#xA;    inherit Dataset" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("HubspotObject")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="6db54-101">Hubspot サービス データセットです。</span><span class="sxs-lookup"><span data-stu-id="6db54-101">Hubspot Serivce dataset.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HubspotObjectDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HubspotObjectDataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6db54-102">HubspotObjectDataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6db54-102">Initializes a new instance of the HubspotObjectDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HubspotObjectDataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HubspotObjectDataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HubspotObjectDataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.HubspotObjectDataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.HubspotObjectDataset (linkedServiceName, additionalProperties, description, structure, parameters)" />
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
      </Parameters>
      <Docs>
        <param name="linkedServiceName"><span data-ttu-id="6db54-103">リンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="6db54-103">Linked service reference.</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="6db54-104">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="6db54-104">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="6db54-105">データセットの説明。</span><span class="sxs-lookup"><span data-stu-id="6db54-105">Dataset description.</span></span></param>
        <param name="structure"><span data-ttu-id="6db54-106">データセットの構造を定義する列。</span><span class="sxs-lookup"><span data-stu-id="6db54-106">Columns that define the structure of the dataset.</span></span> <span data-ttu-id="6db54-107">型: 配列 (または配列の resultType を含む式)、itemType: DatasetDataElement です。</span><span class="sxs-lookup"><span data-stu-id="6db54-107">Type: array (or Expression with resultType array), itemType: DatasetDataElement.</span></span></param>
        <param name="parameters"><span data-ttu-id="6db54-108">データセットのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6db54-108">Parameters for dataset.</span></span></param>
        <summary>
            <span data-ttu-id="6db54-109">HubspotObjectDataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6db54-109">Initializes a new instance of the HubspotObjectDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HubspotObjectDataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hubspotObjectDataset.Validate " />
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
            <span data-ttu-id="6db54-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6db54-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6db54-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6db54-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>