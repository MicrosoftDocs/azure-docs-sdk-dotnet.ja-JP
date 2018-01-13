<Type Name="AzureBlobDataset" FullName="Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset">
  <TypeSignature Language="C#" Value="public class AzureBlobDataset : Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBlobDataset extends Microsoft.Azure.Management.DataFactory.Models.Dataset" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBlobDataset&#xA;Inherits Dataset" />
  <TypeSignature Language="F#" Value="type AzureBlobDataset = class&#xA;    inherit Dataset" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("AzureBlob")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure Blob ストレージです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.#ctor" />
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
            AzureBlobDataset クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobDataset (Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, object structure = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters = null, object folderPath = null, object tableRootLocation = null, object fileName = null, Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format = null, Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, object structure, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; parameters, object folderPath, object tableRootLocation, object fileName, class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat format, class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression compression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.#ctor(Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification},System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat,Microsoft.Azure.Management.DataFactory.Models.DatasetCompression)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As LinkedServiceReference, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional structure As Object = null, Optional parameters As IDictionary(Of String, ParameterSpecification) = null, Optional folderPath As Object = null, Optional tableRootLocation As Object = null, Optional fileName As Object = null, Optional format As DatasetStorageFormat = null, Optional compression As DatasetCompression = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.DataFactory.Models.ParameterSpecification&gt; * obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat * Microsoft.Azure.Management.DataFactory.Models.DatasetCompression -&gt; Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset" Usage="new Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset (linkedServiceName, additionalProperties, description, structure, parameters, folderPath, tableRootLocation, fileName, format, compression)" />
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
        <Parameter Name="folderPath" Type="System.Object" />
        <Parameter Name="tableRootLocation" Type="System.Object" />
        <Parameter Name="fileName" Type="System.Object" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
        <Parameter Name="compression" Type="Microsoft.Azure.Management.DataFactory.Models.DatasetCompression" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName">リンクされたサービスの参照。</param>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="description">データセットの説明。</param>
        <param name="structure">データセットの構造を定義する列。 型: 配列 (または配列の resultType を含む式)、itemType: DatasetDataElement です。</param>
        <param name="parameters">データセットのパラメーターです。</param>
        <param name="folderPath">Azure Blob ストレージのパス。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="tableRootLocation">Blob パスのルートです。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="fileName">Azure Blob の名前。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="format">Azure Blob ストレージの形式です。</param>
        <param name="compression">データの圧縮方法は、blob ストレージに使用します。</param>
        <summary>
            AzureBlobDataset クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Compression">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetCompression Compression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.Compression" />
      <MemberSignature Language="VB.NET" Value="Public Property Compression As DatasetCompression" />
      <MemberSignature Language="F#" Value="member this.Compression : Microsoft.Azure.Management.DataFactory.Models.DatasetCompression with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.Compression" />
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
            取得または blob ストレージに使用されるデータの圧縮方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileName">
      <MemberSignature Language="C#" Value="public object FileName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.FileName" />
      <MemberSignature Language="VB.NET" Value="Public Property FileName As Object" />
      <MemberSignature Language="F#" Value="member this.FileName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.FileName" />
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
            取得または Azure Blob の名前を設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FolderPath">
      <MemberSignature Language="C#" Value="public object FolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.FolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property FolderPath As Object" />
      <MemberSignature Language="F#" Value="member this.FolderPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.FolderPath" />
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
            取得または Azure Blob ストレージのパスを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As DatasetStorageFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.Format" />
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
            取得または Azure Blob ストレージの形式を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableRootLocation">
      <MemberSignature Language="C#" Value="public object TableRootLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TableRootLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.TableRootLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property TableRootLocation As Object" />
      <MemberSignature Language="F#" Value="member this.TableRootLocation : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.TableRootLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.tableRootLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または blob パスのルートを設定します。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.AzureBlobDataset.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="azureBlobDataset.Validate " />
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
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>