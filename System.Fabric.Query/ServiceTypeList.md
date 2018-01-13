<Type Name="ServiceTypeList" FullName="System.Fabric.Query.ServiceTypeList">
  <TypeSignature Language="C#" Value="public sealed class ServiceTypeList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceType&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceType&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceType&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceTypeList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.ServiceType&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.ServiceType&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ServiceType&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceTypeList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceTypeList&#xA;Implements ICollection(Of ServiceType), IEnumerable(Of ServiceType), IList(Of ServiceType)" />
  <TypeSignature Language="F#" Value="type ServiceTypeList = class&#xA;    interface IList&lt;ServiceType&gt;&#xA;    interface ICollection&lt;ServiceType&gt;&#xA;    interface seq&lt;ServiceType&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.ServiceType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ServiceType&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.ServiceType&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>サービスの種類のリストを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.ServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.ServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.Add(System.Fabric.Query.ServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ServiceType)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.ServiceType -&gt; unit&#xA;override this.Add : System.Fabric.Query.ServiceType -&gt; unit" Usage="serviceTypeList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>追加する項目。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Query.ServiceTypeList" /> の末尾にオブジェクトを追加します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="serviceTypeList.Clear " />
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
          <para><see cref="T:System.Fabric.Query.ServiceTypeList" /> からすべての要素を削除します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.ServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.ServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.Contains(System.Fabric.Query.ServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ServiceType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.ServiceType -&gt; bool&#xA;override this.Contains : System.Fabric.Query.ServiceType -&gt; bool" Usage="serviceTypeList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>検索する項目。</para>
        </param>
        <summary>
          <para>要素がであるかどうかを判断、 <see cref="T:System.Fabric.Query.ServiceTypeList" />.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>場合は、項目が、 <see cref="T:System.Fabric.Query.ServiceTypeList" />、それ以外の<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.ServiceType[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.ServiceType[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.CopyTo(System.Fabric.Query.ServiceType[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ServiceType(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.ServiceType[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.ServiceType[] * int -&gt; unit" Usage="serviceTypeList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.ServiceType[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para>サービスの種類の配列。</para>
        </param>
        <param name="arrayIndex">
          <para>配列インデックス。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Query.ServiceTypeList" /> 全体を、互換性のある 1 次元の <see cref="T:System.Fabric.Query.ServiceTypeList" /> にコピーします。コピー操作は、コピー先の配列の指定したインデックスから始まる部分に行います。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceTypeList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.ServiceTypeList.Count" />
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
          <para>取得または設定内の要素の数、<see cref="T:System.Fabric.Query.ServiceTypeList" />です。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Query.ServiceTypeList" /> にある要素の数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceType&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.ServiceType&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ServiceType)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceType&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceType&gt;" Usage="serviceTypeList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ServiceType&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>全体の列挙子を返します<see cref="T:System.Fabric.Query.ServiceTypeList" />.</para>
        </summary>
        <returns>
          <para>全体の列挙子<see cref="T:System.Fabric.Query.ServiceTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.ServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.ServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.IndexOf(System.Fabric.Query.ServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ServiceType) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.ServiceType -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.ServiceType -&gt; int" Usage="serviceTypeList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>検索する項目。</para>
        </param>
        <summary>
          <para>指定された検索<see cref="T:System.Fabric.Query.ServiceType" />全体内で最初に見つかった位置の 0 から始まるインデックスを返しますと<see cref="T:System.Fabric.Query.ServiceTypeList" />です。</para>
        </summary>
        <returns>
          <para>全体内で最初に見つかった位置の 0 から始まるインデックス<see cref="T:System.Fabric.Query.ServiceTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.ServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.ServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.Insert(System.Int32,System.Fabric.Query.ServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ServiceType)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.ServiceType -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.ServiceType -&gt; unit" Usage="serviceTypeList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceType" />
      </Parameters>
      <Docs>
        <param name="index">
          <para>インデックス。</para>
        </param>
        <param name="item">
          <para>挿入する項目。</para>
        </param>
        <summary>
          <para>要素を挿入、<see cref="T:System.Fabric.Query.ServiceTypeList" />指定したインデックス位置。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceTypeList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.ServiceTypeList.IsReadOnly" />
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
          <para>取得または設定するかどうか<see cref="T:System.Fabric.Query.ServiceTypeList" />は読み取り専用です。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合、<see cref="T:System.Fabric.Query.ServiceTypeList" />は読み取り専用です。 それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceType this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ServiceType Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ServiceTypeList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ServiceType" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.ServiceType with get, set" Usage="System.Fabric.Query.ServiceTypeList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceType</ReturnType>
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
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.ServiceType item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.ServiceType item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.Remove(System.Fabric.Query.ServiceType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ServiceType) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.ServiceType -&gt; bool&#xA;override this.Remove : System.Fabric.Query.ServiceType -&gt; bool" Usage="serviceTypeList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ServiceType" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>削除する項目。</para>
        </param>
        <summary>
          <para>最初に見つかった特定のオブジェクトから削除、 <see cref="T:System.Fabric.Query.ServiceTypeList" />.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>場合は、項目が存在します。 それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="serviceTypeList.RemoveAt index" />
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
          <para>インデックスの項目を削除する場所です。</para>
        </param>
        <summary>
          <para>指定したインデックス位置にある要素を削除、 <see cref="T:System.Fabric.Query.ServiceTypeList" />.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ServiceTypeList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para>列挙子を返します、 <see cref="T:System.Fabric.Query.ServiceTypeList" />.</para>
        </summary>
        <returns>
          <para>分子、<see cref="T:System.Fabric.Query.ServiceTypeList" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>