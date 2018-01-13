<Type Name="IStatefulServiceReplica" FullName="System.Fabric.IStatefulServiceReplica">
  <TypeSignature Language="C#" Value="public interface IStatefulServiceReplica" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatefulServiceReplica" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatefulServiceReplica" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatefulServiceReplica" />
  <TypeSignature Language="F#" Value="type IStatefulServiceReplica = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>スタートアップ、初期化、ロールの変更、およびシャット ダウンなど、レプリカのライフ サイクルを制御する動作を定義します。 </para>
    </summary>
    <remarks>
      <para>
                ステートフルなサービスの種類は、このインターフェイスを実装する必要があります。 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservice">信頼性の高いステートフル サービス</see>このインターフェイスを実装し、レプリカのライフ サイクルを内部的に処理します。 </para>
      <para>
                ステートフルなサービスの種類のロジックには、プライマリ レプリカ上で呼び出される動作とセカンダリ レプリカで呼び出される動作が含まれています。</para>
      <para>
                サービスの作成者が作成する場合は、指定された使用<see cref="T:System.Fabric.FabricReplicator" />、サービスを実装する必要がありますも、<see cref="T:System.Fabric.IStateProvider" />の実装を使用する<see cref="T:System.Fabric.IStateReplicator" />はによって提供される<see cref="T:System.Fabric.FabricReplicator" />です。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iStatefulServiceReplica.Abort " />
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
          <para>サービスのレプリカが異常終了します。</para>
        </summary>
        <remarks>
          <para>Service Fabric プロセスのシャット ダウンとの使用によって生じる問題をネットワーク<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />レポートに、<see cref="F:System.Fabric.FaultType.Permanent" />フォールトが異常終了の例を示します。 このメソッドが呼び出されると、サービス レプリカ必要がありますすぐにリリースしのすべての参照をクリーンアップし、返します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iStatefulServiceReplica.ChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Approved public API.")</AttributeName>
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
          <para>更新された<see cref="T:System.Fabric.ReplicaRole" />このレプリカに遷移させなければならないことです。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>サービス レプリカのロールを変更を 1 つの<see cref="T:System.Fabric.ReplicaRole" />です。 </para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.String" />、サービス ファブリックの名前付けを使用して、レプリカに関連付けるには、サービスの新しい接続アドレス。</para>
        </returns>
        <remarks>
          <para>新しいロールは、パラメーターとして示されます。 ときに、サービス ロールに移行する、新しい、サービスが、現在リッスン アドレスを更新することです。
            リッスン アドレスは、電子メール アドレス、クライアントが接続する経由で返されます 1、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.client.servicepartitionresolver#Microsoft_ServiceFabric_Services_Client_ServicePartitionResolver_ResolveAsync_System_Fabric_ResolvedServicePartition_System_Threading_CancellationToken_">ResolveAsync</see> API です。 クライアントからの通信が予想される場合、ポートなどの一部のリソースを要求のみにプライマリ レプリカであるときに、サービスが有効にします。</para>
          <seealso href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-communication" />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStatefulServiceReplica.CloseAsync cancellationToken" />
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
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>シャット ダウンすると、サービスのレプリカを適切に閉じます。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Threading.Tasks.Task" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="iStatefulServiceReplica.Initialize initializationParameters" />
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
          <para><see cref="T:System.Fabric.StatefulServiceInitializationParameters" />このレプリカにします。</para>
        </param>
        <summary>
          <para>新しく作成されたサービスのレプリカを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;" Usage="iStatefulServiceReplica.OpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
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
          <para>これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</para>
        </param>
        <param name="partition">
          <para><see cref="T:System.Fabric.IStatefulServicePartition" />このレプリカの情報です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>その他の操作を実行できるように、初期化されたサービスのレプリカが開きます。</para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Threading.Tasks.Task`1" /> &lt; <see cref="T:System.Fabric.IReplicator" /> &gt;、<see cref="T:System.Fabric.IReplicator" />ステートフル サービスで使用されています。 Service Fabric の実装を使用する<see cref="M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />、レプリカを返す必要があります、<see cref="T:System.Fabric.FabricReplicator" />から取得した<see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>