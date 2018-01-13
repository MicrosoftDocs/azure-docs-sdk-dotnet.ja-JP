<Type Name="AnalyzeRequest" FullName="Microsoft.Azure.Search.Models.AnalyzeRequest">
  <TypeSignature Language="C#" Value="public class AnalyzeRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AnalyzeRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.AnalyzeRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class AnalyzeRequest" />
  <TypeSignature Language="F#" Value="type AnalyzeRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            一部のテキストとそのテキストをトークンに分割するコンポーネントが使用される分析を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AnalyzeRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AnalyzeRequest.#ctor" />
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
            AnalyzeRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AnalyzeRequest (string text, Microsoft.Azure.Search.Models.AnalyzerName analyzer = null, Microsoft.Azure.Search.Models.TokenizerName tokenizer = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string text, class Microsoft.Azure.Search.Models.AnalyzerName analyzer, class Microsoft.Azure.Search.Models.TokenizerName tokenizer, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AnalyzeRequest.#ctor(System.String,Microsoft.Azure.Search.Models.AnalyzerName,Microsoft.Azure.Search.Models.TokenizerName,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.TokenFilterName},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.CharFilterName})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (text As String, Optional analyzer As AnalyzerName = null, Optional tokenizer As TokenizerName = null, Optional tokenFilters As IList(Of TokenFilterName) = null, Optional charFilters As IList(Of CharFilterName) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.AnalyzeRequest : string * Microsoft.Azure.Search.Models.AnalyzerName * Microsoft.Azure.Search.Models.TokenizerName * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; -&gt; Microsoft.Azure.Search.Models.AnalyzeRequest" Usage="new Microsoft.Azure.Search.Models.AnalyzeRequest (text, analyzer, tokenizer, tokenFilters, charFilters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="text" Type="System.String" />
        <Parameter Name="analyzer" Type="Microsoft.Azure.Search.Models.AnalyzerName" />
        <Parameter Name="tokenizer" Type="Microsoft.Azure.Search.Models.TokenizerName" />
        <Parameter Name="tokenFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;" />
        <Parameter Name="charFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;" />
      </Parameters>
      <Docs>
        <param name="text">トークンに分割するテキストです。</param>
        <param name="analyzer">使用して、指定されたテキストを分割するアナライザーの名前。 このパラメーターが指定されていない場合は、代わりに、トークナイザを指定する必要があります。 トークナイザおよびロード テスト アナライザーのパラメーターは相互に排他的です。</param>
        <param name="tokenizer">使用して、指定されたテキストを分割するトークナイザの名前。 このパラメーターが指定されていない場合は、代わりに、アナライザーを指定する必要があります。 トークナイザおよびロード テスト アナライザーのパラメーターは相互に排他的です。</param>
        <param name="tokenFilters">指定したテキストを分割するときに使用するトークンのフィルターのオプションのリスト。 このパラメーターは、トークナイザ パラメーターを使用する場合にのみ設定できます。</param>
        <param name="charFilters">指定したテキストの重大なときに使用する文字のフィルターのオプションのリスト。 このパラメーターは、トークナイザ パラメーターを使用する場合にのみ設定できます。</param>
        <summary>
            AnalyzeRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Analyzer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.AnalyzerName Analyzer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.AnalyzerName Analyzer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.Analyzer" />
      <MemberSignature Language="VB.NET" Value="Public Property Analyzer As AnalyzerName" />
      <MemberSignature Language="F#" Value="member this.Analyzer : Microsoft.Azure.Search.Models.AnalyzerName with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.Analyzer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="analyzer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AnalyzerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を使用して、指定されたテキストを分割するアナライザーの名前。 このパラメーターが指定されていない場合は、代わりに、トークナイザを指定する必要があります。 トークナイザおよびロード テスト アナライザーのパラメーターは相互に排他的です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CharFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.CharFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property CharFilters As IList(Of CharFilterName)" />
      <MemberSignature Language="F#" Value="member this.CharFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.CharFilters" />
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
            取得または指定されたテキストの重大なときに使用する文字のフィルターのオプションのリストを設定します。 このパラメーターは、トークナイザ パラメーターを使用する場合にのみ設定できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Text">
      <MemberSignature Language="C#" Value="public string Text { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Text" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.Text" />
      <MemberSignature Language="VB.NET" Value="Public Property Text As String" />
      <MemberSignature Language="F#" Value="member this.Text : string with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.Text" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="text")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはトークンに分割したテキストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.TokenFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenFilters As IList(Of TokenFilterName)" />
      <MemberSignature Language="F#" Value="member this.TokenFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.TokenFilters" />
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
            取得または指定されたテキストの重大なときに使用するトークンのフィルターのオプションのリストを設定します。 このパラメーターは、トークナイザ パラメーターを使用する場合にのみ設定できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tokenizer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.TokenizerName Tokenizer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.TokenizerName Tokenizer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AnalyzeRequest.Tokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Property Tokenizer As TokenizerName" />
      <MemberSignature Language="F#" Value="member this.Tokenizer : Microsoft.Azure.Search.Models.TokenizerName with get, set" Usage="Microsoft.Azure.Search.Models.AnalyzeRequest.Tokenizer" />
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
            取得または設定を使用して、指定されたテキストを分割するトークナイザの名前。 このパラメーターが指定されていない場合は、代わりに、アナライザーを指定する必要があります。 トークナイザおよびロード テスト アナライザーのパラメーターは相互に排他的です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AnalyzeRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="analyzeRequest.Validate " />
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