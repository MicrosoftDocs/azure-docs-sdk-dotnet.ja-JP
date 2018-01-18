<Type Name="NotifyDictionaryTransactionalEventArgs&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public abstract class NotifyDictionaryTransactionalEventArgs&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit NotifyDictionaryTransactionalEventArgs`2&lt;TKey, TValue&gt; extends Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2&lt;!TKey, !TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs`2" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class NotifyDictionaryTransactionalEventArgs(Of TKey, TValue)&#xA;Inherits NotifyDictionaryChangedEventArgs(Of TKey, TValue)" />
  <TypeSignature Language="F#" Value="type NotifyDictionaryTransactionalEventArgs&lt;'Key, 'Value&gt; = class&#xA;    inherit NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;" />
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
    <typeparam name="TKey"><span data-ttu-id="15204-101">内のキーの種類、<cref name="IReliableDictionary" />です。</span><span class="sxs-lookup"><span data-stu-id="15204-101">The type of the keys in the <cref name="IReliableDictionary" />.</span></span></typeparam>
    <typeparam name="TValue"><span data-ttu-id="15204-102">内の値の型、<cref name="IReliableDictionary" />です。</span><span class="sxs-lookup"><span data-stu-id="15204-102">The type of the values in the <cref name="IReliableDictionary" />.</span></span></typeparam>
    <summary>
            <span data-ttu-id="15204-103">トランザクションの操作によって発生した DictionaryChanged イベントのデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="15204-103">Provides data for the DictionaryChanged event caused by a transactional operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyDictionaryTransactionalEventArgs (Microsoft.ServiceFabric.Data.ITransaction transaction, Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.ITransaction transaction, valuetype Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction action) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs`2.#ctor(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (transaction As ITransaction, action As NotifyDictionaryChangedAction)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs&lt;'Key, 'Value&gt; : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs&lt;'Key, 'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs&lt;'Key, 'Value&gt; (transaction, action)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transaction" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="action" Type="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedAction" />
      </Parameters>
      <Docs>
        <param name="transaction"><span data-ttu-id="15204-104">操作に関連するトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="15204-104">Transaction that the operation is related to.</span></span></param>
        <param name="action"><span data-ttu-id="15204-105">変更の種類です。</span><span class="sxs-lookup"><span data-stu-id="15204-105">Type of the change.</span></span></param>
        <summary>
            <span data-ttu-id="15204-106">新しいインスタンスを初期化します<cref name="NotifyDictionaryTransactionalEventArgs" /></span><span class="sxs-lookup"><span data-stu-id="15204-106">Initializes a new instance of the <cref name="NotifyDictionaryTransactionalEventArgs" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transaction">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.ITransaction Transaction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Data.ITransaction Transaction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs`2.Transaction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transaction As ITransaction" />
      <MemberSignature Language="F#" Value="member this.Transaction : Microsoft.ServiceFabric.Data.ITransaction" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs&lt;'Key, 'Value&gt;.Transaction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.ITransaction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="15204-107">操作が属するトランザクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="15204-107">Gets the transaction that the operation belongs to.</span></span>
            </summary>
        <value><span data-ttu-id="15204-108">通知に関連付けられているトランザクション オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="15204-108">The transaction object associated with the notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>