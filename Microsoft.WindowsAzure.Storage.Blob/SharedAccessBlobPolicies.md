<Type Name="SharedAccessBlobPolicies" FullName="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessBlobPolicies : System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;&gt;, System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;, System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessBlobPolicies extends System.Object implements class System.Collections.Generic.ICollection`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;&gt;, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessBlobPolicies&#xA;Implements ICollection(Of KeyValuePair(Of String, SharedAccessBlobPolicy)), IDictionary(Of String, SharedAccessBlobPolicy), IEnumerable(Of KeyValuePair(Of String, SharedAccessBlobPolicy))" />
  <TypeSignature Language="F#" Value="type SharedAccessBlobPolicies = class&#xA;    interface IDictionary&lt;string, SharedAccessBlobPolicy&gt;&#xA;    interface ICollection&lt;KeyValuePair&lt;string, SharedAccessBlobPolicy&gt;&gt;&#xA;    interface seq&lt;KeyValuePair&lt;string, SharedAccessBlobPolicy&gt;&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            コンテナーに対して定義されている共有アクセス ポリシーのコレクションを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessBlobPolicies ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Add(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As KeyValuePair(Of String, SharedAccessBlobPolicy))" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; -&gt; unit&#xA;override this.Add : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; -&gt; unit" Usage="sharedAccessBlobPolicies.Add item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Add(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item"><see cref="T:System.Collections.Generic.KeyValuePair`2" />キーを含むオブジェクト/<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />共有アクセス ポリシーのコレクションに追加する、ペアの値します。</param>
        <summary>
            指定したキーを追加/<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />に格納された値、 <see cref="T:System.Collections.Generic.KeyValuePair`2" />、共有アクセス ポリシーのコレクションにします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (string key, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(string key, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Add(System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (key As String, value As SharedAccessBlobPolicy)" />
      <MemberSignature Language="F#" Value="abstract member Add : string * Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy -&gt; unit&#xA;override this.Add : string * Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy -&gt; unit" Usage="sharedAccessBlobPolicies.Add (key, value)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IDictionary`2.Add(`0,`1)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />
      </Parameters>
      <Docs>
        <param name="key">キー、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />を追加する値。</param>
        <param name="value"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />値のコレクションに追加する共有アクセス ポリシー。</param>
        <summary>
            指定したキーを追加し、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />共有アクセス ポリシーのコレクションに値。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="sharedAccessBlobPolicies.Clear " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Clear</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            すべてのキーを削除し、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />共有アクセスのコレクションからの値。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Contains(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As KeyValuePair(Of String, SharedAccessBlobPolicy)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; -&gt; bool&#xA;override this.Contains : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; -&gt; bool" Usage="sharedAccessBlobPolicies.Contains item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Contains(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item">A<see cref="T:System.Collections.Generic.KeyValuePair`2" />キーを含むオブジェクトと<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />検索する値。</param>
        <summary>
            共有アクセス ポリシーのコレクションにキーが含まれるかどうかを判断し、 <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> 、指定した値<see cref="T:System.Collections.Generic.KeyValuePair`2" />オブジェクト。
            </summary>
        <returns>
          <c>true</c>共有アクセス ポリシーのコレクションには、指定したキー/値が含まれている場合、それ以外の場合<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsKey">
      <MemberSignature Language="C#" Value="public bool ContainsKey (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ContainsKey(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.ContainsKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsKey (key As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ContainsKey : string -&gt; bool&#xA;override this.ContainsKey : string -&gt; bool" Usage="sharedAccessBlobPolicies.ContainsKey key" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IDictionary`2.ContainsKey(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">共有アクセス ポリシーのコレクション内で検索するキー。</param>
        <summary>
            共有アクセス ポリシーのコレクションに指定したキーが含まれているかどうかを判断します。
            </summary>
        <returns>
          <c>true</c>共有アクセス ポリシーのコレクションでは、指定されたキーを持つ要素が含まれている場合、それ以外の場合<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.CopyTo(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy}[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As KeyValuePair(Of String, SharedAccessBlobPolicy)(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;[] * int -&gt; unit&#xA;override this.CopyTo : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;[] * int -&gt; unit" Usage="sharedAccessBlobPolicies.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">1 次元配列<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />共有アクセス ポリシーのコレクションからコピーされた要素の接続先として機能するオブジェクト。</param>
        <param name="arrayIndex">コピーの開始位置とする <paramref name="array" /> のインデックス (0 から始まる)。</param>
        <summary>
            キー内の各キーのコピー/<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />値のペア互換性のある 1 次元配列を対象となる配列の指定したインデックスから始まります。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Count" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.Count</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キーの数を取得/<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />共有アクセス ポリシーのコレクションに含まれるペアの値します。
            </summary>
        <value>キーの数/<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />共有アクセス ポリシーのコレクションに含まれるペアの値します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of KeyValuePair(Of String, SharedAccessBlobPolicy))" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;&gt;" Usage="sharedAccessBlobPolicies.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            共有アクセス ポリシーのコレクションを反復処理する列挙子を返します。
            </summary>
        <returns><see cref="T:System.Collections.Generic.IEnumerator`1" /> 型の <see cref="T:System.Collections.Generic.KeyValuePair`2" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            共有アクセス ポリシーのコレクションが読み取り専用かどうかを示す値を取得します。 
            </summary>
        <value>
          <c>true</c>共有アクセス ポリシーのコレクションが読み取り専用、それ以外の場合は<c>false</c>です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy this[string key] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(key As String) As SharedAccessBlobPolicy" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IDictionary`2.Item(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">キーを含む文字列、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />値を取得または設定します。</param>
        <summary>
            取得または設定、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />指定されたキーに関連付けられている項目。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> 、指定したキーに関連付けられた項目または<c>null</c>キーが共有アクセス ポリシーのコレクションにない場合。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;string&gt; Keys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;string&gt; Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Keys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Keys As ICollection(Of String)" />
      <MemberSignature Language="F#" Value="member this.Keys : System.Collections.Generic.ICollection&lt;string&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Keys" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IDictionary`2.Keys</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            共有アクセス ポリシーのコレクション内のキーを含むコレクションを取得します。
            </summary>
        <value>共有アクセス ポリシーのコレクションのキーを格納する文字列のコレクション。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Remove(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As KeyValuePair(Of String, SharedAccessBlobPolicy)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; -&gt; bool&#xA;override this.Remove : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; -&gt; bool" Usage="sharedAccessBlobPolicies.Remove item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item"><see cref="T:System.Collections.Generic.KeyValuePair`2" />キーを含むオブジェクトと<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />値、共有アクセス ポリシーのコレクションから削除します。</param>
        <summary>
            削除、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />で指定された値、<see cref="T:System.Collections.Generic.KeyValuePair`2" />共有アクセス ポリシーのコレクションからのオブジェクト。
            </summary>
        <returns>
          <c>true</c>した項目が正常に削除された、それ以外の場合<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Remove(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (key As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : string -&gt; bool&#xA;override this.Remove : string -&gt; bool" Usage="sharedAccessBlobPolicies.Remove key" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IDictionary`2.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">キーを含む文字列、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />削除する項目。</param>
        <summary>
            共有アクセス ポリシーのコレクションから指定されたキーに値を削除します。
            </summary>
        <returns>
          <c>true</c>要素が正常に検出し、削除された、それ以外の場合<c>false</c>です。 このメソッドが戻る<c>false</c>キーが見つからない場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            共有アクセス ポリシーのコレクションを反復処理する列挙子を返します。
            </summary>
        <returns><see cref="T:System.Collections.IEnumerator" />オブジェクトのコレクションを反復処理に使用できる共有アクセス ポリシー。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetValue">
      <MemberSignature Language="C#" Value="public bool TryGetValue (string key, out Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetValue(string key, [out] class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&amp; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.TryGetValue(System.String,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetValue (key As String, ByRef value As SharedAccessBlobPolicy) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetValue : string *  -&gt; bool&#xA;override this.TryGetValue : string *  -&gt; bool" Usage="sharedAccessBlobPolicies.TryGetValue (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="key">取得する値のキーを表す文字列。</param>
        <param name="value"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />を取得する項目。</param>
        <summary>
            取得、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />指定されたキーに関連付けられている項目。 
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />項目; に関連付けられた、指定したキー、キーが見つかった場合、既定値をそれ以外の場合、<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />型です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As ICollection(Of SharedAccessBlobPolicy)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies.Values" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IDictionary`2.Values</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            共有アクセス ポリシーのコレクション内の値を含むコレクションを取得します。
            </summary>
        <value>コレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />共有アクセス ポリシーのコレクション内の項目。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>