<Type Name="DeployedServiceReplicaList" FullName="System.Fabric.Query.DeployedServiceReplicaList">
  <TypeSignature Language="C#" Value="public sealed class DeployedServiceReplicaList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.DeployedServiceReplica&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.DeployedServiceReplica&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.DeployedServiceReplica&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServiceReplicaList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.DeployedServiceReplica&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.DeployedServiceReplica&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.DeployedServiceReplica&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServiceReplicaList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServiceReplicaList&#xA;Implements ICollection(Of DeployedServiceReplica), IEnumerable(Of DeployedServiceReplica), IList(Of DeployedServiceReplica)" />
  <TypeSignature Language="F#" Value="type DeployedServiceReplicaList = class&#xA;    interface IList&lt;DeployedServiceReplica&gt;&#xA;    interface ICollection&lt;DeployedServiceReplica&gt;&#xA;    interface seq&lt;DeployedServiceReplica&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.DeployedServiceReplica&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.DeployedServiceReplica&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.DeployedServiceReplica&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>展開済みサービスのレプリカの一覧が含まれています。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.DeployedServiceReplica item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.DeployedServiceReplica item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaList.Add(System.Fabric.Query.DeployedServiceReplica)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As DeployedServiceReplica)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.DeployedServiceReplica -&gt; unit&#xA;override this.Add : System.Fabric.Query.DeployedServiceReplica -&gt; unit" Usage="deployedServiceReplicaList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServiceReplica" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>コレクションに追加する項目。</para>
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
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="deployedServiceReplicaList.Clear " />
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
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.DeployedServiceReplica item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.DeployedServiceReplica item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaList.Contains(System.Fabric.Query.DeployedServiceReplica)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As DeployedServiceReplica) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.DeployedServiceReplica -&gt; bool&#xA;override this.Contains : System.Fabric.Query.DeployedServiceReplica -&gt; bool" Usage="deployedServiceReplicaList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServiceReplica" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>コレクション内で検索する項目。</para>
        </param>
        <summary>
          <para>コレクションに特定の値が格納されているかどうかを判断します。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>アイテムが存在する場合それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.DeployedServiceReplica[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.DeployedServiceReplica[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaList.CopyTo(System.Fabric.Query.DeployedServiceReplica[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As DeployedServiceReplica(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.DeployedServiceReplica[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.DeployedServiceReplica[] * int -&gt; unit" Usage="deployedServiceReplicaList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.DeployedServiceReplica[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para>コピーされた要素のコピー先である 1 次元配列  
            ハイパーリンク"http://msdn.microsoft.com/en-us/library/system.collections.icollection (v=vs.110).aspx"のコレクションです。 配列には、0 から始まるインデックスが設定されている必要があります。</para>
        </param>
        <param name="arrayIndex">
          <para>コピーの開始位置となる、配列の 0 から始まるインデックス。</para>
        </param>
        <summary>
          <para>この一覧から項目を指定したインデックスから始まる指定した配列にコピーします。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.DeployedServiceReplicaList.Count" />
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
          <para>サービス レプリカの数を取得します。</para>
        </summary>
        <value>
          <para>サービス レプリカの数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServiceReplica&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.DeployedServiceReplica&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of DeployedServiceReplica)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServiceReplica&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServiceReplica&gt;" Usage="deployedServiceReplicaList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.DeployedServiceReplica&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>この一覧に項目を列挙子を取得します。</para>
        </summary>
        <returns>
          <para>この一覧の項目を列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.DeployedServiceReplica item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.DeployedServiceReplica item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaList.IndexOf(System.Fabric.Query.DeployedServiceReplica)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As DeployedServiceReplica) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.DeployedServiceReplica -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.DeployedServiceReplica -&gt; int" Usage="deployedServiceReplicaList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServiceReplica" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>コレクション内で検索する項目。</para>
        </param>
        <summary>
          <para>この一覧に指定した項目のインデックスを取得します。</para>
        </summary>
        <returns>
          <para>この一覧に指定した項目のインデックス。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.DeployedServiceReplica item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.DeployedServiceReplica item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaList.Insert(System.Int32,System.Fabric.Query.DeployedServiceReplica)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As DeployedServiceReplica)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.DeployedServiceReplica -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.DeployedServiceReplica -&gt; unit" Usage="deployedServiceReplicaList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServiceReplica" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.DeployedServiceReplicaList.IsReadOnly" />
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
          <para>コレクションが読み取り専用かどうかを示す値を取得します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>リストが読み取り専用、それ以外の場合<languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.DeployedServiceReplica this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.DeployedServiceReplica Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplicaList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As DeployedServiceReplica" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.DeployedServiceReplica with get, set" Usage="System.Fabric.Query.DeployedServiceReplicaList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.DeployedServiceReplica</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para>インデックス。</para>
        </param>
        <summary>
          <para>指定したインデックス位置の要素を取得します。</para>
        </summary>
        <value>
          <para>指定したインデックス位置にある要素。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.DeployedServiceReplica item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.DeployedServiceReplica item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaList.Remove(System.Fabric.Query.DeployedServiceReplica)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As DeployedServiceReplica) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.DeployedServiceReplica -&gt; bool&#xA;override this.Remove : System.Fabric.Query.DeployedServiceReplica -&gt; bool" Usage="deployedServiceReplicaList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.DeployedServiceReplica" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>削除する項目。</para>
        </param>
        <summary>
          <para>コレクションから、最初に見つかった特定の項目を削除します。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>が正常に削除された、それ以外の場合<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="deployedServiceReplicaList.RemoveAt index" />
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
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplicaList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para>コレクションを反復処理する列挙子を取得します。</para>
        </summary>
        <returns>
          <para>コレクションを反復処理する列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>