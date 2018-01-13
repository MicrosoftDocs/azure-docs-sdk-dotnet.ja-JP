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
      <para>トランザクションを表します。 <see cref="T:System.Fabric.KeyValueStoreReplica" /></para>
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
          <para>トランザクションに関連付けられている操作のセットをコミットします。 レプリケーションおよびローカル ディスクの書き込みを非同期的に実行します。</para>
        </summary>
        <returns>
          <para>
            その結果は、論理トランザクションのシーケンス番号、タスク。 シーケンス番号は、このトランザクションに書き込まれたすべてのキーに関連付けられています、オプティミスティック同時実行制御を実装するためのチェック シーケンス番号のパラメーターを受け入れる Api に渡すことができます。<list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item></list></para>
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
          <para>レプリケーションおよびローカル ディスクに待機する時間を完了するまで書き込みます<see cref="T:System.TimeoutException" />がスローされます。</para>
        </param>
        <summary>
          <para>省略可能なタイムアウトを使用してトランザクションに関連付けられている操作のセットをコミットします。 レプリケーションおよびローカル ディスクの書き込みは、非同期的に実行されます。 複製操作は、基になるいないタイムアウトが発生しても取り消さ可能性がありますに注意してください。</para>
        </summary>
        <returns>
          <para>
             その結果は、論理トランザクションのシーケンス番号、タスク。 シーケンス番号は、このトランザクションに書き込まれたすべてのキーに関連付けられています、オプティミスティック同時実行制御を実装するためのチェック シーケンス番号のパラメーターを受け入れる Api に渡すことができます。
             
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
          <para>レプリケーションおよびローカル ディスクに待機する時間を完了するまで書き込みます<see cref="T:System.TimeoutException" />がスローされます。</para>
        </param>
        <param name="cancellationToken">
          <para>現在は使用されていません。 将来使用するために予約されています。</para>
        </param>
        <summary>
          <para>省略可能なタイムアウトを使用してトランザクションに関連付けられている操作のセットをコミットします。 レプリケーションおよびローカル ディスクの書き込みは、非同期的に実行されます。 複製操作は、基になるいないタイムアウトが発生しても取り消さ可能性がありますに注意してください。</para>
        </summary>
        <returns>
          <para>
             その結果は、論理トランザクションのシーケンス番号、タスク。 シーケンス番号は、このトランザクションに書き込まれたすべてのキーに関連付けられています、オプティミスティック同時実行制御を実装するためのチェック シーケンス番号のパラメーターを受け入れる Api に渡すことができます。
             
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
          <para>Dispose イベントからのトランザクションが破棄されるときに発生、 <languageKeyword>Dispose</languageKeyword>メソッドです。 </para>
        </summary>
        <remarks>
          <para>オーバーライドする<see cref="M:System.Fabric.Transaction.OnDispose" />、必ず<languageKeyword>OnDispose</languageKeyword>基本クラスです。</para>
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
          <para>このトランザクションに関連付けられている操作のセットをロールバックします。</para>
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
          <para>例外をスロー、<see cref="T:System.Fabric.Transaction" />オブジェクトを破棄します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>