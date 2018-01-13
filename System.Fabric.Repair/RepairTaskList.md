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
      <para>リストを表します<see cref="T:System.Fabric.Repair.RepairTask" />オブジェクト。</para>
      <para>このクラスは、Service Fabric プラットフォームをサポートしていますコードから直接呼び出されるものではありません。</para>
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
          <para>リストに追加するオブジェクト。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Repair.RepairTaskList" /> に項目を追加します。</para>
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
          <para><see cref="T:System.Fabric.Repair.RepairTaskList" /> からすべての項目を削除します。</para>
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
          <para>リスト内で検索するオブジェクト。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Repair.RepairTaskList" /> に指定の値が含まれているかどうかを確認します。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>場合、<see cref="T:System.Fabric.Repair.RepairTaskList" />特定の値が含まれています。 それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
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
          <para>コピーされた要素のコピー先である 1 次元配列<see cref="T:System.Fabric.Repair.RepairTaskList" />です。 配列には、0 から始まるインデックスが設定されている必要があります。</para>
        </param>
        <param name="arrayIndex">
          <para>コピーの開始位置となる、配列の 0 から始まるインデックス。</para>
        </param>
        <summary>
          <para>特定の配列インデックスを開始位置として、配列に <see cref="T:System.Fabric.Repair.RepairTaskList" /> の要素をコピーします。</para>
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
          <para><see cref="T:System.Fabric.Repair.RepairTaskList" /> に格納されている要素の数を取得します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Repair.RepairTaskList" /> に含まれている要素の数。</para>
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
          <para>コレクションを反復処理する列挙子を返します。</para>
        </summary>
        <returns>
          <para>コレクションの反復処理に使用できる列挙子。</para>
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
          <para>リスト内で検索するオブジェクト。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Repair.RepairTaskList" /> 内の特定の項目のインデックスを確認します。</para>
        </summary>
        <returns>
          <para>項目のインデックス場合; 一覧にありませんそれ以外の場合、-1 を返します。</para>
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
          <para>項目を挿入する位置の、0 から始まるインデックス。</para>
        </param>
        <param name="item">
          <para>リストに挿入するオブジェクト。</para>
        </param>
        <summary>
          <para>指定したインデックスの <see cref="T:System.Fabric.Repair.RepairTaskList" /> に項目を挿入します。</para>
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
          <para><see cref="T:System.Fabric.Repair.RepairTaskList" /> が読み取り専用であるかどうかを示す値を取得します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合、<see cref="T:System.Fabric.Repair.RepairTaskList" />は読み取り専用です。 それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
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
          <para>取得または設定する要素の、0 から始まるインデックス番号。</para>
        </param>
        <summary>
          <para>指定したインデックスにある要素を取得または設定します。</para>
        </summary>
        <value>
          <para>指定したインデックス位置にある要素。</para>
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
          <para>リストから削除するオブジェクト。</para>
        </param>
        <summary>
          <para>特定のオブジェクトが <see cref="T:System.Fabric.Repair.RepairTaskList" /> 内にあるときに、最初に出現したものを削除します。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>した項目が正常に一覧から削除された、それ以外の場合<languageKeyword>false</languageKeyword>です。 このメソッドも、元のリストに項目が見つからない場合は false を返します。</para>
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
          <para>削除する項目の 0 から始まるインデックス。</para>
        </param>
        <summary>
          <para>指定したインデックスにある項目を削除します。</para>
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
          <para>コレクションを反復処理する列挙子を返します。</para>
        </summary>
        <returns>
          <para>コレクションの反復処理に使用できる列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>