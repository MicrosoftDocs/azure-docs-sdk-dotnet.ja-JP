<Type Name="NotifyDictionaryItemRemovedEventArgs&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemRemovedEventArgs&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public class NotifyDictionaryItemRemovedEventArgs&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs&lt;TKey,TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotifyDictionaryItemRemovedEventArgs`2&lt;TKey, TValue&gt; extends Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs`2&lt;!TKey, !TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemRemovedEventArgs`2" />
  <TypeSignature Language="VB.NET" Value="Public Class NotifyDictionaryItemRemovedEventArgs(Of TKey, TValue)&#xA;Inherits NotifyDictionaryTransactionalEventArgs(Of TKey, TValue)" />
  <TypeSignature Language="F#" Value="type NotifyDictionaryItemRemovedEventArgs&lt;'Key, 'Value&gt; = class&#xA;    inherit NotifyDictionaryTransactionalEventArgs&lt;'Key, 'Value&gt;" />
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
    <typeparam name="TKey"><span data-ttu-id="73b82-101">内のキーの種類、<cref name="IReliableDictionary" />です。</span><span class="sxs-lookup"><span data-stu-id="73b82-101">The type of the keys in the <cref name="IReliableDictionary" />.</span></span></typeparam>
    <typeparam name="TValue"><span data-ttu-id="73b82-102">内の値の型、<cref name="IReliableDictionary" />です。</span><span class="sxs-lookup"><span data-stu-id="73b82-102">The type of the values in the <cref name="IReliableDictionary" />.</span></span></typeparam>
    <summary>
            <span data-ttu-id="73b82-103">項目の削除による DictionaryChanged イベントのデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="73b82-103">Provides data for the DictionaryChanged event caused by item removal.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyDictionaryItemRemovedEventArgs (Microsoft.ServiceFabric.Data.ITransaction transaction, TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.ITransaction transaction, !TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemRemovedEventArgs`2.#ctor(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (transaction As ITransaction, key As TKey)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemRemovedEventArgs&lt;'Key, 'Value&gt; : Microsoft.ServiceFabric.Data.ITransaction * 'Key -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemRemovedEventArgs&lt;'Key, 'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemRemovedEventArgs&lt;'Key, 'Value&gt; (transaction, key)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transaction" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="transaction"><span data-ttu-id="73b82-104">操作に関連するトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="73b82-104">Transaction that the operation is related to.</span></span></param>
        <param name="key"><span data-ttu-id="73b82-105">削除されたキー。</span><span class="sxs-lookup"><span data-stu-id="73b82-105">Key that was removed.</span></span></param>
        <summary>
            <span data-ttu-id="73b82-106">新しいインスタンスを初期化します<cref name="NotifyDictionaryItemRemovedEventArgs" /></span><span class="sxs-lookup"><span data-stu-id="73b82-106">Initializes a new instance of the <cref name="NotifyDictionaryItemRemovedEventArgs" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public TKey Key { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TKey Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemRemovedEventArgs`2.Key" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Key As TKey" />
      <MemberSignature Language="F#" Value="member this.Key : 'Key" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemRemovedEventArgs&lt;'Key, 'Value&gt;.Key" />
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
            <span data-ttu-id="73b82-107">キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="73b82-107">Gets the key.</span></span>
            </summary>
        <value>
            <span data-ttu-id="73b82-108">キー。</span><span class="sxs-lookup"><span data-stu-id="73b82-108">The key.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>