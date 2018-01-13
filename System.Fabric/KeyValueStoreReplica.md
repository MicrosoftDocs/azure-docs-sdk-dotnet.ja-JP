<Type Name="KeyValueStoreReplica" FullName="System.Fabric.KeyValueStoreReplica">
  <TypeSignature Language="C#" Value="public class KeyValueStoreReplica : System.Fabric.IStatefulServiceReplica" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyValueStoreReplica extends System.Object implements class System.Fabric.IStatefulServiceReplica" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreReplica" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyValueStoreReplica&#xA;Implements IStatefulServiceReplica" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplica = class&#xA;    interface IStatefulServiceReplica&#xA;    interface IBackupRestoreReplica" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IStatefulServiceReplica</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>サービスのライター - 任意の Service Fabric サービスに統合するための準備完了に、レプリケートされたトランザクション関連のデータ記憶域コンポーネントを提供します。</para>
            これは、従来の Service Fabric サービスで使用されます。 すべての新しいサービスを使用する必要があります、<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">信頼性の高いコレクション</see>です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica storeName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para>キー/値のストアの名前。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.KeyValueStoreReplica" />指定したキー/値のクラス名を格納します。</para>
        </summary>
        <remarks>
          <para>ストアの名前は、有効なファイル名の文字に従う必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para>キー/値のストアの名前。</para>
        </param>
        <param name="localStoreSettings">
          <para>ローカル ストア用のオプションの設定。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.KeyValueStoreReplica" />指定したキー/値のクラス名とローカル ストアの設定を格納します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.ReplicatorSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, replicatorSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para>キー/値のストアの名前。</para>
        </param>
        <param name="replicatorSettings">
          <para>キー/値のオプションの設定は、レプリケーターを格納します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.KeyValueStoreReplica" />指定したキー/値のストアの名前を持つクラスし、複製物作成会社の設定を保存します。</para>
        </summary>
        <remarks>
          <para>ストアの名前は、有効なファイル名の文字に従う必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para>キー/値のストアの名前。</para>
        </param>
        <param name="localStoreSettings">
          <para>ローカル ストア用のオプションの設定。</para>
        </param>
        <param name="replicatorSettings">
          <para>キー/値のオプションの設定は、レプリケーターを格納します。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.KeyValueStoreReplica" />指定したキー/値のクラス名、ローカル ストアの設定、および複製物作成会社設定を格納します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings, System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode notificationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings, valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode notificationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings,System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings * System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings, notificationMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
        <Parameter Name="notificationMode" Type="System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para>キー/値のストアの名前。</para>
        </param>
        <param name="localStoreSettings">
          <para>ローカル ストア用のオプションの設定。</para>
        </param>
        <param name="replicatorSettings">
          <para>キー/値のオプションの設定は、レプリケーターを格納します。</para>
        </param>
        <param name="notificationMode">
          <para>セカンダリ通知モードを有効にする<see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />と<see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />このレプリカでのコールバック。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.KeyValueStoreReplica" />指定したキー/値のクラス名、ローカル ストアの設定、および複製物作成会社設定を格納します。 セカンダリ レプリカの通知は通知モードを使用して有効にします。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings, System.Fabric.KeyValueStoreReplicaSettings kvsSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings, class System.Fabric.KeyValueStoreReplicaSettings kvsSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings,System.Fabric.KeyValueStoreReplicaSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings * System.Fabric.KeyValueStoreReplicaSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings, kvsSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
        <Parameter Name="kvsSettings" Type="System.Fabric.KeyValueStoreReplicaSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">キー/値のストアの名前。</param>
        <param name="localStoreSettings">ローカル ストア用のオプションの設定。</param>
        <param name="replicatorSettings">キー/値の省略可能な設定には、レプリケーターが格納されます。</param>
        <param name="kvsSettings">キー/値の省略可能な設定には、レプリカが格納されます。</param>
        <summary>
            指定したキー/値のストア名、ローカル ストアの設定、レプリケーター設定、およびレプリカの設定を使用して、KeyValueStoreReplica クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit&#xA;override this.Abort : unit -&gt; unit" Usage="keyValueStoreReplica.Abort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.Abort</InterfaceMember>
      </Implements>
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
          <para>このインスタンスを中止、<see cref="T:System.Fabric.KeyValueStoreReplica" />クラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Add(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Add(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.Add : System.Fabric.TransactionBase * string * byte[] -&gt; unit" Usage="keyValueStoreReplica.Add (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <param name="key">
          <para>キーまたは (文字列) として追加する値のインデックス。 800 文字の長さに制限されます。</para>
        </param>
        <param name="value">
          <para>(バイト配列) として値を格納する 2 GB までの長さは制限されます。</para>
        </param>
        <summary>
          <para>キー/値のストアを指定したキーによってインデックス設定される値を追加します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Backup">
      <MemberSignature Language="C#" Value="public void Backup (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Backup(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Backup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Backup (backupDirectory As String)" />
      <MemberSignature Language="F#" Value="member this.Backup : string -&gt; unit" Usage="keyValueStoreReplica.Backup backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use BackupAsync instead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
          <para>バックアップ先ディレクトリの完全パス。</para>
        </param>
        <summary>
          <para>推奨されなくなりました。 指定した宛先ディレクトリへのレプリカのローカル ストアの完全バックアップを実行します。 </para>
        </summary>
        <remarks>
          <para>
            このメソッドは、互換性のために残されています。 代わりに、<see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" /> を使用してください。</para>
          <para>
            このメソッドを使用して完全バックアップを作成した後は、増分バックアップはサポートされていません。 使用して<see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />以降の増分バックアップが作成される場合は、完全バックアップを作成します。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (string backupDirectory, System.Fabric.StoreBackupOption backupOption, Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;bool&gt;&gt; postBackupAsyncFunc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(string backupDirectory, valuetype System.Fabric.StoreBackupOption backupOption, class System.Func`2&lt;class System.Fabric.StoreBackupInfo, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; postBackupAsyncFunc) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function BackupAsync (backupDirectory As String, backupOption As StoreBackupOption, postBackupAsyncFunc As Func(Of StoreBackupInfo, Task(Of Boolean))) As Task" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : string * System.Fabric.StoreBackupOption * Func&lt;System.Fabric.StoreBackupInfo, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.BackupAsync (backupDirectory, backupOption, postBackupAsyncFunc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="backupOption" Type="System.Fabric.StoreBackupOption" />
        <Parameter Name="postBackupAsyncFunc" Type="System.Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            バックアップが格納されるディレクトリです。 場合<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />、このパラメーターである必要があります<b>null</b>です。
            それ以外の場合、このパラメーターは指定できません<b>null</b>、空または空白のみが含まれています。 UNC パスも指定することがあります。
            ディレクトリが存在しない場合は作成されます。 増分バックアップが失敗したかどうかは、存在し、空でない<see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />です。
            </param>
        <param name="backupOption">
          <para>バックアップのオプションです。</para>
        </param>
        <param name="postBackupAsyncFunc">
            投稿では、Service Fabric を使用するシステムに制御を返す前に、バックアップ後のアクティビティを完了するユーザーによって呼び出される非同期のメソッドをバックアップします。
            場合<b>null</b>が渡されたこれは、増分バックアップは許可されません。
            バックアップ後のメソッドが false を返す場合は、増分バックアップは許可されません。
            </param>
        <summary>
          <para>非同期的にキー/値のストアのバックアップを作成します。</para>
        </summary>
        <returns>非同期のバックアップ操作を表すタスク。</returns>
        <remarks>
            <b>PostBackupAsyncFunc</b>バックアップ中にエラーがある場合は呼び出されません。 また、ときに呼び出されました<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />ここでは 1 つのバックアップ サイクルを完了する、ユーザーから必要な追加の操作が存在しないためです。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <b>backupDirectory</b>は<b>null</b>とき<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />します。
            </exception>
        <exception cref="T:System.ArgumentException">
          <b>backupDirectory</b>が空か、単なる空白文字が含まれていますと<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />または<b>backupDirectory</b>は<b>null</b>とき<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />します。
            </exception>
        <exception cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException">
            ときに<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.Incremental" />バックアップ ディレクトリには既にファイルまたはサブディレクトリが含まれています。        
            </exception>
        <exception cref="T:System.Fabric.FabricBackupInProgressException">
            ときに、以前に開始されたバックアップが現在進行中です。
            </exception>
        <example>
            以下の簡単な実装の例は、 <b>postBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
            {
                return await CopyBackupToAzureBlobStorage(info);
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (string backupDirectory, System.Fabric.StoreBackupOption backupOption, Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;bool&gt;&gt; postBackupAsyncFunc, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(string backupDirectory, valuetype System.Fabric.StoreBackupOption backupOption, class System.Func`2&lt;class System.Fabric.StoreBackupInfo, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; postBackupAsyncFunc, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : string * System.Fabric.StoreBackupOption * Func&lt;System.Fabric.StoreBackupInfo, System.Threading.Tasks.Task&lt;bool&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.BackupAsync (backupDirectory, backupOption, postBackupAsyncFunc, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="backupOption" Type="System.Fabric.StoreBackupOption" />
        <Parameter Name="postBackupAsyncFunc" Type="System.Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            バックアップが格納されるディレクトリです。 場合<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />、このパラメーターである必要があります<b>null</b>です。
            それ以外の場合、このパラメーターは指定できません<b>null</b>、空または空白のみが含まれています。 UNC パスも指定することがあります。
            ディレクトリが存在しない場合は作成されます。 増分バックアップが失敗したかどうかは、存在し、空でない<see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />です。
            </param>
        <param name="backupOption">
          <para>バックアップのオプションです。</para>
        </param>
        <param name="postBackupAsyncFunc">
            投稿では、Service Fabric を使用するシステムに制御を返す前に、バックアップ後のアクティビティを完了するユーザーによって呼び出される非同期のメソッドをバックアップします。
            場合<b>null</b>が渡されたこれは、増分バックアップは許可されません。
            バックアップ後のメソッドが false を返す場合は、増分バックアップは許可されません。
            </param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            非同期的にキー/値のストアのバックアップを作成します。
            </summary>
        <returns>非同期のバックアップ操作を表すタスク。</returns>
        <remarks>
            <b>PostBackupAsyncFunc</b>バックアップ中にエラーがある場合は呼び出されません。 また、ときに呼び出されました<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />ここでは 1 つのバックアップ サイクルを完了する、ユーザーから必要な追加の操作が存在しないためです。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <b>backupDirectory</b>は<b>null</b>とき<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />します。
            </exception>
        <exception cref="T:System.ArgumentException">
          <b>backupDirectory</b>が空か、単なる空白文字が含まれていますと<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />または<b>backupDirectory</b>は<b>null</b>とき<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />します。
            </exception>
        <exception cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException">
            ときに<b>backupOption</b>は<see cref="F:System.Fabric.StoreBackupOption.Incremental" />バックアップ ディレクトリには既にファイルまたはサブディレクトリが含まれています。        
            </exception>
        <exception cref="T:System.Fabric.FabricBackupInProgressException">
            ときに、以前に開始されたバックアップが現在進行中です。
            </exception>
        <example>
            以下の簡単な実装の例は、 <b>postBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
            {
                return await CopyBackupToAzureBlobStorage(info);
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="keyValueStoreReplica.ChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;ChangeRoleAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">
          <para>ターゲット レプリカのロール。</para>
        </param>
        <param name="cancellationToken">
          <para>現在は使用しません。 将来使用するために予約されています。</para>
        </param>
        <summary>
          <para>レプリカとそのレプリケーターのレプリカのロールを変更します。</para>
        </summary>
        <returns>
          <para>このレプリカのアドレスを結果タスク。</para>
        </returns>
        <remarks>
          <para>このメソッドは明示的に呼び出す場合は、アプリケーションのレプリカがから派生する必要はありません<see cref="T:System.Fabric.KeyValueStoreReplica" />、これは、推奨パターン。 ここでは、アプリケーションのレプリカをオーバーライドする必要があります<see cref="M:System.Fabric.KeyValueStoreReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />代わりにします。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;CloseAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>現在は使用しません。 将来使用するために予約されています。</para>
        </param>
        <summary>
          <para>レプリカおよびレプリカ セットからオフラインになっているに備えて、レプリケーターを閉じます。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>
          <para>レプリカが必ずしもから削除されていない永続的に、レプリカ セットと、後で再度開くことができます。 レプリカを閉じるための一般的な原因は、アップグレードまたは負荷分散の準備として正常にシャット ダウンします。 このメソッドは明示的に呼び出す場合は、アプリケーションのレプリカがから派生する必要はありません<see cref="T:System.Fabric.KeyValueStoreReplica" />、これは、推奨パターン。 ここでは、アプリケーションのレプリカをオーバーライドする必要があります<see cref="M:System.Fabric.KeyValueStoreReplica.OnCloseAsync(System.Threading.CancellationToken)" />代わりにします。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Contains(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Contains(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Contains : System.Fabric.TransactionBase * string -&gt; bool" Usage="keyValueStoreReplica.Contains (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <param name="key">
          <para>キーまたは (文字列として) を検索する値のインデックス。 800 文字の長さに制限されます。</para>
        </param>
        <summary>
          <para>キー/値のストアに値が含まれているかどうかを判断します。</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>true</languageKeyword>キー/値のストア; に値が含まれている場合<languageKeyword>false</languageKeyword>、それ以外の場合。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public System.Fabric.Transaction CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Transaction CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction () As Transaction" />
      <MemberSignature Language="F#" Value="member this.CreateTransaction : unit -&gt; System.Fabric.Transaction" Usage="keyValueStoreReplica.CreateTransaction " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Transaction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>一意な作成<see cref="T:System.Fabric.Transaction" />ストア操作をコミットに使用されるインスタンス、またはキー/値のグループをロールバックします。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Fabric.Transaction" />トランザクションを表すオブジェクト。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public System.Fabric.Transaction CreateTransaction (System.Fabric.KeyValueStoreTransactionSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Transaction CreateTransaction(class System.Fabric.KeyValueStoreTransactionSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CreateTransaction(System.Fabric.KeyValueStoreTransactionSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction (settings As KeyValueStoreTransactionSettings) As Transaction" />
      <MemberSignature Language="F#" Value="member this.CreateTransaction : System.Fabric.KeyValueStoreTransactionSettings -&gt; System.Fabric.Transaction" Usage="keyValueStoreReplica.CreateTransaction settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Transaction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.KeyValueStoreTransactionSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para>トランザクションの設定。</para>
        </param>
        <summary>
          <para>一意な作成<see cref="T:System.Fabric.Transaction" />ストア操作をコミットに使用されるインスタンス、またはキー/値のグループをロールバックします。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Fabric.Transaction" />トランザクションを表すオブジェクト。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLossReported">
      <MemberSignature Language="C#" Value="public event EventHandler DataLossReported;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler DataLossReported" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.KeyValueStoreReplica.DataLossReported" />
      <MemberSignature Language="VB.NET" Value="Public Event DataLossReported As EventHandler " />
      <MemberSignature Language="F#" Value="member this.DataLossReported : EventHandler " Usage="member this.DataLossReported : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            データが失われるイベントのハンドラーです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate transactionBase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <summary>
          <para>反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItem" />キー/値のストア内の値。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Fabric.KeyValueStoreItem" />列挙子。</para>
        </returns>
        <remarks>
          <para>
            昇順を辞書式には、キーによって項目が列挙されます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase, string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase, string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase * string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate (transactionBase, keyPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <param name="keyPrefix">
          <para>(文字列) と一致するように、キーまたはインデックスをプレフィックスします。 800 文字の長さに制限されます。</para>
        </param>
        <summary>
          <para>反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItem" />値のキーが指定されたキーのプレフィックスに一致するキー/値の値が格納されます。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Fabric.KeyValueStoreItem" />列挙子。</para>
        </returns>
        <remarks>
          <para>
            呼び出すことと同じ<see cref="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String,System.Boolean)" />で<b>strictPrefix</b> 'éý' <languageKeyword>true</languageKeyword>です。
            </para>
          <para>
            昇順を辞書式には、キーによって項目が列挙されます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase * string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate (transactionBase, keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="transactionBase">トランザクションのインスタンス。</param>
        <param name="keyPrefix">(文字列) と一致するように、キーまたはインデックスをプレフィックスします。 800 文字の長さに制限されます。</param>
        <param name="strictPrefix">True の場合に指定された値を付けたキーのみ<b>keyPrefix</b>が返されます。 一致する、または辞書を超える最初のキーに列挙を開始するそれ以外の場合、 <b>keyPrefix</b>いないキーが複数あるまで継続します。 既定値は <b>true</b> です。</param>
        <summary>
            反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItem" />キー/値のストア内の値。
            </summary>
        <returns>A<see cref="T:System.Fabric.KeyValueStoreItem" />列挙子。</returns>
        <remarks>
          <para>
            昇順を辞書式には、キーによって項目が列挙されます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata transactionBase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <summary>
          <para>反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />キー/値のストア内の値。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />列挙子。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase, string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase, string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase * string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata (transactionBase, keyPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <param name="keyPrefix">
          <para>(文字列) と一致するように、キーまたはインデックスをプレフィックスします。 800 文字の長さに制限されます。</para>
        </param>
        <summary>
          <para>反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />値のキーが指定されたキーのプレフィックスに一致するキー/値の値が格納されます。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />列挙子。</para>
        </returns>
        <remarks>
            呼び出すことと同じ<see cref="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String,System.Boolean)" />で<b>strictPrefix</b> 'éý' <languageKeyword>true</languageKeyword>です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase * string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata (transactionBase, keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="transactionBase">トランザクションのインスタンス。</param>
        <param name="keyPrefix">(文字列) と一致するように、キーまたはインデックスをプレフィックスします。 800 文字の長さに制限されます。</param>
        <param name="strictPrefix">True の場合に指定された値を付けたキーのみ<b>keyPrefix</b>が返されます。 一致する、または辞書を超える最初のキーに列挙を開始するそれ以外の場合、 <b>keyPrefix</b>いないキーが複数あるまで継続します。 既定値は <b>true</b> です。</param>
        <summary>
            反復処理する列挙子を返します、<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />キー/値のストア内の値。
            </summary>
        <returns>A<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />列挙子。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItem Get (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItem Get(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Get(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Get : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItem" Usage="keyValueStoreReplica.Get (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItem</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <param name="key">
          <para>キーまたは (文字列) として取得する値のインデックス。 800 文字の長さに制限されます。</para>
        </param>
        <summary>
          <para>として格納されている値を取得、<see cref="T:System.Fabric.KeyValueStoreItem" />指定されたキーに関連付けられているオブジェクト。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Fabric.KeyValueStoreItem" />格納されている値を表すオブジェクト。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCurrentEpoch">
      <MemberSignature Language="C#" Value="public System.Fabric.Epoch GetCurrentEpoch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.Fabric.Epoch GetCurrentEpoch() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetCurrentEpoch" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCurrentEpoch () As Epoch" />
      <MemberSignature Language="F#" Value="member this.GetCurrentEpoch : unit -&gt; System.Fabric.Epoch" Usage="keyValueStoreReplica.GetCurrentEpoch " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Epoch</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>キー/値のストアの現在のエポックを取得します。</para>
        </summary>
        <returns>
          <para>キー/値のストアの現在のエポックです。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItemMetadata GetMetadata (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItemMetadata GetMetadata(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.GetMetadata : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItemMetadata" Usage="keyValueStoreReplica.GetMetadata (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItemMetadata</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <param name="key">
          <para>キーまたは (文字列) として取得する値のインデックス。 800 文字の長さに制限されます。</para>
        </param>
        <summary>
          <para>として、メタデータを取得、<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />オブジェクト、指定されたキーに関連付けられている値。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />指定した値に関連付けられているメタデータを表すオブジェクト。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValue">
      <MemberSignature Language="C#" Value="public byte[] GetValue (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] GetValue(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetValue(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.GetValue : System.Fabric.TransactionBase * string -&gt; byte[]" Usage="keyValueStoreReplica.GetValue (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <param name="key">
          <para>キーまたは (文字列) として取得する値のインデックス。 800 文字の長さに制限されます。</para>
        </param>
        <summary>
          <para>指定したキーに関連付けられているバイト配列として格納されている値を取得します。</para>
        </summary>
        <returns>
          <para>格納されている値を表すバイト配列。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreSequenceNumberCheck">
      <MemberSignature Language="C#" Value="public const long IgnoreSequenceNumberCheck = 0;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 IgnoreSequenceNumberCheck = (0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.IgnoreSequenceNumberCheck" />
      <MemberSignature Language="VB.NET" Value="Public Const IgnoreSequenceNumberCheck As Long  = 0" />
      <MemberSignature Language="F#" Value="val mutable IgnoreSequenceNumberCheck : int64" Usage="System.Fabric.KeyValueStoreReplica.IgnoreSequenceNumberCheck" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>シーケンス番号のチェックが発生していないことを示します。</para>
        </summary>
        <remarks>
          <para>
             シーケンス番号のチェックが発生していないことを示すためにチェック シーケンス番号のパラメーターを受け入れる Api で使用できます。<list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item></list>
             
             これは、チェック シーケンス番号のパラメーターがない API のオーバー ロードを呼び出すことと同じです。<list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String)" /></description></item></list></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit&#xA;override this.Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="keyValueStoreReplica.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para>レプリカの初期化情報。</para>
        </param>
        <summary>
          <para>開くのための準備でレプリカを初期化します。</para>
        </summary>
        <remarks>
          <para>このメソッドは明示的に呼び出す場合は、アプリケーションのレプリカがから派生する必要はありません<see cref="T:System.Fabric.KeyValueStoreReplica" />、これは、推奨パターン。 ここでは、アプリケーションのレプリカをオーバーライドする必要があります<see cref="M:System.Fabric.KeyValueStoreReplica.OnInitialize(System.Fabric.StatefulServiceInitializationParameters)" />代わりにします。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValueStoreReplicaSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplicaSettings KeyValueStoreReplicaSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.KeyValueStoreReplicaSettings KeyValueStoreReplicaSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.KeyValueStoreReplicaSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyValueStoreReplicaSettings As KeyValueStoreReplicaSettings" />
      <MemberSignature Language="F#" Value="member this.KeyValueStoreReplicaSettings : System.Fabric.KeyValueStoreReplicaSettings" Usage="System.Fabric.KeyValueStoreReplica.KeyValueStoreReplicaSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplicaSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定のオプションの設定、<see cref="T:System.Fabric.KeyValueStoreReplica" />です。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.KeyValueStoreReplica" />オプションを設定します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalStoreSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.LocalStoreSettings LocalStoreSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.LocalStoreSettings LocalStoreSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.LocalStoreSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalStoreSettings As LocalStoreSettings" />
      <MemberSignature Language="F#" Value="member this.LocalStoreSettings : System.Fabric.LocalStoreSettings" Usage="System.Fabric.KeyValueStoreReplica.LocalStoreSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.LocalStoreSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはローカルのキー/値のストアのオプションの設定を設定します。</para>
        </summary>
        <value>
          <para>ローカル ストアのオプション設定。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode NotificationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode NotificationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.NotificationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NotificationMode As KeyValueStoreReplica.SecondaryNotificationMode" />
      <MemberSignature Language="F#" Value="member this.NotificationMode : System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" Usage="System.Fabric.KeyValueStoreReplica.NotificationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このレプリカの作成中に指定されたセカンダリ通知モードを取得します。</para>
        </summary>
        <value>
          <para>現在の通知モード</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected virtual void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="keyValueStoreReplica.OnAbort " />
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
          <para>このインスタンスをシャット ダウンに呼び出されます。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnChangeRoleAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;string&gt; OnChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OnChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="keyValueStoreReplica.OnChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">
          <para>ターゲットのロール。</para>
        </param>
        <param name="cancellationToken">
          <para>現在は使用しません。 将来使用するために予約されています。</para>
        </param>
        <summary>
          <para>このレプリカのロールが変更されることを示します。</para>
        </summary>
        <returns>
          <para>このレプリカの解決可能なアドレスを結果タスク。</para>
        </returns>
        <remarks>
          <para>派生している場合、アプリケーションのレプリカはこのメソッドをオーバーライドする必要があります<see cref="T:System.Fabric.KeyValueStoreReplica" />、これは、推奨パターン。 アプリケーションのレプリカを返す必要があります、<see cref="T:System.Threading.Tasks.Task" />をこのレプリカのアドレスの結果。 同様に、(変更なし) を使用して取得できる、システムでこのレプリカのアドレスが格納されている<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />です。 アプリケーションは、未処理の変更の役割のすべての呼び出しの完了の背後にあるレプリカ セットの再構成がブロックされるため、適切なタイミングでロールの変更を終了する注意する必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>A<see cref="T:System.Threading.CancellationToken" />操作を監視しているオブジェクトの取り消し処理のタスクに通知するために使用できます。</para>
        </param>
        <summary>
          <para>このサービス レプリカがシャット ダウンを閉じる必要があるときに呼び出されます。</para>
        </summary>
        <returns>
          <para>非同期操作です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCopyComplete">
      <MemberSignature Language="C#" Value="protected virtual void OnCopyComplete (System.Fabric.KeyValueStoreEnumerator enumerator);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnCopyComplete(class System.Fabric.KeyValueStoreEnumerator enumerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnCopyComplete (enumerator As KeyValueStoreEnumerator)" />
      <MemberSignature Language="F#" Value="abstract member OnCopyComplete : System.Fabric.KeyValueStoreEnumerator -&gt; unit&#xA;override this.OnCopyComplete : System.Fabric.KeyValueStoreEnumerator -&gt; unit" Usage="keyValueStoreReplica.OnCopyComplete enumerator" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enumerator" Type="System.Fabric.KeyValueStoreEnumerator" />
      </Parameters>
      <Docs>
        <param name="enumerator">
          <para>セカンダリ上のデータの読み取りに使用される列挙子。</para>
        </param>
        <summary>
          <para>プライマリからのビルドが完了したら、レプリケーション操作の適用を開始する準備が整いましたときに、セカンダリ レプリカで、システムによって呼び出されます。</para>
          <para>このメソッドはのみ呼び出すことのセカンダリ レプリカの場合、 <see cref="T:System.Fabric.KeyValueStoreReplica" /> 、有効なオブジェクトが構築されて<see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" />パラメーター。</para>
        </summary>
        <remarks>
          <para><see cref="T:System.Fabric.KeyValueStoreEnumerator" />オブジェクトは、レプリケーション操作が適用される前にこのメソッドのコンテキスト内で、セカンダリ上のデータの読み取りに使用できます。 <see cref="T:System.Fabric.KeyValueStoreEnumerator" />オブジェクトが正しく不要になった後、このメソッドを返し、このメソッドのコンテキストの外部で使用することはできません。 アプリケーションは、レプリケーション操作が、セカンダリ レプリカでキューに登録されているが、このメソッドが戻るまでに適用されるを取得するには開始されませんので、適切なタイミングでこのコールバックを完了する注意する必要があります。 <see cref="T:System.Fabric.KeyValueStoreEnumerator" />オブジェクトは 1 つの基になるローカル トランザクションによってバックアップされ、スレッド セーフではありません。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="keyValueStoreReplica.OnDataLossAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">操作の取り消し状態をチェックするために使用するトークンです。</param>
        <summary>
            レプリカ セットのことを通知で、データの損失が発生した可能性があります。 アプリケーションは、イベントを非同期的に処理またはを使用するには、このメソッドをオーバーライドできますか、<see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" />同期的に処理するイベントです。 両方は、同じイベントを表します。
            </summary>
        <returns>復旧中にデータが変更されたレプリカ セットの再同期する必要があることを示すためには true です。 データが変更されていないことを示すためにそれ以外の場合、false になります。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDatalossReported">
      <MemberSignature Language="C#" Value="protected virtual void OnDatalossReported (EventArgs args);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDatalossReported(class System.EventArgs args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnDatalossReported(System.EventArgs)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnDatalossReported (args As EventArgs)" />
      <MemberSignature Language="F#" Value="abstract member OnDatalossReported : EventArgs -&gt; unit&#xA;override this.OnDatalossReported : EventArgs -&gt; unit" Usage="keyValueStoreReplica.OnDatalossReported args" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="args" Type="System.EventArgs" />
      </Parameters>
      <Docs>
        <param name="args">
          <para>現在データが含まれています。 将来使用するために予約されています。</para>
        </param>
        <summary>
          <para>レプリカ セットのことを通知で、データの損失が発生した可能性があります。 アプリケーションのこのメソッドをオーバーライドまたはリッスンできます、<see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" />イベント。 同じイベントを表す両方</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnInitialize">
      <MemberSignature Language="C#" Value="protected virtual void OnInitialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnInitialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnInitialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnInitialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member OnInitialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit&#xA;override this.OnInitialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="keyValueStoreReplica.OnInitialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para>として表されるサービスのレプリカの初期化パラメーター、<see cref="T:System.Fabric.StatefulServiceInitializationParameters" />オブジェクト。</para>
        </param>
        <summary>
          <para>新しく作成されたサービスのレプリカを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnOpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <para>A<see cref="T:System.Fabric.ReplicaOpenMode" />このレプリカに対して新しいまたは回復であるかどうかを指定するオブジェクト。</para>
        </param>
        <param name="partition">
          <para>A<see cref="T:System.Fabric.IStatefulServicePartition" />このレプリカのステートフルなサービス パーティション情報を表すオブジェクト。 </para>
        </param>
        <param name="cancellationToken">
          <para>A<see cref="T:System.Threading.CancellationToken" />操作を監視しているオブジェクトの取り消し処理のタスクに通知するために使用できます。</para>
        </param>
        <summary>
          <para>開くには追加のアクションを実行できるように、初期化されたサービス レプリカに対して呼び出されます。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期操作を表すオブジェクト。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReplicationOperation">
      <MemberSignature Language="C#" Value="protected virtual void OnReplicationOperation (System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; enumerator);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnReplicationOperation(class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreNotification&gt; enumerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnReplicationOperation (enumerator As IEnumerator(Of KeyValueStoreNotification))" />
      <MemberSignature Language="F#" Value="abstract member OnReplicationOperation : System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; -&gt; unit&#xA;override this.OnReplicationOperation : System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; -&gt; unit" Usage="keyValueStoreReplica.OnReplicationOperation enumerator" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enumerator" Type="System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt;" />
      </Parameters>
      <Docs>
        <param name="enumerator">
          <para>このレプリケーション操作のデータの読み取りに使用される列挙子。</para>
        </param>
        <summary>
          <para>入力方向のレプリケーション操作のセカンダリ レプリカで、システムによって呼び出されます。 各<see cref="T:System.Fabric.KeyValueStoreNotification" />オブジェクトには、1 つの分割不可能なレプリケーション操作のすべてのデータが含まれています。</para>
        </summary>
        <remarks>
          <para>このメソッドはのみ呼び出すことのセカンダリ レプリカの場合、 <see cref="T:System.Fabric.KeyValueStoreReplica" /> 、有効なオブジェクトが構築されて<see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" />です。</para>
          <para>場合、<see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.BlockSecondaryAck" />モードを指定し、入力方向のレプリケーション操作は、セカンダリ レプリカ上でローカルに適用されず、メソッドが戻るまで、プライマリを確認します。 これは、アプリケーションがレプリケーション ストリームをブロックしないようにして、適切なタイミングでこのメソッドから返される注意する必要があることを意味します。 想定できないため、このメソッドが戻るまで、受信確認がプライマリに送信されないこと、計測されたレプリケーション操作は既に (または、後であることが保証) によって適用レプリカ セットのレプリカのクォーラムです。</para>
          <para>場合、<see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.NonBlockingQuorumAcked" />モードが指定されている、計測されたレプリケーション操作をレプリカ セットのレプリカのクォーラムが既に適用されていることが保証されます。 さらに、計測されたレプリケーション操作可能性がありますが既にこのセカンダリでローカルに適用され、システムによって、メソッドが呼び出される時点で、プライマリに受信確認します。 メソッドのコールバックではこのモードでは、レプリケーション ストリームはブロックされませんが、レプリケーション操作の通知ストリームもブロックされます。 つまり、のみあります未処理 OnReplicationOperation メソッド コールバックは 1 つ特定の時点。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnRestoreCompletedAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnRestoreCompletedAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnRestoreCompletedAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnRestoreCompletedAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">操作の取り消し状態をチェックするために使用するトークンです。</param>
        <summary>
            レプリカの状態が、システムによって正常に復元されていることを通知します。
            これは、システムが内部的にバックアップを復元サービスを経由して復元がトリガーされたときにのみ呼び出されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;&#xA;override this.OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;" Usage="keyValueStoreReplica.OpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;OpenAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <para>このレプリカが開かれるコンテキストを指定します。</para>
        </param>
        <param name="partition">
          <para>このレプリカが属しているセットのレプリカを説明する情報が含まれています。</para>
        </param>
        <param name="cancellationToken">
          <para>現在は使用しません。 将来使用するために予約されています。</para>
        </param>
        <summary>
          <para>オンライン レプリカ セット内の前に、レプリカとそのレプリケーターを開きます。</para>
        </summary>
        <returns>
          <para>Open の完了を示すためにタスク<see cref="T:System.Threading.Tasks.Task`1" />です。</para>
        </returns>
        <remarks>
          <para>このメソッドは明示的に呼び出す場合は、アプリケーションのレプリカがから派生する必要はありません<see cref="T:System.Fabric.KeyValueStoreReplica" />、これは、推奨パターン。 この場合、アプリケーションのレプリカでは、OnOpenAsync を代わりにオーバーライドする必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Remove(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Remove : System.Fabric.TransactionBase * string -&gt; unit" Usage="keyValueStoreReplica.Remove (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <param name="key">
          <para>キーまたはインデックス、(文字列) として削除する値。 800 文字の長さに制限されます。</para>
        </param>
        <summary>
          <para>指定したキーによってインデックス設定される値を削除します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (System.Fabric.TransactionBase transactionBase, string key, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Remove(class System.Fabric.TransactionBase transactionBase, string key, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" />
      <MemberSignature Language="F#" Value="member this.Remove : System.Fabric.TransactionBase * string * int64 -&gt; unit" Usage="keyValueStoreReplica.Remove (transactionBase, key, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <param name="key">
          <para>キーまたはインデックス、(文字列) として削除する値。 800 文字の長さに制限されます。</para>
        </param>
        <param name="checkSequenceNumber">
          <para>削除するキーの予期されたシーケンス番号。</para>
        </param>
        <summary>
          <para>指定したキーによってインデックス設定される値を削除します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.ReplicatorSettings ReplicatorSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ReplicatorSettings ReplicatorSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.ReplicatorSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicatorSettings As ReplicatorSettings" />
      <MemberSignature Language="F#" Value="member this.ReplicatorSettings : System.Fabric.ReplicatorSettings" Usage="System.Fabric.KeyValueStoreReplica.ReplicatorSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicatorSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはキー/値のストア レプリケーターのオプションの設定を設定します。</para>
        </summary>
        <value>
          <para>ストアのレプリケーター オプションの設定。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restore">
      <MemberSignature Language="C#" Value="public void Restore (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Restore(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Restore(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Restore (backupDirectory As String)" />
      <MemberSignature Language="F#" Value="member this.Restore : string -&gt; unit" Usage="keyValueStoreReplica.Restore backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use RestoreAsync instead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
          <para>バックアップを含むディレクトリの完全パスです。</para>
        </param>
        <summary>
          <para>このレプリカのローカル ストア データベースを呼び出して作成されたバックアップから復元<see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />です。</para>
        </summary>
        <remarks>
          <para>これは、ローカル レプリカの復元だけであり、レプリカ セットは自動的に復元されません。 再構成では、その他のレプリカの自然なビルドが発生する追加の手順を実行してレプリカ セット全体を復元する必要があります。 推奨される方法は 1 つのレプリカとターゲット レプリカ セットへの呼び出しの後でサイズの増加のみがある空のサービスを復元する<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />必要な場合です。</para>
          <para>復元が成功した場合は、レプリカが自体を再起動し、レプリカが 1 つのレプリカのみを含むセットを復元することを推奨された後にあるオンラインに戻る受信後に、復元したローカル データの使用を開始します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestoreAsync (backupDirectory As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            レプリカがから復元するディレクトリ。
            このパラメーターを null にすることはできませんを空または空白のみが含まれています。 UNC パスも指定することがあります。
            </param>
        <summary>
          <para>このレプリカのローカル ストア データベースを呼び出して作成されたバックアップから復元<see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />です。</para>
        </summary>
        <returns>非同期の復元操作を表すタスク。</returns>
        <remarks>
          <para>内のファイルからストアを復元するときに、更新されたデータが失われるので、復元は進行中に、キー/値のストアへの任意の書き込み操作を実行しないようにお勧め<b>backupDirectory</b>です。 </para>
          <para>これは、ローカル レプリカの復元だけであり、レプリカ セットは自動的に復元されません。 再構成では、その他のレプリカの自然なビルドが発生する追加の手順を実行してレプリカ セット全体を復元する必要があります。 推奨される方法は 1 つのレプリカとターゲット レプリカ セットへの呼び出しの後でサイズの増加のみがある空のサービスを復元する<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />必要な場合です。</para>
          <para>復元が成功した場合は、レプリカが自体を再起動し、レプリカが 1 つのレプリカのみを含むセットを復元することを推奨された後にあるオンラインに戻る受信後に、復元したローカル データの使用を開始します。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <b>backupDirectory</b>は<b>null</b>です。
            </exception>
        <exception cref="T:System.ArgumentException">
          <b>backupDirectory</b>が空か、単なる空白文字が含まれています。
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <b>backupDirectory</b>存在しません。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync (backupDirectory, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            レプリカがから復元するディレクトリ。
            このパラメーターを null にすることはできませんを空または空白のみが含まれています。 UNC パスも指定することがあります。
            </param>
        <param name="cancellationToken">
          <para>キャンセル トークン</para>
        </param>
        <summary>
          <para>このレプリカのローカル ストア データベースを呼び出して作成されたバックアップから復元<see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />です。</para>
        </summary>
        <returns>非同期の復元操作を表すタスク。</returns>
        <remarks>
          <para>内のファイルからストアを復元するときに、更新されたデータが失われるので、復元は進行中に、キー/値のストアへの任意の書き込み操作を実行しないようにお勧め<b>backupDirectory</b>です。 </para>
          <para>これは、ローカル レプリカの復元だけであり、レプリカ セットは自動的に復元されません。 再構成では、その他のレプリカの自然なビルドが発生する追加の手順を実行してレプリカ セット全体を復元する必要があります。 推奨される方法は 1 つのレプリカとターゲット レプリカ セットへの呼び出しの後でサイズの増加のみがある空のサービスを復元する<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />必要な場合です。</para>
          <para>復元が成功した場合は、レプリカが自体を再起動し、レプリカが 1 つのレプリカのみを含むセットを復元することを推奨された後にあるオンラインに戻る受信後に、復元したローカル データの使用を開始します。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <b>backupDirectory</b>は<b>null</b>です。
            </exception>
        <exception cref="T:System.ArgumentException">
          <b>backupDirectory</b>が空か、単なる空白文字が含まれています。
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <b>backupDirectory</b>存在しません。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory, System.Fabric.RestoreSettings settings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory, class System.Fabric.RestoreSettings settings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String,System.Fabric.RestoreSettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string * System.Fabric.RestoreSettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync (backupDirectory, settings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="settings" Type="System.Fabric.RestoreSettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            レプリカがから復元するディレクトリ。
            このパラメーターを null にすることはできませんを空または空白のみが含まれています。 UNC パスも指定することがあります。
            </param>
        <param name="settings">
            変更する設定は、動作を復元します。
            </param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            キー/値のストアのレプリカを非同期的に復元します。
            </summary>
        <returns>非同期の復元操作を表すタスク。</returns>
        <remarks>
          <para>内のファイルからストアを復元するときに、更新されたデータが失われるので、復元は進行中に、キー/値のストアへの任意の書き込み操作を実行しないようにお勧め<b>backupDirectory</b>です。 </para>
          <para>これは、ローカル レプリカの復元だけであり、レプリカ セットは自動的に復元されません。 再構成では、その他のレプリカの自然なビルドが発生する追加の手順を実行してレプリカ セット全体を復元する必要があります。 推奨される方法は 1 つのレプリカとターゲット レプリカ セットへの呼び出しの後でサイズの増加のみがある空のサービスを復元する<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />必要な場合です。</para>
          <para>復元が成功した場合は、レプリカが自体を再起動し、レプリカが 1 つのレプリカのみを含むセットを復元することを推奨された後にあるオンラインに戻る受信後に、復元したローカル データの使用を開始します。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <b>backupDirectory</b>は<b>null</b>です。
            </exception>
        <exception cref="T:System.ArgumentException">
          <b>backupDirectory</b>が空か、単なる空白文字が含まれています。
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <b>backupDirectory</b>存在しません。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StoreName">
      <MemberSignature Language="C#" Value="public string StoreName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.StoreName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreName As String" />
      <MemberSignature Language="F#" Value="member this.StoreName : string" Usage="System.Fabric.KeyValueStoreReplica.StoreName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはキー/値のストアの名前を設定します。</para>
        </summary>
        <value>
          <para>キー/値のストアの名前。</para>
        </value>
        <remarks>
          <para>ストアの名前は、有効なファイル名の文字に従う必要があります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAdd">
      <MemberSignature Language="C#" Value="public bool TryAdd (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryAdd(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryAdd(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.TryAdd : System.Fabric.TransactionBase * string * byte[] -&gt; bool" Usage="keyValueStoreReplica.TryAdd (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">トランザクションのインスタンス。</param>
        <param name="key">キーまたはインデックス、(文字列) として追加する値。 800 文字の長さに制限されます。</param>
        <param name="value">(バイト配列) として値を格納する 2 GB までの長さは制限されます。</param>
        <summary>
            キーと値を指定したキーによってインデックス設定される値を追加する操作を格納します。
            </summary>
        <returns>指定したキーが見つかり、追加されていない場合は true。 指定したキーが既に存在する場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGet">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItem TryGet (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItem TryGet(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGet(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGet : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItem" Usage="keyValueStoreReplica.TryGet (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItem</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">トランザクションのインスタンス。</param>
        <param name="key">キーまたはインデックス、(文字列) として取得する値。 800 文字の長さに制限されます。</param>
        <summary>
            として格納されている値を取得しようとしています、<see cref="T:System.Fabric.KeyValueStoreItem" />指定されたキーに関連付けられているオブジェクト。
            </summary>
        <returns>A<see cref="T:System.Fabric.KeyValueStoreItem" />格納されている値を表すオブジェクト、または指定したキーが存在しない場合は null です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetMetadata">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItemMetadata TryGetMetadata (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItemMetadata TryGetMetadata(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGetMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGetMetadata : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItemMetadata" Usage="keyValueStoreReplica.TryGetMetadata (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItemMetadata</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">トランザクションのインスタンス。</param>
        <param name="key">キーまたはインデックス、(文字列) として取得する値。 800 文字の長さに制限されます。</param>
        <summary>
            としてのメタデータの取得を試みます、<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />オブジェクト、指定されたキーに関連付けられている値。
            </summary>
        <returns>A<see cref="T:System.Fabric.KeyValueStoreItemMetadata" />オブジェクトのメタデータを表す、指定された値に関連付けられているか、指定したキーが存在しない場合は null です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetValue">
      <MemberSignature Language="C#" Value="public byte[] TryGetValue (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] TryGetValue(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGetValue(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGetValue : System.Fabric.TransactionBase * string -&gt; byte[]" Usage="keyValueStoreReplica.TryGetValue (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">トランザクションのインスタンス。</param>
        <param name="key">キーまたはインデックス、(文字列) として取得する値。 800 文字の長さに制限されます。</param>
        <summary>
            指定したキーに関連付けられているバイト配列として格納されている値を取得しようとします。
            </summary>
        <returns>指定したキーが存在しない場合に、格納されている値または null を表すバイト配列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryRemove">
      <MemberSignature Language="C#" Value="public bool TryRemove (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryRemove(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryRemove : System.Fabric.TransactionBase * string -&gt; bool" Usage="keyValueStoreReplica.TryRemove (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">トランザクションのインスタンス。</param>
        <param name="key">キーまたはインデックス、(文字列) として削除する値。 800 文字の長さに制限されます。</param>
        <summary>
            指定したキーによってインデックス設定される値を削除しようとしています。
            </summary>
        <returns>指定したキーが見つかり削除された場合は true。 指定したキーが存在しない場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryRemove">
      <MemberSignature Language="C#" Value="public bool TryRemove (System.Fabric.TransactionBase transactionBase, string key, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryRemove(class System.Fabric.TransactionBase transactionBase, string key, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" />
      <MemberSignature Language="F#" Value="member this.TryRemove : System.Fabric.TransactionBase * string * int64 -&gt; bool" Usage="keyValueStoreReplica.TryRemove (transactionBase, key, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">トランザクションのインスタンス。</param>
        <param name="key">キーまたはインデックス、(文字列) として削除する値。 800 文字の長さに制限されます。</param>
        <param name="checkSequenceNumber">削除するキーの予期されたシーケンス番号。</param>
        <summary>
            指定したキーによってインデックス設定される値を削除しようとしています。
            </summary>
        <returns>指定したキーが見つかり削除された場合は true。 指定したキーが存在しない場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryUpdate">
      <MemberSignature Language="C#" Value="public bool TryUpdate (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryUpdate(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.TryUpdate : System.Fabric.TransactionBase * string * byte[] -&gt; bool" Usage="keyValueStoreReplica.TryUpdate (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">トランザクションのインスタンス。</param>
        <param name="key">キー、または (文字列) として更新する値のインデックス番号します。 800 文字の長さに制限されます。</param>
        <param name="value">(バイト配列) として値を格納する 2 GB までの長さは制限されます。</param>
        <summary>
            指定したキーによってインデックス設定される値を更新しようとしています。
            </summary>
        <returns>指定したキーが見つかり、更新された場合は true。 指定したキーが存在しない場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryUpdate">
      <MemberSignature Language="C#" Value="public bool TryUpdate (System.Fabric.TransactionBase transactionBase, string key, byte[] value, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryUpdate(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" />
      <MemberSignature Language="F#" Value="member this.TryUpdate : System.Fabric.TransactionBase * string * byte[] * int64 -&gt; bool" Usage="keyValueStoreReplica.TryUpdate (transactionBase, key, value, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">トランザクションのインスタンス。</param>
        <param name="key">キー、または (文字列) として更新する値のインデックス番号します。 800 文字の長さに制限されます。</param>
        <param name="value">(バイト配列) として値を格納する 2 GB までの長さは制限されます。</param>
        <param name="checkSequenceNumber">更新するキーの予期されたシーケンス番号。</param>
        <summary>
            指定したキーによってインデックス設定される値を更新しようとしています。
            </summary>
        <returns>指定したキーが見つかり、更新された場合は true。 指定したキーが存在しない場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public void Update (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Update(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.Update : System.Fabric.TransactionBase * string * byte[] -&gt; unit" Usage="keyValueStoreReplica.Update (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <param name="key">
          <para>キーまたは (文字列) として更新する値のインデックス。 800 文字の長さに制限されます。</para>
        </param>
        <param name="value">
          <para>(バイト配列) として値を格納する 2 GB までの長さは制限されます。</para>
        </param>
        <summary>
          <para>指定したキーに関連付けられている格納されている値を更新します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public void Update (System.Fabric.TransactionBase transactionBase, string key, byte[] value, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Update(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" />
      <MemberSignature Language="F#" Value="member this.Update : System.Fabric.TransactionBase * string * byte[] * int64 -&gt; unit" Usage="keyValueStoreReplica.Update (transactionBase, key, value, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>トランザクションのインスタンス。</para>
        </param>
        <param name="key">
          <para>キーまたは (文字列) として更新する値のインデックス。 800 文字の長さに制限されます。</para>
        </param>
        <param name="value">
          <para>(バイト配列) として値を格納する 2 GB までの長さは制限されます。</para>
        </param>
        <param name="checkSequenceNumber">
          <para>更新するキーの予期されたシーケンス番号。</para>
        </param>
        <summary>
          <para>指定したキーによってインデックス設定される値を更新します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReplicatorSettings">
      <MemberSignature Language="C#" Value="public void UpdateReplicatorSettings (System.Fabric.ReplicatorSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateReplicatorSettings(class System.Fabric.ReplicatorSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.UpdateReplicatorSettings(System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateReplicatorSettings (settings As ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="member this.UpdateReplicatorSettings : System.Fabric.ReplicatorSettings -&gt; unit" Usage="keyValueStoreReplica.UpdateReplicatorSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para>使用して、キー/値の更新設定には、レプリケーターが格納されます。</para>
        </param>
        <summary>
          <para>指定した設定でキーと値のストアのレプリケーターを更新<see cref="T:System.Fabric.ReplicatorSettings" />オブジェクト。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>