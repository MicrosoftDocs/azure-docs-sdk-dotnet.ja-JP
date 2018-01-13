<Type Name="RepairTaskList" FullName="System.Fabric.Repair.RepairTaskList">
  <TypeSignature Language="C#" Value="public sealed class RepairTaskList : System.Collections.Generic.ICollection&lt;System.Fabric.Repair.RepairTask&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Repair.RepairTask&gt;, System.Collections.Generic.IList&lt;System.Fabric.Repair.RepairTask&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RepairTaskList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Repair.RepairTask&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Repair.RepairTask&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Repair.RepairTask&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.RepairTaskList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RepairTaskList&#xA;Implements ICollection(Of RepairTask), IEnumerable(Of RepairTask), IList(Of RepairTask)" />
  <TypeSignature Language="F#" Value="type RepairTaskList = class&#xA;    interface IList&lt;RepairTask&gt;&#xA;    interface ICollection&lt;RepairTask&gt;&#xA;    interface seq&lt;RepairTask&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Repair.RepairTask&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Repair.RepairTask&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Repair.RepairTask&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="aeb2b-101">リストを表します<see cref="T:System.Fabric.Repair.RepairTask" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-101">Represents a list of <see cref="T:System.Fabric.Repair.RepairTask" /> objects.</span></span></para>
      <para><span data-ttu-id="aeb2b-102">このクラスは、Service Fabric プラットフォームをサポートしていますコードから直接呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-102">This class supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Repair.RepairTask item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Repair.RepairTask item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.Add(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As RepairTask)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Repair.RepairTask -&gt; unit&#xA;override this.Add : System.Fabric.Repair.RepairTask -&gt; unit" Usage="repairTaskList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="aeb2b-103">リストに追加するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-103">The object to add to the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="aeb2b-104"><see cref="T:System.Fabric.Repair.RepairTaskList" /> に項目を追加します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-104">Adds an item to the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="repairTaskList.Clear " />
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
          <para><span data-ttu-id="aeb2b-105"><see cref="T:System.Fabric.Repair.RepairTaskList" /> からすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-105">Removes all items from the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Repair.RepairTask item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Repair.RepairTask item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.Contains(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As RepairTask) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Repair.RepairTask -&gt; bool&#xA;override this.Contains : System.Fabric.Repair.RepairTask -&gt; bool" Usage="repairTaskList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="aeb2b-106">リスト内で検索するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-106">The object to locate in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="aeb2b-107"><see cref="T:System.Fabric.Repair.RepairTaskList" /> に指定の値が含まれているかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-107">Determines whether the <see cref="T:System.Fabric.Repair.RepairTaskList" /> contains a specific value.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="aeb2b-108"><languageKeyword>true</languageKeyword>場合、<see cref="T:System.Fabric.Repair.RepairTaskList" />特定の値が含まれています。 それ以外の場合、 <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-108"><languageKeyword>true</languageKeyword> if the <see cref="T:System.Fabric.Repair.RepairTaskList" /> contains a specific value; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Repair.RepairTask[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Repair.RepairTask[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.CopyTo(System.Fabric.Repair.RepairTask[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As RepairTask(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Repair.RepairTask[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Repair.RepairTask[] * int -&gt; unit" Usage="repairTaskList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Repair.RepairTask[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="aeb2b-109">コピーされた要素のコピー先である 1 次元配列<see cref="T:System.Fabric.Repair.RepairTaskList" />です。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-109">The one-dimensional Array that is the destination of elements copied from <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span> <span data-ttu-id="aeb2b-110">配列には、0 から始まるインデックスが設定されている必要があります。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-110">The Array must have zero-based indexing.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="aeb2b-111">コピーの開始位置となる、配列の 0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-111">The zero-based index in array at which copying begins.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="aeb2b-112">特定の配列インデックスを開始位置として、配列に <see cref="T:System.Fabric.Repair.RepairTaskList" /> の要素をコピーします。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-112">Copies the elements of the <see cref="T:System.Fabric.Repair.RepairTaskList" /> to an Array, starting at a particular Array index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTaskList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Repair.RepairTaskList.Count" />
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
          <para><span data-ttu-id="aeb2b-113"><see cref="T:System.Fabric.Repair.RepairTaskList" /> に格納されている要素の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-113">Gets the number of elements contained in the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="aeb2b-114"><see cref="T:System.Fabric.Repair.RepairTaskList" /> に含まれている要素の数。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-114">The number of elements contained in the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Repair.RepairTask&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Repair.RepairTask&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of RepairTask)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Repair.RepairTask&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Repair.RepairTask&gt;" Usage="repairTaskList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Repair.RepairTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="aeb2b-115">コレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-115">Returns an enumerator that iterates through the collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="aeb2b-116">コレクションの反復処理に使用できる列挙子。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-116">An enumerator that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Repair.RepairTask item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Repair.RepairTask item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.IndexOf(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As RepairTask) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Repair.RepairTask -&gt; int&#xA;override this.IndexOf : System.Fabric.Repair.RepairTask -&gt; int" Usage="repairTaskList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="aeb2b-117">リスト内で検索するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-117">The object to locate in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="aeb2b-118"><see cref="T:System.Fabric.Repair.RepairTaskList" /> 内の特定の項目のインデックスを確認します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-118">Determines the index of a specific item in the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="aeb2b-119">項目のインデックス場合; 一覧にありませんそれ以外の場合、-1 を返します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-119">The index of item if found in the list; otherwise, -1.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Repair.RepairTask item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Repair.RepairTask item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.Insert(System.Int32,System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As RepairTask)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Repair.RepairTask -&gt; unit&#xA;override this.Insert : int * System.Fabric.Repair.RepairTask -&gt; unit" Usage="repairTaskList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="aeb2b-120">項目を挿入する位置の、0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-120">The zero-based index at which item should be inserted.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="aeb2b-121">リストに挿入するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-121">The object to insert into the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="aeb2b-122">指定したインデックスの <see cref="T:System.Fabric.Repair.RepairTaskList" /> に項目を挿入します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-122">Inserts an item to the <see cref="T:System.Fabric.Repair.RepairTaskList" /> at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTaskList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Repair.RepairTaskList.IsReadOnly" />
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
          <para><span data-ttu-id="aeb2b-123"><see cref="T:System.Fabric.Repair.RepairTaskList" /> が読み取り専用であるかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-123">Gets a value indicating whether the <see cref="T:System.Fabric.Repair.RepairTaskList" /> is read-only.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="aeb2b-124"><languageKeyword>true</languageKeyword>場合、<see cref="T:System.Fabric.Repair.RepairTaskList" />は読み取り専用です。 それ以外の場合、 <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-124"><languageKeyword>true</languageKeyword> if the <see cref="T:System.Fabric.Repair.RepairTaskList" /> is read-only; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.RepairTask this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Repair.RepairTask Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.RepairTaskList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As RepairTask" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Repair.RepairTask with get, set" Usage="System.Fabric.Repair.RepairTaskList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTask</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="aeb2b-125">取得または設定する要素の、0 から始まるインデックス番号。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-125">The zero-based index of the element to get or set.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="aeb2b-126">指定したインデックスにある要素を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-126">Gets or sets the element at the specified index.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="aeb2b-127">指定したインデックス位置にある要素。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-127">The element at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Repair.RepairTask item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Repair.RepairTask item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.Remove(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As RepairTask) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Repair.RepairTask -&gt; bool&#xA;override this.Remove : System.Fabric.Repair.RepairTask -&gt; bool" Usage="repairTaskList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="aeb2b-128">リストから削除するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-128">The object to remove from the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="aeb2b-129">特定のオブジェクトが <see cref="T:System.Fabric.Repair.RepairTaskList" /> 内にあるときに、最初に出現したものを削除します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-129">Removes the first occurrence of a specific object from the <see cref="T:System.Fabric.Repair.RepairTaskList" />.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="aeb2b-130"><languageKeyword>true</languageKeyword>した項目が正常に一覧から削除された、それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-130"><languageKeyword>true</languageKeyword> if the item was successfully removed from the list; otherwise, <languageKeyword>false</languageKeyword>.</span></span> <span data-ttu-id="aeb2b-131">このメソッドも、元のリストに項目が見つからない場合は false を返します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-131">This method also returns false if item is not found in the original list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="repairTaskList.RemoveAt index" />
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
          <para><span data-ttu-id="aeb2b-132">削除する項目の 0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-132">The zero-based index of the item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="aeb2b-133">指定したインデックスにある項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-133">Removes the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.RepairTaskList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para><span data-ttu-id="aeb2b-134">コレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-134">Returns an enumerator that iterates through the collection.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="aeb2b-135">コレクションの反復処理に使用できる列挙子。</span><span class="sxs-lookup"><span data-stu-id="aeb2b-135">An enumerator that can be used to iterate through the collection.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>