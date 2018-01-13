<Type Name="AzureSqlTableDataset" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureSqlTableDataset">
  <TypeSignature Language="C#" Value="public class AzureSqlTableDataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureSqlTableDataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureSqlTableDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSqlTableDataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type AzureSqlTableDataset = class&#xA;    inherit Dataset" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureSqlTable")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="fe74e-101">Azure SQL Server データベース データセットです。</span><span class="sxs-lookup"><span data-stu-id="fe74e-101">The Azure SQL Server database dataset.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlTableDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureSqlTableDataset.#ctor" />
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
            <span data-ttu-id="fe74e-102">AzureSqlTableDataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fe74e-102">Initializes a new instance of the AzureSqlTableDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlTableDataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object tableName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object tableName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureSqlTableDataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, tableName As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureSqlTableDataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureSqlTableDataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureSqlTableDataset (linkedServiceName, tableName, additionalProperties, description, structure, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="tableName" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="structure" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt;" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName"><span data-ttu-id="fe74e-103">リンクされたサービスの参照。</span><span class="sxs-lookup"><span data-stu-id="fe74e-103">Linked service reference.</span></span></param>
        <param name="tableName"><span data-ttu-id="fe74e-104">Azure SQL データベースのテーブル名。</span><span class="sxs-lookup"><span data-stu-id="fe74e-104">The table name of the Azure SQL database.</span></span>
            <span data-ttu-id="fe74e-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fe74e-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="fe74e-106">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="fe74e-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="fe74e-107">データセットの説明。</span><span class="sxs-lookup"><span data-stu-id="fe74e-107">Dataset description.</span></span></param>
        <param name="structure"><span data-ttu-id="fe74e-108">データセットの構造を定義する列。</span><span class="sxs-lookup"><span data-stu-id="fe74e-108">Columns that define the structure of the dataset.</span></span> <span data-ttu-id="fe74e-109">型: 配列 (または配列の resultType を含む式)、itemType: DatasetDataElement です。</span><span class="sxs-lookup"><span data-stu-id="fe74e-109">Type: array (or Expression with resultType array), itemType: DatasetDataElement.</span></span></param>
        <param name="parameters"><span data-ttu-id="fe74e-110">データセットのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fe74e-110">Parameters for dataset.</span></span></param>
        <summary>
            <span data-ttu-id="fe74e-111">AzureSqlTableDataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fe74e-111">Initializes a new instance of the AzureSqlTableDataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public object TableName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureSqlTableDataset.TableName" />
      <MemberSignature Language="VB.NET" Value="Public Property TableName As Object" />
      <MemberSignature Language="F#" Value="member this.TableName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureSqlTableDataset.TableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.tableName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe74e-112">取得または Azure SQL データベースのテーブル名を設定します。</span><span class="sxs-lookup"><span data-stu-id="fe74e-112">Gets or sets the table name of the Azure SQL database.</span></span> <span data-ttu-id="fe74e-113">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="fe74e-113">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureSqlTableDataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureSqlTableDataset.Validate " />
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
            <span data-ttu-id="fe74e-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="fe74e-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fe74e-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fe74e-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>