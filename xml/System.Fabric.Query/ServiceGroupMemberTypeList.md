<Type Name="ServiceGroupMemberTypeList" FullName="System.Fabric.Query.ServiceGroupMemberTypeList">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupMemberTypeList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceGroupMemberType&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceGroupMemberType&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceGroupMemberType&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupMemberTypeList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.ServiceGroupMemberType&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.ServiceGroupMemberType&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ServiceGroupMemberType&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceGroupMemberTypeList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupMemberTypeList&#xA;Implements ICollection(Of ServiceGroupMemberType), IEnumerable(Of ServiceGroupMemberType), IList(Of ServiceGroupMemberType)" />
  <TypeSignature Language="F#" Value="type ServiceGroupMemberTypeList = class&#xA;    interface IList&lt;ServiceGroupMemberType&gt;&#xA;    interface ICollection&lt;ServiceGroupMemberType&gt;&#xA;    interface seq&lt;ServiceGroupMemberType&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceGroupMemberType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceGroupMemberType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceGroupMemberType&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="e929e-101">サービス グループ メンバーの型リストをサービス グループ メンバーの型が含まれています。</span><span class="sxs-lookup"><span data-stu-id="e929e-101">The service group member type list that contains the service group member types.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.ServiceGroupMemberType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.ServiceGroupMemberType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.Add(System.Fabric.Query.ServiceGroupMemberType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ServiceGroupMemberType)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.ServiceGroupMemberType -&gt; unit&#xA;override this.Add : System.Fabric.Query.ServiceGroupMemberType -&gt; unit" Usage="serviceGroupMemberTypeList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberType" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="e929e-102">追加するサービス グループ メンバーの種類。</span><span class="sxs-lookup"><span data-stu-id="e929e-102">The service group member type to be added.</span></span></param>
        <summary>
            <span data-ttu-id="e929e-103">サービス グループ メンバーの種類を追加します。</span><span class="sxs-lookup"><span data-stu-id="e929e-103">Add the service group member type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="serviceGroupMemberTypeList.Clear " />
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
            <span data-ttu-id="e929e-104">サービス グループ メンバーの種類をオフにします。</span><span class="sxs-lookup"><span data-stu-id="e929e-104">Clear the service group member types.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.ServiceGroupMemberType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.ServiceGroupMemberType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.Contains(System.Fabric.Query.ServiceGroupMemberType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ServiceGroupMemberType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.ServiceGroupMemberType -&gt; bool&#xA;override this.Contains : System.Fabric.Query.ServiceGroupMemberType -&gt; bool" Usage="serviceGroupMemberTypeList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberType" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="e929e-105">検索するサービス グループ メンバーの種類。</span><span class="sxs-lookup"><span data-stu-id="e929e-105">The service group member type to be searched.</span></span></param>
        <summary>
            <span data-ttu-id="e929e-106">検索する場合、サービス グループ メンバーの種類が含まれています。</span><span class="sxs-lookup"><span data-stu-id="e929e-106">Search if contains the service group member type.</span></span>
            </summary>
        <returns><span data-ttu-id="e929e-107">検索の結果。</span><span class="sxs-lookup"><span data-stu-id="e929e-107">The result of the search.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.ServiceGroupMemberType[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.ServiceGroupMemberType[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.CopyTo(System.Fabric.Query.ServiceGroupMemberType[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ServiceGroupMemberType(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.ServiceGroupMemberType[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.ServiceGroupMemberType[] * int -&gt; unit" Usage="serviceGroupMemberTypeList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.ServiceGroupMemberType[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array"><span data-ttu-id="e929e-108">コピーされるサービス グループ メンバーの種類。</span><span class="sxs-lookup"><span data-stu-id="e929e-108">The service group member type to be copied.</span></span></param>
        <param name="arrayIndex"><span data-ttu-id="e929e-109">コピーを開始するインデックス。</span><span class="sxs-lookup"><span data-stu-id="e929e-109">The index to begin the copy.</span></span></param>
        <summary>
            <span data-ttu-id="e929e-110">サービス グループ メンバーの種類をコピーします。</span><span class="sxs-lookup"><span data-stu-id="e929e-110">Copy the service group member type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberTypeList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.ServiceGroupMemberTypeList.Count" />
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
            <span data-ttu-id="e929e-111">サービス グループ メンバーの種類の数。</span><span class="sxs-lookup"><span data-stu-id="e929e-111">The count of the service group member type.</span></span>
            </summary>
        <value><span data-ttu-id="e929e-112">サービス グループ メンバーの種類の数。</span><span class="sxs-lookup"><span data-stu-id="e929e-112">The count of the service group member type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberType&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.ServiceGroupMemberType&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ServiceGroupMemberType)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberType&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberType&gt;" Usage="serviceGroupMemberTypeList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberType&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e929e-113">サービス グループ メンバーの列挙子の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="e929e-113">Get the enumerator of the service group member types.</span></span>
            </summary>
        <returns><span data-ttu-id="e929e-114">サービス グループ メンバーの種類の列挙子。</span><span class="sxs-lookup"><span data-stu-id="e929e-114">The enumerator of the service group member types.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.ServiceGroupMemberType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.ServiceGroupMemberType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.IndexOf(System.Fabric.Query.ServiceGroupMemberType)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ServiceGroupMemberType) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.ServiceGroupMemberType -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.ServiceGroupMemberType -&gt; int" Usage="serviceGroupMemberTypeList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberType" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="e929e-115">検索するサービス グループ メンバーの種類。</span><span class="sxs-lookup"><span data-stu-id="e929e-115">The service group member type to be searched.</span></span></param>
        <summary>
            <span data-ttu-id="e929e-116">サービス グループ メンバーの種類のインデックスを検索します。</span><span class="sxs-lookup"><span data-stu-id="e929e-116">Search for the index of the service group member type.</span></span>
            </summary>
        <returns><span data-ttu-id="e929e-117">サービス グループ メンバーの種類のインデックス。</span><span class="sxs-lookup"><span data-stu-id="e929e-117">The index of the service group member type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.ServiceGroupMemberType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.ServiceGroupMemberType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.Insert(System.Int32,System.Fabric.Query.ServiceGroupMemberType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ServiceGroupMemberType)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.ServiceGroupMemberType -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.ServiceGroupMemberType -&gt; unit" Usage="serviceGroupMemberTypeList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberType" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="e929e-118">挿入するインデックス。</span><span class="sxs-lookup"><span data-stu-id="e929e-118">The index to be inserted.</span></span></param>
        <param name="item"><span data-ttu-id="e929e-119">挿入するサービス グループ メンバーの種類。</span><span class="sxs-lookup"><span data-stu-id="e929e-119">The service group member type to be inserted.</span></span></param>
        <summary>
            <span data-ttu-id="e929e-120">サービス グループ メンバーの種類を挿入します。</span><span class="sxs-lookup"><span data-stu-id="e929e-120">Insert the service group member type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberTypeList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.ServiceGroupMemberTypeList.IsReadOnly" />
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
            <span data-ttu-id="e929e-121">読み取り専用のフラグ。</span><span class="sxs-lookup"><span data-stu-id="e929e-121">The flag of read only.</span></span>
            </summary>
        <value><span data-ttu-id="e929e-122">読み取り専用のフラグ。</span><span class="sxs-lookup"><span data-stu-id="e929e-122">The flag of read only.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceGroupMemberType this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ServiceGroupMemberType Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberTypeList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ServiceGroupMemberType" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.ServiceGroupMemberType with get, set" Usage="System.Fabric.Query.ServiceGroupMemberTypeList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceGroupMemberType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="e929e-123">サービスにアクセスできるグループ メンバーの種類のインデックス。</span><span class="sxs-lookup"><span data-stu-id="e929e-123">The index of service group member type to be accessed.</span></span></param>
        <summary>
            <span data-ttu-id="e929e-124">サービス グループ メンバーの種類にアクセスします。</span><span class="sxs-lookup"><span data-stu-id="e929e-124">Access the service group member type.</span></span>
            </summary>
        <value><span data-ttu-id="e929e-125">サービス グループ メンバーの種類のインデックス。</span><span class="sxs-lookup"><span data-stu-id="e929e-125">Index of the service group member type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.ServiceGroupMemberType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.ServiceGroupMemberType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.Remove(System.Fabric.Query.ServiceGroupMemberType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ServiceGroupMemberType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.ServiceGroupMemberType -&gt; bool&#xA;override this.Remove : System.Fabric.Query.ServiceGroupMemberType -&gt; bool" Usage="serviceGroupMemberTypeList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberType" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="e929e-126">削除するサービス グループ メンバーの種類。</span><span class="sxs-lookup"><span data-stu-id="e929e-126">The service group member type to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="e929e-127">サービス グループ メンバーの種類を削除します。</span><span class="sxs-lookup"><span data-stu-id="e929e-127">Remove the service group member type.</span></span>
            </summary>
        <returns><span data-ttu-id="e929e-128">削除の結果。</span><span class="sxs-lookup"><span data-stu-id="e929e-128">The result of the remove.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="serviceGroupMemberTypeList.RemoveAt index" />
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
        <param name="index"><span data-ttu-id="e929e-129">サービスを削除するグループ メンバーの種類のインデックス。</span><span class="sxs-lookup"><span data-stu-id="e929e-129">The index of service group member type to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="e929e-130">サービス グループ メンバーの種類を削除します。</span><span class="sxs-lookup"><span data-stu-id="e929e-130">Remove service group member type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberTypeList.System#Collections#IEnumerable#GetEnumerator" />
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
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>