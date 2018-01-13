<Type Name="ExtensibleEnumValueFactory&lt;T&gt;" FullName="Microsoft.Azure.Search.Serialization.ExtensibleEnumValueFactory&lt;T&gt;">
  <TypeSignature Language="C#" Value="public delegate T ExtensibleEnumValueFactory&lt;T&gt;(string name) where T : ExtensibleEnum&lt;T&gt;;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ExtensibleEnumValueFactory`1&lt;(class Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;!T&gt;) T&gt; extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Serialization.ExtensibleEnumValueFactory`1" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function ExtensibleEnumValueFactory(Of T)(name As String) As T " />
  <TypeSignature Language="F#" Value="type ExtensibleEnumValueFactory&lt;'T (requires 'T :&gt; ExtensibleEnum&lt;'T&gt;)&gt; = delegate of string -&gt; 'T" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;T&gt;</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="name" Type="System.String" />
  </Parameters>
  <ReturnValue>
    <ReturnType>T</ReturnType>
  </ReturnValue>
  <Docs>
    <typeparam name="T">ExtensibleEnum の型が返されます。</typeparam>
    <param name="name">検索または作成する列挙値。</param>
    <summary>
            デリゲートを作成するかを指定する文字列から ExtensibleEnum インスタンスを検索するファクトリ メソッドの型。
            </summary>
    <returns>T 型のインスタンス</returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>