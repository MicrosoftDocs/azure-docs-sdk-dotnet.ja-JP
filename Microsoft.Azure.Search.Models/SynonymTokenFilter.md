<Type Name="SynonymTokenFilter" FullName="Microsoft.Azure.Search.Models.SynonymTokenFilter">
  <TypeSignature Language="C#" Value="public class SynonymTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SynonymTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SynonymTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class SynonymTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type SynonymTokenFilter = class&#xA;    inherit TokenFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.TokenFilter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.SynonymTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            トークン ストリームで 1 つまたは複数の単語のシノニムを一致します。 このトークンのフィルターは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/synonym/SynonymFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SynonymTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymTokenFilter.#ctor" />
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
            SynonymTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SynonymTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; synonyms, Nullable&lt;bool&gt; ignoreCase = null, Nullable&lt;bool&gt; expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; synonyms, valuetype System.Nullable`1&lt;bool&gt; ignoreCase, valuetype System.Nullable`1&lt;bool&gt; expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, synonyms As IList(Of String), Optional ignoreCase As Nullable(Of Boolean) = null, Optional expand As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SynonymTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.SynonymTokenFilter" Usage="new Microsoft.Azure.Search.Models.SynonymTokenFilter (name, synonyms, ignoreCase, expand)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="synonyms" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="ignoreCase" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="expand" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="synonyms">2 つの形式の次のいずれかのシノニムの一覧: 1。 驚異的な多く、fabulous =&gt;驚き - の左側にあるすべての用語 =&gt;シンボルは、右側にある; 上のすべての用語に置き換えられます2 になります。 驚異的な多く、fabulous、驚くほどの同等の単語のコンマ区切り一覧。 この一覧を解釈する方法を変更する展開オプションを設定します。</param>
        <param name="ignoreCase">示す値の照合 case-fold 入力するかどうか。 既定値は false です。</param>
        <param name="expand">すべてのシノニムの一覧で単語かどうかを示す値 (場合 =&gt;表記は使用されません) 相互にマップされます。 シノニムの一覧で、true の場合、すべての単語 (場合 =&gt;表記は使用されません) が相互にマップします。 次の一覧: 驚異的な多く、fabulous、優れたは等価: 驚異的な多く、fabulous、優れた =&gt;驚異的な多く、fabulous、優れたです。 False の場合、次の一覧: に同等では、fabulous、驚異的な多くの優れた: 驚異的な多く、fabulous、優れた =&gt;驚異的なです。
            既定値は true です。</param>
        <summary>
            SynonymTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expand">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Expand { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Expand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymTokenFilter.Expand" />
      <MemberSignature Language="VB.NET" Value="Public Property Expand As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Expand : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SynonymTokenFilter.Expand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expand")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはすべてのシノニムの一覧で単語かどうかを示す値を設定 (場合 =&amp;gt; 表記は使用されません) が相互にマップします。 シノニムの一覧で、true の場合、すべての単語 (場合 =&amp;gt; 表記は使用されません) が相互にマップします。 次の一覧: 驚異的な多く、fabulous、優れたは等価: 驚異的な多く、fabulous、優れた =&amp;gt; 驚異的な多く、fabulous、優れたです。 False の場合、次の一覧: に同等では、fabulous、驚異的な多くの優れた: 驚異的な多く、fabulous、優れた =&amp;gt; 驚異的なです。
            既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreCase">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreCase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreCase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymTokenFilter.IgnoreCase" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreCase As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreCase : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SynonymTokenFilter.IgnoreCase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ignoreCase")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはの照合 case-fold 入力するかどうかを示す値を設定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Synonyms">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Synonyms { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Synonyms" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymTokenFilter.Synonyms" />
      <MemberSignature Language="VB.NET" Value="Public Property Synonyms As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Synonyms : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SynonymTokenFilter.Synonyms" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="synonyms")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または 2 つの形式の次のいずれのシノニムの一覧を設定します。 1。
            驚異的な多く、fabulous =&amp;gt; すばらしい - の左側にあるすべての用語 =&amp;gt; シンボルは、右側にある; 上のすべての用語に置き換えられます2 になります。 驚異的な多く、fabulous、驚くほどの同等の単語のコンマ区切り一覧。 この一覧を解釈する方法を変更する展開オプションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="synonymTokenFilter.Validate " />
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