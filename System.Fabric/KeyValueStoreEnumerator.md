<Type Name="KeyValueStoreEnumerator" FullName="System.Fabric.KeyValueStoreEnumerator">
  <TypeSignature Language="C#" Value="public sealed class KeyValueStoreEnumerator" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KeyValueStoreEnumerator extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreEnumerator" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KeyValueStoreEnumerator" />
  <TypeSignature Language="F#" Value="type KeyValueStoreEnumerator = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>コピー完了コールバックのコンテキスト内でセカンダリ レプリカのローカル ストアの内容を読み取ります。</para>
      <seealso cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.Enumerate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Enumerate (keyPrefix As String) As IEnumerator(Of KeyValueStoreItem)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreEnumerator.Enumerate keyPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para>列挙中に適用するオプションのキーのプレフィックス フィルターを指定します。</para>
        </param>
        <summary>
          <para>ローカル ストアの内容を列挙し、キーと値のペアが列挙されたすべてのデータ値が含まれています。</para>
        </summary>
        <returns>
          <para>ローカル ストアの内容に対する列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.Enumerate(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function Enumerate (keyPrefix As String, strictPrefix As Boolean) As IEnumerator(Of KeyValueStoreItem)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreEnumerator.Enumerate (keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para>列挙中に適用するオプションのキーのプレフィックス フィルターを指定します。</para>
        </param>
        <param name="strictPrefix">
          <para>True の場合に指定された値を付けたキーのみ<b>keyPrefix</b>が返されます。 一致する、または辞書を超える最初のキーに列挙を開始するそれ以外の場合、 <b>keyPrefix</b>いないキーが複数あるまで継続します。 既定値は <b>true</b> です。</para>
        </param>
        <summary>
          <para>ローカル ストアの内容を列挙し、キーと値のペアが列挙されたすべてのデータ値が含まれています。</para>
        </summary>
        <returns>
          <para>ローカル ストアの内容に対する列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.EnumerateMetadata(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumerateMetadata (keyPrefix As String) As IEnumerator(Of KeyValueStoreItemMetadata)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreEnumerator.EnumerateMetadata keyPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para>列挙中に適用する、省略可能なプレフィックス フィルターを指定します。</para>
        </param>
        <summary>
          <para>ローカル ストアの内容を列挙しますが、キーと値のペアが列挙されたすべてのデータ値が含まれません。</para>
        </summary>
        <returns>
          <para>ローカル ストアの内容に対する列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreEnumerator.EnumerateMetadata(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumerateMetadata (keyPrefix As String, strictPrefix As Boolean) As IEnumerator(Of KeyValueStoreItemMetadata)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreEnumerator.EnumerateMetadata (keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="keyPrefix">
          <para>列挙中に適用するオプションのキーのプレフィックス フィルターを指定します。</para>
        </param>
        <param name="strictPrefix">
          <para>True の場合に指定された値を付けたキーのみ<b>keyPrefix</b>が返されます。 一致する、または辞書を超える最初のキーに列挙を開始するそれ以外の場合、 <b>keyPrefix</b>いないキーが複数あるまで継続します。 既定値は <b>true</b> です。</para>
        </param>
        <summary>
          <para>ローカル ストアの内容を列挙しますが、キーと値のペアが列挙されたすべてのデータ値が含まれません。</para>
        </summary>
        <returns>
          <para>ローカル ストアの内容に対する列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>