<Type Name="ProvisionedFabricConfigVersionList" FullName="System.Fabric.Query.ProvisionedFabricConfigVersionList">
  <TypeSignature Language="C#" Value="public sealed class ProvisionedFabricConfigVersionList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ProvisionedFabricConfigVersionList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersion&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersion&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersion&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ProvisionedFabricConfigVersionList&#xA;Implements ICollection(Of ProvisionedFabricConfigVersion), IEnumerable(Of ProvisionedFabricConfigVersion), IList(Of ProvisionedFabricConfigVersion)" />
  <TypeSignature Language="F#" Value="type ProvisionedFabricConfigVersionList = class&#xA;    interface IList&lt;ProvisionedFabricConfigVersion&gt;&#xA;    interface ICollection&lt;ProvisionedFabricConfigVersion&gt;&#xA;    interface seq&lt;ProvisionedFabricConfigVersion&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>呼び出して取得プロビジョニング済みの Service Fabric (クラスター マニフェスト) の構成バージョンの一覧を表す<see cref="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync(System.String)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.ProvisionedFabricConfigVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.ProvisionedFabricConfigVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.Add(System.Fabric.Query.ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; unit&#xA;override this.Add : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; unit" Usage="provisionedFabricConfigVersionList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricConfigVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>指定した項目を一覧に追加します。</para>
        </param>
        <summary>
          <para>この一覧に指定した項目を追加します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="provisionedFabricConfigVersionList.Clear " />
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
          <para>このリストからすべての項目を削除します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.ProvisionedFabricConfigVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.ProvisionedFabricConfigVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.Contains(System.Fabric.Query.ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ProvisionedFabricConfigVersion) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; bool&#xA;override this.Contains : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; bool" Usage="provisionedFabricConfigVersionList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricConfigVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>一覧に含まれている指定された項目。</para>
        </param>
        <summary>
          <para>指定した項目がこの一覧に含まれている場合は true を返します。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>指定した項目がこの一覧に含まれている、それ以外の場合は<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.ProvisionedFabricConfigVersion[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.ProvisionedFabricConfigVersion[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.CopyTo(System.Fabric.Query.ProvisionedFabricConfigVersion[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ProvisionedFabricConfigVersion(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.ProvisionedFabricConfigVersion[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.ProvisionedFabricConfigVersion[] * int -&gt; unit" Usage="provisionedFabricConfigVersionList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.ProvisionedFabricConfigVersion[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para>コピーされた要素のコピー先である 1 次元配列<see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />です。 配列には、0 から始まるインデックスが設定されている必要があります。</para>
        </param>
        <param name="arrayIndex">
          <para>コピーの開始位置となる、配列の 0 から始まるインデックス。</para>
        </param>
        <summary>
          <para>この一覧から項目を指定したインデックス位置の指定した配列にコピーします。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ProvisionedFabricConfigVersionList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.ProvisionedFabricConfigVersionList.Count" />
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
          <para>この一覧の項目の数を取得します。</para>
        </summary>
        <value>
          <para>この一覧のアイテムの数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersion&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;" Usage="provisionedFabricConfigVersionList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricConfigVersion&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>この一覧の項目を列挙子を返します。</para>
        </summary>
        <returns>
          <para>この一覧の項目を列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.ProvisionedFabricConfigVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.ProvisionedFabricConfigVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.IndexOf(System.Fabric.Query.ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ProvisionedFabricConfigVersion) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; int" Usage="provisionedFabricConfigVersionList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricConfigVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>一覧内で検索する指定された項目。</para>
        </param>
        <summary>
          <para>この一覧に指定された項目のインデックスを返します。</para>
        </summary>
        <returns>
          <para>この一覧に指定した項目のインデックス。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.ProvisionedFabricConfigVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.ProvisionedFabricConfigVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.Insert(System.Int32,System.Fabric.Query.ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; unit" Usage="provisionedFabricConfigVersionList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricConfigVersion" />
      </Parameters>
      <Docs>
        <param name="index">
          <para>項目を挿入する位置の、0 から始まるインデックス。</para>
        </param>
        <param name="item">
          <para>リストに挿入するオブジェクト。</para>
        </param>
        <summary>
          <para>指定したインデックス位置には、この一覧に指定した項目を挿入します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ProvisionedFabricConfigVersionList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.ProvisionedFabricConfigVersionList.IsReadOnly" />
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
          <para>このプロパティが false の場合にのみ、リストを変更できるかどうかを示す値を取得します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>のみです。 それ以外の場合、リストを変更できる場合<languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ProvisionedFabricConfigVersion this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ProvisionedFabricConfigVersion Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ProvisionedFabricConfigVersionList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ProvisionedFabricConfigVersion" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.ProvisionedFabricConfigVersion with get, set" Usage="System.Fabric.Query.ProvisionedFabricConfigVersionList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ProvisionedFabricConfigVersion</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para>指定したインデックス。</para>
        </param>
        <summary>
          <para>指定したインデックスにある項目を取得します。</para>
        </summary>
        <value>
          <para>指定したインデックスにある項目。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.ProvisionedFabricConfigVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.ProvisionedFabricConfigVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.Remove(System.Fabric.Query.ProvisionedFabricConfigVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ProvisionedFabricConfigVersion) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; bool&#xA;override this.Remove : System.Fabric.Query.ProvisionedFabricConfigVersion -&gt; bool" Usage="provisionedFabricConfigVersionList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricConfigVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>リストから削除するオブジェクト。</para>
        </param>
        <summary>
          <para>この一覧から、指定した項目を削除します。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>した項目が正常に一覧から削除された、それ以外の場合<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="provisionedFabricConfigVersionList.RemoveAt index" />
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
          <para>指定したインデックスから、項目を削除します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricConfigVersionList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para>この一覧に項目を列挙子を取得します。</para>
        </summary>
        <returns>
          <para>この一覧の項目を列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>