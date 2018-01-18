<Type Name="ITableEntity" FullName="Microsoft.Azure.CosmosDB.Table.ITableEntity">
  <TypeSignature Language="C#" Value="public interface ITableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITableEntity" />
  <TypeSignature Language="F#" Value="type ITableEntity = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7aeaa-101">テーブルのエンティティ型に必要なインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-101">An interface required for table entity types.</span></span> <span data-ttu-id="7aeaa-102"><see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />インターフェイスが、必須のエンティティのプロパティの getter および setter メソッドを宣言および<see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />と<see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />シリアル化と逆シリアル化、プロパティ ディクショナリを使用してすべてのエンティティのプロパティのメソッドです。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-102">The <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> interface declares getter and setter methods for the mandatory entity properties, and <see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" /> and <see cref="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> methods for serialization and de-serialization of all entity properties using a property dictionary.</span></span> <span data-ttu-id="7aeaa-103">実装するクラスを作成する<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />プロパティの格納、取得、シリアル化および逆シリアル化をカスタマイズして、テーブル エンティティの追加のカスタム ロジックを指定します。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-103">Create classes implementing <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> to customize property storage, retrieval, serialization and de-serialization, and to provide additional custom logic for a table entity.</span></span>
            </summary>
    <remarks>
      <para><span data-ttu-id="7aeaa-104">ストレージ クライアント ライブラリには 2 つの実装が含まれています<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />単純なプロパティ アクセスとシリアル化を提供します。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-104">The storage client library includes two implementations of <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> that provide for simple property access and serialization:</span></span></para>
      <para>
        <span data-ttu-id="7aeaa-105"><see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />実装する<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />し格納およびプロパティを取得する単純なプロパティ ディクショナリを提供します。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-105"><see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> implements <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> and provides a simple property dictionary to store and retrieve properties.</span></span> <span data-ttu-id="7aeaa-106">使用して、<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />簡単なアクセス プロパティのサブセットのみを返す場合 (たとえば、クエリの select 句) をエンティティのプロパティまたはシナリオは、クエリが異なるプロパティを持つ複数のエンティティ型を返すことができます。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-106">Use a <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> for simple access to entity properties when only a subset of properties are returned (for example, by a select clause in a query), or for scenarios where your query can return multiple entity types with different properties.</span></span> <span data-ttu-id="7aeaa-107">また、この種類を使用する、プロパティ情報を失うことがなく異種エンティティの一括テーブルの更新を実行することができます。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-107">You can also use this type to perform bulk table updates of heterogeneous entities without losing property information.</span></span></para>
      <para>
        <span data-ttu-id="7aeaa-108"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />実装は、<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />でシリアル化と逆シリアル化をリフレクション ベースで動作を使用するその<see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />と<see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-108"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> is an implementation of <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> that uses reflection-based serialization and de-serialization behavior in its <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" /> and <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> methods.</span></span> 
            <span data-ttu-id="7aeaa-109"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />派生クラスの型と名前付けをシリアル化して自動的に逆シリアル化の規則に従っているメソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-109"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />-derived classes with methods that follow a convention for types and naming are serialized and deserialized automatically.</span></span> <span data-ttu-id="7aeaa-110"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />-も、派生クラスは、Microsoft Azure テーブル サービスでサポートされている型の get と set に対応のパブリック プロパティを指定する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-110"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />-derived classes must also provide a get-able and set-able public property of a type that is supported by the Microsoft Azure Table service.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.ITableEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.ITableEntity.ETag" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="7aeaa-111">取得またはエンティティの現在の ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-111">Gets or sets the entity's current ETag.</span></span>  <span data-ttu-id="7aeaa-112">この値を ' \*'、更新操作の一部としてエンティティを無条件で上書きするためにします。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-112">Set this value to '\*' in order to blindly overwrite an entity as part of an update operation.</span></span>
            </summary>
        <value><span data-ttu-id="7aeaa-113">エンティティのタイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-113">The entity's timestamp.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.ITableEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.ITableEntity.PartitionKey" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="7aeaa-114">取得またはエンティティのパーティション キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-114">Gets or sets the entity's partition key.</span></span>
            </summary>
        <value><span data-ttu-id="7aeaa-115">エンティティのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-115">The entity's partition key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="iTableEntity.ReadEntity (properties, operationContext)" />
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
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="7aeaa-116">文字列プロパティ名の辞書<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データ値を逆シリアル化し、このテーブル エンティティ インスタンスに格納します。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-116">The dictionary of string property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values to deserialize and store in this table entity instance.</span></span></param>
        <param name="operationContext"><span data-ttu-id="7aeaa-117"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-117">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="7aeaa-118">エンティティのプロパティを設定、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />のデータ値が、<paramref name="properties" />ディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-118">Populates the entity's properties from the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values in the <paramref name="properties" /> dictionary.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.ITableEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.ITableEntity.RowKey" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="7aeaa-119">取得またはエンティティの行キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-119">Gets or sets the entity's row key.</span></span>
            </summary>
        <value><span data-ttu-id="7aeaa-120">エンティティの行キーです。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-120">The entity's row key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.ITableEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.Azure.CosmosDB.Table.ITableEntity.Timestamp" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="7aeaa-121">取得またはエンティティのタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-121">Gets or sets the entity's timestamp.</span></span>
            </summary>
        <value><span data-ttu-id="7aeaa-122">エンティティのタイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-122">The entity's timestamp.</span></span> <span data-ttu-id="7aeaa-123">プロパティは、Microsoft Azure テーブル サービスで設定されます。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-123">The property is populated by the Microsoft Azure Table Service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity (Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity(class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.ITableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WriteEntity : Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="iTableEntity.WriteEntity operationContext" />
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
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operationContext"><span data-ttu-id="7aeaa-124"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-124">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="7aeaa-125">シリアル化、<see cref="T:System.Collections.Generic.IDictionary`2" />にマッピングされたプロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />エンティティ インスタンスからのデータ値。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-125">Serializes the <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names mapped to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values from the entity instance.</span></span>
            </summary>
        <returns><span data-ttu-id="7aeaa-126"><see cref="T:System.Collections.Generic.IDictionary`2" />オブジェクトにプロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データは、このテーブル エンティティ インスタンスをシリアル化によって作成された値を入力します。</span><span class="sxs-lookup"><span data-stu-id="7aeaa-126">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object of property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data typed values created by serializing this table entity instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>