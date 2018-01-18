<Type Name="ServiceGroupMemberList" FullName="System.Fabric.Query.ServiceGroupMemberList">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupMemberList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceGroupMember&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceGroupMember&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceGroupMember&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupMemberList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.ServiceGroupMember&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.ServiceGroupMember&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ServiceGroupMember&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceGroupMemberList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupMemberList&#xA;Implements ICollection(Of ServiceGroupMember), IEnumerable(Of ServiceGroupMember), IList(Of ServiceGroupMember)" />
  <TypeSignature Language="F#" Value="type ServiceGroupMemberList = class&#xA;    interface IList&lt;ServiceGroupMember&gt;&#xA;    interface ICollection&lt;ServiceGroupMember&gt;&#xA;    interface seq&lt;ServiceGroupMember&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceGroupMember&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceGroupMember&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceGroupMember&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="297ec-101">サービス グループのメンバーを含んでいる、サービス グループ メンバーの一覧です。</span><span class="sxs-lookup"><span data-stu-id="297ec-101">The service group member list that contains service group members.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.ServiceGroupMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.ServiceGroupMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.Add(System.Fabric.Query.ServiceGroupMember)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ServiceGroupMember)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.ServiceGroupMember -&gt; unit&#xA;override this.Add : System.Fabric.Query.ServiceGroupMember -&gt; unit" Usage="serviceGroupMemberList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="297ec-102">サービス グループ メンバーを追加します。</span><span class="sxs-lookup"><span data-stu-id="297ec-102">The service group member to be added.</span></span></param>
        <summary>
            <span data-ttu-id="297ec-103">サービス グループ メンバーを追加します。</span><span class="sxs-lookup"><span data-stu-id="297ec-103">Add service group member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="serviceGroupMemberList.Clear " />
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
            <span data-ttu-id="297ec-104">サービス グループのメンバーをオフにします。</span><span class="sxs-lookup"><span data-stu-id="297ec-104">Clear the service group members.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.ServiceGroupMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.ServiceGroupMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.Contains(System.Fabric.Query.ServiceGroupMember)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ServiceGroupMember) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.ServiceGroupMember -&gt; bool&#xA;override this.Contains : System.Fabric.Query.ServiceGroupMember -&gt; bool" Usage="serviceGroupMemberList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="297ec-105">検索するサービスのグループのメンバー。</span><span class="sxs-lookup"><span data-stu-id="297ec-105">The service group member to be searched.</span></span></param>
        <summary>
            <span data-ttu-id="297ec-106">場合に、検索サービス グループのメンバーが含まれています。</span><span class="sxs-lookup"><span data-stu-id="297ec-106">Search if contains service group member.</span></span>
            </summary>
        <returns><span data-ttu-id="297ec-107">検索の結果。</span><span class="sxs-lookup"><span data-stu-id="297ec-107">The result of the search.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.ServiceGroupMember[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.ServiceGroupMember[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.CopyTo(System.Fabric.Query.ServiceGroupMember[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ServiceGroupMember(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.ServiceGroupMember[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.ServiceGroupMember[] * int -&gt; unit" Usage="serviceGroupMemberList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.ServiceGroupMember[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array"><span data-ttu-id="297ec-108">コピーするサービス グループのメンバーです。</span><span class="sxs-lookup"><span data-stu-id="297ec-108">The service group members to be copied.</span></span></param>
        <param name="arrayIndex"><span data-ttu-id="297ec-109">コピーを開始する配列のインデックス。</span><span class="sxs-lookup"><span data-stu-id="297ec-109">The index of the array to begin copy.</span></span></param>
        <summary>
            <span data-ttu-id="297ec-110">サービス グループのメンバーをコピーします。</span><span class="sxs-lookup"><span data-stu-id="297ec-110">Copy the service group members.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.ServiceGroupMemberList.Count" />
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
            <span data-ttu-id="297ec-111">サービス グループ メンバーの数。</span><span class="sxs-lookup"><span data-stu-id="297ec-111">The count of the service group members.</span></span>
            </summary>
        <value><span data-ttu-id="297ec-112">サービス グループ メンバーの数。</span><span class="sxs-lookup"><span data-stu-id="297ec-112">The count of the service group members.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMember&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.ServiceGroupMember&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ServiceGroupMember)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMember&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMember&gt;" Usage="serviceGroupMemberList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceGroupMember&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="297ec-113">サービス グループのメンバーの列挙子を取得します。</span><span class="sxs-lookup"><span data-stu-id="297ec-113">Get the enumerator of the service group members.</span></span>
            </summary>
        <returns><span data-ttu-id="297ec-114">サービス グループのメンバーの列挙子。</span><span class="sxs-lookup"><span data-stu-id="297ec-114">The enumerator of the service group members.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.ServiceGroupMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.ServiceGroupMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.IndexOf(System.Fabric.Query.ServiceGroupMember)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ServiceGroupMember) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.ServiceGroupMember -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.ServiceGroupMember -&gt; int" Usage="serviceGroupMemberList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="297ec-115">検索するサービスのグループのメンバー。</span><span class="sxs-lookup"><span data-stu-id="297ec-115">The service group member to be searched.</span></span></param>
        <summary>
            <span data-ttu-id="297ec-116">サービス グループ メンバーのインデックスを検索します。</span><span class="sxs-lookup"><span data-stu-id="297ec-116">Find the index of the service group member.</span></span>
            </summary>
        <returns><span data-ttu-id="297ec-117">サービス グループ メンバーのインデックス。</span><span class="sxs-lookup"><span data-stu-id="297ec-117">The index of the service group member.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.ServiceGroupMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.ServiceGroupMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.Insert(System.Int32,System.Fabric.Query.ServiceGroupMember)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ServiceGroupMember)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.ServiceGroupMember -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.ServiceGroupMember -&gt; unit" Usage="serviceGroupMemberList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMember" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="297ec-118">挿入するインデックス。</span><span class="sxs-lookup"><span data-stu-id="297ec-118">The index to be inserted.</span></span></param>
        <param name="item"><span data-ttu-id="297ec-119">挿入するサービスのグループのメンバー。</span><span class="sxs-lookup"><span data-stu-id="297ec-119">The service group member to be inserted.</span></span></param>
        <summary>
            <span data-ttu-id="297ec-120">サービス グループ メンバーを挿入します。</span><span class="sxs-lookup"><span data-stu-id="297ec-120">Insert the service group member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.ServiceGroupMemberList.IsReadOnly" />
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
            <span data-ttu-id="297ec-121">読み取り専用のフラグ。</span><span class="sxs-lookup"><span data-stu-id="297ec-121">The flag of read only.</span></span>
            </summary>
        <value><span data-ttu-id="297ec-122">読み取り専用のフラグ。</span><span class="sxs-lookup"><span data-stu-id="297ec-122">The flag of read only.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceGroupMember this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ServiceGroupMember Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceGroupMemberList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ServiceGroupMember" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.ServiceGroupMember with get, set" Usage="System.Fabric.Query.ServiceGroupMemberList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceGroupMember</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index"><span data-ttu-id="297ec-123">サービス グループ メンバーのインデックス。</span><span class="sxs-lookup"><span data-stu-id="297ec-123">The index of the service group member.</span></span></param>
        <summary>
            <span data-ttu-id="297ec-124">サービス グループのメンバーにアクセスします。</span><span class="sxs-lookup"><span data-stu-id="297ec-124">Access the service group member.</span></span>
            </summary>
        <value><span data-ttu-id="297ec-125">サービス グループ メンバーのインデックス。</span><span class="sxs-lookup"><span data-stu-id="297ec-125">Index of the service group member.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.ServiceGroupMember item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.ServiceGroupMember item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.Remove(System.Fabric.Query.ServiceGroupMember)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ServiceGroupMember) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.ServiceGroupMember -&gt; bool&#xA;override this.Remove : System.Fabric.Query.ServiceGroupMember -&gt; bool" Usage="serviceGroupMemberList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceGroupMember" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="297ec-126">サービス グループのメンバーは削除します。</span><span class="sxs-lookup"><span data-stu-id="297ec-126">The service group member to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="297ec-127">サービス グループ メンバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="297ec-127">Remove the service group member.</span></span>
            </summary>
        <returns><span data-ttu-id="297ec-128">削除の結果。</span><span class="sxs-lookup"><span data-stu-id="297ec-128">The result of the remove.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="serviceGroupMemberList.RemoveAt index" />
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
        <param name="index"><span data-ttu-id="297ec-129">削除するサービス グループ メンバーのインデックス。</span><span class="sxs-lookup"><span data-stu-id="297ec-129">The index of service group member to be removed.</span></span></param>
        <summary>
            <span data-ttu-id="297ec-130">サービス グループ メンバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="297ec-130">Remove the service group member.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceGroupMemberList.System#Collections#IEnumerable#GetEnumerator" />
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