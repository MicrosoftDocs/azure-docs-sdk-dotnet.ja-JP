<Type Name="Transformation" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation">
  <TypeSignature Language="C#" Value="public class Transformation : Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Transformation extends Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
  <TypeSignature Language="VB.NET" Value="Public Class Transformation&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type Transformation = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            名前付きの変換に関連付けられているすべての情報を含む変換オブジェクト。 ストリーミング ジョブの下では、すべての変換が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Transformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            変換クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Transformation (string id = null, string name = null, string type = null, Nullable&lt;int&gt; streamingUnits = null, string query = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, valuetype System.Nullable`1&lt;int32&gt; streamingUnits, string query, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.#ctor(System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional streamingUnits As Nullable(Of Integer) = null, Optional query As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.Transformation : string * string * string * Nullable&lt;int&gt; * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.Transformation (id, name, type, streamingUnits, query, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="streamingUnits" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="streamingUnits">ストリーミング ジョブが使用するストリーミング ユニットの数を指定します。</param>
        <param name="query">ストリーミング ジョブで実行されるクエリを指定します。 Stream Analytics クエリ言語 (SAQL) ここで詳細については、: https://msdn.microsoft.com/library/azure/dn834998 です。 PUT (CreateOrReplace) 要求に必要です。</param>
        <param name="etag">変換の現在のエンティティ タグ。
            これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。</param>
        <summary>
            変換クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            変換の現在のエンティティ タグを取得します。 これは、不透明な文字列です。 要求間でリソースが変更されたかどうかを検出するために使用できます。 使用することできますも、If-match または [なし]-If-match ヘッダーでオプティミスティック同時実行制御の書き込み操作のためです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public string Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As String" />
      <MemberSignature Language="F#" Value="member this.Query : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ストリーミング ジョブで実行されるクエリを指定します。 Stream Analytics クエリ言語 (SAQL) ここで詳細については、: https://msdn.microsoft.com/library/azure/dn834998 です。
            PUT (CreateOrReplace) 要求に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamingUnits">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; StreamingUnits { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; StreamingUnits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.StreamingUnits" />
      <MemberSignature Language="VB.NET" Value="Public Property StreamingUnits As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.StreamingUnits : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation.StreamingUnits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.streamingUnits")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ストリーミング ジョブが使用するストリーミング ユニットの数を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>