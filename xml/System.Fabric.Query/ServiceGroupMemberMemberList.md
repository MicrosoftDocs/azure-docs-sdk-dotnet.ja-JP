<Type Name="ServiceGroupMemberMemberList" FullName="System.Fabric.Query.ServiceGroupMemberMemberList">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupMemberMemberList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceGroupMemberMember&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceGroupMemberMember&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceGroupMemberMember&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupMemberMemberList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.ServiceGroupMemberMember&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.ServiceGroupMemberMember&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ServiceGroupMemberMember&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceGroupMemberMemberList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupMemberMemberList&#xA;Implements ICollection(Of ServiceGroupMemberMember), IEnumerable(Of ServiceGroupMemberMember), IList(Of ServiceGroupMemberMember)" />
  <TypeSignature Language="F#" Value="type ServiceGroupMemberMemberList = class&#xA;    interface IList&lt;ServiceGroupMemberMember&gt;&#xA;    interface ICollection&lt;ServiceGroupMemberMember&gt;&#xA;    interface seq&lt;ServiceGroupMemberMember&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceGroupMemberMember&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceGroupMemberMember&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceGroupMemberMember&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="09c92-101">サービス グループ メンバーのメンバー リストをサービス グループ メンバーのメンバーが含まれています。</span><span class="sxs-lookup"><span data-stu-id="09c92-101">The service group member member list that contains service group member members.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.ServiceGroupMemberMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.ServiceGroupMemberMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberMemberList.Add(System.Fabric.Query.ServiceGroupMemberMember)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ServiceGroupMemberMember)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.ServiceGroupMemberMember -&gt; unit&#xA;override this.Add : System.Fabric.Query.ServiceGroupMemberMember -&gt; unit" Usage="serviceGroupMemberMemberList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="09c92-102">追加するサービス グループ メンバーのメンバー。</span><span class="sxs-lookup"><span data-stu-id="09c92-102">The service group member member to be added.</span></span></param>
        <summary>
            <span data-ttu-id="09c92-103">サービス グループのメンバーを追加します。</span><span class="sxs-lookup"><span data-stu-id="09c92-103">Add service group member member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberMemberList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="serviceGroupMemberMemberList.Clear " />
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
            <span data-ttu-id="09c92-104">サービス グループ メンバーのメンバーをオフにします。</span><span class="sxs-lookup"><span data-stu-id="09c92-104">Clear the service group member members.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.ServiceGroupMemberMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.ServiceGroupMemberMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberMemberList.Contains(System.Fabric.Query.ServiceGroupMemberMember)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ServiceGroupMemberMember) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.ServiceGroupMemberMember -&gt; bool&#xA;override this.Contains : System.Fabric.Query.ServiceGroupMemberMember -&gt; bool" Usage="serviceGroupMemberMemberList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="09c92-105">検索するサービス グループ メンバーのメンバー。</span><span class="sxs-lookup"><span data-stu-id="09c92-105">The service group member member to be searched.</span></span></param>
        <summary>
            <span data-ttu-id="09c92-106">検索する場合、サービス グループ メンバーのメンバーが含まれています。</span><span class="sxs-lookup"><span data-stu-id="09c92-106">Search if contains the service group member member.</span></span>
            </summary>
        <returns><span data-ttu-id="09c92-107">検索の結果。</span><span class="sxs-lookup"><span data-stu-id="09c92-107">The result of the search.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.ServiceGroupMemberMember[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.ServiceGroupMemberMember[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberMemberList.CopyTo(System.Fabric.Query.ServiceGroupMemberMember[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ServiceGroupMemberMember(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.ServiceGroupMemberMember[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.ServiceGroupMemberMember[] * int -&gt; unit" Usage="serviceGroupMemberMemberList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.ServiceGroupMemberMember[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array"><span data-ttu-id="09c92-108">コピーされるサービス グループ メンバーのメンバー。</span><span class="sxs-lookup"><span data-stu-id="09c92-108">The service group member member to be copied.</span></span></param>
        <param name="arrayIndex"><span data-ttu-id="09c92-109">コピーを開始するインデックス。</span><span class="sxs-lookup"><span data-stu-id="09c92-109">The index to begin copy.</span></span></param>
        <summary>
            <span data-ttu-id="09c92-110">サービス グループのメンバーにコピーします。</span><span class="sxs-lookup"><span data-stu-id="09c92-110">Copy to the service group member member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberMemberList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.ServiceGroupMemberMemberList.Count" />
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
            <span data-ttu-id="09c92-111">サービス グループ メンバーのメンバーの数。</span><span class="sxs-lookup"><span data-stu-id="09c92-111">The count of the service group member members.</span></span>
            </summary>
        <value><span data-ttu-id="09c92-112">サービス グループ メンバーのメンバーの数。</span><span class="sxs-lookup"><span data-stu-id="09c92-112">The count of the service group member members.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberMember&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.ServiceGroupMemberMember&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberMemberList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ServiceGroupMemberMember)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberMember&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberMember&gt;" Usage="serviceGroupMemberMemberList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMemberMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="09c92-113">サービス グループ メンバーの列挙子メンバーを取得します。</span><span class="sxs-lookup"><span data-stu-id="09c92-113">Get the enumerator of the service group member members.</span></span>
            </summary>
        <returns><span data-ttu-id="09c92-114">サービス グループ メンバーのメンバーの列挙子。</span><span class="sxs-lookup"><span data-stu-id="09c92-114">The enumerator of the service group member members.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.ServiceGroupMemberMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.ServiceGroupMemberMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberMemberList.IndexOf(System.Fabric.Query.ServiceGroupMemberMember)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ServiceGroupMemberMember) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.ServiceGroupMemberMember -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.ServiceGroupMemberMember -&gt; int" Usage="serviceGroupMemberMemberList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="09c92-115">検索するサービス グループ メンバーのメンバー。</span><span class="sxs-lookup"><span data-stu-id="09c92-115">The service group member member to be searched.</span></span></param>
        <summary>
            <span data-ttu-id="09c92-116">サービス グループのメンバーのインデックスを検索します。</span><span class="sxs-lookup"><span data-stu-id="09c92-116">Search for the index of the service group member member.</span></span>
            </summary>
        <returns><span data-ttu-id="09c92-117">サービス グループのメンバーのインデックス。</span><span class="sxs-lookup"><span data-stu-id="09c92-117">The index of the service group member member.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.ServiceGroupMemberMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.ServiceGroupMemberMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberMemberList.Insert(System.Int32,System.Fabric.Query.ServiceGroupMemberMember)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ServiceGroupMemberMember)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.ServiceGroupMemberMember -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.ServiceGroupMemberMember -&gt; unit" Usage="serviceGroupMemberMemberList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberMember" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="09c92-118">サービス グループのメンバーを挿入するインデックス。</span><span class="sxs-lookup"><span data-stu-id="09c92-118">The index of the service group member member to insert.</span></span></param>
        <param name="item"><span data-ttu-id="09c92-119">挿入するサービス グループ メンバーのメンバー。</span><span class="sxs-lookup"><span data-stu-id="09c92-119">The service group member member to be inserted.</span></span></param>
        <summary>
            <span data-ttu-id="09c92-120">サービス グループのメンバーを挿入します。</span><span class="sxs-lookup"><span data-stu-id="09c92-120">Insert the service group member member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberMemberList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.ServiceGroupMemberMemberList.IsReadOnly" />
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
            <span data-ttu-id="09c92-121">読み取り専用のフラグ。</span><span class="sxs-lookup"><span data-stu-id="09c92-121">The flag of read only.</span></span>
            </summary>
        <value><span data-ttu-id="09c92-122">読み取り専用のフラグ。</span><span class="sxs-lookup"><span data-stu-id="09c92-122">The flag of read only.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceGroupMemberMember this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ServiceGroupMemberMember Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberMemberList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ServiceGroupMemberMember" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.ServiceGroupMemberMember with get, set" Usage="System.Fabric.Query.ServiceGroupMemberMemberList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceGroupMemberMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="09c92-123">サービス グループのメンバーへのアクセスのインデックス。</span><span class="sxs-lookup"><span data-stu-id="09c92-123">The index of the service group member member to access.</span></span></param>
        <summary>
            <span data-ttu-id="09c92-124">サービス グループのメンバーにアクセスします。</span><span class="sxs-lookup"><span data-stu-id="09c92-124">Access the service group member member.</span></span>
            </summary>
        <value><span data-ttu-id="09c92-125">サービス グループのメンバーのインデックス。</span><span class="sxs-lookup"><span data-stu-id="09c92-125">Index of the service group member member.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.ServiceGroupMemberMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.ServiceGroupMemberMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberMemberList.Remove(System.Fabric.Query.ServiceGroupMemberMember)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ServiceGroupMemberMember) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.ServiceGroupMemberMember -&gt; bool&#xA;override this.Remove : System.Fabric.Query.ServiceGroupMemberMember -&gt; bool" Usage="serviceGroupMemberMemberList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMemberMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="09c92-126">削除するサービス グループ メンバーのメンバー。</span><span class="sxs-lookup"><span data-stu-id="09c92-126">The service group member member to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="09c92-127">サービス グループのメンバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="09c92-127">Remove the service group member member.</span></span>
            </summary>
        <returns><span data-ttu-id="09c92-128">削除の結果。</span><span class="sxs-lookup"><span data-stu-id="09c92-128">The result of the remove.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberMemberList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="serviceGroupMemberMemberList.RemoveAt index" />
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
        <param name="index"><span data-ttu-id="09c92-129">削除するサービス グループのメンバーのインデックス。</span><span class="sxs-lookup"><span data-stu-id="09c92-129">The index of service group member member to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="09c92-130">サービス グループのメンバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="09c92-130">Remove the service group member member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberMemberList.System#Collections#IEnumerable#GetEnumerator" />
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