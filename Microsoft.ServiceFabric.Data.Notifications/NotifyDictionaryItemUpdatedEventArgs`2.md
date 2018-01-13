<Type Name="NotifyDictionaryItemUpdatedEventArgs&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemUpdatedEventArgs&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public class NotifyDictionaryItemUpdatedEventArgs&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs&lt;TKey,TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotifyDictionaryItemUpdatedEventArgs`2&lt;TKey, TValue&gt; extends Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs`2&lt;!TKey, !TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemUpdatedEventArgs`2" />
  <TypeSignature Language="VB.NET" Value="Public Class NotifyDictionaryItemUpdatedEventArgs(Of TKey, TValue)&#xA;Inherits NotifyDictionaryTransactionalEventArgs(Of TKey, TValue)" />
  <TypeSignature Language="F#" Value="type NotifyDictionaryItemUpdatedEventArgs&lt;'Key, 'Value&gt; = class&#xA;    inherit NotifyDictionaryTransactionalEventArgs&lt;'Key, 'Value&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs&lt;TKey,TValue&gt;</BaseTypeName>
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
            項目の更新による DictionaryChanged イベントのデータを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyDictionaryItemUpdatedEventArgs (Microsoft.ServiceFabric.Data.ITransaction transaction, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.ITransaction transaction, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemUpdatedEventArgs`2.#ctor(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (transaction As ITransaction, key As TKey, value As TValue)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemUpdatedEventArgs&lt;'Key, 'Value&gt; : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemUpdatedEventArgs&lt;'Key, 'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemUpdatedEventArgs&lt;'Key, 'Value&gt; (transaction, key, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transaction" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="transaction">操作に関連するトランザクションです。</param>
        <param name="key">更新されたキー。</param>
        <param name="value">新しい値。</param>
        <summary>
            新しいインスタンスを初期化します<cref name="NotifyDictionaryItemUpdatedEventArgs" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public TKey Key { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TKey Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemUpdatedEventArgs`2.Key" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Key As TKey" />
      <MemberSignature Language="F#" Value="member this.Key : 'Key" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemUpdatedEventArgs&lt;'Key, 'Value&gt;.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キーを取得します。
            </summary>
        <value>
            キー。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public TValue Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TValue Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemUpdatedEventArgs`2.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As TValue" />
      <MemberSignature Language="F#" Value="member this.Value : 'Value" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemUpdatedEventArgs&lt;'Key, 'Value&gt;.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TValue</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            値を取得します。
            </summary>
        <value>
            値。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>