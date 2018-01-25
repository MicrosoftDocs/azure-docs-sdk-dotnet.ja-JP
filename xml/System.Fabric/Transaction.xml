<Type Name="Transaction" FullName="System.Fabric.Transaction">
  <TypeSignature Language="C#" Value="public class Transaction : System.Fabric.TransactionBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Transaction extends System.Fabric.TransactionBase" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Transaction" />
  <TypeSignature Language="VB.NET" Value="Public Class Transaction&#xA;Inherits TransactionBase" />
  <TypeSignature Language="F#" Value="type Transaction = class&#xA;    inherit TransactionBase" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.TransactionBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="083e7-101">トランザクションを表します。</span><span class="sxs-lookup"><span data-stu-id="083e7-101">Represents a transaction.</span></span> <see cref="T:System.Fabric.KeyValueStoreReplica" /></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CommitAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CommitAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Transaction.CommitAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CommitAsync () As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : unit -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="transaction.CommitAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="083e7-102">トランザクションに関連付けられている操作のセットをコミットします。</span><span class="sxs-lookup"><span data-stu-id="083e7-102">Commits the set of operations associated with the transaction.</span></span> <span data-ttu-id="083e7-103">レプリケーションおよびローカル ディスクの書き込みを非同期的に実行します。</span><span class="sxs-lookup"><span data-stu-id="083e7-103">Replication and local disk writes are performed asynchronously</span></span></para>
        </summary>
        <returns>
          <para>
            <span data-ttu-id="083e7-104">その結果は、論理トランザクションのシーケンス番号、タスク。</span><span class="sxs-lookup"><span data-stu-id="083e7-104">A Task whose result is the Logical Sequence Number of the transaction.</span></span> <span data-ttu-id="083e7-105">シーケンス番号は、このトランザクションに書き込まれたすべてのキーに関連付けられています、オプティミスティック同時実行制御を実装するためのチェック シーケンス番号のパラメーターを受け入れる Api に渡すことができます。<list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item></list></span><span class="sxs-lookup"><span data-stu-id="083e7-105">The sequence number is associated with all keys written in this transaction and can be passed into APIs accepting a check sequence number parameter to implement optimistic concurrency: <list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item></list></span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CommitAsync (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CommitAsync(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Transaction.CommitAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function CommitAsync (timeout As TimeSpan) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="transaction.CommitAsync timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="083e7-106">レプリケーションおよびローカル ディスクに待機する時間を完了するまで書き込みます<see cref="T:System.TimeoutException" />がスローされます。</span><span class="sxs-lookup"><span data-stu-id="083e7-106">The amount of time to wait for replication and local disk writes to complete before <see cref="T:System.TimeoutException" /> is thrown.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="083e7-107">省略可能なタイムアウトを使用してトランザクションに関連付けられている操作のセットをコミットします。</span><span class="sxs-lookup"><span data-stu-id="083e7-107">Commits the set of operations that are associated with the transaction with an optional timeout.</span></span> <span data-ttu-id="083e7-108">レプリケーションおよびローカル ディスクの書き込みは、非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="083e7-108">Replication and local disk writes are performed asynchronously.</span></span> <span data-ttu-id="083e7-109">複製操作は、基になるいないタイムアウトが発生しても取り消さ可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="083e7-109">Note that the underlying replication operation may not have been cancelled even in the event of a timeout.</span></span></para>
        </summary>
        <returns>
          <para>
             <span data-ttu-id="083e7-110">その結果は、論理トランザクションのシーケンス番号、タスク。</span><span class="sxs-lookup"><span data-stu-id="083e7-110">A Task whose result is the Logical Sequence Number of the transaction.</span></span> <span data-ttu-id="083e7-111">シーケンス番号は、このトランザクションに書き込まれたすべてのキーに関連付けられています、オプティミスティック同時実行制御を実装するためのチェック シーケンス番号のパラメーターを受け入れる Api に渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="083e7-111">The sequence number is associated with all keys written in this transaction and can be passed into APIs accepting a check sequence number parameter to implement optimistic concurrency:</span></span>
             
             <list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item></list></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CommitAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CommitAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Transaction.CommitAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="transaction.CommitAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use CommitAsync() or CommitAsync(TimeSpan) overloads")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="083e7-112">レプリケーションおよびローカル ディスクに待機する時間を完了するまで書き込みます<see cref="T:System.TimeoutException" />がスローされます。</span><span class="sxs-lookup"><span data-stu-id="083e7-112">The amount of time to wait for replication and local disk writes to complete before <see cref="T:System.TimeoutException" /> is thrown.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="083e7-113">現在は使用されていません。</span><span class="sxs-lookup"><span data-stu-id="083e7-113">Currently not used.</span></span> <span data-ttu-id="083e7-114">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="083e7-114">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="083e7-115">省略可能なタイムアウトを使用してトランザクションに関連付けられている操作のセットをコミットします。</span><span class="sxs-lookup"><span data-stu-id="083e7-115">Commits the set of operations that are associated with the transaction with an optional timeout.</span></span> <span data-ttu-id="083e7-116">レプリケーションおよびローカル ディスクの書き込みは、非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="083e7-116">Replication and local disk writes are performed asynchronously.</span></span> <span data-ttu-id="083e7-117">複製操作は、基になるいないタイムアウトが発生しても取り消さ可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="083e7-117">Note that the underlying replication operation may not have been cancelled even in the event of a timeout.</span></span></para>
        </summary>
        <returns>
          <para>
             <span data-ttu-id="083e7-118">その結果は、論理トランザクションのシーケンス番号、タスク。</span><span class="sxs-lookup"><span data-stu-id="083e7-118">A Task whose result is the Logical Sequence Number of the transaction.</span></span> <span data-ttu-id="083e7-119">シーケンス番号は、このトランザクションに書き込まれたすべてのキーに関連付けられています、オプティミスティック同時実行制御を実装するためのチェック シーケンス番号のパラメーターを受け入れる Api に渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="083e7-119">The sequence number is associated with all keys written in this transaction and can be passed into APIs accepting a check sequence number parameter to implement optimistic concurrency:</span></span>
             
             <list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item></list></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispose">
      <MemberSignature Language="C#" Value="protected internal override void OnDispose ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig virtual instance void OnDispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Transaction.OnDispose" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overrides Sub OnDispose ()" />
      <MemberSignature Language="F#" Value="override this.OnDispose : unit -&gt; unit" Usage="transaction.OnDispose " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="083e7-120">Dispose イベントからのトランザクションが破棄されるときに発生、 <languageKeyword>Dispose</languageKeyword>メソッドです。</span><span class="sxs-lookup"><span data-stu-id="083e7-120">The dispose event occurs when the transaction is disposed of through the <languageKeyword>Dispose</languageKeyword> method.</span></span> </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="083e7-121">オーバーライドする<see cref="M:System.Fabric.Transaction.OnDispose" />、必ず<languageKeyword>OnDispose</languageKeyword>基本クラスです。</span><span class="sxs-lookup"><span data-stu-id="083e7-121">To override <see cref="M:System.Fabric.Transaction.OnDispose" />, be sure to call <languageKeyword>OnDispose</languageKeyword> on the base class.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Rollback">
      <MemberSignature Language="C#" Value="public void Rollback ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Rollback() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Transaction.Rollback" />
      <MemberSignature Language="VB.NET" Value="Public Sub Rollback ()" />
      <MemberSignature Language="F#" Value="member this.Rollback : unit -&gt; unit" Usage="transaction.Rollback " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="083e7-122">このトランザクションに関連付けられている操作のセットをロールバックします。</span><span class="sxs-lookup"><span data-stu-id="083e7-122">Rolls back the set of operations that are associated with this transaction.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrowIfDisposed">
      <MemberSignature Language="C#" Value="protected void ThrowIfDisposed ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ThrowIfDisposed() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Transaction.ThrowIfDisposed" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ThrowIfDisposed ()" />
      <MemberSignature Language="F#" Value="member this.ThrowIfDisposed : unit -&gt; unit" Usage="transaction.ThrowIfDisposed " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="083e7-123">例外をスロー、<see cref="T:System.Fabric.Transaction" />オブジェクトを破棄します。</span><span class="sxs-lookup"><span data-stu-id="083e7-123">Throws an exception if the <see cref="T:System.Fabric.Transaction" /> object is disposed.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>