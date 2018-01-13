<Type Name="NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public abstract class NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt; : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit NotifyDictionaryChangedEventArgs`2&lt;TKey, TValue&gt; extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class NotifyDictionaryChangedEventArgs(Of TKey, TValue)&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt; = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TKey">内のキーの種類、<cref name="IReliableDictionary" />です。</typeparam>
    <typeparam name="TValue">内の値の型、<cref name="IReliableDictionary" />です。</typeparam>
    <summary>
            DictionaryChanged イベントのデータを提供します。
            </summary>
    <remarks>
            DictionaryChanged 通知は同期的に、発生<cref name="IReliableDictionary" />操作の適用の一部として。
            これらのイベントの完了を維持するいると、イベントの完了時にブロックされるまでに、レプリカ可能性があります。
            イベントができる限り高速に処理されることをお勧めします。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyDictionaryChangedEventArgs (Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2.#ctor(Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (action As NotifyDictionaryChangedAction)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt; : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt; action" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="action" Type="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction" />
      </Parameters>
      <Docs>
        <param name="action">通知の種類。</param>
        <summary>
            新しいインスタンスを初期化します<cref name="NotifyDictionaryChangedEventArgs" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction Action { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2.Action" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Action As NotifyDictionaryChangedAction" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            イベントの原因となったアクションを取得します。
            </summary>
        <value>通知の種類。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>