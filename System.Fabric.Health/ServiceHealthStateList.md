<Type Name="ServiceHealthStateList" FullName="System.Fabric.Health.ServiceHealthStateList">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStateList : System.Collections.Generic.ICollection&lt;System.Fabric.Health.ServiceHealthState&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Health.ServiceHealthState&gt;, System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStateList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Health.ServiceHealthState&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Health.ServiceHealthState&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ServiceHealthState&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStateList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStateList&#xA;Implements ICollection(Of ServiceHealthState), IEnumerable(Of ServiceHealthState), IList(Of ServiceHealthState)" />
  <TypeSignature Language="F#" Value="type ServiceHealthStateList = class&#xA;    interface IList&lt;ServiceHealthState&gt;&#xA;    interface ICollection&lt;ServiceHealthState&gt;&#xA;    interface seq&lt;ServiceHealthState&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Health.ServiceHealthState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Health.ServiceHealthState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthState&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>コレクションを表します<see cref="T:System.Fabric.Health.ServiceHealthState" />をインデックスによって個別にアクセスできることができます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Health.ServiceHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Health.ServiceHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.Add(System.Fabric.Health.ServiceHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ServiceHealthState)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Health.ServiceHealthState -&gt; unit&#xA;override this.Add : System.Fabric.Health.ServiceHealthState -&gt; unit" Usage="serviceHealthStateList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ServiceHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>追加する項目。</para>
        </param>
        <summary>
          <para>項目をコレクションに追加します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="serviceHealthStateList.Clear " />
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
          <para>コレクションからすべての項目を削除します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Health.ServiceHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Health.ServiceHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.Contains(System.Fabric.Health.ServiceHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ServiceHealthState) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Health.ServiceHealthState -&gt; bool&#xA;override this.Contains : System.Fabric.Health.ServiceHealthState -&gt; bool" Usage="serviceHealthStateList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ServiceHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>コレクション内で検索する項目。</para>
        </param>
        <summary>
          <para>コレクションに特定の値が格納されているかどうかを判断します。</para>
        </summary>
        <returns>
          <para>返します<languageKeyword>true</languageKeyword>項目が見つかった場合<languageKeyword>false</languageKeyword>それ以外の場合。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Health.ServiceHealthState[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Health.ServiceHealthState[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.CopyTo(System.Fabric.Health.ServiceHealthState[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ServiceHealthState(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Health.ServiceHealthState[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Health.ServiceHealthState[] * int -&gt; unit" Usage="serviceHealthStateList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Health.ServiceHealthState[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para>ICollection から要素がコピーのコピー先である 1 次元配列。 配列には、0 から始まるインデックスが設定されている必要があります。</para>
        </param>
        <param name="arrayIndex">
          <para>コピーの開始位置となる、配列の 0 から始まるインデックス。</para>
        </param>
        <summary>
          <para>特定の配列インデックスを開始位置として、配列に ICollection の要素をコピーします。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Health.ServiceHealthStateList.Count" />
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
          <para>要素の数を取得します。</para>
        </summary>
        <value>
          <para>要素の数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ServiceHealthState&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Health.ServiceHealthState&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ServiceHealthState)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ServiceHealthState&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ServiceHealthState&gt;" Usage="serviceHealthStateList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Health.ServiceHealthState&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>コレクションを反復処理する列挙子を返します。</para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Collections.Generic.IEnumerator`1" />コレクションを反復処理するために使用できるオブジェクト。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Health.ServiceHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Health.ServiceHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.IndexOf(System.Fabric.Health.ServiceHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ServiceHealthState) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Health.ServiceHealthState -&gt; int&#xA;override this.IndexOf : System.Fabric.Health.ServiceHealthState -&gt; int" Usage="serviceHealthStateList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ServiceHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>コレクション内で検索する項目。</para>
        </param>
        <summary>
          <para>コレクション内の特定の項目のインデックスを決定します。</para>
        </summary>
        <returns>
          <para>項目のインデックス場合; コレクションで見つかったそれ以外の場合は-1。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Health.ServiceHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Health.ServiceHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.Insert(System.Int32,System.Fabric.Health.ServiceHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ServiceHealthState)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Health.ServiceHealthState -&gt; unit&#xA;override this.Insert : int * System.Fabric.Health.ServiceHealthState -&gt; unit" Usage="serviceHealthStateList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ServiceHealthState" />
      </Parameters>
      <Docs>
        <param name="index">
          <para>値を挿入する位置を示す、0 から始まるインデックス。</para>
        </param>
        <param name="item">
          <para>挿入する項目。</para>
        </param>
        <summary>
          <para>指定したインデックス位置に項目を挿入します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Health.ServiceHealthStateList.IsReadOnly" />
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
          <para>リストが読み取り専用かどうかを示す値を取得します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>リストが読み取り専用、それ以外の場合<languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceHealthState this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceHealthState Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ServiceHealthState" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Health.ServiceHealthState with get, set" Usage="System.Fabric.Health.ServiceHealthStateList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceHealthState</ReturnType>
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
          <para>返します<see cref="T:System.Fabric.Health.ServiceHealthState" />指定したインデックス位置。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Health.ServiceHealthState item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Health.ServiceHealthState item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.Remove(System.Fabric.Health.ServiceHealthState)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ServiceHealthState) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Health.ServiceHealthState -&gt; bool&#xA;override this.Remove : System.Fabric.Health.ServiceHealthState -&gt; bool" Usage="serviceHealthStateList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Health.ServiceHealthState" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>削除する項目。</para>
        </param>
        <summary>
          <para>コレクションから、最初に見つかった特定の項目を削除します。</para>
        </summary>
        <returns>
          <para>返します<languageKeyword>true</languageKeyword>項目が削除された場合<languageKeyword>false</languageKeyword>それ以外の場合。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="serviceHealthStateList.RemoveAt index" />
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
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para>返します<see cref="T:System.Collections.IEnumerator" />コレクションを反復処理するために使用できるオブジェクト。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>