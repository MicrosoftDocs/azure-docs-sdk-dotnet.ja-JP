<Type Name="ApplicationTypeList" FullName="System.Fabric.Query.ApplicationTypeList">
  <TypeSignature Language="C#" Value="public sealed class ApplicationTypeList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.ApplicationType&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ApplicationType&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.ApplicationType&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationTypeList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.ApplicationType&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.ApplicationType&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ApplicationType&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationTypeList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationTypeList&#xA;Implements ICollection(Of ApplicationType), IEnumerable(Of ApplicationType), IList(Of ApplicationType)" />
  <TypeSignature Language="F#" Value="type ApplicationTypeList = class&#xA;    interface IList&lt;ApplicationType&gt;&#xA;    interface ICollection&lt;ApplicationType&gt;&#xA;    interface seq&lt;ApplicationType&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.ApplicationType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ApplicationType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.ApplicationType&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="be50a-101">一覧を表す、<see cref="T:System.Fabric.Query.ApplicationType" />呼び出すことによって取得<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync(System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="be50a-101">Represents the list of the <see cref="T:System.Fabric.Query.ApplicationType" /> retrieved by calling <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync(System.String)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.ApplicationType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.ApplicationType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypeList.Add(System.Fabric.Query.ApplicationType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ApplicationType)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.ApplicationType -&gt; unit&#xA;override this.Add : System.Fabric.Query.ApplicationType -&gt; unit" Usage="applicationTypeList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ApplicationType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="be50a-102">一覧に追加する項目。</span><span class="sxs-lookup"><span data-stu-id="be50a-102">The item to add in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="be50a-103">この一覧に項目を追加します。</span><span class="sxs-lookup"><span data-stu-id="be50a-103">Adds an item to this list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypeList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="applicationTypeList.Clear " />
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
          <para><span data-ttu-id="be50a-104">このリストからすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="be50a-104">Removes all items from this list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.ApplicationType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.ApplicationType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypeList.Contains(System.Fabric.Query.ApplicationType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ApplicationType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.ApplicationType -&gt; bool&#xA;override this.Contains : System.Fabric.Query.ApplicationType -&gt; bool" Usage="applicationTypeList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ApplicationType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="be50a-105">一覧で指定された項目。</span><span class="sxs-lookup"><span data-stu-id="be50a-105">The specified item in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="be50a-106">指定した項目がリストの場合は true を返します。</span><span class="sxs-lookup"><span data-stu-id="be50a-106">Returns true if the specified item is in the list.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="be50a-107"><languageKeyword>true</languageKeyword>場合、指定した項目は一覧にあるそれ以外の場合、 <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="be50a-107"><languageKeyword>true</languageKeyword> if the specified item is in the list; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.ApplicationType[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.ApplicationType[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypeList.CopyTo(System.Fabric.Query.ApplicationType[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ApplicationType(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.ApplicationType[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.ApplicationType[] * int -&gt; unit" Usage="applicationTypeList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.ApplicationType[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="be50a-108">コピーされた要素のコピー先である 1 次元配列<see cref="T:System.Fabric.Query.ApplicationTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="be50a-108">The one-dimensional array that is the destination of elements copied from <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</span></span> <span data-ttu-id="be50a-109">配列には、0 から始まるインデックスが設定されている必要があります。</span><span class="sxs-lookup"><span data-stu-id="be50a-109">The array must have zero-based indexing.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="be50a-110">コピーの開始位置となる、配列の 0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="be50a-110">The zero-based index in array at which copying begins.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="be50a-111">この一覧から項目を指定したインデックスから始まる指定した配列にコピーします。</span><span class="sxs-lookup"><span data-stu-id="be50a-111">Copies items from this list to the specified array starting at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationTypeList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.ApplicationTypeList.Count" />
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
          <para><span data-ttu-id="be50a-112">この一覧の項目の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="be50a-112">Gets the number of items in this list.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="be50a-113">この一覧のアイテムの数。</span><span class="sxs-lookup"><span data-stu-id="be50a-113">The number of items in this list.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ApplicationType&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.ApplicationType&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypeList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ApplicationType)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ApplicationType&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ApplicationType&gt;" Usage="applicationTypeList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ApplicationType&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="be50a-114">この一覧の項目を列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="be50a-114">Returns an enumerator to items in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="be50a-115">この一覧の項目を列挙子。</span><span class="sxs-lookup"><span data-stu-id="be50a-115">An enumerator to items in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.ApplicationType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.ApplicationType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypeList.IndexOf(System.Fabric.Query.ApplicationType)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ApplicationType) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.ApplicationType -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.ApplicationType -&gt; int" Usage="applicationTypeList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ApplicationType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="be50a-116">一覧で指定された項目。</span><span class="sxs-lookup"><span data-stu-id="be50a-116">The specified item in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="be50a-117">この一覧に指定された項目のインデックスを返します。</span><span class="sxs-lookup"><span data-stu-id="be50a-117">Returns the index of the specified item in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="be50a-118">この一覧に指定した項目のインデックス。</span><span class="sxs-lookup"><span data-stu-id="be50a-118">The index of the specified item in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.ApplicationType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.ApplicationType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypeList.Insert(System.Int32,System.Fabric.Query.ApplicationType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ApplicationType)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.ApplicationType -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.ApplicationType -&gt; unit" Usage="applicationTypeList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ApplicationType" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="be50a-119">項目を挿入する位置の、0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="be50a-119">The zero-based index at which item should be inserted.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="be50a-120">リストに挿入するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="be50a-120">The object to insert into the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="be50a-121">指定したインデックス位置には、この一覧に項目を挿入します。</span><span class="sxs-lookup"><span data-stu-id="be50a-121">Inserts an item into this list at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationTypeList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.ApplicationTypeList.IsReadOnly" />
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
          <para><span data-ttu-id="be50a-122">取得または一覧は、このプロパティが false の場合にのみ変更するかどうかの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="be50a-122">Gets or sets a value whether the list can only be modified if this property is false.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="be50a-123"><languageKeyword>true</languageKeyword>一覧には、それ以外の変更のみを指定できる場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="be50a-123"><languageKeyword>true</languageKeyword> if the list can only be modified; otherwise <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationType this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ApplicationType Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationTypeList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ApplicationType" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.ApplicationType with get, set" Usage="System.Fabric.Query.ApplicationTypeList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="be50a-124">指定したインデックス。</span><span class="sxs-lookup"><span data-stu-id="be50a-124">The specified index.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="be50a-125">指定したインデックスにある項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="be50a-125">Gets the item at the specified index.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="be50a-126">指定したインデックスにある項目。</span><span class="sxs-lookup"><span data-stu-id="be50a-126">The item at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.ApplicationType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.ApplicationType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypeList.Remove(System.Fabric.Query.ApplicationType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ApplicationType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.ApplicationType -&gt; bool&#xA;override this.Remove : System.Fabric.Query.ApplicationType -&gt; bool" Usage="applicationTypeList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ApplicationType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="be50a-127">リストから削除するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="be50a-127">The object to remove from the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="be50a-128">指定した項目をリストから削除します。</span><span class="sxs-lookup"><span data-stu-id="be50a-128">Removes the specified item from the list.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="be50a-129"><languageKeyword>true</languageKeyword>した項目が正常に一覧から削除された、それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="be50a-129"><languageKeyword>true</languageKeyword> if the item was successfully removed from the list; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypeList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="applicationTypeList.RemoveAt index" />
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
          <para><span data-ttu-id="be50a-130">削除する項目の 0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="be50a-130">The zero-based index of the item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="be50a-131">一覧から指定したインデックス位置にある項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="be50a-131">Removes the item at the specified index from the list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypeList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para><span data-ttu-id="be50a-132">この一覧に項目を列挙子を取得します。</span><span class="sxs-lookup"><span data-stu-id="be50a-132">Gets an enumerator to items in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="be50a-133">この一覧の項目を列挙子。</span><span class="sxs-lookup"><span data-stu-id="be50a-133">An enumerator to items in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>