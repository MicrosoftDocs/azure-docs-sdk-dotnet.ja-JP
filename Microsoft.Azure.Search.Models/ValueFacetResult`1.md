<Type Name="ValueFacetResult&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.ValueFacetResult&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class ValueFacetResult&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ValueFacetResult`1&lt;T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.ValueFacetResult`1" />
  <TypeSignature Language="VB.NET" Value="Public Class ValueFacetResult(Of T)" />
  <TypeSignature Language="F#" Value="type ValueFacetResult&lt;'T&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">
            ファセットが適用されているフィールドの種類に対応する型。
            </typeparam>
    <summary>
            単純または間隔ファセット クエリ結果のフィールドまたは特定の間隔内で特定の値を持つを持つドキュメントの数を報告するの単一バケット。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public long Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ValueFacetResult`1.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Long" />
      <MemberSignature Language="F#" Value="member this.Count : int64" Usage="Microsoft.Azure.Search.Models.ValueFacetResult&lt;'T&gt;.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このファセットにより説明されるバケット内のドキュメントのおおよその数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public T Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ValueFacetResult`1.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As T" />
      <MemberSignature Language="F#" Value="member this.Value : 'T" Usage="Microsoft.Azure.Search.Models.ValueFacetResult&lt;'T&gt;.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            間隔ファセットである場合は、ファセット、または下限の値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>