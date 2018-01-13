<Type Name="SqlParameterCollection" FullName="Microsoft.Azure.Documents.SqlParameterCollection">
  <TypeSignature Language="C#" Value="public sealed class SqlParameterCollection : System.Collections.Generic.ICollection&lt;Microsoft.Azure.Documents.SqlParameter&gt;, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.SqlParameter&gt;, System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.SqlParameter&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SqlParameterCollection extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class Microsoft.Azure.Documents.SqlParameter&gt;, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Documents.SqlParameter&gt;, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Documents.SqlParameter&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.SqlParameterCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SqlParameterCollection&#xA;Implements ICollection(Of SqlParameter), IEnumerable(Of SqlParameter), IList(Of SqlParameter)" />
  <TypeSignature Language="F#" Value="type SqlParameterCollection = class&#xA;    interface IList&lt;SqlParameter&gt;&#xA;    interface ICollection&lt;SqlParameter&gt;&#xA;    interface seq&lt;SqlParameter&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;Microsoft.Azure.Documents.SqlParameter&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.SqlParameter&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;Microsoft.Azure.Documents.SqlParameter&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="40247-101">関連付けられているパラメーターのコレクションを表します<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />Cosmos DB の Azure サービスで使用するためです。</span><span class="sxs-lookup"><span data-stu-id="40247-101">Represents a collection of parameters associated with <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> for use in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlParameterCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="40247-102">Azure Cosmos DB サービスの SqlParameterCollection クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="40247-102">Initialize a new instance of the SqlParameterCollection class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlParameterCollection (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.SqlParameter&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Documents.SqlParameter&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Azure.Documents.SqlParameter})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (parameters As IEnumerable(Of SqlParameter))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SqlParameterCollection : seq&lt;Microsoft.Azure.Documents.SqlParameter&gt; -&gt; Microsoft.Azure.Documents.SqlParameterCollection" Usage="new Microsoft.Azure.Documents.SqlParameterCollection parameters" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="parameters" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.SqlParameter&gt;" />
      </Parameters>
      <Docs>
        <param name="parameters"><span data-ttu-id="40247-103">パラメーターのコレクション。</span><span class="sxs-lookup"><span data-stu-id="40247-103">The collection of parameters.</span></span></param>
        <summary>
            <span data-ttu-id="40247-104">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.SqlParameterCollection" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="40247-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.SqlParameterCollection" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (Microsoft.Azure.Documents.SqlParameter item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class Microsoft.Azure.Documents.SqlParameter item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.Add(Microsoft.Azure.Documents.SqlParameter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As SqlParameter)" />
      <MemberSignature Language="F#" Value="abstract member Add : Microsoft.Azure.Documents.SqlParameter -&gt; unit&#xA;override this.Add : Microsoft.Azure.Documents.SqlParameter -&gt; unit" Usage="sqlParameterCollection.Add item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Add(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.Azure.Documents.SqlParameter" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="40247-105">コレクションに追加する項目。</span><span class="sxs-lookup"><span data-stu-id="40247-105">The item to add to the collection.</span></span></param>
        <summary>
            <span data-ttu-id="40247-106">Azure Cosmos DB コレクションに項目を追加します。</span><span class="sxs-lookup"><span data-stu-id="40247-106">Adds an item to the Azure Cosmos DB collection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="sqlParameterCollection.Clear " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Clear</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="40247-107">Azure Cosmos DB コレクションからすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="40247-107">Removes all items from the Azure Cosmos DB collection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (Microsoft.Azure.Documents.SqlParameter item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class Microsoft.Azure.Documents.SqlParameter item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.Contains(Microsoft.Azure.Documents.SqlParameter)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As SqlParameter) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : Microsoft.Azure.Documents.SqlParameter -&gt; bool&#xA;override this.Contains : Microsoft.Azure.Documents.SqlParameter -&gt; bool" Usage="sqlParameterCollection.Contains item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Contains(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.Azure.Documents.SqlParameter" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="40247-108">検索する値。</span><span class="sxs-lookup"><span data-stu-id="40247-108">The value to search for.</span></span></param>
        <summary>
            <span data-ttu-id="40247-109">Azure Cosmos DB コレクションに特定の値が含まれているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="40247-109">Determines whether the Azure Cosmos DB collection contains a specific value.</span></span>
            </summary>
        <returns><span data-ttu-id="40247-110">コレクションには、特定の値が含まれている場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="40247-110">true if the collection contains a specific value; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (Microsoft.Azure.Documents.SqlParameter[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class Microsoft.Azure.Documents.SqlParameter[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.CopyTo(Microsoft.Azure.Documents.SqlParameter[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As SqlParameter(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : Microsoft.Azure.Documents.SqlParameter[] * int -&gt; unit&#xA;override this.CopyTo : Microsoft.Azure.Documents.SqlParameter[] * int -&gt; unit" Usage="sqlParameterCollection.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="Microsoft.Azure.Documents.SqlParameter[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array"><span data-ttu-id="40247-111">コピー先の配列。</span><span class="sxs-lookup"><span data-stu-id="40247-111">The array to copy into.</span></span></param>
        <param name="arrayIndex"><span data-ttu-id="40247-112">要素の追加を開始するインデックスの配列内の位置。</span><span class="sxs-lookup"><span data-stu-id="40247-112">The location in the index array in which to start adding elements.</span></span></param>
        <summary>
            <span data-ttu-id="40247-113">Azure Cosmos DB コレクションの要素をコピー、<see cref="T:System.Array" />特定の開始、<see cref="T:System.Array" />インデックス。</span><span class="sxs-lookup"><span data-stu-id="40247-113">Copies the elements of the Azure Cosmos DB collection to an <see cref="T:System.Array" />, starting at a particular <see cref="T:System.Array" /> index.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlParameterCollection.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.Azure.Documents.SqlParameterCollection.Count" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.Count</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40247-114">Azure Cosmos DB コレクションに含まれる要素の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="40247-114">Gets the number of elements contained in the Azure Cosmos DB collection.</span></span>
            </summary>
        <value><span data-ttu-id="40247-115">コレクションに格納されている要素の数。</span><span class="sxs-lookup"><span data-stu-id="40247-115">The number of elements contained in the collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Documents.SqlParameter&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.Azure.Documents.SqlParameter&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of SqlParameter)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Documents.SqlParameter&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Documents.SqlParameter&gt;" Usage="sqlParameterCollection.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.Documents.SqlParameter&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="40247-116">Azure Cosmos DB コレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="40247-116">Returns an enumerator that iterates through the Azure Cosmos DB collection.</span></span>
            </summary>
        <returns><span data-ttu-id="40247-117">コレクションの列挙子。</span><span class="sxs-lookup"><span data-stu-id="40247-117">An enumerator for the collection.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (Microsoft.Azure.Documents.SqlParameter item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class Microsoft.Azure.Documents.SqlParameter item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.IndexOf(Microsoft.Azure.Documents.SqlParameter)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As SqlParameter) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : Microsoft.Azure.Documents.SqlParameter -&gt; int&#xA;override this.IndexOf : Microsoft.Azure.Documents.SqlParameter -&gt; int" Usage="sqlParameterCollection.IndexOf item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.IndexOf(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.Azure.Documents.SqlParameter" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="40247-118">検索する項目。</span><span class="sxs-lookup"><span data-stu-id="40247-118">The item to find.</span></span></param>
        <summary>
            <span data-ttu-id="40247-119">Azure Cosmos DB コレクション内の特定の項目のインデックスを決定します。</span><span class="sxs-lookup"><span data-stu-id="40247-119">Determines the index of a specific item in the Azure Cosmos DB collection.</span></span>
            </summary>
        <returns><span data-ttu-id="40247-120">項目のインデックス値。</span><span class="sxs-lookup"><span data-stu-id="40247-120">The index value for the item.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, Microsoft.Azure.Documents.SqlParameter item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class Microsoft.Azure.Documents.SqlParameter item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.Insert(System.Int32,Microsoft.Azure.Documents.SqlParameter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As SqlParameter)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * Microsoft.Azure.Documents.SqlParameter -&gt; unit&#xA;override this.Insert : int * Microsoft.Azure.Documents.SqlParameter -&gt; unit" Usage="sqlParameterCollection.Insert (index, item)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.Insert(System.Int32,`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="item" Type="Microsoft.Azure.Documents.SqlParameter" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="40247-121">要素の挿入を開始するインデックスの配列内の位置。</span><span class="sxs-lookup"><span data-stu-id="40247-121">The location in the index array in which to start inserting elements.</span></span></param>
        <param name="item"><span data-ttu-id="40247-122">インデックスにコピーする項目。</span><span class="sxs-lookup"><span data-stu-id="40247-122">The item to copy into the index.</span></span></param>
        <summary>
            <span data-ttu-id="40247-123">Azure Cosmos DB コレクション内の指定したインデックス位置に項目を挿入します。</span><span class="sxs-lookup"><span data-stu-id="40247-123">Inserts an item at the specified index in the Azure Cosmos DB collection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlParameterCollection.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.Azure.Documents.SqlParameterCollection.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="40247-124">Azure Cosmos DB コレクションは読み取り専用であるかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="40247-124">Gets a value indicating whether the Azure Cosmos DB collection is read-only.</span></span>
            </summary>
        <value><span data-ttu-id="40247-125">コレクションが読み取り専用である場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="40247-125">true if the collection is read-only; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.SqlParameter this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.SqlParameter Item(int32)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlParameterCollection.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As SqlParameter" />
      <MemberSignature Language="F#" Value="member this.Item(int) : Microsoft.Azure.Documents.SqlParameter with get, set" Usage="Microsoft.Azure.Documents.SqlParameterCollection.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.SqlParameter</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="40247-126">インデックス内の位置。</span><span class="sxs-lookup"><span data-stu-id="40247-126">The location in the index.</span></span></param>
        <summary>
            <span data-ttu-id="40247-127">取得または Azure Cosmos DB コレクション内の指定したインデックス位置の要素を設定します。</span><span class="sxs-lookup"><span data-stu-id="40247-127">Gets or sets the element at the specified index in the Azure Cosmos DB collection.</span></span>
            </summary>
        <value><span data-ttu-id="40247-128">指定したインデックス位置にある要素。</span><span class="sxs-lookup"><span data-stu-id="40247-128">The element at the specified index.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (Microsoft.Azure.Documents.SqlParameter item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class Microsoft.Azure.Documents.SqlParameter item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.Remove(Microsoft.Azure.Documents.SqlParameter)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As SqlParameter) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : Microsoft.Azure.Documents.SqlParameter -&gt; bool&#xA;override this.Remove : Microsoft.Azure.Documents.SqlParameter -&gt; bool" Usage="sqlParameterCollection.Remove item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.Azure.Documents.SqlParameter" />
      </Parameters>
      <Docs>
        <param name="item">
            <span data-ttu-id="40247-129">コレクションから削除する項目。</span><span class="sxs-lookup"><span data-stu-id="40247-129">The item to remove from the collection.</span></span>
            </param>
        <summary>
            <span data-ttu-id="40247-130">Azure Cosmos DB コレクションから、最初に見つかった特定のオブジェクトを削除します。</span><span class="sxs-lookup"><span data-stu-id="40247-130">/// Removes the first occurrence of a specific object from the Azure Cosmos DB collection.</span></span>
            </summary>
        <returns><span data-ttu-id="40247-131">最初の項目が削除された場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="40247-131">true if the first item was removed; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="sqlParameterCollection.RemoveAt index" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.RemoveAt(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="40247-132">項目を削除、インデックス内の位置。</span><span class="sxs-lookup"><span data-stu-id="40247-132">The location in the index where the item will be removed from.</span></span></param>
        <summary>
            <span data-ttu-id="40247-133">Azure Cosmos DB コレクションから指定したインデックス位置にある項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="40247-133">Removes the item at the specified index from the Azure Cosmos DB collection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameterCollection.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="40247-134">Azure Cosmos DB コレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="40247-134">Returns an enumerator that iterates through the Azure Cosmos DB collection.</span></span>
            </summary>
        <returns><span data-ttu-id="40247-135">コレクションを反復処理する列挙子。</span><span class="sxs-lookup"><span data-stu-id="40247-135">An enumerator to iterate through the collection.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>