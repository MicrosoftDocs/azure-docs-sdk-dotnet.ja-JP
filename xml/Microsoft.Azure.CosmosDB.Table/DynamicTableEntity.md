<Type Name="DynamicTableEntity" FullName="Microsoft.Azure.CosmosDB.Table.DynamicTableEntity">
  <TypeSignature Language="C#" Value="public sealed class DynamicTableEntity : Microsoft.Azure.CosmosDB.Table.ITableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DynamicTableEntity extends System.Object implements class Microsoft.Azure.CosmosDB.Table.ITableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DynamicTableEntity&#xA;Implements ITableEntity" />
  <TypeSignature Language="F#" Value="type DynamicTableEntity = class&#xA;    interface ITableEntity" />
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
            <span data-ttu-id="43ba8-101">A<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />呼び出し元のエンティティのプロパティ マップに直接アクセスを許可する型。</span><span class="sxs-lookup"><span data-stu-id="43ba8-101">A <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> type which allows callers direct access to the property map of the entity.</span></span> <span data-ttu-id="43ba8-102">このクラスは、シリアル化と逆シリアル化のリフレクションの使用を排除します。</span><span class="sxs-lookup"><span data-stu-id="43ba8-102">This class eliminates the use of reflection for serialization and deserialization.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicTableEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.#ctor" />
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
            <span data-ttu-id="43ba8-103"><see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="43ba8-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicTableEntity (string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.DynamicTableEntity : string * string -&gt; Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" Usage="new Microsoft.Azure.CosmosDB.Table.DynamicTableEntity (partitionKey, rowKey)" />
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
        <param name="partitionKey"><span data-ttu-id="43ba8-104">エンティティのパーティション キー値を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="43ba8-104">A string containing the partition key value for the entity.</span></span></param>
        <param name="rowKey"><span data-ttu-id="43ba8-105">エンティティの行のキー値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="43ba8-105">A string containing the row key value for the entity.</span></span></param>
        <summary>
            <span data-ttu-id="43ba8-106">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />指定されたパーティション キーと行キーを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="43ba8-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> class with the specified partition key and row key.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicTableEntity (string partitionKey, string rowKey, string etag, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKey, string rowKey, string etag, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.#ctor(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As String, rowKey As String, etag As String, properties As IDictionary(Of String, EntityProperty))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.DynamicTableEntity : string * string * string * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; -&gt; Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" Usage="new Microsoft.Azure.CosmosDB.Table.DynamicTableEntity (partitionKey, rowKey, etag, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="43ba8-107">エンティティのパーティション キー値を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="43ba8-107">A string containing the partition key value for the entity.</span></span></param>
        <param name="rowKey"><span data-ttu-id="43ba8-108">エンティティの行のキー値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="43ba8-108">A string containing the row key value for the entity.</span></span></param>
        <param name="etag"><span data-ttu-id="43ba8-109">エンティティの ETag を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="43ba8-109">A string containing the ETag for the entity.</span></span></param>
        <param name="properties"><span data-ttu-id="43ba8-110"><see cref="T:System.Collections.Generic.IDictionary`2" />エンティティのプロパティ、プロパティ名でインデックスを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="43ba8-110">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the entity's properties, indexed by property name.</span></span></param>
        <summary>
            <span data-ttu-id="43ba8-111">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />エンティティのパーティション キー、行キー、ETag (使用可能または必要な) 場合、およびプロパティを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="43ba8-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> class with the entity's partition key, row key, ETag (if available/required), and properties.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.ETag" />
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
            <span data-ttu-id="43ba8-112">取得またはエンティティの現在の ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="43ba8-112">Gets or sets the entity's current ETag.</span></span>
            </summary>
        <value><span data-ttu-id="43ba8-113">エンティティの ETag を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="43ba8-113">A string containing the ETag for the entity.</span></span></value>
        <remarks><span data-ttu-id="43ba8-114">この値を設定 ' \*' を更新操作の一部としてエンティティを無条件で上書きします。</span><span class="sxs-lookup"><span data-stu-id="43ba8-114">Set this value to '\*' to blindly overwrite an entity as part of an update operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.EntityProperty this[string key] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.EntityProperty Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(key As String) As EntityProperty" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.Azure.CosmosDB.Table.EntityProperty with get, set" Usage="Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.EntityProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="43ba8-115">プロパティの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="43ba8-115">A string containing the name of the property.</span></span></param>
        <summary>
            <span data-ttu-id="43ba8-116">取得またはプロパティの名前を指定されたエンティティのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="43ba8-116">Gets or sets the entity's property, given the name of the property.</span></span>
            </summary>
        <value><span data-ttu-id="43ba8-117"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="43ba8-117">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.PartitionKey" />
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
            <span data-ttu-id="43ba8-118">取得またはエンティティのパーティション キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="43ba8-118">Gets or sets the entity's partition key.</span></span>
            </summary>
        <value><span data-ttu-id="43ba8-119">エンティティのパーティション キー値を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="43ba8-119">A string containing the partition key value for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As IDictionary(Of String, EntityProperty)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="43ba8-120">取得またはプロパティ名でインデックス付けされた、テーブル エンティティのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="43ba8-120">Gets or sets the properties in the table entity, indexed by property name.</span></span>
            </summary>
        <value><span data-ttu-id="43ba8-121"><see cref="T:System.Collections.Generic.IDictionary`2" />エンティティのプロパティを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="43ba8-121">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the entity's properties.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit&#xA;override this.ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="dynamicTableEntity.ReadEntity (properties, operationContext)" />
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
        <param name="properties"><span data-ttu-id="43ba8-122">含むコレクション、<see cref="T:System.Collections.Generic.IDictionary`2" />型の値にマップされている文字列プロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />これに格納する<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="43ba8-122">A collection containing the <see cref="T:System.Collections.Generic.IDictionary`2" /> of string property names mapped to values of type <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> to store in this <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> instance.</span></span></param>
        <param name="operationContext"><span data-ttu-id="43ba8-123"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="43ba8-123">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="43ba8-124">これを逆シリアル化<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />インスタンスの指定を使用して<see cref="T:System.Collections.Generic.IDictionary`2" />型の値にプロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />します。</span><span class="sxs-lookup"><span data-stu-id="43ba8-124">Deserializes this <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> instance using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names to values of type <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />.</span></span>
            </summary>
        <remarks><span data-ttu-id="43ba8-125">この API に渡されたプロパティ ディクショナリはコピーではなく、参照として内部的に格納されます。</span><span class="sxs-lookup"><span data-stu-id="43ba8-125">The properties dictionary passed to this API is stored internally as a reference, not a copy.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.RowKey" />
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
            <span data-ttu-id="43ba8-126">取得またはエンティティの行キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="43ba8-126">Gets or sets the entity's row key.</span></span>
            </summary>
        <value><span data-ttu-id="43ba8-127">エンティティの行のキー値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="43ba8-127">A string containing the row key value for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.Timestamp" />
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
            <span data-ttu-id="43ba8-128">取得またはエンティティのタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="43ba8-128">Gets or sets the entity's timestamp.</span></span>
            </summary>
        <value><span data-ttu-id="43ba8-129">A<see cref="T:System.DateTimeOffset" />エンティティのタイムスタンプを表すです。</span><span class="sxs-lookup"><span data-stu-id="43ba8-129">A <see cref="T:System.DateTimeOffset" /> containing the timestamp for the entity.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity (Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity(class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WriteEntity : Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;&#xA;override this.WriteEntity : Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="dynamicTableEntity.WriteEntity operationContext" />
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
        <param name="operationContext"><span data-ttu-id="43ba8-130"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="43ba8-130">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="43ba8-131">シリアル化、<see cref="T:System.Collections.Generic.IDictionary`2" />型の値にマッピングされたプロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />これから<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="43ba8-131">Serializes the <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names mapped to values of type <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> from this <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> instance.</span></span>
            </summary>
        <returns><span data-ttu-id="43ba8-132"><see cref="T:System.Collections.Generic.IDictionary`2" />オブジェクト型の値に文字列プロパティ名のマップを含む<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />これに格納されている<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="43ba8-132">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the map of string property names to values of type <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> stored in this <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>