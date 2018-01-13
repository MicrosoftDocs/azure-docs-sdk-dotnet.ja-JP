<Type Name="CustomAnalyzer" FullName="Microsoft.Azure.Search.Models.CustomAnalyzer">
  <TypeSignature Language="C#" Value="public class CustomAnalyzer : Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomAnalyzer extends Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.CustomAnalyzer" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomAnalyzer&#xA;Inherits Analyzer" />
  <TypeSignature Language="F#" Value="type CustomAnalyzer = class&#xA;    inherit Analyzer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Analyzer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.CustomAnalyzer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            検索インデックス可能/トークンのテキストに変換するプロセスが細かく制御できます。 1 つの定義済みトークナイザと 1 つまたは複数のフィルターで構成されるユーザー定義の構成することをお勧めします。
            トークナイザがトークン、およびトークナイザによって生成されます。 トークンを変更するためのフィルター テキストに分割することを担当します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomAnalyzer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CustomAnalyzer.#ctor" />
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
            CustomAnalyzer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomAnalyzer (string name, Microsoft.Azure.Search.Models.TokenizerName tokenizer, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.TokenizerName tokenizer, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CustomAnalyzer.#ctor(System.String,Microsoft.Azure.Search.Models.TokenizerName,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.TokenFilterName},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.CharFilterName})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, tokenizer As TokenizerName, Optional tokenFilters As IList(Of TokenFilterName) = null, Optional charFilters As IList(Of CharFilterName) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.CustomAnalyzer : string * Microsoft.Azure.Search.Models.TokenizerName * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; -&gt; Microsoft.Azure.Search.Models.CustomAnalyzer" Usage="new Microsoft.Azure.Search.Models.CustomAnalyzer (name, tokenizer, tokenFilters, charFilters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tokenizer" Type="Microsoft.Azure.Search.Models.TokenizerName" />
        <Parameter Name="tokenFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;" />
        <Parameter Name="charFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;" />
      </Parameters>
      <Docs>
        <param name="name">アナライザーの名前です。 文字、数字、スペース、ダッシュまたはアンダー スコア、だけ開始されますが、および文字の英数字で終わるのみを含める必要があり、128 文字に制限されます。</param>
        <param name="tokenizer">使用して文を単語に分割することなどのトークンの一連の連続するテキストに分割するトークナイザの名前。</param>
        <param name="tokenFilters">フィルターで除外または、トークナイザで生成されたトークンの変更に使用されるトークンのフィルターの一覧。 たとえば、すべての文字を小文字に変換する lowercase フィルターを指定することができます。 フィルターはリストされている順序で実行されます。</param>
        <param name="charFilters">トークナイザで処理される前に、入力テキストを準備するために使用する文字フィルターの一覧。 たとえば、特定の文字や記号が置き換えです。 フィルターはリストされている順序で実行されます。</param>
        <summary>
            CustomAnalyzer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CharFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CustomAnalyzer.CharFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property CharFilters As IList(Of CharFilterName)" />
      <MemberSignature Language="F#" Value="member this.CharFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CustomAnalyzer.CharFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="charFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトークナイザによって処理される前に、入力テキストを準備するために使用する文字フィルターの一覧を設定します。 たとえば、特定の文字や記号が置き換えです。 フィルターはリストされている順序で実行されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CustomAnalyzer.TokenFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenFilters As IList(Of TokenFilterName)" />
      <MemberSignature Language="F#" Value="member this.TokenFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CustomAnalyzer.TokenFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフィルターで除外または、トークナイザで生成されたトークンの変更に使用されるトークンのフィルターの一覧を設定します。 たとえば、すべての文字を小文字に変換する lowercase フィルターを指定することができます。 フィルターはリストされている順序で実行されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tokenizer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.TokenizerName Tokenizer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.TokenizerName Tokenizer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CustomAnalyzer.Tokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Property Tokenizer As TokenizerName" />
      <MemberSignature Language="F#" Value="member this.Tokenizer : Microsoft.Azure.Search.Models.TokenizerName with get, set" Usage="Microsoft.Azure.Search.Models.CustomAnalyzer.Tokenizer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenizer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を使用して文を単語に分割することなどのトークンの一連の連続するテキストに分割するトークナイザの名前。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CustomAnalyzer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="customAnalyzer.Validate " />
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