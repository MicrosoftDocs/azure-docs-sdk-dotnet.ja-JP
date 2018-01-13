<Type Name="EntityPropertyConverter" FullName="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter">
  <TypeSignature Language="C#" Value="public static class EntityPropertyConverter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EntityPropertyConverter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter" />
  <TypeSignature Language="VB.NET" Value="Public Class EntityPropertyConverter" />
  <TypeSignature Language="F#" Value="type EntityPropertyConverter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            EntityPropertyConverter クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ConvertBack&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T ConvertBack&lt;T&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; flattenedEntityProperties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T ConvertBack&lt;T&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; flattenedEntityProperties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; 'T" Usage="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.ConvertBack (flattenedEntityProperties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="flattenedEntityProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="T">設定されるオブジェクトの種類</typeparam>
        <param name="flattenedEntityProperties">フラット化されたエンティティ プロパティのディクショナリ。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            フラット化されたエンティティのプロパティのディクショナリを使用して T 型の完全なオブジェクト グラフを再構築し、再構築されたオブジェクトを返します。
            プロパティ辞書には、基本的なプロパティのみ、入れ子になったプロパティのみまたは両方の種類の組み合わせが含まれて可能性があります。
            </summary>
        <returns>完全なオブジェクト階層で再構築されたオブジェクトを含む結果を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertBack&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T ConvertBack&lt;T&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; flattenedEntityProperties, Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T ConvertBack&lt;T&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; flattenedEntityProperties, class Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; 'T" Usage="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.ConvertBack (flattenedEntityProperties, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="flattenedEntityProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="T">設定されるオブジェクトの種類</typeparam>
        <param name="flattenedEntityProperties">フラット化されたエンティティ プロパティのディクショナリ。</param>
        <param name="entityPropertyConverterOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />変換オプションは、エンティティ プロパティを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            フラット化されたエンティティのプロパティのディクショナリを使用して T 型の完全なオブジェクト グラフを再構築し、再構築されたオブジェクトを返します。
            プロパティ辞書には、基本的なプロパティのみ、入れ子になったプロパティのみまたは両方の種類の組み合わせが含まれて可能性があります。
            </summary>
        <returns>完全なオブジェクト階層で再構築されたオブジェクトを含む結果を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultPropertyNameDelimiter">
      <MemberSignature Language="C#" Value="public const string DefaultPropertyNameDelimiter;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultPropertyNameDelimiter" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.DefaultPropertyNameDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultPropertyNameDelimiter As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultPropertyNameDelimiter : string" Usage="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.DefaultPropertyNameDelimiter" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プロパティの区切り記号。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.Dictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten (object root, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.Dictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten(object root, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.Flatten(System.Object,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.Dictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.Flatten (root, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="root" Type="System.Object" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="root">フラット化して変換するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            オブジェクト グラフを通過する時間を平坦化する EntityProperties を入れ子になったすべて (およびいない入れ子になった) のプロパティに変換、プロパティ ディクショナリに格納します。
            キーは、'_' で区切られた各終了ノードのプロパティをルートから前の注文の深さの最初のトラバース時に閲覧のプロパティの名前を追加することによって構築されます。
            永続的な記憶域システムに格納されているまたは一般的な方法で web サービスの間で受け渡しする複雑なオブジェクトを使用します。
            </summary>
        <returns>結果を含む<see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />フラット化されたルート オブジェクトのすべてのプロパティ オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.Dictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten (object root, Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.Dictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten(object root, class Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.Flatten(System.Object,Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.Dictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverter.Flatten (root, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="root" Type="System.Object" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="root">フラット化して変換するオブジェクト。</param>
        <param name="entityPropertyConverterOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />変換オプションは、エンティティ プロパティを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            オブジェクト グラフを通過する時間を平坦化する EntityProperties を入れ子になったすべて (およびいない入れ子になった) のプロパティに変換、プロパティ ディクショナリに格納します。
            キーは、'_' で区切られた各終了ノードのプロパティをルートから前の注文の深さの最初のトラバース時に閲覧のプロパティの名前を追加することによって構築されます。
            永続的な記憶域システムに格納されているまたは一般的な方法で web サービスの間で受け渡しする複雑なオブジェクトを使用します。
            </summary>
        <returns>結果を含む<see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />フラット化されたルート オブジェクトのすべてのプロパティ オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>