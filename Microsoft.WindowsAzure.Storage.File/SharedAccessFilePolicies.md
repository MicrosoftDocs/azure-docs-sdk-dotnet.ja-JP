<Type Name="SharedAccessFilePolicies" FullName="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessFilePolicies : System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;, System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;, System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessFilePolicies extends System.Object implements class System.Collections.Generic.ICollection`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessFilePolicies&#xA;Implements ICollection(Of KeyValuePair(Of String, SharedAccessFilePolicy)), IDictionary(Of String, SharedAccessFilePolicy), IEnumerable(Of KeyValuePair(Of String, SharedAccessFilePolicy))" />
  <TypeSignature Language="F#" Value="type SharedAccessFilePolicies = class&#xA;    interface IDictionary&lt;string, SharedAccessFilePolicy&gt;&#xA;    interface ICollection&lt;KeyValuePair&lt;string, SharedAccessFilePolicy&gt;&gt;&#xA;    interface seq&lt;KeyValuePair&lt;string, SharedAccessFilePolicy&gt;&gt;&#xA;    interface IEnumerable" />
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
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="c92d2-101">共有に対して定義されている共有アクセス ポリシーのコレクションを表します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-101">Represents the collection of shared access policies defined for a share.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessFilePolicies ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.#ctor" />
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
      <MemberSignature Language="C#" Value="public void Add (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Add(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As KeyValuePair(Of String, SharedAccessFilePolicy))" />
      <MemberSignature Language="F#" Value="abstract member Add : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; unit&#xA;override this.Add : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; unit" Usage="sharedAccessFilePolicies.Add item" />
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
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="c92d2-102"><see cref="T:System.Collections.Generic.KeyValuePair`2" />キーを含むオブジェクト/<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />共有アクセス ポリシーのコレクションに追加する、ペアの値します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-102">The <see cref="T:System.Collections.Generic.KeyValuePair`2" /> object, containing a key/<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value pair, to add to the shared access policies collection.</span></span></param>
        <summary>
            <span data-ttu-id="c92d2-103">指定したキーを追加/<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />に格納された値、 <see cref="T:System.Collections.Generic.KeyValuePair`2" />、共有アクセス ポリシーのコレクションにします。</span><span class="sxs-lookup"><span data-stu-id="c92d2-103">Adds the specified key/<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value, stored in a <see cref="T:System.Collections.Generic.KeyValuePair`2" />, to the collection of shared access policies.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (string key, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(string key, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Add(System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (key As String, value As SharedAccessFilePolicy)" />
      <MemberSignature Language="F#" Value="abstract member Add : string * Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy -&gt; unit&#xA;override this.Add : string * Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy -&gt; unit" Usage="sharedAccessFilePolicies.Add (key, value)" />
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
        <Parameter Name="value" Type="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="c92d2-104">キー、<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />を追加する値。</span><span class="sxs-lookup"><span data-stu-id="c92d2-104">The key of the <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value to add.</span></span></param>
        <param name="value"><span data-ttu-id="c92d2-105"><see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />値のコレクションに追加する共有アクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="c92d2-105">The <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value to add the collection of shared access policies.</span></span></param>
        <summary>
            <span data-ttu-id="c92d2-106">指定したキーを追加し、<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />共有アクセス ポリシーのコレクションに値。</span><span class="sxs-lookup"><span data-stu-id="c92d2-106">Adds the specified key and <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value to the collection of shared access policies.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="sharedAccessFilePolicies.Clear " />
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
            <span data-ttu-id="c92d2-107">すべてのキーを削除し、<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />共有アクセスのコレクションからの値。</span><span class="sxs-lookup"><span data-stu-id="c92d2-107">Removes all keys and <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> values from the shared access collection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Contains(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As KeyValuePair(Of String, SharedAccessFilePolicy)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; bool&#xA;override this.Contains : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; bool" Usage="sharedAccessFilePolicies.Contains item" />
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
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="c92d2-108">A<see cref="T:System.Collections.Generic.KeyValuePair`2" />キーを含むオブジェクトと<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />検索する値。</span><span class="sxs-lookup"><span data-stu-id="c92d2-108">A <see cref="T:System.Collections.Generic.KeyValuePair`2" /> object containing the key and <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value to search for.</span></span></param>
        <summary>
            <span data-ttu-id="c92d2-109">共有アクセス ポリシーのコレクションにキーが含まれるかどうかを判断し、 <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> 、指定した値<see cref="T:System.Collections.Generic.KeyValuePair`2" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c92d2-109">Determines whether the collection of shared access policies contains the key and <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value in the specified <see cref="T:System.Collections.Generic.KeyValuePair`2" /> object.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="c92d2-110"><c>true</c>共有アクセス ポリシーのコレクションには、指定したキー/値が含まれている場合、それ以外の場合<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="c92d2-110"><c>true</c> if the shared access policies collection contains the specified key/value; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsKey">
      <MemberSignature Language="C#" Value="public bool ContainsKey (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ContainsKey(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.ContainsKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsKey (key As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ContainsKey : string -&gt; bool&#xA;override this.ContainsKey : string -&gt; bool" Usage="sharedAccessFilePolicies.ContainsKey key" />
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
        <param name="key"><span data-ttu-id="c92d2-111">共有アクセス ポリシーのコレクション内で検索するキー。</span><span class="sxs-lookup"><span data-stu-id="c92d2-111">The key to locate in the collection of shared access policies.</span></span></param>
        <summary>
            <span data-ttu-id="c92d2-112">共有アクセス ポリシーのコレクションに指定したキーが含まれているかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-112">Determines whether the collection of shared access policies contains the specified key.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="c92d2-113"><c>true</c>共有アクセス ポリシーのコレクションでは、指定されたキーを持つ要素が含まれている場合、それ以外の場合<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="c92d2-113"><c>true</c> if the collection of shared access policies contains an element with the specified key; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.CopyTo(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy}[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As KeyValuePair(Of String, SharedAccessFilePolicy)(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;[] * int -&gt; unit&#xA;override this.CopyTo : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;[] * int -&gt; unit" Usage="sharedAccessFilePolicies.CopyTo (array, arrayIndex)" />
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
        <Parameter Name="array" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array"><span data-ttu-id="c92d2-114">1 次元配列<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />共有アクセス ポリシーのコレクションからコピーされた要素の接続先として機能するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c92d2-114">A one-dimensional array of <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> objects that serves as the destination for the elements copied from the shared access policies collection.</span></span></param>
        <param name="arrayIndex"><span data-ttu-id="c92d2-115">コピーの開始位置とする <paramref name="array" /> のインデックス (0 から始まる)。</span><span class="sxs-lookup"><span data-stu-id="c92d2-115">The zero-based index in <paramref name="array" /> at which copying begins.</span></span></param>
        <summary>
            <span data-ttu-id="c92d2-116">キー内の各キーのコピー/<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />値のペア互換性のある 1 次元配列を対象となる配列の指定したインデックスから始まります。</span><span class="sxs-lookup"><span data-stu-id="c92d2-116">Copies each key in the key/<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value pair to a compatible one-dimensional array, starting at the specified index of the target array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Count" />
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
            <span data-ttu-id="c92d2-117">キーの数を取得/<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />共有アクセス ポリシーのコレクションに含まれるペアの値します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-117">Gets the number of key/<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value pairs contained in the shared access policies collection.</span></span>
            </summary>
        <value><span data-ttu-id="c92d2-118">キーの数/<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />共有アクセス ポリシーのコレクションに含まれるペアの値します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-118">The number of key/<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value pairs contained in the shared access policies collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of KeyValuePair(Of String, SharedAccessFilePolicy))" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;" Usage="sharedAccessFilePolicies.GetEnumerator " />
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
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c92d2-119">共有アクセス ポリシーのコレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-119">Returns an enumerator that iterates through the collection of shared access policies.</span></span>
            </summary>
        <returns><span data-ttu-id="c92d2-120"><see cref="T:System.Collections.Generic.IEnumerator`1" /> 型の <see cref="T:System.Collections.Generic.KeyValuePair`2" />。</span><span class="sxs-lookup"><span data-stu-id="c92d2-120">An <see cref="T:System.Collections.Generic.IEnumerator`1" /> of type <see cref="T:System.Collections.Generic.KeyValuePair`2" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.IsReadOnly" />
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
            <span data-ttu-id="c92d2-121">共有アクセス ポリシーのコレクションが読み取り専用かどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-121">Gets a value indicating whether the collection of shared access policies is read-only.</span></span> 
            </summary>
        <value>
          <span data-ttu-id="c92d2-122"><c>true</c>共有アクセス ポリシーのコレクションが読み取り専用、それ以外の場合は<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="c92d2-122"><c>true</c> if the collection of shared access policies is read-only; otherwise, <c>false</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy this[string key] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(key As String) As SharedAccessFilePolicy" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Item" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="c92d2-123">キーを含む文字列、<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-123">A string containing the key of the <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value to get or set.</span></span></param>
        <summary>
            <span data-ttu-id="c92d2-124">取得または設定、<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />指定されたキーに関連付けられている項目。</span><span class="sxs-lookup"><span data-stu-id="c92d2-124">Gets or sets the <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> item associated with the specified key.</span></span>
            </summary>
        <value><span data-ttu-id="c92d2-125"><see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> 、指定したキーに関連付けられた項目または<c>null</c>キーが共有アクセス ポリシーのコレクションにない場合。</span><span class="sxs-lookup"><span data-stu-id="c92d2-125">The <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> item associated with the specified key, or <c>null</c> if key is not in the shared access policies collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;string&gt; Keys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;string&gt; Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Keys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Keys As ICollection(Of String)" />
      <MemberSignature Language="F#" Value="member this.Keys : System.Collections.Generic.ICollection&lt;string&gt;" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Keys" />
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
            <span data-ttu-id="c92d2-126">共有アクセス ポリシーのコレクション内のキーを含むコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-126">Gets a collection containing the keys in the shared access policies collection.</span></span>
            </summary>
        <value><span data-ttu-id="c92d2-127">共有アクセス ポリシーのコレクションのキーを格納する文字列のコレクション。</span><span class="sxs-lookup"><span data-stu-id="c92d2-127">A collection of strings containing the keys of the shared access policies collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (System.Collections.Generic.KeyValuePair&lt;string,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(valuetype System.Collections.Generic.KeyValuePair`2&lt;string, class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Remove(System.Collections.Generic.KeyValuePair{System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy})" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As KeyValuePair(Of String, SharedAccessFilePolicy)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; bool&#xA;override this.Remove : System.Collections.Generic.KeyValuePair&lt;string, Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; -&gt; bool" Usage="sharedAccessFilePolicies.Remove item" />
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
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="c92d2-128"><see cref="T:System.Collections.Generic.KeyValuePair`2" />キーを含むオブジェクトと<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />値、共有アクセス ポリシーのコレクションから削除します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-128">The <see cref="T:System.Collections.Generic.KeyValuePair`2" /> object, containing a key and <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value, to remove from the shared access policies collection.</span></span></param>
        <summary>
            <span data-ttu-id="c92d2-129">削除、<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />で指定された値、<see cref="T:System.Collections.Generic.KeyValuePair`2" />共有アクセス ポリシーのコレクションからのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="c92d2-129">Removes the <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> value, specified in the <see cref="T:System.Collections.Generic.KeyValuePair`2" /> object, from the shared access policies collection.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="c92d2-130"><c>true</c>した項目が正常に削除された、それ以外の場合<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="c92d2-130"><c>true</c> if the item was successfully removed; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Remove(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (key As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : string -&gt; bool&#xA;override this.Remove : string -&gt; bool" Usage="sharedAccessFilePolicies.Remove key" />
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
        <param name="key"><span data-ttu-id="c92d2-131">キーを含む文字列、<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />削除する項目。</span><span class="sxs-lookup"><span data-stu-id="c92d2-131">A string containing the key of the <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> item to remove.</span></span></param>
        <summary>
            <span data-ttu-id="c92d2-132">共有アクセス ポリシーのコレクションから指定されたキーに値を削除します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-132">Removes the value with the specified key from the shared access policies collection.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="c92d2-133"><c>true</c>要素が正常に検出し、削除された、それ以外の場合<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="c92d2-133"><c>true</c> if the element is successfully found and removed; otherwise, <c>false</c>.</span></span> <span data-ttu-id="c92d2-134">このメソッドが戻る<c>false</c>キーが見つからない場合。</span><span class="sxs-lookup"><span data-stu-id="c92d2-134">This method returns <c>false</c> if the key is not found.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.System#Collections#IEnumerable#GetEnumerator" />
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
            <span data-ttu-id="c92d2-135">共有アクセス ポリシーのコレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-135">Returns an enumerator that iterates through the collection of shared access policies.</span></span>
            </summary>
        <returns><span data-ttu-id="c92d2-136"><see cref="T:System.Collections.IEnumerator" />オブジェクトのコレクションを反復処理に使用できる共有アクセス ポリシー。</span><span class="sxs-lookup"><span data-stu-id="c92d2-136">An <see cref="T:System.Collections.IEnumerator" /> object that can be used to iterate through the collection of shared access policies.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetValue">
      <MemberSignature Language="C#" Value="public bool TryGetValue (string key, out Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetValue(string key, [out] class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&amp; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.TryGetValue(System.String,Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetValue (key As String, ByRef value As SharedAccessFilePolicy) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetValue : string *  -&gt; bool&#xA;override this.TryGetValue : string *  -&gt; bool" Usage="sharedAccessFilePolicies.TryGetValue (key, value)" />
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
        <Parameter Name="value" Type="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="c92d2-137">取得する値のキーを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="c92d2-137">A string containing the key of the value to get.</span></span></param>
        <param name="value"><span data-ttu-id="c92d2-138"><see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />を取得する項目。</span><span class="sxs-lookup"><span data-stu-id="c92d2-138">The <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> item to get.</span></span></param>
        <summary>
            <span data-ttu-id="c92d2-139">取得、<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />指定されたキーに関連付けられている項目。</span><span class="sxs-lookup"><span data-stu-id="c92d2-139">Gets the <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> item associated with the specified key.</span></span> 
            </summary>
        <returns><span data-ttu-id="c92d2-140"><see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />項目; に関連付けられた、指定したキー、キーが見つかった場合、既定値をそれ以外の場合、<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />型です。</span><span class="sxs-lookup"><span data-stu-id="c92d2-140">The <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> item associated with the specified key, if the key is found; otherwise, the default value for the <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As ICollection(Of SharedAccessFilePolicy)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicies.Values" />
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
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c92d2-141">共有アクセス ポリシーのコレクション内の値を含むコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="c92d2-141">Gets a collection containing the values in the shared access policies collection.</span></span>
            </summary>
        <value><span data-ttu-id="c92d2-142">コレクション<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />共有アクセス ポリシーのコレクション内の項目。</span><span class="sxs-lookup"><span data-stu-id="c92d2-142">A collection of <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" /> items in the shared access policies collection.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>