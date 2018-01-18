<Type Name="TableEntity" FullName="Microsoft.Azure.CosmosDB.Table.TableEntity">
  <TypeSignature Language="C#" Value="public class TableEntity : Microsoft.Azure.CosmosDB.Table.ITableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi TableEntity extends System.Object implements class Microsoft.Azure.CosmosDB.Table.ITableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class TableEntity&#xA;Implements ITableEntity" />
  <TypeSignature Language="F#" Value="type TableEntity = class&#xA;    interface ITableEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="5083a-101">テーブル サービスでのテーブル エンティティの基本オブジェクトの種類を表します。</span><span class="sxs-lookup"><span data-stu-id="5083a-101">Represents the base object type for a table entity in the Table service.</span></span>
            </summary>
    <remarks>
      <span data-ttu-id="5083a-102"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />基本実装を提供、<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />を提供するインターフェイス<see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />と<see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />メソッドを既定ではおよびリフレクションを使用してすべてのプロパティを逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="5083a-102"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> provides a base implementation for the <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> interface that provides <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" /> and <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> methods that by default serialize and deserialize all properties via reflection.</span></span> <span data-ttu-id="5083a-103">テーブル エンティティ クラスがこのクラスを拡張し、オーバーライド、<see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />と<see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />をカスタマイズしたりパフォーマンスのシリアル化ロジックのより強力なメソッドです。</span><span class="sxs-lookup"><span data-stu-id="5083a-103">A table entity class may extend this class and override the <see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" /> and <see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> methods to provide customized or better performing serialization logic.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5083a-104"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5083a-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntity (string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.TableEntity : string * string -&gt; Microsoft.Azure.CosmosDB.Table.TableEntity" Usage="new Microsoft.Azure.CosmosDB.Table.TableEntity (partitionKey, rowKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="5083a-105">パーティション キーを含む文字列、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />初期化されるようにします。</span><span class="sxs-lookup"><span data-stu-id="5083a-105">A string containing the partition key of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> to be initialized.</span></span></param>
        <param name="rowKey"><span data-ttu-id="5083a-106">行キーを含む文字列、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />初期化されるようにします。</span><span class="sxs-lookup"><span data-stu-id="5083a-106">A string containing the row key of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> to be initialized.</span></span></param>
        <summary>
            <span data-ttu-id="5083a-107">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />指定されたパーティション キーと行キーを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="5083a-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> class with the specified partition key and row key.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertBack&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public static TResult ConvertBack&lt;TResult&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TResult ConvertBack&lt;TResult&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; 'Result" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.ConvertBack (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="5083a-108">Recomposed オブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="5083a-108">The type of the recomposed object.</span></span> <span data-ttu-id="5083a-109">これには、フラットな構造を持つ単純なオブジェクトまたは複雑なプロパティとオブジェクトの階層の複数のレベルで複雑なオブジェクトを指定できます。</span><span class="sxs-lookup"><span data-stu-id="5083a-109">This can be a simple object with a flat structure or a complex object with complex properties and multiple levels of object hierarchy.</span></span></typeparam>
        <param name="properties"><span data-ttu-id="5083a-110"><see cref="T:System.Collections.Generic.IDictionary`2" />文字列プロパティにマップするオブジェクトの名前を<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データ値を逆シリアル化し、このテーブル エンティティ インスタンスに格納します。</span><span class="sxs-lookup"><span data-stu-id="5083a-110">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps string property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values to deserialize and store in this table entity instance.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5083a-111"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-111">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5083a-112">指定して再構成されているカスタム エンティティ インスタンスを返します<see cref="T:System.Collections.Generic.IDictionary`2" />プロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データ型の値。</span><span class="sxs-lookup"><span data-stu-id="5083a-112">Returns a custom entity instance which is recomposed using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data typed values.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertBack&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public static TResult ConvertBack&lt;TResult&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TResult ConvertBack&lt;TResult&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions * Microsoft.Azure.Storage.OperationContext -&gt; 'Result" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.ConvertBack (properties, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="5083a-113">Recomposed オブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="5083a-113">The type of the recomposed object.</span></span> <span data-ttu-id="5083a-114">これには、フラットな構造を持つ単純なオブジェクトまたは複雑なプロパティとオブジェクトの階層の複数のレベルで複雑なオブジェクトを指定できます。</span><span class="sxs-lookup"><span data-stu-id="5083a-114">This can be a simple object with a flat structure or a complex object with complex properties and multiple levels of object hierarchy.</span></span></typeparam>
        <param name="properties"><span data-ttu-id="5083a-115"><see cref="T:System.Collections.Generic.IDictionary`2" />文字列プロパティにマップするオブジェクトの名前を<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データ値を逆シリアル化し、このテーブル エンティティ インスタンスに格納します。</span><span class="sxs-lookup"><span data-stu-id="5083a-115">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps string property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values to deserialize and store in this table entity instance.</span></span></param>
        <param name="entityPropertyConverterOptions"><span data-ttu-id="5083a-116">A<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" />変換オプションは、エンティティ プロパティを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-116">A <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" /> object that specifies options for the entity property conversion.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5083a-117"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-117">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5083a-118">指定して再構成されているカスタム エンティティ インスタンスを返します<see cref="T:System.Collections.Generic.IDictionary`2" />プロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データ型の値。</span><span class="sxs-lookup"><span data-stu-id="5083a-118">Returns a custom entity instance which is recomposed using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data typed values.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableCompiledSerializers">
      <MemberSignature Language="C#" Value="public static bool DisableCompiledSerializers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool DisableCompiledSerializers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.DisableCompiledSerializers" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property DisableCompiledSerializers As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableCompiledSerializers : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.DisableCompiledSerializers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5083a-119">動的に読み取りを生成し、実行時にラムダを記述する機能を無効にします。</span><span class="sxs-lookup"><span data-stu-id="5083a-119">Disables the ability to dynamically generate read and write lambdas at runtime.</span></span> <span data-ttu-id="5083a-120">これを false に設定が TableEntity から派生するすべての型のインスタンス間で共有される静的キャッシュがクリアされます。</span><span class="sxs-lookup"><span data-stu-id="5083a-120">Setting this to false will clear out the static cache shared across all type instances that derive from TableEntity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisablePropertyResolverCache">
      <MemberSignature Language="C#" Value="public static bool DisablePropertyResolverCache { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool DisablePropertyResolverCache" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.DisablePropertyResolverCache" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property DisablePropertyResolverCache As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisablePropertyResolverCache : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.DisablePropertyResolverCache" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5083a-121">取得または設定のプロパティのリゾルバー キャッシュの状態、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />です。</span><span class="sxs-lookup"><span data-stu-id="5083a-121">Gets or sets the status of the property resolver cache for the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="5083a-122">プロパティのリゾルバー キャッシュでは、エンティティが逆シリアル化し、ペイロードが JSON メタデータを含まないときに既知のエンティティ型と、それぞれのプロパティの競合回避モジュールの辞書をキャッシュします。</span><span class="sxs-lookup"><span data-stu-id="5083a-122">The property resolver cache caches known entity types and their respective property resolver dictionaries when entities are deserialized and the payload does not include JSON metadata.</span></span> <span data-ttu-id="5083a-123">ほとんどのシナリオでは、プロパティ リゾルバー キャッシュを無効化はお勧めしませんパフォーマンスに与える影響のためです。</span><span class="sxs-lookup"><span data-stu-id="5083a-123">For most scenarios, disabling the property resolver cache is not recommended due to its effect on performance.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.ETag" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.CosmosDB.Table.ITableEntity.ETag</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5083a-124">取得またはエンティティの ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="5083a-124">Gets or sets the entity's ETag.</span></span> <span data-ttu-id="5083a-125">この値を ' \*'、更新操作の一部としてエンティティを強制的に上書きするためにします。</span><span class="sxs-lookup"><span data-stu-id="5083a-125">Set this value to '\*' in order to force an overwrite to an entity as part of an update operation.</span></span>
            </summary>
        <value><span data-ttu-id="5083a-126">エンティティの ETag 値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="5083a-126">A string containing the ETag value for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten (object entity, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten(object entity, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.Flatten(System.Object,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.Flatten (entity, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5083a-127">シリアル化するエンティティ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-127">The entity object to serialize.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5083a-128"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-128">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5083a-129">エンティティをフラット化し、作成、<see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-129">Flattens the entity and creates a <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all properties of the specified entity object.</span></span>
            </summary>
        <returns><span data-ttu-id="5083a-130"><see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-130">An <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all the properties of the specified entity object.</span></span></returns>
        <remarks><span data-ttu-id="5083a-131">エンティティ型には、フラットな構造を持つ単純なオブジェクトまたは複雑なプロパティとオブジェクトの階層の複数のレベルで複雑なオブジェクトを指定できます。</span><span class="sxs-lookup"><span data-stu-id="5083a-131">The entity type can be a simple object with a flat structure or a complex object with complex properties and multiple levels of object hierarchy.</span></span>
            <span data-ttu-id="5083a-132">ジェネリックの ConvertBack メソッドでは、このメソッドの戻り値を使用して元のエンティティを再構成できます。</span><span class="sxs-lookup"><span data-stu-id="5083a-132">Generic ConvertBack method can recompose the original entity using the return value of this method.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten (object entity, Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten(object entity, class Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.Flatten(System.Object,Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.Flatten (entity, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5083a-133">シリアル化するエンティティ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-133">The entity object to serialize.</span></span></param>
        <param name="entityPropertyConverterOptions"><span data-ttu-id="5083a-134">A<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" />変換オプションは、エンティティ プロパティを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-134">A <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" /> object that specifies options for the entity property conversion.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5083a-135"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-135">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5083a-136">エンティティをフラット化し、作成、<see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-136">Flattens the entity and creates a <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all properties of the specified entity object.</span></span>
            </summary>
        <returns><span data-ttu-id="5083a-137"><see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-137">An <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all the properties of the specified entity object.</span></span></returns>
        <remarks><span data-ttu-id="5083a-138">エンティティ型には、フラットな構造を持つ単純なオブジェクトまたは複雑なプロパティとオブジェクトの階層の複数のレベルで複雑なオブジェクトを指定できます。</span><span class="sxs-lookup"><span data-stu-id="5083a-138">The entity type can be a simple object with a flat structure or a complex object with complex properties and multiple levels of object hierarchy.</span></span>
            <span data-ttu-id="5083a-139">ジェネリックの ConvertBack メソッドでは、このメソッドの戻り値を使用して元のエンティティを再構成できます。</span><span class="sxs-lookup"><span data-stu-id="5083a-139">Generic ConvertBack method can recompose the original entity using the return value of this method.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.CosmosDB.Table.ITableEntity.PartitionKey</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5083a-140">取得またはエンティティのパーティション キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="5083a-140">Gets or sets the entity's partition key.</span></span>
            </summary>
        <value><span data-ttu-id="5083a-141">エンティティのパーティション キーを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="5083a-141">A string containing the partition key for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public virtual void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit&#xA;override this.ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="tableEntity.ReadEntity (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.CosmosDB.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="5083a-142"><see cref="T:System.Collections.Generic.IDictionary`2" />プロパティをマップするオブジェクト名を入力して<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />値。</span><span class="sxs-lookup"><span data-stu-id="5083a-142">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps property names to typed <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> values.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5083a-143"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-143">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5083a-144">指定されたを使用してエンティティを逆シリアル化<see cref="T:System.Collections.Generic.IDictionary`2" />に型指定されたプロパティ名をマップする<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />値。</span><span class="sxs-lookup"><span data-stu-id="5083a-144">Deserializes the entity using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> that maps property names to typed <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> values.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserObject">
      <MemberSignature Language="C#" Value="public static void ReadUserObject (object entity, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadUserObject(object entity, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ReadUserObject(System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ReadUserObject : obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.ReadUserObject (entity, properties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5083a-145">逆シリアル化されるカスタム エンティティ インスタンス。</span><span class="sxs-lookup"><span data-stu-id="5083a-145">The custom entity instance being deserialized.</span></span></param>
        <param name="properties"><span data-ttu-id="5083a-146"><see cref="T:System.Collections.Generic.IDictionary`2" />文字列プロパティにマップするオブジェクトの名前を<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データ値を逆シリアル化し、このテーブル エンティティ インスタンスに格納します。</span><span class="sxs-lookup"><span data-stu-id="5083a-146">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps string property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values to deserialize and store in this table entity instance.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5083a-147"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-147">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5083a-148">指定されたを使用してカスタム エンティティ インスタンスを逆シリアル化<see cref="T:System.Collections.Generic.IDictionary`2" />プロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データ型の値。</span><span class="sxs-lookup"><span data-stu-id="5083a-148">Deserializes a custom entity instance using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data typed values.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.RowKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.CosmosDB.Table.ITableEntity.RowKey</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5083a-149">取得またはエンティティの行キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="5083a-149">Gets or sets the entity's row key.</span></span>
            </summary>
        <value><span data-ttu-id="5083a-150">エンティティの行キーを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="5083a-150">A string containing the row key for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.CosmosDB.Table.ITableEntity.Timestamp</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5083a-151">取得またはエンティティのタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="5083a-151">Gets or sets the entity's timestamp.</span></span>
            </summary>
        <value><span data-ttu-id="5083a-152">A<see cref="T:System.DateTimeOffset" />エンティティのタイムスタンプを格納します。</span><span class="sxs-lookup"><span data-stu-id="5083a-152">A <see cref="T:System.DateTimeOffset" /> containing the timestamp of the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity (Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity(class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WriteEntity : Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;&#xA;override this.WriteEntity : Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="tableEntity.WriteEntity operationContext" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.CosmosDB.Table.ITableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operationContext"><span data-ttu-id="5083a-153"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-153">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5083a-154">シリアル化、<see cref="T:System.Collections.Generic.IDictionary`2" />にマッピングされたプロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />これからのデータ値<see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="5083a-154">Serializes the <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names mapped to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values from this <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> instance.</span></span>
            </summary>
        <returns><span data-ttu-id="5083a-155"><see cref="T:System.Collections.Generic.IDictionary`2" />文字列プロパティにマップするオブジェクトの名前を<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />このテーブル エンティティ インスタンスをシリアル化によって作成された値を入力します。</span><span class="sxs-lookup"><span data-stu-id="5083a-155">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps string property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> typed values created by serializing this table entity instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteUserObject">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteUserObject (object entity, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteUserObject(object entity, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntity.WriteUserObject(System.Object,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member WriteUserObject : obj * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="Microsoft.Azure.CosmosDB.Table.TableEntity.WriteUserObject (entity, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity"><span data-ttu-id="5083a-156">シリアル化するエンティティ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-156">The entity object to serialize.</span></span></param>
        <param name="operationContext"><span data-ttu-id="5083a-157"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-157">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="5083a-158">作成、<see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-158">Create a <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all the properties of the specified entity object.</span></span>
            </summary>
        <returns><span data-ttu-id="5083a-159"><see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />指定されたエンティティ オブジェクトのすべてのプロパティのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5083a-159">An <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all the properties of the specified entity object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>