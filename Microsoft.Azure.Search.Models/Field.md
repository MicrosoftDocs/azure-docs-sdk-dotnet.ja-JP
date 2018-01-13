<Type Name="Field" FullName="Microsoft.Azure.Search.Models.Field">
  <TypeSignature Language="C#" Value="public class Field" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Field extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.Field" />
  <TypeSignature Language="VB.NET" Value="Public Class Field" />
  <TypeSignature Language="F#" Value="type Field = class" />
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
            名前、データ型、およびフィールドの検索の動作を記述する Azure Search のインデックスの定義でフィールドを表します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Index" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Field ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Field.#ctor" />
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
            フィールドのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Field (string name, Microsoft.Azure.Search.Models.AnalyzerName analyzerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.AnalyzerName analyzerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Field.#ctor(System.String,Microsoft.Azure.Search.Models.AnalyzerName)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Field : string * Microsoft.Azure.Search.Models.AnalyzerName -&gt; Microsoft.Azure.Search.Models.Field" Usage="new Microsoft.Azure.Search.Models.Field (name, analyzerName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="analyzerName" Type="Microsoft.Azure.Search.Models.AnalyzerName" />
      </Parameters>
      <Docs>
        <param name="name">フィールドの名前。</param>
        <param name="analyzerName">フィールドに使用するアナライザーの名前。</param>
        <summary>
            必須の引数でフィールドのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>検索と Edm.String 型の新しいフィールドは自動的に。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Field (string name, Microsoft.Azure.Search.Models.DataType dataType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.DataType dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Field.#ctor(System.String,Microsoft.Azure.Search.Models.DataType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Field : string * Microsoft.Azure.Search.Models.DataType -&gt; Microsoft.Azure.Search.Models.Field" Usage="new Microsoft.Azure.Search.Models.Field (name, dataType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="dataType" Type="Microsoft.Azure.Search.Models.DataType" />
      </Parameters>
      <Docs>
        <param name="name">フィールドの名前。</param>
        <param name="dataType">フィールドのデータ型。</param>
        <summary>
            必須の引数でフィールドのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Field (string name, Microsoft.Azure.Search.Models.DataType dataType, Microsoft.Azure.Search.Models.AnalyzerName analyzerName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.DataType dataType, class Microsoft.Azure.Search.Models.AnalyzerName analyzerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Field.#ctor(System.String,Microsoft.Azure.Search.Models.DataType,Microsoft.Azure.Search.Models.AnalyzerName)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Field : string * Microsoft.Azure.Search.Models.DataType * Microsoft.Azure.Search.Models.AnalyzerName -&gt; Microsoft.Azure.Search.Models.Field" Usage="new Microsoft.Azure.Search.Models.Field (name, dataType, analyzerName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="dataType" Type="Microsoft.Azure.Search.Models.DataType" />
        <Parameter Name="analyzerName" Type="Microsoft.Azure.Search.Models.AnalyzerName" />
      </Parameters>
      <Docs>
        <param name="name">フィールドの名前。</param>
        <param name="dataType">フィールドのデータ型。</param>
        <param name="analyzerName">フィールドに使用するアナライザーの名前。</param>
        <summary>
            必須の引数でフィールドのクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>新しいフィールドは自動的に検索可能ななります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Analyzer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.AnalyzerName Analyzer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.AnalyzerName Analyzer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.Analyzer" />
      <MemberSignature Language="VB.NET" Value="Public Property Analyzer As AnalyzerName" />
      <MemberSignature Language="F#" Value="member this.Analyzer : Microsoft.Azure.Search.Models.AnalyzerName with get, set" Usage="Microsoft.Azure.Search.Models.Field.Analyzer" />
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
            取得または検索時およびインデックスの作成時に、フィールドに使用するアナライザーの名前を設定します。 このオプションは、検索可能なフィールドでのみ使用でき、SearchAnalyzer または IndexAnalyzer のいずれかと共に設定することはできません。 フィールドのアナライザーを選択した後は変更できません。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Language-support" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexAnalyzer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.AnalyzerName IndexAnalyzer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.AnalyzerName IndexAnalyzer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IndexAnalyzer" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexAnalyzer As AnalyzerName" />
      <MemberSignature Language="F#" Value="member this.IndexAnalyzer : Microsoft.Azure.Search.Models.AnalyzerName with get, set" Usage="Microsoft.Azure.Search.Models.Field.IndexAnalyzer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexAnalyzer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AnalyzerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフィールドのインデックス作成時に使用される、アナライザーの名前を設定します。 このオプションは、検索可能なフィールドでのみ使用できます。 SearchAnalyzer と共に設定する必要があり、アナライザー オプションと共に設定することはできません。 フィールドのアナライザーを選択した後は変更できません。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Language-support" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsFacetable">
      <MemberSignature Language="C#" Value="public bool IsFacetable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsFacetable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsFacetable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsFacetable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsFacetable : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsFacetable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("facetable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのフィールドのファセットを行うことがあるかどうかを示す値を設定します。 地理的座標フィールドに対しては無効です。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsFilterable">
      <MemberSignature Language="C#" Value="public bool IsFilterable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsFilterable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsFilterable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsFilterable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsFilterable : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsFilterable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("filterable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフィールドをフィルター式で使用できるかどうかを示す値を設定します。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsKey">
      <MemberSignature Language="C#" Value="public bool IsKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsKey" />
      <MemberSignature Language="VB.NET" Value="Public Property IsKey As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsKey : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフィールドが、インデックスのキーであるかどうかを示す値を設定します。 文字列フィールドにのみ有効です。 すべてのインデックス キーの 1 つのフィールドが必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetrievable">
      <MemberSignature Language="C#" Value="public bool IsRetrievable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRetrievable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsRetrievable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsRetrievable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRetrievable : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsRetrievable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("retrievable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフィールドが検索結果で返されるかどうかを示す値を設定します。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSearchable">
      <MemberSignature Language="C#" Value="public bool IsSearchable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSearchable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsSearchable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSearchable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSearchable : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsSearchable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("searchable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフルテキスト検索でフィールドが含まれているかどうかを示す値を設定します。 文字列または文字列のコレクションのフィールドに対してのみ有効です。 既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSortable">
      <MemberSignature Language="C#" Value="public bool IsSortable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSortable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.IsSortable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSortable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSortable : bool with get, set" Usage="Microsoft.Azure.Search.Models.Field.IsSortable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty("sortable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または orderby 式でフィールドを使用できるかどうかを示す値を設定します。 文字列コレクションのフィールドには無効です。
            既定値は false です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.Field.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            フィールドの名前を取得または設定します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchAnalyzer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.AnalyzerName SearchAnalyzer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.AnalyzerName SearchAnalyzer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.SearchAnalyzer" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchAnalyzer As AnalyzerName" />
      <MemberSignature Language="F#" Value="member this.SearchAnalyzer : Microsoft.Azure.Search.Models.AnalyzerName with get, set" Usage="Microsoft.Azure.Search.Models.Field.SearchAnalyzer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="searchAnalyzer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AnalyzerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフィールドの検索時に使用される、アナライザーの名前を設定します。 このオプションは、検索可能なフィールドでのみ使用できます。 IndexAnalyzer と共に設定する必要があり、アナライザー オプションと共に設定することはできません。 このアナライザーは、既存のフィールドで更新できます。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Language-support" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynonymMaps">
      <MemberSignature Language="C#" Value="public string[] SynonymMaps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string[] SynonymMaps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.SynonymMaps" />
      <MemberSignature Language="VB.NET" Value="Public Property SynonymMaps As String()" />
      <MemberSignature Language="F#" Value="member this.SynonymMaps : string[] with get, set" Usage="Microsoft.Azure.Search.Models.Field.SynonymMaps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="synonymMaps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフィールドのシノニムのマップの名前を設定します。 このオプションは、フィールドに対する検索のクエリ時のシノニムの拡張を有効にし、検索可能なフィールドでのみ使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Field.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As DataType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Search.Models.DataType with get, set" Usage="Microsoft.Azure.Search.Models.Field.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはフィールドのデータ型を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Field.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="field.Validate " />
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
            オブジェクトを検証します。 検証が失敗した場合は、ValidationException をスローします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>