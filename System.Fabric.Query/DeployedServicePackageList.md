<Type Name="DeployedServicePackageList" FullName="System.Fabric.Query.DeployedServicePackageList">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.DeployedServicePackage&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.DeployedServicePackage&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.DeployedServicePackage&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.DeployedServicePackage&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.DeployedServicePackage&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.DeployedServicePackage&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServicePackageList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageList&#xA;Implements ICollection(Of DeployedServicePackage), IEnumerable(Of DeployedServicePackage), IList(Of DeployedServicePackage)" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageList = class&#xA;    interface IList&lt;DeployedServicePackage&gt;&#xA;    interface ICollection&lt;DeployedServicePackage&gt;&#xA;    interface seq&lt;DeployedServicePackage&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.DeployedServicePackage&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.DeployedServicePackage&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.DeployedServicePackage&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="b518e-101">一覧を表す<see cref="T:System.Fabric.Query.DeployedServicePackage" />です。</span><span class="sxs-lookup"><span data-stu-id="b518e-101">Represents a list of <see cref="T:System.Fabric.Query.DeployedServicePackage" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.DeployedServicePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.DeployedServicePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServicePackageList.Add(System.Fabric.Query.DeployedServicePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As DeployedServicePackage)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.DeployedServicePackage -&gt; unit&#xA;override this.Add : System.Fabric.Query.DeployedServicePackage -&gt; unit" Usage="deployedServicePackageList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServicePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="b518e-102">追加する項目。</span><span class="sxs-lookup"><span data-stu-id="b518e-102">The item to add.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b518e-103">指定した項目を一覧に追加します。</span><span class="sxs-lookup"><span data-stu-id="b518e-103">Adds the specified item to the list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServicePackageList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="deployedServicePackageList.Clear " />
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
          <para><span data-ttu-id="b518e-104">リストからすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="b518e-104">Removes all items from the list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.DeployedServicePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.DeployedServicePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServicePackageList.Contains(System.Fabric.Query.DeployedServicePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As DeployedServicePackage) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.DeployedServicePackage -&gt; bool&#xA;override this.Contains : System.Fabric.Query.DeployedServicePackage -&gt; bool" Usage="deployedServicePackageList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServicePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="b518e-105">検索する項目。</span><span class="sxs-lookup"><span data-stu-id="b518e-105">The item to search.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b518e-106">指定した項目が一覧にあるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="b518e-106">Indicates whether the specified item is in the list.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="b518e-107"><languageKeyword>true</languageKeyword>場合、指定した項目は一覧にあるそれ以外の場合、 <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="b518e-107"><languageKeyword>true</languageKeyword> if the specified item is in the list; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.DeployedServicePackage[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.DeployedServicePackage[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServicePackageList.CopyTo(System.Fabric.Query.DeployedServicePackage[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As DeployedServicePackage(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.DeployedServicePackage[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.DeployedServicePackage[] * int -&gt; unit" Usage="deployedServicePackageList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.DeployedServicePackage[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="b518e-108">項目のコピー先は、リストからコピーします。</span><span class="sxs-lookup"><span data-stu-id="b518e-108">The destination of the items copied from the list.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="b518e-109">コピーの開始位置とする <paramref name="array" /> のインデックス (0 から始まる)。</span><span class="sxs-lookup"><span data-stu-id="b518e-109">The zero-based index in <paramref name="array" /> at which copying begins.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b518e-110">一覧から指定された配列の指定した開始インデックス位置に項目をコピーします。</span><span class="sxs-lookup"><span data-stu-id="b518e-110">Copies items from the list to the specified array at the specified starting index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServicePackageList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.DeployedServicePackageList.Count" />
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
          <para><span data-ttu-id="b518e-111">このリスト内の項目数を取得します。</span><span class="sxs-lookup"><span data-stu-id="b518e-111">Gets the number of items in this list</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b518e-112">この一覧のアイテムの数。</span><span class="sxs-lookup"><span data-stu-id="b518e-112">The number of items in this list.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServicePackage&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.DeployedServicePackage&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServicePackageList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of DeployedServicePackage)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServicePackage&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServicePackage&gt;" Usage="deployedServicePackageList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServicePackage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b518e-113">この一覧に項目を列挙子を取得します。</span><span class="sxs-lookup"><span data-stu-id="b518e-113">Gets an enumerator to items in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b518e-114">この一覧の項目を列挙子。</span><span class="sxs-lookup"><span data-stu-id="b518e-114">An enumerator to items in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.DeployedServicePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.DeployedServicePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServicePackageList.IndexOf(System.Fabric.Query.DeployedServicePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As DeployedServicePackage) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.DeployedServicePackage -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.DeployedServicePackage -&gt; int" Usage="deployedServicePackageList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServicePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="b518e-115">項目。</span><span class="sxs-lookup"><span data-stu-id="b518e-115">The item.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b518e-116">この一覧に指定した項目のインデックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="b518e-116">Gets the index of the specified item in this list</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b518e-117">この一覧に指定した項目のインデックス。</span><span class="sxs-lookup"><span data-stu-id="b518e-117">The index of the specified item in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.DeployedServicePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.DeployedServicePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServicePackageList.Insert(System.Int32,System.Fabric.Query.DeployedServicePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As DeployedServicePackage)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.DeployedServicePackage -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.DeployedServicePackage -&gt; unit" Usage="deployedServicePackageList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServicePackage" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="b518e-118"><paramref name="item" /> を挿入する位置の、0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="b518e-118">The zero-based index at which <paramref name="item" /> should be inserted.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="b518e-119">挿入するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b518e-119">The object to insert.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b518e-120">指定したインデックス位置の項目を挿入します。</span><span class="sxs-lookup"><span data-stu-id="b518e-120">Inserts the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServicePackageList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.DeployedServicePackageList.IsReadOnly" />
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
          <para><span data-ttu-id="b518e-121">リストが読み取り専用かどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="b518e-121">Gets a value indicating whether the list is read-only.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="b518e-122"><languageKeyword>true</languageKeyword>リストが読み取り専用、それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="b518e-122"><languageKeyword>true</languageKeyword> if the list is read-only; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.DeployedServicePackage this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.DeployedServicePackage Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServicePackageList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As DeployedServicePackage" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.DeployedServicePackage with get, set" Usage="System.Fabric.Query.DeployedServicePackageList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.DeployedServicePackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="b518e-123">取得する項目の、0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="b518e-123">The zero-based index of the item to get.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b518e-124">指定したインデックス位置に項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="b518e-124">Gets the item at the specified index</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b518e-125">指定したインデックスにある項目。</span><span class="sxs-lookup"><span data-stu-id="b518e-125">The item at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.DeployedServicePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.DeployedServicePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServicePackageList.Remove(System.Fabric.Query.DeployedServicePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As DeployedServicePackage) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.DeployedServicePackage -&gt; bool&#xA;override this.Remove : System.Fabric.Query.DeployedServicePackage -&gt; bool" Usage="deployedServicePackageList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServicePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="b518e-126">一覧から削除する項目。</span><span class="sxs-lookup"><span data-stu-id="b518e-126">The item to remove from the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b518e-127">この一覧から、指定した項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="b518e-127">Removes the specified item from this list.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="b518e-128"><languageKeyword>true</languageKeyword>が正常に削除された、それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="b518e-128"><languageKeyword>true</languageKeyword> if successfully removed; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServicePackageList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="deployedServicePackageList.RemoveAt index" />
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
          <para><span data-ttu-id="b518e-129">削除する項目の 0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="b518e-129">The zero-based index of the item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b518e-130">指定したインデックスにある項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="b518e-130">Removes the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServicePackageList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para><span data-ttu-id="b518e-131">この一覧の項目の列挙子を取得します。</span><span class="sxs-lookup"><span data-stu-id="b518e-131">Gets an enumerator for items in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b518e-132">この一覧のアイテムの列挙子。</span><span class="sxs-lookup"><span data-stu-id="b518e-132">An enumerator for items in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>