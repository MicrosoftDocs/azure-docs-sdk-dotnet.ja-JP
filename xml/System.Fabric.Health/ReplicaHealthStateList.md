<Type Name="ReplicaHealthStateList" FullName="System.Fabric.Health.ReplicaHealthStateList">
  <TypeSignature Language="C#" Value="public sealed class ReplicaHealthStateList : System.Collections.Generic.ICollection&lt;System.Fabric.Health.ReplicaHealthState&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Health.ReplicaHealthState&gt;, System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthState&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicaHealthStateList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Health.ReplicaHealthState&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Health.ReplicaHealthState&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ReplicaHealthState&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealthStateList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicaHealthStateList&#xA;Implements ICollection(Of ReplicaHealthState), IEnumerable(Of ReplicaHealthState), IList(Of ReplicaHealthState)" />
  <TypeSignature Language="F#" Value="type ReplicaHealthStateList = class&#xA;    interface IList&lt;ReplicaHealthState&gt;&#xA;    interface ICollection&lt;ReplicaHealthState&gt;&#xA;    interface seq&lt;ReplicaHealthState&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Health.ReplicaHealthState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Health.ReplicaHealthState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthState&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="68a24-101">コレクションを表します<see cref="T:System.Fabric.Health.ReplicaHealthState" />をインデックスによって個別にアクセスできることができます。</span><span class="sxs-lookup"><span data-stu-id="68a24-101">Represents a collection of <see cref="T:System.Fabric.Health.ReplicaHealthState" /> that can be individually accessed by index.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Health.ReplicaHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Health.ReplicaHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateList.Add(System.Fabric.Health.ReplicaHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ReplicaHealthState)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Health.ReplicaHealthState -&gt; unit&#xA;override this.Add : System.Fabric.Health.ReplicaHealthState -&gt; unit" Usage="replicaHealthStateList.Add item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Add(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Fabric.Health.ReplicaHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="68a24-102">追加する項目。</span><span class="sxs-lookup"><span data-stu-id="68a24-102">The item to add.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="68a24-103">項目をコレクションに追加します。</span><span class="sxs-lookup"><span data-stu-id="68a24-103">Adds an item to the collection.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="replicaHealthStateList.Clear " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Clear</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="68a24-104">コレクションからすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="68a24-104">Removes all items from the collection.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Health.ReplicaHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Health.ReplicaHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateList.Contains(System.Fabric.Health.ReplicaHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ReplicaHealthState) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Health.ReplicaHealthState -&gt; bool&#xA;override this.Contains : System.Fabric.Health.ReplicaHealthState -&gt; bool" Usage="replicaHealthStateList.Contains item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Contains(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Fabric.Health.ReplicaHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="68a24-105">コレクション内で検索する項目。</span><span class="sxs-lookup"><span data-stu-id="68a24-105">The item to locate in the collection.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="68a24-106">コレクションに特定の値が格納されているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="68a24-106">Determines whether the collection contains a specific value.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="68a24-107">返します<languageKeyword>true</languageKeyword>項目が見つかった場合<languageKeyword>false</languageKeyword>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="68a24-107">Returns <languageKeyword>true</languageKeyword> if the item is found; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Health.ReplicaHealthState[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Health.ReplicaHealthState[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateList.CopyTo(System.Fabric.Health.ReplicaHealthState[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ReplicaHealthState(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Health.ReplicaHealthState[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Health.ReplicaHealthState[] * int -&gt; unit" Usage="replicaHealthStateList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Health.ReplicaHealthState[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="68a24-108">ICollection から要素がコピーのコピー先である 1 次元配列。</span><span class="sxs-lookup"><span data-stu-id="68a24-108">The one-dimensional Array that is the destination of the elements copied from ICollection.</span></span> <span data-ttu-id="68a24-109">配列には、0 から始まるインデックスが設定されている必要があります。</span><span class="sxs-lookup"><span data-stu-id="68a24-109">The Array must have zero-based indexing.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="68a24-110">コピーの開始位置となる、配列の 0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="68a24-110">The zero-based index in array at which copying begins.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="68a24-111">特定の配列インデックスを開始位置として、配列に ICollection の要素をコピーします。</span><span class="sxs-lookup"><span data-stu-id="68a24-111">Copies the elements of the ICollection to an Array, starting at a particular Array index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStateList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Health.ReplicaHealthStateList.Count" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.Count</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="68a24-112">要素の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="68a24-112">Gets the number of elements.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="68a24-113">要素の数。</span><span class="sxs-lookup"><span data-stu-id="68a24-113">The number of elements.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ReplicaHealthState&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Health.ReplicaHealthState&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ReplicaHealthState)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ReplicaHealthState&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ReplicaHealthState&gt;" Usage="replicaHealthStateList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ReplicaHealthState&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="68a24-114">コレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="68a24-114">Returns an enumerator that iterates through a collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="68a24-115">返します<see cref="T:System.Collections.Generic.IEnumerator`1" />コレクションを反復処理するために使用できるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="68a24-115">Returns <see cref="T:System.Collections.Generic.IEnumerator`1" /> object that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Health.ReplicaHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Health.ReplicaHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateList.IndexOf(System.Fabric.Health.ReplicaHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ReplicaHealthState) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Health.ReplicaHealthState -&gt; int&#xA;override this.IndexOf : System.Fabric.Health.ReplicaHealthState -&gt; int" Usage="replicaHealthStateList.IndexOf item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.IndexOf(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Fabric.Health.ReplicaHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="68a24-116">コレクション内で検索する項目。</span><span class="sxs-lookup"><span data-stu-id="68a24-116">The item to locate in the collection.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="68a24-117">コレクション内の特定の項目のインデックスを決定します。</span><span class="sxs-lookup"><span data-stu-id="68a24-117">Determines the index of a specific item in the collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="68a24-118">返します<see cref="T:System.Int32" />; コレクションで見つかった場合は、項目のインデックスを表す場合は-1。</span><span class="sxs-lookup"><span data-stu-id="68a24-118">Returns <see cref="T:System.Int32" /> which represents the index of the item if found in the collection; -1 otherwise.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Health.ReplicaHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Health.ReplicaHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateList.Insert(System.Int32,System.Fabric.Health.ReplicaHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ReplicaHealthState)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Health.ReplicaHealthState -&gt; unit&#xA;override this.Insert : int * System.Fabric.Health.ReplicaHealthState -&gt; unit" Usage="replicaHealthStateList.Insert (index, item)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.Insert(System.Int32,`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="item" Type="System.Fabric.Health.ReplicaHealthState" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="68a24-119">値を挿入する位置を示す、0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="68a24-119">The zero-based index at which value should be inserted.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="68a24-120">挿入する項目。</span><span class="sxs-lookup"><span data-stu-id="68a24-120">The item to be inserted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="68a24-121">指定したインデックス位置に項目を挿入します。</span><span class="sxs-lookup"><span data-stu-id="68a24-121">Inserts an item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStateList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Health.ReplicaHealthStateList.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="68a24-122">リストが読み取り専用かどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="68a24-122">Gets a value indicating whether the list is read-only.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="68a24-123"><languageKeyword>true</languageKeyword>リストが読み取り専用、それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="68a24-123"><languageKeyword>true</languageKeyword> if the list is read-only; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ReplicaHealthState this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ReplicaHealthState Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStateList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ReplicaHealthState" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Health.ReplicaHealthState with get, set" Usage="System.Fabric.Health.ReplicaHealthStateList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ReplicaHealthState</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="68a24-124">取得または設定する要素の、0 から始まるインデックス番号。</span><span class="sxs-lookup"><span data-stu-id="68a24-124">The zero-based index of the element to get or set.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="68a24-125">指定したインデックスにある要素を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="68a24-125">Gets or sets the element at the specified index.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="68a24-126">返します<see cref="T:System.Fabric.Health.ReplicaHealthState" />指定したインデックス位置。</span><span class="sxs-lookup"><span data-stu-id="68a24-126">Returns <see cref="T:System.Fabric.Health.ReplicaHealthState" /> at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Health.ReplicaHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Health.ReplicaHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateList.Remove(System.Fabric.Health.ReplicaHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ReplicaHealthState) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Health.ReplicaHealthState -&gt; bool&#xA;override this.Remove : System.Fabric.Health.ReplicaHealthState -&gt; bool" Usage="replicaHealthStateList.Remove item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Fabric.Health.ReplicaHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="68a24-127">削除する項目。</span><span class="sxs-lookup"><span data-stu-id="68a24-127">The item to be removed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="68a24-128">コレクションから、最初に見つかった特定の項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="68a24-128">Removes the first occurrence of a specific item from the collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="68a24-129">返します<languageKeyword>true</languageKeyword>項目が削除された場合<languageKeyword>false</languageKeyword>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="68a24-129">Returns <languageKeyword>true</languageKeyword> if the item was removed; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="replicaHealthStateList.RemoveAt index" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IList`1.RemoveAt(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="68a24-130">削除する項目の 0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="68a24-130">The zero-based index of the item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="68a24-131">指定したインデックスにある項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="68a24-131">Removes the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateList.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="68a24-132">コレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="68a24-132">Returns an enumerator that iterates through a collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="68a24-133">返します<see cref="T:System.Collections.IEnumerator" />コレクションを反復処理するために使用できるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="68a24-133">Returns <see cref="T:System.Collections.IEnumerator" /> object that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>