<Type Name="DocumentIndexResult" FullName="Microsoft.Azure.Search.Models.DocumentIndexResult">
  <TypeSignature Language="C#" Value="public class DocumentIndexResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentIndexResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DocumentIndexResult" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentIndexResult" />
  <TypeSignature Language="F#" Value="type DocumentIndexResult = class" />
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
            すべてのドキュメントのインデックス作成の要求での操作の状態を含む応答。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentIndexResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DocumentIndexResult.#ctor" />
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
            DocumentIndexResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentIndexResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt; results = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.IndexingResult&gt; results) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DocumentIndexResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Search.Models.IndexingResult})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional results As IList(Of IndexingResult) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DocumentIndexResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt; -&gt; Microsoft.Azure.Search.Models.DocumentIndexResult" Usage="new Microsoft.Azure.Search.Models.DocumentIndexResult results" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="results" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt;" />
      </Parameters>
      <Docs>
        <param name="results">インデックス作成の要求内の各ドキュメントの状態に関する情報の一覧。</param>
        <summary>
            DocumentIndexResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt; Results { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.IndexingResult&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentIndexResult.Results" />
      <MemberSignature Language="VB.NET" Value="Public Property Results As IList(Of IndexingResult)" />
      <MemberSignature Language="F#" Value="member this.Results : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentIndexResult.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インデックス作成の要求では、各ドキュメントの状態に関する情報の一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>