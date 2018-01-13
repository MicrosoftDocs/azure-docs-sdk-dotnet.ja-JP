<Type Name="Suggester" FullName="Microsoft.Azure.Search.Models.Suggester">
  <TypeSignature Language="C#" Value="public class Suggester" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi Suggester extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.Suggester" />
  <TypeSignature Language="VB.NET" Value="Public Class Suggester" />
  <TypeSignature Language="F#" Value="type Suggester = class" />
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
            Suggest API が、インデックス内のフィールドのグループに適用する方法を定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Suggester ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Suggester.#ctor" />
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
            Suggester クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Suggester (string name, System.Collections.Generic.IList&lt;string&gt; sourceFields);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; sourceFields) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Suggester.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, sourceFields As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Suggester : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.Suggester" Usage="new Microsoft.Azure.Search.Models.Suggester (name, sourceFields)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sourceFields" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Suggester の名前。</param>
        <param name="sourceFields">Suggester を適用するフィールド名の一覧です。 各フィールドを検索可能にする必要があります。</param>
        <summary>
            Suggester クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Suggester (string name, params string[] sourceFields);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string[] sourceFields) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Suggester.#ctor(System.String,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, ParamArray sourceFields As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Suggester : string * string[] -&gt; Microsoft.Azure.Search.Models.Suggester" Usage="new Microsoft.Azure.Search.Models.Suggester (name, sourceFields)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sourceFields" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="name">Suggester の名前。</param>
        <param name="sourceFields">、Suggester を適用するフィールド名の一覧各フィールドを検索可能にする必要があります。</param>
        <summary>
            必須の引数で Suggester クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Suggester.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.Suggester.Name" />
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
            取得または、suggester の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchMode">
      <MemberSignature Language="C#" Value="public static string SearchMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string SearchMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Suggester.SearchMode" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property SearchMode As String" />
      <MemberSignature Language="F#" Value="member this.SearchMode : string" Usage="Microsoft.Azure.Search.Models.Suggester.SearchMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="searchMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Suggester の機能を示す値。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceFields">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SourceFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SourceFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Suggester.SourceFields" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceFields As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SourceFields : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.Suggester.SourceFields" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceFields")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、suggester を適用するフィールド名の一覧を設定します。 各フィールドを検索可能にする必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Suggester.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="suggester.Validate " />
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