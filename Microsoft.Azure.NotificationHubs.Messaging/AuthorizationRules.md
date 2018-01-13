<Type Name="AuthorizationRules" FullName="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules">
  <TypeSignature Language="C#" Value="public class AuthorizationRules : System.Collections.Generic.ICollection&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AuthorizationRules extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthorizationRules&#xA;Implements ICollection(Of AuthorizationRule), IEnumerable(Of AuthorizationRule)" />
  <TypeSignature Language="F#" Value="type AuthorizationRules = class&#xA;    interface ICollection&lt;AuthorizationRule&gt;&#xA;    interface seq&lt;AuthorizationRule&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.CollectionDataContract(ItemName="AuthorizationRule", Name="AuthorizationRules", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>コレクションを表します<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />です。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationRules ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationRules (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; enumerable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; enumerable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enumerable As IEnumerable(Of AuthorizationRule))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules : seq&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; -&gt; Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" Usage="new Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules enumerable" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enumerable" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;" />
      </Parameters>
      <Docs>
        <param name="enumerable">一連の<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />します。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" />のリストがクラス<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />です。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.Add(Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As AuthorizationRule)" />
      <MemberSignature Language="F#" Value="abstract member Add : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule -&gt; unit&#xA;override this.Add : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule -&gt; unit" Usage="authorizationRules.Add item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Add(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />
      </Parameters>
      <Docs>
        <param name="item">追加される <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />。</param>
        <summary>指定した追加<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />コレクションにします。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="authorizationRules.Clear " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Clear</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>コレクション内のすべての要素を消去します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.Contains(Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As AuthorizationRule) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule -&gt; bool&#xA;override this.Contains : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule -&gt; bool" Usage="authorizationRules.Contains item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Contains(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />
      </Parameters>
      <Docs>
        <param name="item">コレクション内で検索する項目。</param>
        <summary>指定した項目がコレクション内に存在するかどうかを判断します。</summary>
        <returns>指定した項目が見つかった場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.CopyTo(Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As AuthorizationRule(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule[] * int -&gt; unit&#xA;override this.CopyTo : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule[] * int -&gt; unit" Usage="authorizationRules.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">コピーされた要素を保持する配列。</param>
        <param name="arrayIndex">コピーの開始位置を示す 0 から始まるインデックス。</param>
        <summary>指定した配列インデックスから始まる配列に要素をコピーします。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.Count" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.Count</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定数<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />コレクションに含まれています。</summary>
        <value>数<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />コレクションに含まれています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;" Usage="authorizationRules.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>コレクションを反復処理する列挙子を取得します。</summary>
        <returns>コレクションを反復処理に使用できる列挙子。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; GetRules (Predicate&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; match);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.List`1&lt;class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; GetRules(class System.Predicate`1&lt;class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; match) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.GetRules(System.Predicate{Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRules (match As Predicate(Of AuthorizationRule)) As List(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="member this.GetRules : Predicate&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; -&gt; System.Collections.Generic.List&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;" Usage="authorizationRules.GetRules match" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="match" Type="System.Predicate&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;" />
      </Parameters>
      <Docs>
        <param name="match">指定した値と一致する承認規則。</param>
        <summary>セットを取得<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />です。</summary>
        <returns>セット<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />指定した値に一致します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; GetRules (string claimValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.List`1&lt;class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; GetRules(string claimValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.GetRules(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRules (claimValue As String) As List(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="member this.GetRules : string -&gt; System.Collections.Generic.List&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;" Usage="authorizationRules.GetRules claimValue" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="claimValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="claimValue">検索する値。</param>
        <summary>セットを取得<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />指定した値に一致します。</summary>
        <returns>セット<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />指定した値に一致します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasEqualRuntimeBehavior">
      <MemberSignature Language="C#" Value="public bool HasEqualRuntimeBehavior (Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules comparand);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool HasEqualRuntimeBehavior(class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules comparand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.HasEqualRuntimeBehavior(Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules)" />
      <MemberSignature Language="VB.NET" Value="Public Function HasEqualRuntimeBehavior (comparand As AuthorizationRules) As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasEqualRuntimeBehavior : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules -&gt; bool" Usage="authorizationRules.HasEqualRuntimeBehavior comparand" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="comparand" Type="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" />
      </Parameters>
      <Docs>
        <param name="comparand"><see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" />現在のオブジェクトと比較します。</param>
        <summary>決定するかどうか、指定した<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" />この現在のオブジェクトと等しいランタイム動作します。</summary>
        <returns>場合、true、等しく実行時の動作です。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="innerCollection">
      <MemberSignature Language="C#" Value="public readonly System.Collections.Generic.ICollection&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; innerCollection;" />
      <MemberSignature Language="ILAsm" Value=".field public initonly class System.Collections.Generic.ICollection`1&lt;class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt; innerCollection" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.innerCollection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly innerCollection As ICollection(Of AuthorizationRule) " />
      <MemberSignature Language="F#" Value="val mutable innerCollection : System.Collections.Generic.ICollection&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.innerCollection" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>内部コレクションを指定します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定するかどうか、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" />は読み取り専用です。</summary>
        <value>true の場合、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" />は読み取りだけです。 それ以外の場合は false。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.Remove(Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As AuthorizationRule) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule -&gt; bool&#xA;override this.Remove : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule -&gt; bool" Usage="authorizationRules.Remove item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" />
      </Parameters>
      <Docs>
        <param name="item">削除する項目。</param>
        <summary>指定された <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRule" /> をコレクションから削除します。</summary>
        <returns>操作が成功した場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresEncryption">
      <MemberSignature Language="C#" Value="public bool RequiresEncryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.RequiresEncryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequiresEncryption As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresEncryption : bool" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.RequiresEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>示す値を取得するかどうか、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" />暗号化が必要です。</summary>
        <value>true の場合、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" />暗号化が必要です。 それ以外の場合は false。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serializer">
      <MemberSignature Language="C#" Value="public static readonly System.Runtime.Serialization.DataContractSerializer Serializer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Runtime.Serialization.DataContractSerializer Serializer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.Serializer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Serializer As DataContractSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable Serializer : System.Runtime.Serialization.DataContractSerializer" Usage="Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.Serializer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.DataContractSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>オブジェクトをシリアル化と、シリアライザーを指定します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>コレクションを反復処理する列挙子を取得します。</summary>
        <returns>コレクションを反復処理に使用できる列挙子。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetSharedAccessAuthorizationRule">
      <MemberSignature Language="C#" Value="public bool TryGetSharedAccessAuthorizationRule (string keyName, out Microsoft.Azure.NotificationHubs.Messaging.SharedAccessAuthorizationRule rule);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetSharedAccessAuthorizationRule(string keyName, [out] class Microsoft.Azure.NotificationHubs.Messaging.SharedAccessAuthorizationRule&amp; rule) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules.TryGetSharedAccessAuthorizationRule(System.String,Microsoft.Azure.NotificationHubs.Messaging.SharedAccessAuthorizationRule@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetSharedAccessAuthorizationRule (keyName As String, ByRef rule As SharedAccessAuthorizationRule) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetSharedAccessAuthorizationRule : string *  -&gt; bool" Usage="authorizationRules.TryGetSharedAccessAuthorizationRule (keyName, rule)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="rule" Type="Microsoft.Azure.NotificationHubs.Messaging.SharedAccessAuthorizationRule&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="keyName">キー名。</param>
        <param name="rule">指定したキーに関連付けられているルール。</param>
        <summary>指定したキーに関連付けられているルールを取得します。</summary>
        <returns>true の場合、<see cref="T:Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" />要素が指定されたキーに含まれるそれ以外の場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>