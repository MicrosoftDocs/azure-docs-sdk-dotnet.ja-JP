<Type Name="MappingCharFilter" FullName="Microsoft.Azure.Search.Models.MappingCharFilter">
  <TypeSignature Language="C#" Value="public class MappingCharFilter : Microsoft.Azure.Search.Models.CharFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MappingCharFilter extends Microsoft.Azure.Search.Models.CharFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.MappingCharFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class MappingCharFilter&#xA;Inherits CharFilter" />
  <TypeSignature Language="F#" Value="type MappingCharFilter = class&#xA;    inherit CharFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.CharFilter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.MappingCharFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            文字フィルターをマッピング オプションを使用して定義されているマップを適用します。 一致では最長一致 (最長パターン マッチには特定のポイントの wins) です。 置換は、空の文字列が許可されます。 この文字のフィルターは、Apache Lucene を使用して実装されます。
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/charfilter/MappingCharFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MappingCharFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MappingCharFilter.#ctor" />
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
            MappingCharFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MappingCharFilter (string name, System.Collections.Generic.IList&lt;string&gt; mappings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; mappings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MappingCharFilter.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, mappings As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.MappingCharFilter : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.MappingCharFilter" Usage="new Microsoft.Azure.Search.Models.MappingCharFilter (name, mappings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mappings" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Char 型のフィルターの名前です。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="mappings">次の形式のマッピングの一覧:"、=&gt;b"("a"に置き換えられます"b"の文字の文字のすべての出現数)。</param>
        <summary>
            MappingCharFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Mappings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Mappings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MappingCharFilter.Mappings" />
      <MemberSignature Language="VB.NET" Value="Public Property Mappings As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Mappings : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MappingCharFilter.Mappings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mappings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            次の形式のマッピングの一覧を取得または:"、=&amp;gt; b"("a"に置き換えられます"b"の文字の文字のすべての出現数)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MappingCharFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="mappingCharFilter.Validate " />
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