<Type Name="ApplicationHealthStateList" FullName="System.Fabric.Health.ApplicationHealthStateList">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthStateList : System.Collections.Generic.ICollection&lt;System.Fabric.Health.ApplicationHealthState&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Health.ApplicationHealthState&gt;, System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthState&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthStateList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Health.ApplicationHealthState&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Health.ApplicationHealthState&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ApplicationHealthState&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthStateList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthStateList&#xA;Implements ICollection(Of ApplicationHealthState), IEnumerable(Of ApplicationHealthState), IList(Of ApplicationHealthState)" />
  <TypeSignature Language="F#" Value="type ApplicationHealthStateList = class&#xA;    interface IList&lt;ApplicationHealthState&gt;&#xA;    interface ICollection&lt;ApplicationHealthState&gt;&#xA;    interface seq&lt;ApplicationHealthState&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Health.ApplicationHealthState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Health.ApplicationHealthState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthState&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="81fbf-101">コレクションを表します<see cref="T:System.Fabric.Health.ApplicationHealthState" />をインデックスによって個別にアクセスできることができます。</span><span class="sxs-lookup"><span data-stu-id="81fbf-101">Represents a collection of <see cref="T:System.Fabric.Health.ApplicationHealthState" /> that can be individually accessed by index.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Health.ApplicationHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Health.ApplicationHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateList.Add(System.Fabric.Health.ApplicationHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ApplicationHealthState)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Health.ApplicationHealthState -&gt; unit&#xA;override this.Add : System.Fabric.Health.ApplicationHealthState -&gt; unit" Usage="applicationHealthStateList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ApplicationHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="81fbf-102">追加する項目。</span><span class="sxs-lookup"><span data-stu-id="81fbf-102">The item to add.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="81fbf-103">項目をコレクションに追加します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-103">Adds an item to the collection.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="applicationHealthStateList.Clear " />
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
          <para><span data-ttu-id="81fbf-104">コレクションからすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-104">Removes all items from the collection.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Health.ApplicationHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Health.ApplicationHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateList.Contains(System.Fabric.Health.ApplicationHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ApplicationHealthState) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Health.ApplicationHealthState -&gt; bool&#xA;override this.Contains : System.Fabric.Health.ApplicationHealthState -&gt; bool" Usage="applicationHealthStateList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ApplicationHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="81fbf-105">コレクション内で検索する項目。</span><span class="sxs-lookup"><span data-stu-id="81fbf-105">The item to locate in the collection.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="81fbf-106">コレクションに特定の値が格納されているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-106">Determines whether the collection contains a specific value.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="81fbf-107"><languageKeyword>true</languageKeyword>項目が、それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="81fbf-107"><languageKeyword>true</languageKeyword> if the item is found; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Health.ApplicationHealthState[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Health.ApplicationHealthState[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateList.CopyTo(System.Fabric.Health.ApplicationHealthState[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ApplicationHealthState(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Health.ApplicationHealthState[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Health.ApplicationHealthState[] * int -&gt; unit" Usage="applicationHealthStateList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Health.ApplicationHealthState[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="81fbf-108">ICollection から要素がコピーのコピー先である 1 次元配列。</span><span class="sxs-lookup"><span data-stu-id="81fbf-108">The one-dimensional Array that is the destination of the elements copied from ICollection.</span></span> <span data-ttu-id="81fbf-109">配列には、0 から始まるインデックスが設定されている必要があります。</span><span class="sxs-lookup"><span data-stu-id="81fbf-109">The Array must have zero-based indexing.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="81fbf-110">コピーの開始位置となる、配列の 0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="81fbf-110">The zero-based index in array at which copying begins.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="81fbf-111">特定の配列インデックスを開始位置として、配列に ICollection の要素をコピーします。</span><span class="sxs-lookup"><span data-stu-id="81fbf-111">Copies the elements of the ICollection to an Array, starting at a particular Array index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Health.ApplicationHealthStateList.Count" />
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
          <para><span data-ttu-id="81fbf-112">要素の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-112">Gets the number of elements.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="81fbf-113"><see cref="T:System.Int32" />要素の数を表すです。</span><span class="sxs-lookup"><span data-stu-id="81fbf-113">The <see cref="T:System.Int32" /> representing the number of elements.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ApplicationHealthState&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Health.ApplicationHealthState&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ApplicationHealthState)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ApplicationHealthState&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ApplicationHealthState&gt;" Usage="applicationHealthStateList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ApplicationHealthState&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="81fbf-114">コレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-114">Returns an enumerator that iterates through a collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="81fbf-115"><see cref="T:System.Collections.Generic.IEnumerator`1" />コレクションを反復処理するために使用できるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="81fbf-115">The <see cref="T:System.Collections.Generic.IEnumerator`1" /> object that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Health.ApplicationHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Health.ApplicationHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateList.IndexOf(System.Fabric.Health.ApplicationHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ApplicationHealthState) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Health.ApplicationHealthState -&gt; int&#xA;override this.IndexOf : System.Fabric.Health.ApplicationHealthState -&gt; int" Usage="applicationHealthStateList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ApplicationHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="81fbf-116">コレクション内で検索する項目。</span><span class="sxs-lookup"><span data-stu-id="81fbf-116">The item to locate in the collection.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="81fbf-117">コレクション内の特定の項目のインデックスを決定します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-117">Determines the index of a specific item in the collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="81fbf-118"><see cref="T:System.Int32" />コレクション内で見つかった、それ以外の場合は、項目のインデックスを表す-1 です。</span><span class="sxs-lookup"><span data-stu-id="81fbf-118">An <see cref="T:System.Int32" /> which represents the index of the item if found in the collection; otherwise, -1.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Health.ApplicationHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Health.ApplicationHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateList.Insert(System.Int32,System.Fabric.Health.ApplicationHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ApplicationHealthState)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Health.ApplicationHealthState -&gt; unit&#xA;override this.Insert : int * System.Fabric.Health.ApplicationHealthState -&gt; unit" Usage="applicationHealthStateList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ApplicationHealthState" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="81fbf-119">値を挿入する位置を示す、0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="81fbf-119">The zero-based index at which value should be inserted.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="81fbf-120">挿入する項目。</span><span class="sxs-lookup"><span data-stu-id="81fbf-120">The item to be inserted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="81fbf-121">指定したインデックス位置に項目を挿入します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-121">Inserts an item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Health.ApplicationHealthStateList.IsReadOnly" />
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
          <para><span data-ttu-id="81fbf-122">リストが読み取り専用かどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-122">Gets a value indicating whether the list is read-only.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="81fbf-123"><languageKeyword>true</languageKeyword>のみです。 それ以外の場合、一覧を読み取る場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="81fbf-123"><languageKeyword>true</languageKeyword> if the list is read only; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthState this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthState Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ApplicationHealthState" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Health.ApplicationHealthState with get, set" Usage="System.Fabric.Health.ApplicationHealthStateList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthState</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="81fbf-124">取得または設定する要素の、0 から始まるインデックス番号。</span><span class="sxs-lookup"><span data-stu-id="81fbf-124">The zero-based index of the element to get or set.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="81fbf-125">指定したインデックスにある要素を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-125">Gets or sets the element at the specified index.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="81fbf-126">指定されたインデックス位置にある <see cref="T:System.Fabric.Health.ApplicationHealthState" />。</span><span class="sxs-lookup"><span data-stu-id="81fbf-126">The <see cref="T:System.Fabric.Health.ApplicationHealthState" /> at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Health.ApplicationHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Health.ApplicationHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateList.Remove(System.Fabric.Health.ApplicationHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ApplicationHealthState) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Health.ApplicationHealthState -&gt; bool&#xA;override this.Remove : System.Fabric.Health.ApplicationHealthState -&gt; bool" Usage="applicationHealthStateList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ApplicationHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="81fbf-127">削除する項目。</span><span class="sxs-lookup"><span data-stu-id="81fbf-127">The item to be removed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="81fbf-128">コレクションから、最初に見つかった特定の項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-128">Removes the first occurrence of a specific item from the collection.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="81fbf-129"><languageKeyword>true</languageKeyword>した項目が削除された、それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="81fbf-129"><languageKeyword>true</languageKeyword> if the item was removed; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="applicationHealthStateList.RemoveAt index" />
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
          <para><span data-ttu-id="81fbf-130">削除する項目の 0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="81fbf-130">The zero-based index of the item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="81fbf-131">指定したインデックスにある項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-131">Removes the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para><span data-ttu-id="81fbf-132">コレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="81fbf-132">Returns an enumerator that iterates through a collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="81fbf-133">コレクションを反復処理するために使用できる <see cref="T:System.Collections.IEnumerator" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="81fbf-133">An <see cref="T:System.Collections.IEnumerator" /> object that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>