<Type Name="Zone" FullName="Microsoft.Azure.Management.Dns.Models.Zone">
  <TypeSignature Language="C#" Value="public class Zone : Microsoft.Azure.Management.Dns.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Zone extends Microsoft.Azure.Management.Dns.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Models.Zone" />
  <TypeSignature Language="VB.NET" Value="Public Class Zone&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Zone = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Dns.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            DNS ゾーンをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Zone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Models.Zone.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ゾーンのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Zone (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string etag = null, Nullable&lt;long&gt; maxNumberOfRecordSets = null, Nullable&lt;long&gt; numberOfRecordSets = null, System.Collections.Generic.IList&lt;string&gt; nameServers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string etag, valuetype System.Nullable`1&lt;int64&gt; maxNumberOfRecordSets, valuetype System.Nullable`1&lt;int64&gt; numberOfRecordSets, class System.Collections.Generic.IList`1&lt;string&gt; nameServers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Models.Zone.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional etag As String = null, Optional maxNumberOfRecordSets As Nullable(Of Long) = null, Optional numberOfRecordSets As Nullable(Of Long) = null, Optional nameServers As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Dns.Models.Zone : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Dns.Models.Zone" Usage="new Microsoft.Azure.Management.Dns.Models.Zone (location, id, name, type, tags, etag, maxNumberOfRecordSets, numberOfRecordSets, nameServers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="maxNumberOfRecordSets" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="numberOfRecordSets" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="nameServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所。</param>
        <param name="id">リソースの ID</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="tags">リソース タグ。</param>
        <param name="etag">ゾーンの etag です。</param>
        <param name="maxNumberOfRecordSets">この DNS ゾーンに作成できるレコードのセットの最大数。  これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。</param>
        <param name="numberOfRecordSets">現在のレコードの数は、この DNS ゾーンに設定します。  これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。</param>
        <param name="nameServers">この DNS ゾーンのネーム サーバー。 これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。</param>
        <summary>
            ゾーンのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.Zone.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Dns.Models.Zone.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはゾーンの etag を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfRecordSets">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxNumberOfRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxNumberOfRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.Zone.MaxNumberOfRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxNumberOfRecordSets As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfRecordSets : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Dns.Models.Zone.MaxNumberOfRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxNumberOfRecordSets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この DNS ゾーンに作成できるレコードのセットの最大数を取得します。  これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NameServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NameServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.Zone.NameServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NameServers : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Dns.Models.Zone.NameServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nameServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この DNS ゾーンのネーム サーバーを取得します。 これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfRecordSets">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; NumberOfRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; NumberOfRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.Zone.NumberOfRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfRecordSets As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.NumberOfRecordSets : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Dns.Models.Zone.NumberOfRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberOfRecordSets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この DNS ゾーン内の現在のレコード セットの数を取得します。  これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Models.Zone.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="zone.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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