<Type Name="DeployedServiceTypeList" FullName="System.Fabric.Query.DeployedServiceTypeList">
  <TypeSignature Language="C#" Value="public sealed class DeployedServiceTypeList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.DeployedServiceType&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.DeployedServiceType&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.DeployedServiceType&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServiceTypeList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.DeployedServiceType&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.DeployedServiceType&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.DeployedServiceType&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServiceTypeList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServiceTypeList&#xA;Implements ICollection(Of DeployedServiceType), IEnumerable(Of DeployedServiceType), IList(Of DeployedServiceType)" />
  <TypeSignature Language="F#" Value="type DeployedServiceTypeList = class&#xA;    interface IList&lt;DeployedServiceType&gt;&#xA;    interface ICollection&lt;DeployedServiceType&gt;&#xA;    interface seq&lt;DeployedServiceType&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.DeployedServiceType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.DeployedServiceType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.DeployedServiceType&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="16cf2-101">一覧を表す<see cref="T:System.Fabric.Query.DeployedServiceType" />です。</span><span class="sxs-lookup"><span data-stu-id="16cf2-101">Represents a list of <see cref="T:System.Fabric.Query.DeployedServiceType" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.DeployedServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.DeployedServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceTypeList.Add(System.Fabric.Query.DeployedServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As DeployedServiceType)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.DeployedServiceType -&gt; unit&#xA;override this.Add : System.Fabric.Query.DeployedServiceType -&gt; unit" Usage="deployedServiceTypeList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="16cf2-102">追加する項目。</span><span class="sxs-lookup"><span data-stu-id="16cf2-102">The item to add.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="16cf2-103">指定した項目を一覧に追加します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-103">Adds the specified item to the list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceTypeList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="deployedServiceTypeList.Clear " />
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
          <para><span data-ttu-id="16cf2-104">リストからすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-104">Removes all items from the list.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.DeployedServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.DeployedServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceTypeList.Contains(System.Fabric.Query.DeployedServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As DeployedServiceType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.DeployedServiceType -&gt; bool&#xA;override this.Contains : System.Fabric.Query.DeployedServiceType -&gt; bool" Usage="deployedServiceTypeList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="16cf2-105">検索する項目。</span><span class="sxs-lookup"><span data-stu-id="16cf2-105">The item to search.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="16cf2-106">一覧に特定の項目が含まれるかどうかを指定するフラグを示します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-106">Indicates a flag that specifies whether the list contains a specific item.</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="16cf2-107"><languageKeyword>true</languageKeyword>項目、それ以外の特定が一覧に含まれる場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="16cf2-107"><languageKeyword>true</languageKeyword> if the list contains a specific item; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.DeployedServiceType[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.DeployedServiceType[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceTypeList.CopyTo(System.Fabric.Query.DeployedServiceType[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As DeployedServiceType(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.DeployedServiceType[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.DeployedServiceType[] * int -&gt; unit" Usage="deployedServiceTypeList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.DeployedServiceType[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para><span data-ttu-id="16cf2-108">配列。</span><span class="sxs-lookup"><span data-stu-id="16cf2-108">The array.</span></span></para>
        </param>
        <param name="arrayIndex">
          <para><span data-ttu-id="16cf2-109">配列の開始インデックス。</span><span class="sxs-lookup"><span data-stu-id="16cf2-109">The starting index of the array.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="16cf2-110">一覧から指定された配列の指定した開始インデックス位置に項目をコピーします。</span><span class="sxs-lookup"><span data-stu-id="16cf2-110">Copies items from the list to the specified array at the specified starting index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceTypeList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.DeployedServiceTypeList.Count" />
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
          <para><span data-ttu-id="16cf2-111">取得または、この一覧の項目の数を設定します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-111">Gets or sets the number of items in this list.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16cf2-112">この一覧のアイテムの数。</span><span class="sxs-lookup"><span data-stu-id="16cf2-112">The number of items in this list.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServiceType&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.DeployedServiceType&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceTypeList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of DeployedServiceType)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServiceType&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServiceType&gt;" Usage="deployedServiceTypeList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServiceType&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="16cf2-113">この一覧に項目を列挙子を取得します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-113">Gets an enumerator to items in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="16cf2-114">この一覧の項目を列挙子。</span><span class="sxs-lookup"><span data-stu-id="16cf2-114">The enumerator to items in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.DeployedServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.DeployedServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceTypeList.IndexOf(System.Fabric.Query.DeployedServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As DeployedServiceType) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.DeployedServiceType -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.DeployedServiceType -&gt; int" Usage="deployedServiceTypeList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="16cf2-115">リスト内の項目。</span><span class="sxs-lookup"><span data-stu-id="16cf2-115">The item in the list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="16cf2-116">この一覧に指定した項目のインデックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-116">Gets the index of the specified item in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="16cf2-117">この一覧に指定した項目のインデックス。</span><span class="sxs-lookup"><span data-stu-id="16cf2-117">The index of the specified item in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.DeployedServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.DeployedServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceTypeList.Insert(System.Int32,System.Fabric.Query.DeployedServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As DeployedServiceType)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.DeployedServiceType -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.DeployedServiceType -&gt; unit" Usage="deployedServiceTypeList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServiceType" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="16cf2-118">項目を挿入するインデックス。</span><span class="sxs-lookup"><span data-stu-id="16cf2-118">The index where the item will be inserted.</span></span></para>
        </param>
        <param name="item">
          <para><span data-ttu-id="16cf2-119">挿入する項目。</span><span class="sxs-lookup"><span data-stu-id="16cf2-119">The item to insert.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="16cf2-120">指定したインデックス位置の項目を挿入します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-120">Inserts the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceTypeList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.DeployedServiceTypeList.IsReadOnly" />
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
          <para><span data-ttu-id="16cf2-121">取得またはリストを変更できるかどうかを示すフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-121">Gets or sets a flag that indicates whether the list can be modified.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="16cf2-122"><languageKeyword>true</languageKeyword>変更後、それ以外の一覧が表示できる場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="16cf2-122"><languageKeyword>true</languageKeyword> if the list can be modified; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.DeployedServiceType this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.DeployedServiceType Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceTypeList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As DeployedServiceType" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.DeployedServiceType with get, set" Usage="System.Fabric.Query.DeployedServiceTypeList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.DeployedServiceType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para><span data-ttu-id="16cf2-123">項目のインデックス。</span><span class="sxs-lookup"><span data-stu-id="16cf2-123">The index of the item.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="16cf2-124">指定したインデックスにある項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-124">Gets the item at the specified index.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16cf2-125">指定したインデックスにある項目。</span><span class="sxs-lookup"><span data-stu-id="16cf2-125">The item at the specified index.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.DeployedServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.DeployedServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceTypeList.Remove(System.Fabric.Query.DeployedServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As DeployedServiceType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.DeployedServiceType -&gt; bool&#xA;override this.Remove : System.Fabric.Query.DeployedServiceType -&gt; bool" Usage="deployedServiceTypeList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para><span data-ttu-id="16cf2-126">削除する項目。</span><span class="sxs-lookup"><span data-stu-id="16cf2-126">The item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="16cf2-127">この一覧から、指定した項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-127">Remove the specified item from this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="16cf2-128">削除された項目の一覧です。</span><span class="sxs-lookup"><span data-stu-id="16cf2-128">The list with removed item.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceTypeList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="deployedServiceTypeList.RemoveAt index" />
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
          <para><span data-ttu-id="16cf2-129">削除する項目のインデックス。</span><span class="sxs-lookup"><span data-stu-id="16cf2-129">The index of the item to remove.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="16cf2-130">指定したインデックスにある項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-130">Removes the item at the specified index.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceTypeList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para><span data-ttu-id="16cf2-131">この一覧の項目の列挙子を取得します。</span><span class="sxs-lookup"><span data-stu-id="16cf2-131">Gets an enumerator for items in this list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="16cf2-132">この一覧のアイテムの列挙子。</span><span class="sxs-lookup"><span data-stu-id="16cf2-132">The enumerator for items in this list.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>