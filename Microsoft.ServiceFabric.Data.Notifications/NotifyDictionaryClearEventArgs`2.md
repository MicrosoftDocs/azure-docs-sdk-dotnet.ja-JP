<Type Name="NotifyDictionaryClearEventArgs&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public class NotifyDictionaryClearEventArgs&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotifyDictionaryClearEventArgs`2&lt;TKey, TValue&gt; extends Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2&lt;!TKey, !TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs`2" />
  <TypeSignature Language="VB.NET" Value="Public Class NotifyDictionaryClearEventArgs(Of TKey, TValue)&#xA;Inherits NotifyDictionaryChangedEventArgs(Of TKey, TValue)" />
  <TypeSignature Language="F#" Value="type NotifyDictionaryClearEventArgs&lt;'Key, 'Value&gt; = class&#xA;    inherit NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;" />
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
            クリア操作によって発生した DictionaryChanged イベントのデータを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyDictionaryClearEventArgs (long commitSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 commitSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs`2.#ctor(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (commitSequenceNumber As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs&lt;'Key, 'Value&gt; : int64 -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs&lt;'Key, 'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs&lt;'Key, 'Value&gt; commitSequenceNumber" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commitSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="commitSequenceNumber">
            トランザクションのコミット シーケンス番号をクリアします<cref name="IReliableDictionary" /></param>
        <summary>
            新しいインスタンスを初期化します<cref name="NotifyDictionaryClearEventArgs" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitSequenceNumber">
      <MemberSignature Language="C#" Value="public long CommitSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CommitSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs`2.CommitSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CommitSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.CommitSequenceNumber : int64" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryClearEventArgs&lt;'Key, 'Value&gt;.CommitSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クリア テキストのコミット操作のコミット シーケンス番号を取得します。
            </summary>
        <value>
            クリア テキストがコミットされたシーケンス番号。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>