<Type Name="NotifyDictionaryRebuildEventArgs&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public class NotifyDictionaryRebuildEventArgs&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotifyDictionaryRebuildEventArgs`2&lt;TKey, TValue&gt; extends Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2&lt;!TKey, !TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2" />
  <TypeSignature Language="VB.NET" Value="Public Class NotifyDictionaryRebuildEventArgs(Of TKey, TValue)&#xA;Inherits NotifyDictionaryChangedEventArgs(Of TKey, TValue)" />
  <TypeSignature Language="F#" Value="type NotifyDictionaryRebuildEventArgs&lt;'Key, 'Value&gt; = class&#xA;    inherit NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TKey">TKey</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TValue">TValue</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TKey">内のキーの種類、<cref name="IReliableDictionary" />です。</typeparam>
    <typeparam name="TValue">内の値の型、<cref name="IReliableDictionary" />です。</typeparam>
    <summary>
            再構築操作によって発生した RebuildNotificationAsyncCallback イベントのデータを提供します。
            再構築の回復、コピーまたは信頼性の高い状態の復元の終了時に通知が発生します。
            </summary>
    <remarks>
            なお、この操作が完了するまでの再構築、<cref name="IReliableDictionary" />は完了しません。
            これが原因でブロックされるまでに、レプリカを続行する前に完了コールバックを待機しています。 非同期のイテレーションの状態の上には、IO を必要があります。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyDictionaryRebuildEventArgs (Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt; enumerableState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt; enumerableState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2.#ctor(Microsoft.ServiceFabric.Data.IAsyncEnumerable{System.Collections.Generic.KeyValuePair{`0,`1}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enumerableState As IAsyncEnumerable(Of KeyValuePair(Of TKey, TValue)))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;'Key, 'Value&gt; : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt; -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;'Key, 'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;'Key, 'Value&gt; enumerableState" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enumerableState" Type="Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="enumerableState">
          <cref name="IAsyncEnumerable" />新しい状態を反復処理に使用できる、<cref name="IReliableDictionary" />です。</param>
        <summary>
            新しいインスタンスを初期化します<cref name="NotifyDictionaryRebuildEventArgs" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As IAsyncEnumerable(Of KeyValuePair(Of TKey, TValue))" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;'Key, 'Value&gt;.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、非同期列挙可能なすべての項目を含む、<cref name="IReliableDictionary" />です。
            </summary>
        <value>非同期列挙可能な新しい状態を格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>