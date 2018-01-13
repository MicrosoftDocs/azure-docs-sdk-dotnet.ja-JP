<Type Name="PagedListHelper" FullName="System.Fabric.Query.PagedListHelper">
  <TypeSignature Language="C#" Value="public static class PagedListHelper" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PagedListHelper extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.PagedListHelper" />
  <TypeSignature Language="VB.NET" Value="Public Module PagedListHelper" />
  <TypeSignature Language="F#" Value="type PagedListHelper = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>
            ページのリスト操作用の拡張機能です。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToArray&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T[] ToArray&lt;T&gt; (this System.Fabric.Query.PagedList&lt;T&gt; list);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T[] ToArray&lt;T&gt;(class System.Fabric.Query.PagedList`1&lt;!!T&gt; list) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.PagedListHelper.ToArray``1(System.Fabric.Query.PagedList{``0})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ToArray(Of T) (list As PagedList(Of T)) As T()" />
      <MemberSignature Language="F#" Value="static member ToArray : System.Fabric.Query.PagedList&lt;'T&gt; -&gt; 'T[]" Usage="System.Fabric.Query.PagedListHelper.ToArray list" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T[]</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="list" Type="System.Fabric.Query.PagedList&lt;T&gt;" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="T">
          <para>リスト オブジェクトの型。</para>
        </typeparam>
        <param name="list">
          <para>ページの一覧です。</para>
        </param>
        <summary>
          <para>
            ページの一覧で、項目を含む配列を返します。
            </para>
        </summary>
        <returns>
          <para>配列。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>