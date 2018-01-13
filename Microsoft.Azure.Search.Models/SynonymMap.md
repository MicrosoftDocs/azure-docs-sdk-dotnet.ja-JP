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
            Azure Search でシノニム マップの定義を表します。
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
            SynonymMap クラスの新しいインスタンスを初期化します。
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
        <param name="name">シノニムのマップの名前。</param>
        <param name="format">シノニムのマップの形式です。 'Solr' 形式のみが現在サポートされています。</param>
        <param name="synonyms">一連のシノニムの指定したマップ形式のシノニム ルール。 ルールは、改行で区切る必要があります。</param>
        <param name="eTag">シノニムのマップの ETag。</param>
        <summary>
            SynonymMap クラスの新しいインスタンスを初期化します。
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
            取得またはシノニム マップの ETag を設定します。
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
            取得またはシノニム マップの形式を設定します。 'Solr' 形式のみが現在サポートされています。
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
            取得またはシノニム マップの名前を設定します。
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
            取得または一連のシノニムの規則をシノニムの指定したマップ形式に設定します。 ルールは、改行で区切る必要があります。
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