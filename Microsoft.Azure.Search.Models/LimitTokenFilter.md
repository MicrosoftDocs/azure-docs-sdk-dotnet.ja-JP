<Type Name="LimitTokenFilter" FullName="Microsoft.Azure.Search.Models.LimitTokenFilter">
  <TypeSignature Language="C#" Value="public class LimitTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LimitTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.LimitTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class LimitTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type LimitTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.LimitTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            インデックス作成中に、トークンの数を制限します。 このトークンのフィルターは、Apache Lucene を使用して実装されます。
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/LimitTokenCountFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LimitTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.LimitTokenFilter.#ctor" />
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
            LimitTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LimitTokenFilter (string name, Nullable&lt;int&gt; maxTokenCount = null, Nullable&lt;bool&gt; consumeAllTokens = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; maxTokenCount, valuetype System.Nullable`1&lt;bool&gt; consumeAllTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.LimitTokenFilter.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional maxTokenCount As Nullable(Of Integer) = null, Optional consumeAllTokens As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.LimitTokenFilter : string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.LimitTokenFilter" Usage="new Microsoft.Azure.Search.Models.LimitTokenFilter (name, maxTokenCount, consumeAllTokens)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxTokenCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="consumeAllTokens" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">トークンのフィルターの名前。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="maxTokenCount">生成するためにトークンの最大数。 既定値は 1 です。</param>
        <param name="consumeAllTokens">MaxTokenCount に達した場合でも、入力からのすべてのトークンを使用する必要があるかどうかを示す値。 既定値は false です。</param>
        <summary>
            LimitTokenFilter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumeAllTokens">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ConsumeAllTokens { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ConsumeAllTokens" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.LimitTokenFilter.ConsumeAllTokens" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsumeAllTokens As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ConsumeAllTokens : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.LimitTokenFilter.ConsumeAllTokens" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="consumeAllTokens")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または maxTokenCount に達した場合でも、入力からのすべてのトークンを使用する必要があるかどうかを示す値を設定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTokenCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTokenCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTokenCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.LimitTokenFilter.MaxTokenCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTokenCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTokenCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.LimitTokenFilter.MaxTokenCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTokenCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または生成するためにトークンの最大数を設定します。 既定値は 1 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.LimitTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="limitTokenFilter.Validate " />
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