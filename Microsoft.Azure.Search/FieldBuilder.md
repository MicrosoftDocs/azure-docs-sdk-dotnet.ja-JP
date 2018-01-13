<Type Name="FieldBuilder" FullName="Microsoft.Azure.Search.FieldBuilder">
  <TypeSignature Language="C#" Value="public static class FieldBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FieldBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.FieldBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class FieldBuilder" />
  <TypeSignature Language="F#" Value="type FieldBuilder = class" />
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
            ユーザー定義モデルの種類を反映して Azure Search インデックスのフィールド定義をビルドします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildForType&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt; BuildForType&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Field&gt; BuildForType&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.FieldBuilder.BuildForType``1" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function BuildForType(Of T) () As IList(Of Field)" />
      <MemberSignature Language="F#" Value="static member BuildForType : unit -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt;" Usage="Microsoft.Azure.Search.FieldBuilder.BuildForType " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            作成対象となるフィールドは、型は、そのプロパティに基づいています。
            </typeparam>
        <summary>
            コレクションを作成<see cref="T:Microsoft.Azure.Search.Models.Field" />指定した型のプロパティに対応するオブジェクト。
            </summary>
        <returns>フィールドのコレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildForType&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt; BuildForType&lt;T&gt; (Newtonsoft.Json.Serialization.IContractResolver contractResolver);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.Field&gt; BuildForType&lt;T&gt;(class Newtonsoft.Json.Serialization.IContractResolver contractResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.FieldBuilder.BuildForType``1(Newtonsoft.Json.Serialization.IContractResolver)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function BuildForType(Of T) (contractResolver As IContractResolver) As IList(Of Field)" />
      <MemberSignature Language="F#" Value="static member BuildForType : Newtonsoft.Json.Serialization.IContractResolver -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt;" Usage="Microsoft.Azure.Search.FieldBuilder.BuildForType contractResolver" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.Field&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="contractResolver" Type="Newtonsoft.Json.Serialization.IContractResolver" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            作成対象となるフィールドは、型は、そのプロパティに基づいています。
            </typeparam>
        <param name="contractResolver">
            コントラクトの競合回避モジュールを<see cref="T:Microsoft.Azure.Search.SearchIndexClient" />が使用されます。
            これにより、フィールド名は、モデルをシリアル化される方法に一貫性のある方法で生成されること。
            </param>
        <summary>
            コレクションを作成<see cref="T:Microsoft.Azure.Search.Models.Field" />指定した型のプロパティに対応するオブジェクト。
            </summary>
        <returns>フィールドのコレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>