<Type Name="TableEntity" FullName="Microsoft.WindowsAzure.Storage.Table.TableEntity">
  <TypeSignature Language="C#" Value="public class TableEntity : Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi TableEntity extends System.Object implements class Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class TableEntity&#xA;Implements ITableEntity" />
  <TypeSignature Language="F#" Value="type TableEntity = class&#xA;    interface ITableEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            テーブル サービスでのテーブル エンティティの基本オブジェクトの種類を表します。
            </summary>
    <remarks>
      <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />基本実装を提供、<see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />を提供するインターフェイス<see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />と<see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" />メソッドを既定ではおよびリフレクションを使用してすべてのプロパティを逆シリアル化します。 テーブル エンティティ クラスがこのクラスを拡張し、オーバーライド、<see cref="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />と<see cref="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" />をカスタマイズしたりパフォーマンスのシリアル化ロジックのより強力なメソッドです。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntity (string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.TableEntity : string * string -&gt; Microsoft.WindowsAzure.Storage.Table.TableEntity" Usage="new Microsoft.WindowsAzure.Storage.Table.TableEntity (partitionKey, rowKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionKey">パーティション キーを含む文字列、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />初期化されるようにします。</param>
        <param name="rowKey">行キーを含む文字列、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />初期化されるようにします。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />指定されたパーティション キーと行キーを持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertBack&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public static TResult ConvertBack&lt;TResult&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TResult ConvertBack&lt;TResult&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; 'Result" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.ConvertBack (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">Recomposed オブジェクトの型。 これには、フラットな構造を持つ単純なオブジェクトまたは複雑なプロパティとオブジェクトの階層の複数のレベルで複雑なオブジェクトを指定できます。</typeparam>
        <param name="properties"><see cref="T:System.Collections.Generic.IDictionary`2" />文字列プロパティにマップするオブジェクトの名前を<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />データ値を逆シリアル化し、このテーブル エンティティ インスタンスに格納します。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定して再構成されているカスタム エンティティ インスタンスを返します<see cref="T:System.Collections.Generic.IDictionary`2" />プロパティ名の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />データ型の値。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertBack&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public static TResult ConvertBack&lt;TResult&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TResult ConvertBack&lt;TResult&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; 'Result" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.ConvertBack (properties, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">Recomposed オブジェクトの型。 これには、フラットな構造を持つ単純なオブジェクトまたは複雑なプロパティとオブジェクトの階層の複数のレベルで複雑なオブジェクトを指定できます。</typeparam>
        <param name="properties"><see cref="T:System.Collections.Generic.IDictionary`2" />文字列プロパティにマップするオブジェクトの名前を<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />データ値を逆シリアル化し、このテーブル エンティティ インスタンスに格納します。</param>
        <param name="entityPropertyConverterOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />変換オプションは、エンティティ プロパティを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定して再構成されているカスタム エンティティ インスタンスを返します<see cref="T:System.Collections.Generic.IDictionary`2" />プロパティ名の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />データ型の値。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableCompiledSerializers">
      <MemberSignature Language="C#" Value="public static bool DisableCompiledSerializers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool DisableCompiledSerializers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.DisableCompiledSerializers" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property DisableCompiledSerializers As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableCompiledSerializers : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.DisableCompiledSerializers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            動的に読み取りを生成し、実行時にラムダを記述する機能を無効にします。 これを false に設定が TableEntity から派生するすべての型のインスタンス間で共有される静的キャッシュがクリアされます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisablePropertyResolverCache">
      <MemberSignature Language="C#" Value="public static bool DisablePropertyResolverCache { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool DisablePropertyResolverCache" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.DisablePropertyResolverCache" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property DisablePropertyResolverCache As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisablePropertyResolverCache : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.DisablePropertyResolverCache" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のプロパティのリゾルバー キャッシュの状態、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />です。 
            </summary>
        <value>To be added.</value>
        <remarks>
            プロパティのリゾルバー キャッシュでは、エンティティが逆シリアル化し、ペイロードが JSON メタデータを含まないときに既知のエンティティ型と、それぞれのプロパティの競合回避モジュールの辞書をキャッシュします。 ほとんどのシナリオでは、プロパティ リゾルバー キャッシュを無効化はお勧めしませんパフォーマンスに与える影響のためです。 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.ETag" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ETag</InterfaceMember>
      </Implements>
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
            取得またはエンティティの ETag を設定します。 この値を ' *'、更新操作の一部としてエンティティを強制的に上書きするためにします。
            </summary>
        <value>エンティティの ETag 値を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten (object entity, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten(object entity, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.Flatten(System.Object,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.Flatten (entity, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity">シリアル化するエンティティ オブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            エンティティをフラット化し、作成、<see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティ オブジェクト。
            </summary>
        <returns><see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティのオブジェクト。</returns>
        <remarks>エンティティ型には、フラットな構造を持つ単純なオブジェクトまたは複雑なプロパティとオブジェクトの階層の複数のレベルで複雑なオブジェクトを指定できます。
            ジェネリックの ConvertBack メソッドでは、このメソッドの戻り値を使用して元のエンティティを再構成できます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten (object entity, Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten(object entity, class Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.Flatten(System.Object,Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.Flatten (entity, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity">シリアル化するエンティティ オブジェクト。</param>
        <param name="entityPropertyConverterOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />変換オプションは、エンティティ プロパティを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            エンティティをフラット化し、作成、<see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティ オブジェクト。
            </summary>
        <returns><see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティのオブジェクト。</returns>
        <remarks>エンティティ型には、フラットな構造を持つ単純なオブジェクトまたは複雑なプロパティとオブジェクトの階層の複数のレベルで複雑なオブジェクトを指定できます。
            ジェネリックの ConvertBack メソッドでは、このメソッドの戻り値を使用して元のエンティティを再構成できます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.PartitionKey</InterfaceMember>
      </Implements>
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
            取得またはエンティティのパーティション キーを設定します。
            </summary>
        <value>エンティティのパーティション キーを含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public virtual void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="tableEntity.ReadEntity (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><see cref="T:System.Collections.Generic.IDictionary`2" />プロパティをマップするオブジェクト名を入力して<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />値。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定されたを使用してエンティティを逆シリアル化<see cref="T:System.Collections.Generic.IDictionary`2" />に型指定されたプロパティ名をマップする<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />値。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserObject">
      <MemberSignature Language="C#" Value="public static void ReadUserObject (object entity, System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadUserObject(object entity, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ReadUserObject(System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ReadUserObject : obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.ReadUserObject (entity, properties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity">逆シリアル化されるカスタム エンティティ インスタンス。</param>
        <param name="properties"><see cref="T:System.Collections.Generic.IDictionary`2" />文字列プロパティにマップするオブジェクトの名前を<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />データ値を逆シリアル化し、このテーブル エンティティ インスタンスに格納します。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定されたを使用してカスタム エンティティ インスタンスを逆シリアル化<see cref="T:System.Collections.Generic.IDictionary`2" />プロパティ名の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />データ型の値。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.RowKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.RowKey</InterfaceMember>
      </Implements>
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
            取得またはエンティティの行キーを設定します。
            </summary>
        <value>エンティティの行キーを含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.Timestamp</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンティティのタイムスタンプを設定します。
            </summary>
        <value>A<see cref="T:System.DateTimeOffset" />エンティティのタイムスタンプを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity (Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity(class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WriteEntity : Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;&#xA;override this.WriteEntity : Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="tableEntity.WriteEntity operationContext" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            シリアル化、<see cref="T:System.Collections.Generic.IDictionary`2" />にマッピングされたプロパティ名の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />これからのデータ値<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />インスタンス。
            </summary>
        <returns><see cref="T:System.Collections.Generic.IDictionary`2" />文字列プロパティにマップするオブジェクトの名前を<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />このテーブル エンティティ インスタンスをシリアル化によって作成された値を入力します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteUserObject">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteUserObject (object entity, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteUserObject(object entity, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.WriteUserObject(System.Object,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member WriteUserObject : obj * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.WriteUserObject (entity, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity">シリアル化するエンティティ オブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            作成、<see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティのオブジェクト。
            </summary>
        <returns><see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティのオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>