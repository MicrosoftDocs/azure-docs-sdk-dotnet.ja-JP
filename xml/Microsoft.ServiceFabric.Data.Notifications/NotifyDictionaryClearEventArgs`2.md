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
    <typeparam name="TKey"><span data-ttu-id="01cc3-101">内のキーの種類、<cref name="IReliableDictionary" />です。</span><span class="sxs-lookup"><span data-stu-id="01cc3-101">The type of the keys in the <cref name="IReliableDictionary" />.</span></span></typeparam>
    <typeparam name="TValue"><span data-ttu-id="01cc3-102">内の値の型、<cref name="IReliableDictionary" />です。</span><span class="sxs-lookup"><span data-stu-id="01cc3-102">The type of the values in the <cref name="IReliableDictionary" />.</span></span></typeparam>
    <summary>
            <span data-ttu-id="01cc3-103">クリア操作によって発生した DictionaryChanged イベントのデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="01cc3-103">Provides data for the DictionaryChanged event caused by a clear operation.</span></span>
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
            <span data-ttu-id="01cc3-104">トランザクションのコミット シーケンス番号をクリアします<cref name="IReliableDictionary" /></span><span class="sxs-lookup"><span data-stu-id="01cc3-104">The commit sequence number of the transaction cleared the <cref name="IReliableDictionary" /></span></span></param>
        <summary>
            <span data-ttu-id="01cc3-105">新しいインスタンスを初期化します<cref name="NotifyDictionaryClearEventArgs" /></span><span class="sxs-lookup"><span data-stu-id="01cc3-105">Initializes a new instance of the <cref name="NotifyDictionaryClearEventArgs" /></span></span></summary>
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
            <span data-ttu-id="01cc3-106">クリア テキストのコミット操作のコミット シーケンス番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="01cc3-106">Gets the commit sequence number for the operation that committed the clear.</span></span>
            </summary>
        <value>
            <span data-ttu-id="01cc3-107">クリア テキストがコミットされたシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="01cc3-107">Sequence number at which the Clear was committed.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>