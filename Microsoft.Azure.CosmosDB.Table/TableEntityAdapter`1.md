<Type Name="TableEntityAdapter&lt;T&gt;" FullName="Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class TableEntityAdapter&lt;T&gt; : Microsoft.Azure.CosmosDB.Table.TableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableEntityAdapter`1&lt;T&gt; extends Microsoft.Azure.CosmosDB.Table.TableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" />
  <TypeSignature Language="VB.NET" Value="Public Class TableEntityAdapter(Of T)&#xA;Inherits TableEntity" />
  <TypeSignature Language="F#" Value="type TableEntityAdapter&lt;'T&gt; = class&#xA;    inherit TableEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.CosmosDB.Table.TableEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T"><span data-ttu-id="7c435-101">読み書きを Azure テーブル ストレージでは、クラスまたは構造体を使用できますのオブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="7c435-101">The type of object to read and write to Azure Table Storage, it can be a class or a struct.</span></span></typeparam>
    <summary>
            <span data-ttu-id="7c435-102">読み取りとから継承せず、オブジェクトを Azure テーブル ストレージに書き込みを許可するアダプター クラス<see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" />クラスの実装または<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="7c435-102">Adapter class to allow reading and writing objects to Azure Table Storage without inheriting from <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> class or implementing <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> interface.</span></span> <span data-ttu-id="7c435-103">オブジェクトには、単純な POCO オブジェクトまたは入れ子になった複雑なプロパティを含む複合オブジェクトを指定できます。</span><span class="sxs-lookup"><span data-stu-id="7c435-103">The objects can be simple POCO objects or complex objects with nested complex properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.#ctor" />
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
            <span data-ttu-id="7c435-104"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7c435-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter (T originalEntity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T originalEntity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (originalEntity As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; : 'T -&gt; Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt;" Usage="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; originalEntity" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="originalEntity" Type="T" />
      </Parameters>
      <Docs>
        <param name="originalEntity"><span data-ttu-id="7c435-105">Azure テーブル ストレージに書き込むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7c435-105">The object to write to Azure Table Storage.</span></span></param>
        <summary>
            <span data-ttu-id="7c435-106">指定されたオブジェクトで <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7c435-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" /> class with the specified object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter (T originalEntity, string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T originalEntity, string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.#ctor(`0,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (originalEntity As T, partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; : 'T * string * string -&gt; Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt;" Usage="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; (originalEntity, partitionKey, rowKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="originalEntity" Type="T" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originalEntity"><span data-ttu-id="7c435-107">Azure テーブル ストレージに書き込むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7c435-107">The object to write to Azure Table Storage.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="7c435-108">エンティティのパーティション キー値を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="7c435-108">A string containing the partition key value for the entity.</span></span></param>
        <param name="rowKey"><span data-ttu-id="7c435-109">エンティティの行のキー値を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="7c435-109">A string containing the row key value for the entity.</span></span></param>
        <summary>
            <span data-ttu-id="7c435-110">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" />指定したオブジェクト、パーティション キーと行キーを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="7c435-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" /> class with the specified object, partition key and row key.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginalEntity">
      <MemberSignature Language="C#" Value="public T OriginalEntity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T OriginalEntity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginalEntity As T" />
      <MemberSignature Language="F#" Value="member this.OriginalEntity : 'T with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt;.OriginalEntity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c435-111">読み取りし、書き込みは azure テーブル ストレージにある元のエンティティです。</span><span class="sxs-lookup"><span data-stu-id="7c435-111">The original entity that is read and written to azure table storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public override void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="tableEntityAdapter.ReadEntity (properties, operationContext)" />
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
        <param name="properties"><span data-ttu-id="7c435-112"><see cref="T:System.Collections.Generic.IDictionary`2" />プロパティをマップするオブジェクト名を入力して<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />値。</span><span class="sxs-lookup"><span data-stu-id="7c435-112">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps property names to typed <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> values.</span></span></param>
        <param name="operationContext"><span data-ttu-id="7c435-113"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7c435-113">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="7c435-114">逆シリアル化<see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" />インスタンスの指定を使用して<see cref="T:System.Collections.Generic.IDictionary`2" />のプロパティ名をマップする、<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />に型指定された<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />、値に格納、<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="7c435-114">Deserializes <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" /> instance using the specified <see cref="T:System.Collections.Generic.IDictionary`2" /> that maps property names of the <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> to typed <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> values and stores it in the <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> property.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity (Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity(class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.WriteEntity : Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="tableEntityAdapter.WriteEntity operationContext" />
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
        <param name="operationContext"><span data-ttu-id="7c435-115"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7c435-115">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="7c435-116">シリアル化、<see cref="T:System.Collections.Generic.IDictionary`2" />にマッピングされたプロパティ名の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />データ値から、<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="7c435-116">Serializes the <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names mapped to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> data values from the <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> property.</span></span>
            </summary>
        <returns><span data-ttu-id="7c435-117"><see cref="T:System.Collections.Generic.IDictionary`2" />文字列プロパティにマップするオブジェクトの名前を<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />このテーブル エンティティ インスタンスをシリアル化によって作成された値を入力します。</span><span class="sxs-lookup"><span data-stu-id="7c435-117">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object that maps string property names to <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> typed values created by serializing this table entity instance.</span></span></returns>
        <remarks><span data-ttu-id="7c435-118">場合<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />単純なプロパティ (プリミティブ型、string, byte[],...) を持つ単純な POCO オブジェクト<see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />メソッドは、作成<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />オブジェクトをこれらのプロパティを使用します。</span><span class="sxs-lookup"><span data-stu-id="7c435-118">If <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> is a simple POCO object with simple properties (primitive types, string, byte[], ...), <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> method will create <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects using these properties.</span></span><br />
             <span data-ttu-id="7c435-119">Ie です。</span><span class="sxs-lookup"><span data-stu-id="7c435-119">Ie.</span></span> <span data-ttu-id="7c435-120">使用して、単純な POCO オブジェクト A B および C のプロパティを持つこの構造体 A -&gt;B、A-&gt;{"B", EntityProperty(B)} のキー値のペアに変換される C, {"C", EntityProperty(C)}。</span><span class="sxs-lookup"><span data-stu-id="7c435-120">A simple POCO object A with properties of B and C with this structure A-&gt;B, A-&gt;C, will be converted to key value pairs of {"B", EntityProperty(B)}, {"C", EntityProperty(C)}.</span></span><br />
            <span data-ttu-id="7c435-121">場合<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />複雑なプロパティ (および可能性のある独自の複雑なプロパティを持つこれらのプロパティ) を持つ<see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />メソッドが平坦化<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />最初。</span><span class="sxs-lookup"><span data-stu-id="7c435-121">If <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> has complex properties (and potentially these properties having complex properties of their own), <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> method will flatten <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> first.</span></span><br />
            <span data-ttu-id="7c435-122">Ie です。</span><span class="sxs-lookup"><span data-stu-id="7c435-122">Ie.</span></span> <span data-ttu-id="7c435-123">B の単純なプロパティと、この構造では A - E と F の独自のプロパティである必要が C および D の複雑なプロパティを持つオブジェクト A&gt;B、A -&gt;C -&gt;E と A -&gt;d-&gt;F はキーの値をフラット化します。ペア。</span><span class="sxs-lookup"><span data-stu-id="7c435-123">An object A with a simple property of B and complex properties of C and D which have their own properties of E and F with this structure A-&gt;B, A-&gt;C-&gt;E and A-&gt;D-&gt;F, will be flattened to key value pairs of:</span></span><br />
            <span data-ttu-id="7c435-124">{"B", EntityProperty(B)}、{"C_E", EntityProperty(E)} と {"D_F"、EntityProperty(F)}。</span><span class="sxs-lookup"><span data-stu-id="7c435-124">{"B", EntityProperty(B)}, {"C_E", EntityProperty(E)} and {"D_F", EntityProperty(F)}.</span></span><br />
            <span data-ttu-id="7c435-125">キーの値のペアごとに。</span><span class="sxs-lookup"><span data-stu-id="7c435-125">For each key value pair:</span></span><br />
            1. <span data-ttu-id="7c435-126">「_」で区切られた最後のノード プロパティ (E または F) に、ルート (A) からアクセスしたプロパティの名前を追加することによって構成されます。</span><span class="sxs-lookup"><span data-stu-id="7c435-126">The key is composed by appending the names of the properties visited from root (A) to end node property (E or F) delimited by "_".</span></span><br />
            2. <span data-ttu-id="7c435-127">値が、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />オブジェクト、最後のノード プロパティの値によってインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="7c435-127">The value is the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> object, instantiated by the value of the end node property.</span></span><br />
            <span data-ttu-id="7c435-128">すべてのキー値のペアが格納される、返された<see cref="T:System.Collections.Generic.IDictionary`2" />です。</span><span class="sxs-lookup"><span data-stu-id="7c435-128">All key value pairs will be stored in the returned <see cref="T:System.Collections.Generic.IDictionary`2" />.</span></span><br /><span data-ttu-id="7c435-129"><see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />メソッドは、元 (POCO または複合型) を使用してオブジェクトを recomposes、<see cref="T:System.Collections.Generic.IDictionary`2" />格納して、このメソッドによって返される<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="7c435-129"><see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" /> method recomposes the original object (POCO or complex) using the <see cref="T:System.Collections.Generic.IDictionary`2" /> returned by this method and store it in <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> property.</span></span><br />
            <span data-ttu-id="7c435-130">マークされたプロパティ<see cref="T:Microsoft.Azure.CosmosDB.Table.IgnorePropertyAttribute" />で、<see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />オブジェクトは無視され、このメソッドでは処理されません。</span><span class="sxs-lookup"><span data-stu-id="7c435-130">Properties that are marked with <see cref="T:Microsoft.Azure.CosmosDB.Table.IgnorePropertyAttribute" /> in the <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> object will be ignored and not processed by this method.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>