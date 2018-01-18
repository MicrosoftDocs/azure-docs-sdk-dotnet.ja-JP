<Type Name="ReadOnlyDictionary45&lt;TKey,TValue&gt;" FullName="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public sealed class ReadOnlyDictionary45&lt;TKey,TValue&gt; : System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;, System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;, System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;, System.Collections.IDictionary" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ReadOnlyDictionary45`2&lt;TKey, TValue&gt; extends System.Object implements class System.Collections.Generic.ICollection`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;, class System.Collections.Generic.IDictionary`2&lt;!TKey, !TValue&gt;, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;, class System.Collections.ICollection, class System.Collections.IDictionary, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReadOnlyDictionary45(Of TKey, TValue)&#xA;Implements ICollection(Of KeyValuePair(Of TKey, TValue)), IDictionary, IDictionary(Of TKey, TValue), IEnumerable(Of KeyValuePair(Of TKey, TValue))" />
  <TypeSignature Language="F#" Value="type ReadOnlyDictionary45&lt;'Key, 'Value&gt; = class&#xA;    interface IDictionary&lt;'Key, 'Value&gt;&#xA;    interface ICollection&lt;KeyValuePair&lt;'Key, 'Value&gt;&gt;&#xA;    interface seq&lt;KeyValuePair&lt;'Key, 'Value&gt;&gt;&#xA;    interface IEnumerable&#xA;    interface IDictionary&#xA;    interface ICollection" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.IDictionary</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.DebuggerDisplay("Count = {Count}")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="TKey">To be added.</typeparam>
    <typeparam name="TValue">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReadOnlyDictionary45 (System.Collections.Generic.IDictionary&lt;TKey,TValue&gt; dictionary);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;!TKey, !TValue&gt; dictionary) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.#ctor(System.Collections.Generic.IDictionary{`0,`1})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (dictionary As IDictionary(Of TKey, TValue))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt; : System.Collections.Generic.IDictionary&lt;'Key, 'Value&gt; -&gt; Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;" Usage="new Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt; dictionary" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dictionary" Type="System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="dictionary">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsKey">
      <MemberSignature Language="C#" Value="public bool ContainsKey (TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ContainsKey(!TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.ContainsKey(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsKey (key As TKey) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ContainsKey : 'Key -&gt; bool&#xA;override this.ContainsKey : 'Key -&gt; bool" Usage="readOnlyDictionary45.ContainsKey key" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IDictionary`2.ContainsKey(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.Count" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.Count</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dictionary">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IDictionary&lt;TKey,TValue&gt; Dictionary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;!TKey, !TValue&gt; Dictionary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.Dictionary" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Dictionary As IDictionary(Of TKey, TValue)" />
      <MemberSignature Language="F#" Value="member this.Dictionary : System.Collections.Generic.IDictionary&lt;'Key, 'Value&gt;" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.Dictionary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of KeyValuePair(Of TKey, TValue))" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;" Usage="readOnlyDictionary45.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public TValue this[TKey key] { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TValue Item(!TKey)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.Item(`0)" />
      <MemberSignature Language="VB.NET" Value="Default Public ReadOnly Property Item(key As TKey) As TValue" />
      <MemberSignature Language="F#" Value="member this.Item('Key) : 'Value" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;TKey,TValue&gt;.KeyCollection Keys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2/KeyCollection&lt;!TKey, !TValue&gt; Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.Keys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Keys As ReadOnlyDictionary45(Of TKey, TValue).KeyCollection" />
      <MemberSignature Language="F#" Value="member this.Keys : Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.KeyCollection" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.Keys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;TKey,TValue&gt;+KeyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.Add">
      <MemberSignature Language="C#" Value="void ICollection&lt;KeyValuePair&lt;TKey,TValue&gt;&gt;.Add (System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.Add(valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#Generic#ICollection&lt;System#Collections#Generic#KeyValuePair&lt;TKey,TValue&gt;&gt;#Add(System.Collections.Generic.KeyValuePair{`0,`1})" />
      <MemberSignature Language="VB.NET" Value="Sub Add (item As KeyValuePair(Of TKey, TValue)) Implements ICollection(Of KeyValuePair(Of TKey, TValue)).Add" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Add(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="item">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.Clear">
      <MemberSignature Language="C#" Value="void ICollection&lt;KeyValuePair&lt;TKey,TValue&gt;&gt;.Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#Generic#ICollection&lt;System#Collections#Generic#KeyValuePair&lt;TKey,TValue&gt;&gt;#Clear" />
      <MemberSignature Language="VB.NET" Value="Sub Clear () Implements ICollection(Of KeyValuePair(Of TKey, TValue)).Clear" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Clear</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.Contains">
      <MemberSignature Language="C#" Value="bool ICollection&lt;KeyValuePair&lt;TKey,TValue&gt;&gt;.Contains (System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.Contains(valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#Generic#ICollection&lt;System#Collections#Generic#KeyValuePair&lt;TKey,TValue&gt;&gt;#Contains(System.Collections.Generic.KeyValuePair{`0,`1})" />
      <MemberSignature Language="VB.NET" Value="Function Contains (item As KeyValuePair(Of TKey, TValue)) As Boolean Implements ICollection(Of KeyValuePair(Of TKey, TValue)).Contains" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Contains(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="item">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.CopyTo">
      <MemberSignature Language="C#" Value="void ICollection&lt;KeyValuePair&lt;TKey,TValue&gt;&gt;.CopyTo (System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.CopyTo(valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#Generic#ICollection&lt;System#Collections#Generic#KeyValuePair&lt;TKey,TValue&gt;&gt;#CopyTo(System.Collections.Generic.KeyValuePair{`0,`1}[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Sub CopyTo (array As KeyValuePair(Of TKey, TValue)(), arrayIndex As Integer) Implements ICollection(Of KeyValuePair(Of TKey, TValue)).CopyTo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">To be added.</param>
        <param name="arrayIndex">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.IsReadOnly">
      <MemberSignature Language="C#" Value="bool System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#Generic#ICollection&lt;System#Collections#Generic#KeyValuePair&lt;TKey,TValue&gt;&gt;#IsReadOnly" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property IsReadOnly As Boolean Implements ICollection(Of KeyValuePair(Of TKey, TValue)).IsReadOnly" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.Remove">
      <MemberSignature Language="C#" Value="bool ICollection&lt;KeyValuePair&lt;TKey,TValue&gt;&gt;.Remove (System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt; item);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool System.Collections.Generic.ICollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;.Remove(valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt; item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#Generic#ICollection&lt;System#Collections#Generic#KeyValuePair&lt;TKey,TValue&gt;&gt;#Remove(System.Collections.Generic.KeyValuePair{`0,`1})" />
      <MemberSignature Language="VB.NET" Value="Function Remove (item As KeyValuePair(Of TKey, TValue)) As Boolean Implements ICollection(Of KeyValuePair(Of TKey, TValue)).Remove" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="item">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Add">
      <MemberSignature Language="C#" Value="void IDictionary&lt;TKey,TValue&gt;.Add (TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Add(!TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#Generic#IDictionary&lt;TKey,TValue&gt;#Add(`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Sub Add (key As TKey, value As TValue) Implements IDictionary(Of TKey, TValue).Add" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IDictionary`2.Add(`0,`1)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <param name="value">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Item">
      <MemberSignature Language="C#" Value="TValue System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Item[TKey key] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TValue System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Item(!TKey)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#Generic#IDictionary&lt;TKey,TValue&gt;#Item(`0)" />
      <MemberSignature Language="VB.NET" Value=" Property Item(key As TKey) As TValue Implements IDictionary(Of TKey, TValue).Item" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IDictionary`2.Item(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Keys">
      <MemberSignature Language="C#" Value="System.Collections.Generic.ICollection&lt;TKey&gt; System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Keys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;!TKey&gt; System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#Generic#IDictionary&lt;TKey,TValue&gt;#Keys" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Keys As ICollection(Of TKey) Implements IDictionary(Of TKey, TValue).Keys" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Keys" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IDictionary`2.Keys</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Remove">
      <MemberSignature Language="C#" Value="bool IDictionary&lt;TKey,TValue&gt;.Remove (TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Remove(!TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#Generic#IDictionary&lt;TKey,TValue&gt;#Remove(`0)" />
      <MemberSignature Language="VB.NET" Value="Function Remove (key As TKey) As Boolean Implements IDictionary(Of TKey, TValue).Remove" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IDictionary`2.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Values">
      <MemberSignature Language="C#" Value="System.Collections.Generic.ICollection&lt;TValue&gt; System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;!TValue&gt; System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#Generic#IDictionary&lt;TKey,TValue&gt;#Values" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Values As ICollection(Of TValue) Implements IDictionary(Of TKey, TValue).Values" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.System.Collections.Generic.IDictionary&lt;TKey,TValue&gt;.Values" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.IDictionary`2.Values</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.ICollection.CopyTo">
      <MemberSignature Language="C#" Value="void ICollection.CopyTo (Array array, int index);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Collections.ICollection.CopyTo(class System.Array array, int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#ICollection#CopyTo(System.Array,System.Int32)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.ICollection.CopyTo(System.Array,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="System.Array" />
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">To be added.</param>
        <param name="index">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.ICollection.IsSynchronized">
      <MemberSignature Language="C#" Value="bool System.Collections.ICollection.IsSynchronized { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.Collections.ICollection.IsSynchronized" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#ICollection#IsSynchronized" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property IsSynchronized As Boolean Implements ICollection.IsSynchronized" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.System.Collections.ICollection.IsSynchronized" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.ICollection.IsSynchronized</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.ICollection.SyncRoot">
      <MemberSignature Language="C#" Value="object System.Collections.ICollection.SyncRoot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object System.Collections.ICollection.SyncRoot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#ICollection#SyncRoot" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property SyncRoot As Object Implements ICollection.SyncRoot" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.System.Collections.ICollection.SyncRoot" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.ICollection.SyncRoot</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IDictionary.Add">
      <MemberSignature Language="C#" Value="void IDictionary.Add (object key, object value);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Collections.IDictionary.Add(object key, object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#IDictionary#Add(System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Sub Add (key As Object, value As Object) Implements IDictionary.Add" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IDictionary.Add(System.Object,System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Object" />
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <param name="value">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IDictionary.Clear">
      <MemberSignature Language="C#" Value="void IDictionary.Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Collections.IDictionary.Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#IDictionary#Clear" />
      <MemberSignature Language="VB.NET" Value="Sub Clear () Implements IDictionary.Clear" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IDictionary.Clear</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IDictionary.Contains">
      <MemberSignature Language="C#" Value="bool IDictionary.Contains (object key);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool System.Collections.IDictionary.Contains(object key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#IDictionary#Contains(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Function Contains (key As Object) As Boolean Implements IDictionary.Contains" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IDictionary.Contains(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IDictionary.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IDictionaryEnumerator IDictionary.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IDictionaryEnumerator System.Collections.IDictionary.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#IDictionary#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IDictionaryEnumerator Implements IDictionary.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IDictionary.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IDictionaryEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IDictionary.IsFixedSize">
      <MemberSignature Language="C#" Value="bool System.Collections.IDictionary.IsFixedSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.Collections.IDictionary.IsFixedSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#IDictionary#IsFixedSize" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property IsFixedSize As Boolean Implements IDictionary.IsFixedSize" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.System.Collections.IDictionary.IsFixedSize" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.IDictionary.IsFixedSize</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IDictionary.IsReadOnly">
      <MemberSignature Language="C#" Value="bool System.Collections.IDictionary.IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.Collections.IDictionary.IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#IDictionary#IsReadOnly" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property IsReadOnly As Boolean Implements IDictionary.IsReadOnly" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.System.Collections.IDictionary.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.IDictionary.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IDictionary.Item">
      <MemberSignature Language="C#" Value="object System.Collections.IDictionary.Item[object key] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object System.Collections.IDictionary.Item(object)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#IDictionary#Item(System.Object)" />
      <MemberSignature Language="VB.NET" Value=" Property Item(key As Object) As Object Implements IDictionary.Item" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.System.Collections.IDictionary.Item" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.IDictionary.Item(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IDictionary.Keys">
      <MemberSignature Language="C#" Value="System.Collections.ICollection System.Collections.IDictionary.Keys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ICollection System.Collections.IDictionary.Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#IDictionary#Keys" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Keys As ICollection Implements IDictionary.Keys" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.System.Collections.IDictionary.Keys" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.IDictionary.Keys</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ICollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IDictionary.Remove">
      <MemberSignature Language="C#" Value="void IDictionary.Remove (object key);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Collections.IDictionary.Remove(object key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#IDictionary#Remove(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Sub Remove (key As Object) Implements IDictionary.Remove" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IDictionary.Remove(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IDictionary.Values">
      <MemberSignature Language="C#" Value="System.Collections.ICollection System.Collections.IDictionary.Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ICollection System.Collections.IDictionary.Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#IDictionary#Values" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Values As ICollection Implements IDictionary.Values" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.System.Collections.IDictionary.Values" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.IDictionary.Values</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ICollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetValue">
      <MemberSignature Language="C#" Value="public bool TryGetValue (TKey key, out TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetValue(!TKey key, [out] !TValue&amp; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.TryGetValue(`0,`1@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetValue (key As TKey, ByRef value As TValue) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetValue : 'Key *  -&gt; bool&#xA;override this.TryGetValue : 'Key *  -&gt; bool" Usage="readOnlyDictionary45.TryGetValue (key, value)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IDictionary`2.TryGetValue(`0,`1@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="key">To be added.</param>
        <param name="value">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;TKey,TValue&gt;.ValueCollection Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2/ValueCollection&lt;!TKey, !TValue&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Common.ReadOnlyDictionary45`2.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As ReadOnlyDictionary45(Of TKey, TValue).ValueCollection" />
      <MemberSignature Language="F#" Value="member this.Values : Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.ValueCollection" Usage="Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;'Key, 'Value&gt;.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Common.ReadOnlyDictionary45&lt;TKey,TValue&gt;+ValueCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>