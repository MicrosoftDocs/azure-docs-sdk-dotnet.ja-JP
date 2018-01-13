<Type Name="DocumentSearchResult&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class DocumentSearchResult&lt;T&gt; : Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;Microsoft.Azure.Search.Models.SearchResult&lt;T&gt;,T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentSearchResult`1&lt;class T&gt; extends Microsoft.Azure.Search.Models.DocumentSearchResultBase`2&lt;class Microsoft.Azure.Search.Models.SearchResult`1&lt;!T&gt;, !T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DocumentSearchResult`1" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentSearchResult(Of T)&#xA;Inherits DocumentSearchResultBase(Of SearchResult(Of T), T)" />
  <TypeSignature Language="F#" Value="type DocumentSearchResult&lt;'T (requires 'T : null)&gt; = class&#xA;    inherit DocumentSearchResultBase&lt;SearchResult&lt;'T&gt;, 'T (requires 'T : null)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;Microsoft.Azure.Search.Models.SearchResult&lt;T&gt;,T&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TResult">Microsoft.Azure.Search.Models.SearchResult&lt;T&gt;</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TDoc">T</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
    <summary>
            Azure Search インデックスから検索を含む応答の結果します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentSearchResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DocumentSearchResult`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>