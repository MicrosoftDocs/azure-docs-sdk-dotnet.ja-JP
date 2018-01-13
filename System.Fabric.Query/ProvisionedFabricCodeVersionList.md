<Type Name="ProvisionedFabricCodeVersionList" FullName="System.Fabric.Query.ProvisionedFabricCodeVersionList">
  <TypeSignature Language="C#" Value="public sealed class ProvisionedFabricCodeVersionList : System.Collections.Generic.ICollection&lt;System.Fabric.Query.ProvisionedFabricCodeVersion&gt;, System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ProvisionedFabricCodeVersion&gt;, System.Collections.Generic.IList&lt;System.Fabric.Query.ProvisionedFabricCodeVersion&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ProvisionedFabricCodeVersionList extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersion&gt;, class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersion&gt;, class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersion&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ProvisionedFabricCodeVersionList&#xA;Implements ICollection(Of ProvisionedFabricCodeVersion), IEnumerable(Of ProvisionedFabricCodeVersion), IList(Of ProvisionedFabricCodeVersion)" />
  <TypeSignature Language="F#" Value="type ProvisionedFabricCodeVersionList = class&#xA;    interface IList&lt;ProvisionedFabricCodeVersion&gt;&#xA;    interface ICollection&lt;ProvisionedFabricCodeVersion&gt;&#xA;    interface seq&lt;ProvisionedFabricCodeVersion&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Fabric.Query.ProvisionedFabricCodeVersion&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Fabric.Query.ProvisionedFabricCodeVersion&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IList&lt;System.Fabric.Query.ProvisionedFabricCodeVersion&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>呼び出して取得プロビジョニング済みの Service Fabric コードのバージョンの一覧を表す<see cref="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.Query.ProvisionedFabricCodeVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class System.Fabric.Query.ProvisionedFabricCodeVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricCodeVersionList.Add(System.Fabric.Query.ProvisionedFabricCodeVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As ProvisionedFabricCodeVersion)" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Fabric.Query.ProvisionedFabricCodeVersion -&gt; unit&#xA;override this.Add : System.Fabric.Query.ProvisionedFabricCodeVersion -&gt; unit" Usage="provisionedFabricCodeVersionList.Add item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricCodeVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>一覧に追加する項目。</para>
        </param>
        <summary>
          <para>指定した項目を一覧に追加します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricCodeVersionList.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="provisionedFabricCodeVersionList.Clear " />
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
          <para>リストからすべての項目を削除します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.Query.ProvisionedFabricCodeVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class System.Fabric.Query.ProvisionedFabricCodeVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricCodeVersionList.Contains(System.Fabric.Query.ProvisionedFabricCodeVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As ProvisionedFabricCodeVersion) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Fabric.Query.ProvisionedFabricCodeVersion -&gt; bool&#xA;override this.Contains : System.Fabric.Query.ProvisionedFabricCodeVersion -&gt; bool" Usage="provisionedFabricCodeVersionList.Contains item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricCodeVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>検索する項目。</para>
        </param>
        <summary>
          <para>一覧が、指定した項目を含むかどうかを示します。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>項目です。 それ以外の場合、指定された一覧に含まれる場合<languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Fabric.Query.ProvisionedFabricCodeVersion[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class System.Fabric.Query.ProvisionedFabricCodeVersion[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricCodeVersionList.CopyTo(System.Fabric.Query.ProvisionedFabricCodeVersion[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As ProvisionedFabricCodeVersion(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Fabric.Query.ProvisionedFabricCodeVersion[] * int -&gt; unit&#xA;override this.CopyTo : System.Fabric.Query.ProvisionedFabricCodeVersion[] * int -&gt; unit" Usage="provisionedFabricCodeVersionList.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Fabric.Query.ProvisionedFabricCodeVersion[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">
          <para>コピーする項目の配列。</para>
        </param>
        <param name="arrayIndex">
          <para>項目の配列のコピー先インデックスです。</para>
        </param>
        <summary>
          <para>一覧から指定された配列の指定した開始インデックス位置に項目をコピーします。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ProvisionedFabricCodeVersionList.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="System.Fabric.Query.ProvisionedFabricCodeVersionList.Count" />
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
          <para>取得または、この一覧の項目の数を設定します。</para>
        </summary>
        <value>
          <para>この一覧のアイテムの数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricCodeVersion&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersion&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricCodeVersionList.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of ProvisionedFabricCodeVersion)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricCodeVersion&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricCodeVersion&gt;" Usage="provisionedFabricCodeVersionList.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.Query.ProvisionedFabricCodeVersion&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>この一覧に項目を列挙子を取得します。</para>
        </summary>
        <returns>
          <para>リストを反復処理する列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexOf">
      <MemberSignature Language="C#" Value="public int IndexOf (System.Fabric.Query.ProvisionedFabricCodeVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 IndexOf(class System.Fabric.Query.ProvisionedFabricCodeVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricCodeVersionList.IndexOf(System.Fabric.Query.ProvisionedFabricCodeVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function IndexOf (item As ProvisionedFabricCodeVersion) As Integer" />
      <MemberSignature Language="F#" Value="abstract member IndexOf : System.Fabric.Query.ProvisionedFabricCodeVersion -&gt; int&#xA;override this.IndexOf : System.Fabric.Query.ProvisionedFabricCodeVersion -&gt; int" Usage="provisionedFabricCodeVersionList.IndexOf item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricCodeVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>指定された項目。</para>
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
      <MemberSignature Language="C#" Value="public void Insert (int index, System.Fabric.Query.ProvisionedFabricCodeVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Insert(int32 index, class System.Fabric.Query.ProvisionedFabricCodeVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricCodeVersionList.Insert(System.Int32,System.Fabric.Query.ProvisionedFabricCodeVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Insert (index As Integer, item As ProvisionedFabricCodeVersion)" />
      <MemberSignature Language="F#" Value="abstract member Insert : int * System.Fabric.Query.ProvisionedFabricCodeVersion -&gt; unit&#xA;override this.Insert : int * System.Fabric.Query.ProvisionedFabricCodeVersion -&gt; unit" Usage="provisionedFabricCodeVersionList.Insert (index, item)" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricCodeVersion" />
      </Parameters>
      <Docs>
        <param name="index">
          <para>項目を挿入する場所です。</para>
        </param>
        <param name="item">
          <para>挿入する項目。</para>
        </param>
        <summary>
          <para>指定したインデックス位置の項目を挿入します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ProvisionedFabricCodeVersionList.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="System.Fabric.Query.ProvisionedFabricCodeVersionList.IsReadOnly" />
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
          <para>取得またはリストが読み取り専用かどうかを示すフラグを設定します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>のみです。 それ以外の場合、一覧を読み取る場合<languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ProvisionedFabricCodeVersion this[int index] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ProvisionedFabricCodeVersion Item(int32)" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ProvisionedFabricCodeVersionList.Item(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(index As Integer) As ProvisionedFabricCodeVersion" />
      <MemberSignature Language="F#" Value="member this.Item(int) : System.Fabric.Query.ProvisionedFabricCodeVersion with get, set" Usage="System.Fabric.Query.ProvisionedFabricCodeVersionList.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IList`1.Item(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ProvisionedFabricCodeVersion</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="index">
          <para>項目のインデックス。</para>
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
      <MemberSignature Language="C#" Value="public bool Remove (System.Fabric.Query.ProvisionedFabricCodeVersion item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class System.Fabric.Query.ProvisionedFabricCodeVersion item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricCodeVersionList.Remove(System.Fabric.Query.ProvisionedFabricCodeVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As ProvisionedFabricCodeVersion) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Fabric.Query.ProvisionedFabricCodeVersion -&gt; bool&#xA;override this.Remove : System.Fabric.Query.ProvisionedFabricCodeVersion -&gt; bool" Usage="provisionedFabricCodeVersionList.Remove item" />
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
        <Parameter Name="item" Type="System.Fabric.Query.ProvisionedFabricCodeVersion" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>削除する項目。</para>
        </param>
        <summary>
          <para>この一覧から、指定した項目を削除します。</para>
        </summary>
        <returns>
          <para>削除された項目の一覧です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveAt">
      <MemberSignature Language="C#" Value="public void RemoveAt (int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RemoveAt(int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricCodeVersionList.RemoveAt(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveAt (index As Integer)" />
      <MemberSignature Language="F#" Value="abstract member RemoveAt : int -&gt; unit&#xA;override this.RemoveAt : int -&gt; unit" Usage="provisionedFabricCodeVersionList.RemoveAt index" />
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
          <para>削除する項目のインデックス。</para>
        </param>
        <summary>
          <para>指定したインデックス位置にある項目を削除します</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ProvisionedFabricCodeVersionList.System#Collections#IEnumerable#GetEnumerator" />
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
          <para>この一覧の項目の列挙子を取得します。</para>
        </summary>
        <returns>
          <para>リストを反復処理する列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>