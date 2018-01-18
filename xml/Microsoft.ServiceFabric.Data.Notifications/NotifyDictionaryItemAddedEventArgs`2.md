<Type Name="NotifyDictionaryItemAddedEventArgs&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemAddedEventArgs&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public class NotifyDictionaryItemAddedEventArgs&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs&lt;TKey,TValue&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NotifyDictionaryItemAddedEventArgs`2&lt;TKey, TValue&gt; extends Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryTransactionalEventArgs`2&lt;!TKey, !TValue&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemAddedEventArgs`2" />
  <TypeSignature Language="VB.NET" Value="Public Class NotifyDictionaryItemAddedEventArgs(Of TKey, TValue)&#xA;Inherits NotifyDictionaryTransactionalEventArgs(Of TKey, TValue)" />
  <TypeSignature Language="F#" Value="type NotifyDictionaryItemAddedEventArgs&lt;'Key, 'Value&gt; = class&#xA;    inherit NotifyDictionaryTransactionalEventArgs&lt;'Key, 'Value&gt;" />
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
    <typeparam name="TKey"><span data-ttu-id="5a5b8-101">内のキーの種類、<cref name="IReliableDictionary" />です。</span><span class="sxs-lookup"><span data-stu-id="5a5b8-101">The type of the keys in the <cref name="IReliableDictionary" />.</span></span></typeparam>
    <typeparam name="TValue"><span data-ttu-id="5a5b8-102">内の値の型、<cref name="IReliableDictionary" />です。</span><span class="sxs-lookup"><span data-stu-id="5a5b8-102">The type of the values in the <cref name="IReliableDictionary" />.</span></span></typeparam>
    <summary>
            <span data-ttu-id="5a5b8-103">項目の追加による DictionaryChanged イベントのデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="5a5b8-103">Provides data for the DictionaryChanged event caused by item addition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotifyDictionaryItemAddedEventArgs (Microsoft.ServiceFabric.Data.ITransaction transaction, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.ITransaction transaction, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemAddedEventArgs`2.#ctor(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (transaction As ITransaction, key As TKey, value As TValue)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemAddedEventArgs&lt;'Key, 'Value&gt; : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemAddedEventArgs&lt;'Key, 'Value&gt;" Usage="new Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemAddedEventArgs&lt;'Key, 'Value&gt; (transaction, key, value)" />
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
        <param name="transaction"><span data-ttu-id="5a5b8-104">操作に関連するトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="5a5b8-104">Transaction that the operation is related to.</span></span></param>
        <param name="key"><span data-ttu-id="5a5b8-105">追加されたキー。</span><span class="sxs-lookup"><span data-stu-id="5a5b8-105">Key that was added.</span></span></param>
        <param name="value"><span data-ttu-id="5a5b8-106">追加した値です。</span><span class="sxs-lookup"><span data-stu-id="5a5b8-106">Value that was added.</span></span></param>
        <summary>
            <span data-ttu-id="5a5b8-107">新しいインスタンスを初期化します<cref name="NotifyDictionaryItemAddedEventArgs" /></span><span class="sxs-lookup"><span data-stu-id="5a5b8-107">Initializes a new instance of the <cref name="NotifyDictionaryItemAddedEventArgs" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public TKey Key { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TKey Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemAddedEventArgs`2.Key" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Key As TKey" />
      <MemberSignature Language="F#" Value="member this.Key : 'Key" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemAddedEventArgs&lt;'Key, 'Value&gt;.Key" />
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
            <span data-ttu-id="5a5b8-108">キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="5a5b8-108">Gets the key.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5a5b8-109">キー。</span><span class="sxs-lookup"><span data-stu-id="5a5b8-109">The key.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public TValue Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TValue Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemAddedEventArgs`2.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As TValue" />
      <MemberSignature Language="F#" Value="member this.Value : 'Value" Usage="Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryItemAddedEventArgs&lt;'Key, 'Value&gt;.Value" />
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
            <span data-ttu-id="5a5b8-110">値を取得します。</span><span class="sxs-lookup"><span data-stu-id="5a5b8-110">Gets the value.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5a5b8-111">値。</span><span class="sxs-lookup"><span data-stu-id="5a5b8-111">The value.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>