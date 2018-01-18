<Type Name="DeployedCodePackageList" FullName="System.Fabric.Query.DeployedCodePackageList">
  <TypeSignature Language="C#" Value="public sealed class DeployedCodePackageList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.DeployedCodePackage&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.DeployedCodePackage&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.DeployedCodePackage&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedCodePackageList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.DeployedCodePackage&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.DeployedCodePackage&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.DeployedCodePackage&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedCodePackageList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedCodePackageList&#xA;Implements ICollection(Of DeployedCodePackage), IEnumerable(Of DeployedCodePackage), IList(Of DeployedCodePackage)" />
  <TypeSignature Language="F#" Value="type DeployedCodePackageList = class&#xA;    interface IList&lt;DeployedCodePackage&gt;&#xA;    interface ICollection&lt;DeployedCodePackage&gt;&#xA;    interface seq&lt;DeployedCodePackage&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.DeployedCodePackage&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.DeployedCodePackage&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.DeployedCodePackage&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="bfd8b-101">このプロパティが false の場合にのみ変更可能なこのリストを表します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-101">Represents this list that can be modified only if this property is false.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.DeployedCodePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.DeployedCodePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.Add(System.Fabric.Query.DeployedCodePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As DeployedCodePackage)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.DeployedCodePackage -&gt; unit&#xA;override this.Add : System.Fabric.Query.DeployedCodePackage -&gt; unit" Usage="deployedCodePackageList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedCodePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="bfd8b-102">追加する項目。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-102">The item to be added.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="bfd8b-103">指定した項目を一覧に追加します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-103">Adds the specified item to the list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="deployedCodePackageList.Clear " />
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
          <para><span data-ttu-id="bfd8b-104">リストからすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-104">Removes all items from the list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.DeployedCodePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.DeployedCodePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.Contains(System.Fabric.Query.DeployedCodePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As DeployedCodePackage) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.DeployedCodePackage -&gt; bool&#xA;override this.Contains : System.Fabric.Query.DeployedCodePackage -&gt; bool" Usage="deployedCodePackageList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedCodePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="bfd8b-105">一覧に含まれている指定された項目。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-105">The specified item that contained in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="bfd8b-106">指定した項目がリストの場合は true を返します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-106">Returns true if the specified item is in the list.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="bfd8b-107"><languageKeyword>true</languageKeyword>項目です。 それ以外の場合、指定された一覧に含まれる場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-107"><languageKeyword>true</languageKeyword> if the list contains the specified item; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.DeployedCodePackage[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.DeployedCodePackage[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.CopyTo(System.Fabric.Query.DeployedCodePackage[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As DeployedCodePackage(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.DeployedCodePackage[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.DeployedCodePackage[] * int -&gt; unit" Usage="deployedCodePackageList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.DeployedCodePackage[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="bfd8b-108">1 次元配列。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-108">The one-dimensional array.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="bfd8b-109">コピーを開始するコピー先の配列内のインデックス。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-109">The index in the destination array to start copying.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="bfd8b-110">一覧から指定された配列の指定した開始インデックス位置に項目をコピーします。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-110">Copies items from the list to the specified array at the specified starting index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackageList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.DeployedCodePackageList.Count" />
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
          <para><span data-ttu-id="bfd8b-111">取得または、この一覧内の項目の数を示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-111">Gets or sets a value that indicates the number of items in this list.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="bfd8b-112">この一覧のアイテムの数。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-112">The number of items in this list.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedCodePackage&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.DeployedCodePackage&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of DeployedCodePackage)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedCodePackage&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedCodePackage&gt;" Usage="deployedCodePackageList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedCodePackage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="bfd8b-113">この一覧に項目を列挙子を取得します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-113">Gets an enumerator to items in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="bfd8b-114">この一覧の項目を列挙子</span><span class="sxs-lookup"><span data-stu-id="bfd8b-114">An enumerator to items in this list</span></span> </para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.DeployedCodePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.DeployedCodePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.IndexOf(System.Fabric.Query.DeployedCodePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As DeployedCodePackage) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.DeployedCodePackage -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.DeployedCodePackage -&gt; int" Usage="deployedCodePackageList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedCodePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="bfd8b-115">項目の指定したインデックス。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-115">The specified index of the item.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="bfd8b-116">この一覧に指定した項目のインデックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-116">Gets the index of the specified item in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="bfd8b-117">この一覧に指定した項目のインデックス。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-117">The index of the specified item in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.DeployedCodePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.DeployedCodePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.Insert(System.Int32,System.Fabric.Query.DeployedCodePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As DeployedCodePackage)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.DeployedCodePackage -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.DeployedCodePackage -&gt; unit" Usage="deployedCodePackageList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedCodePackage" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="bfd8b-118">項目を挿入する位置の、0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-118">The zero-based index at which item should be inserted.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="bfd8b-119">リストに挿入するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-119">The object to insert into the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="bfd8b-120">指定したインデックス位置の項目を挿入します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-120">Inserts the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackageList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.DeployedCodePackageList.IsReadOnly" />
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
          <para><span data-ttu-id="bfd8b-121">取得またはこのプロパティが false の場合にのみ、このリストを変更できるかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-121">Gets or sets a value that indicates whether this list can be modified only if this property is false.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="bfd8b-122"><languageKeyword>true</languageKeyword>一覧できるだけ変更後、それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-122"><languageKeyword>true</languageKeyword> if the list can only be modified; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.DeployedCodePackage this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.DeployedCodePackage Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackageList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As DeployedCodePackage" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.DeployedCodePackage with get, set" Usage="System.Fabric.Query.DeployedCodePackageList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.DeployedCodePackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="bfd8b-123">項目の指定したインデックス。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-123">The specified index of the item.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="bfd8b-124">指定したインデックスにある項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-124">Gets the item at the specified index.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="bfd8b-125">指定したインデックスに配置された項目。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-125">The deployed item at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.DeployedCodePackage item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.DeployedCodePackage item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.Remove(System.Fabric.Query.DeployedCodePackage)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As DeployedCodePackage) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.DeployedCodePackage -&gt; bool&#xA;override this.Remove : System.Fabric.Query.DeployedCodePackage -&gt; bool" Usage="deployedCodePackageList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedCodePackage" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="bfd8b-126">リストから削除するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-126">The object to remove from the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="bfd8b-127">この一覧から、指定した項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-127">Removes the specified item from this list.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="bfd8b-128"><languageKeyword>true</languageKeyword>した項目が正常に一覧から削除された、それ以外の場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-128"><languageKeyword>true</languageKeyword> if the item was successfully removed from the list; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="deployedCodePackageList.RemoveAt index" />
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
          <para><span data-ttu-id="bfd8b-129">削除する項目の 0 から始まるインデックス。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-129">The zero-based index of the item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="bfd8b-130">指定したインデックスにある項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-130">Removes the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedCodePackageList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para><span data-ttu-id="bfd8b-131">この一覧の項目の列挙子を取得します。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-131">Gets an enumerator for items in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="bfd8b-132">この一覧のアイテムの列挙子。</span><span class="sxs-lookup"><span data-stu-id="bfd8b-132">An enumerator for items in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>