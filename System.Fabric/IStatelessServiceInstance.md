<Type Name="IStatelessServiceInstance" FullName="System.Fabric.IStatelessServiceInstance">
  <TypeSignature Language="C#" Value="public interface IStatelessServiceInstance" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatelessServiceInstance" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatelessServiceInstance" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatelessServiceInstance" />
  <TypeSignature Language="F#" Value="type IStatelessServiceInstance = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>スタートアップ、初期化、およびシャット ダウンなどのステートレス サービス インスタンスのライフ サイクルを制御する動作を定義します。 </para>
      <remarks>
            ステートレス サービスの種類は、このインターフェイスを実装する必要があります。 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statelessservice">信頼性の高いステートレス サービス</see>このインターフェイスを実装し、インスタンスのライフ サイクルを内部的に処理します。
            </remarks>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iStatelessServiceInstance.Abort " />
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
          <para> このインスタンスをこの同期メソッドの呼び出しで異常終了します。 </para>
        </summary>
        <remarks>
          <para>異常終了の例は、その結果、Service Fabric プロセスのシャット ダウンし使用するネットワーク問題<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />レポートに、<see cref="F:System.Fabric.FaultType.Permanent" />フォールトします。 サービス インスタンスは、このメソッドを受信すると、必要がありますすぐにリリースしのすべての参照をクリーンアップし、返します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStatelessServiceInstance.CloseAsync cancellationToken" />
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
          <para>サービス インスタンスがシャット ダウンすると、このサービス インスタンスを適切に閉じます。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Threading.Tasks.Task" /> を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatelessServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatelessServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.Initialize(System.Fabric.StatelessServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatelessServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatelessServiceInitializationParameters -&gt; unit" Usage="iStatelessServiceInstance.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatelessServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para>このサービスの <see cref="T:System.Fabric.StatelessServiceInitializationParameters" />。</para>
        </param>
        <summary>
          <para> 新しく作成されたサービス インスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; OpenAsync (System.Fabric.IStatelessServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OpenAsync(class System.Fabric.IStatelessServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.OpenAsync(System.Fabric.IStatelessServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.IStatelessServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iStatelessServiceInstance.OpenAsync (partition, cancellationToken)" />
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
        <Parameter Name="partition" Type="System.Fabric.IStatelessServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partition">
          <para>
                <see cref="T:System.Fabric.IStatelessServicePartition" />このインスタンスに関連付けられています。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>クライアントが接続できるように、初期化されたサービス インスタンスを開きます。</para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.String" />します。</para>
        </returns>
        <remarks>
          <para>インスタンスのステートレスなサービスを開くことを示しますサービス今すぐ解決とサービス クライアントで検出することです。 返される文字列は、このサービス インスタンスのアドレスです。 アドレスが Service Fabric が名前付けを使用して、サービス名に関連付けられているし、経由でサービスを解決するにはクライアントに返される<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />です。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>