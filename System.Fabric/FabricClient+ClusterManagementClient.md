<Type Name="FabricClient+ClusterManagementClient" FullName="System.Fabric.FabricClient+ClusterManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.ClusterManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/ClusterManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ClusterManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.ClusterManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ClusterManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>クラスターのメンテナンス操作を実行するには、クラスター管理クライアントを表します。</para>
    </summary>
    <remarks>
      <para><see cref="T:System.Fabric.FabricClient.ClusterManagementClient" />クラスター全体の管理に役立つ Api を提供します。 これらは、ノードおよび重大な障害の場合のサービスを回復しなければならないの損失などの主要なクラスター イベントに関連する通常の管理コマンドです。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ActivateNodeAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ActivateNodeAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ActivateNodeAsync (nodeName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.ActivateNodeAsync : string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ActivateNodeAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>アクティブ化するノードです。</para>
        </param>
        <summary>
          <para>現在非アクティブ化されている Service Fabric クラスター ノードをアクティブにします。</para>
        </summary>
        <returns>
          <para>要求の非同期受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                アクティブ化すると、ノードはもう一度、新しいレプリカを配置するための有効なターゲットなり、残りのノードで閉じられたレプリカでもは開かれます。</para>
          <para>
                この API の完了時にアクティブ化することを目的は、システムによって登録されていることを意味します。 アクティブ化が完了したことは限りません。 使用して、操作の進行状況を決定できます、 <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ActivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ActivateNodeAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ActivateNodeAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ActivateNodeAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ActivateNodeAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>アクティブ化するノードです。</para>
        </param>
        <param name="timeout">
          <para>返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>現在非アクティブ化されている Service Fabric クラスター ノードをアクティブにします。</para>
        </summary>
        <returns>
          <para>要求の非同期受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                アクティブ化すると、ノードはもう一度、新しいレプリカを配置するための有効なターゲットなり、残りのノードで閉じられたレプリカでもは開かれます。</para>
          <para>
                この API の完了時にアクティブ化することを目的は、システムによって登録されていることを意味します。 アクティブ化が完了したことは限りません。 使用して、操作の進行状況を決定できます、 <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CopyClusterPackage">
      <MemberSignature Language="C#" Value="public void CopyClusterPackage (string imageStoreConnectionString, string clusterManifestPath, string clusterManifestPathInImageStore, string codePackagePath, string codePackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyClusterPackage(string imageStoreConnectionString, string clusterManifestPath, string clusterManifestPathInImageStore, string codePackagePath, string codePackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyClusterPackage (imageStoreConnectionString As String, clusterManifestPath As String, clusterManifestPathInImageStore As String, codePackagePath As String, codePackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.CopyClusterPackage : string * string * string * string * string -&gt; unit" Usage="clusterManagementClient.CopyClusterPackage (imageStoreConnectionString, clusterManifestPath, clusterManifestPathInImageStore, codePackagePath, codePackagePathInImageStore)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageStoreConnectionString" Type="System.String" />
        <Parameter Name="clusterManifestPath" Type="System.String" />
        <Parameter Name="clusterManifestPathInImageStore" Type="System.String" />
        <Parameter Name="codePackagePath" Type="System.String" />
        <Parameter Name="codePackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。 内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。 Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore" イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。 
            </para>
        </param>
        <param name="clusterManifestPath">
          <para>クラスターへの完全パスでは、コピーするファイルをマニフェストします。</para>
        </param>
        <param name="clusterManifestPathInImageStore">
          <para>イメージ ストアに変換先のファイル名を指定の相対パス。 ClusterManifestPath が指定されている場合に、このパラメーターを使用することが必要です。 このパスが、イメージ ストアにルート ディレクトリに対して相対的な作成され、クラスター マニフェストのコピーの送信先として使用します。</para>
        </param>
        <param name="codePackagePath">
          <para>Service Fabric コード パッケージをコピーするへの完全パス。</para>
        </param>
        <param name="codePackagePathInImageStore">
          <para>イメージ ストアに変換先のファイル名を指定の相対パス。 CodePackagePathInImageStore が指定されている場合に、このパラメーターを使用することが必要です。 このパスが、イメージ ストアにルート ディレクトリに対して相対的な作成され、コード パッケージのコピーの送信先として使用します。</para>
        </param>
        <summary>
          <para>クラスター マニフェストのファイルや Service Fabric コード パッケージをイメージ ストアにコピーします。</para>
        </summary>
        <remarks>
          <para>ソース クラスター マニフェストのパスとソース コードのパスの両方を null にすることはできません。</para>
        </remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>イメージ ストア上のファイルへのアクセス エラーが発生しました。</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>必要なファイルが、イメージ ストアに見つかりませんでした。</para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para>イメージ ストアに必要なディレクトリが見つかりませんでした。</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>イメージ ストア ファイル/ディレクトリへのパスが長すぎます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeactivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeactivateNodeAsync (string nodeName, System.Fabric.NodeDeactivationIntent deactivationIntent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeactivateNodeAsync(string nodeName, valuetype System.Fabric.NodeDeactivationIntent deactivationIntent) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeactivateNodeAsync (nodeName As String, deactivationIntent As NodeDeactivationIntent) As Task" />
      <MemberSignature Language="F#" Value="member this.DeactivateNodeAsync : string * System.Fabric.NodeDeactivationIntent -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.DeactivateNodeAsync (nodeName, deactivationIntent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="deactivationIntent" Type="System.Fabric.NodeDeactivationIntent" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>非アクティブ化するノードの名前。</para>
        </param>
        <param name="deactivationIntent">
          <para><see cref="T:System.Fabric.NodeDeactivationIntent" />をノードを非アクティブ化します。</para>
        </param>
        <summary>
          <para>指定した特定のノードを非アクティブ化<see cref="T:System.Fabric.NodeDeactivationIntent" />です。</para>
        </summary>
        <returns>
          <para>要求の非同期受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                この API の完了時に、非アクティブ化することを目的は、システムによって登録されていることを意味します。 非アクティブ化が完了したことは限りません。 使用して、操作の進行状況を決定できます、 <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API </para>
          <para>
                非アクティブ化インテントの「高く」が減少しない、非アクティブ化が進行中は、いったん (であるノードが非アクティブ化など、<see cref="F:System.Fabric.NodeDeactivationIntent.Pause" />インテントを非アクティブ化を指定できます<see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />、です逆はできなくします。 使用してノードを再びアクティブにすることがあります<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" />が非アクティブ化した後にいちます。 非アクティブ化が完了していない場合、非アクティブ化を取り消します。 ノードがダウンし、その復帰を非アクティブ化中には、サービスがそのノードに配置される前に再アクティブ化する必要があります。</para>
          <para>
                Service Fabric を非アクティブ化が 'セーフ' プロセスことを確認します。 いくつかの安全性チェックが実行されます (を参照してください<see cref="T:System.Fabric.SafetyCheckKind" />) 可用性またはデータの損失がないことを確認するには </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeactivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeactivateNodeAsync (string nodeName, System.Fabric.NodeDeactivationIntent deactivationIntent, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeactivateNodeAsync(string nodeName, valuetype System.Fabric.NodeDeactivationIntent deactivationIntent, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeactivateNodeAsync : string * System.Fabric.NodeDeactivationIntent * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.DeactivateNodeAsync (nodeName, deactivationIntent, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="deactivationIntent" Type="System.Fabric.NodeDeactivationIntent" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>非アクティブ化するノードの名前。</para>
        </param>
        <param name="deactivationIntent">
          <para><see cref="T:System.Fabric.NodeDeactivationIntent" />をノードを非アクティブ化します。</para>
        </param>
        <param name="timeout">
          <para>返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定した特定のノードを非アクティブ化<see cref="T:System.Fabric.NodeDeactivationIntent" />です。</para>
        </summary>
        <returns>
          <para>要求の非同期受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                この API の完了時に、非アクティブ化することを目的は、システムによって登録されていることを意味します。 非アクティブ化が完了したことは限りません。 使用して、操作の進行状況を決定できます、 <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API </para>
          <para>
                非アクティブ化インテントの「高く」が減少しない、非アクティブ化が進行中は、いったん (であるノードが非アクティブ化など、<see cref="F:System.Fabric.NodeDeactivationIntent.Pause" />インテントを非アクティブ化を指定できます<see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />、です逆はできなくします。 使用してノードを再びアクティブにすることがあります<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" />が非アクティブ化した後にいちます。 非アクティブ化が完了していない場合、非アクティブ化を取り消します。 ノードがダウンし、その復帰を非アクティブ化中には、サービスがそのノードに配置される前に再アクティブ化する必要があります。</para>
          <para>
                Service Fabric を非アクティブ化が 'セーフ' プロセスことを確認します。 いくつかの安全性チェックが実行されます (を参照してください<see cref="T:System.Fabric.SafetyCheckKind" />) 可用性またはデータの損失がないことを確認するには </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Service Fabric クラスターの構成ファイルを文字列として取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric クラスターを文字列としての構成ファイル。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync (string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync(string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationAsync (apiVersion As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync apiVersion" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="apiVersion">Api のバージョン。</param>
        <summary>
          <para>Service Fabric クラスターの構成ファイルを文字列として取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric クラスターを文字列としての構成ファイル。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>Service Fabric クラスターの構成ファイルを文字列として指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>指定したタイムアウトとキャンセル トークンを使用して、文字列として Service Fabric クラスターの構成ファイル。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync (string apiVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync(string apiVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync (apiVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiVersion">Api バージョン。</param>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>Service Fabric クラスターの構成ファイルを文字列として指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>指定したタイムアウトとキャンセル トークンを使用して、文字列として Service Fabric クラスターの構成ファイル。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationUpgradeStatusAsync () As Task(Of FabricOrchestrationUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アップグレードが進行中の状態を取得します。
            </summary>
        <returns>FabricOrchestrationUpgradeProgress</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"></param>
        <summary>
            アップグレードが進行中の状態を取得します。
            </summary>
        <returns>FabricOrchestrationUpgradeProgress</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationUpgradeStatusAsync (timeout As TimeSpan) As Task(Of FabricOrchestrationUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <summary>
            アップグレードが進行中の状態を取得します。
            </summary>
        <returns>FabricOrchestrationUpgradeProgress</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
            アップグレードが進行中の状態を取得します。
            </summary>
        <returns>FabricOrchestrationUpgradeProgress</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterManifestAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterManifestAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterManifestAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetClusterManifestAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterManifestAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>現在の実行中のクラスター マニフェストの XML コンテンツを取得します。</para>
        </summary>
        <returns>
          <para>クラスター マニフェストの内容。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterManifestAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterManifestAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterManifestAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterManifestAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>現在の実行中のクラスター マニフェストの XML コンテンツを取得します。</para>
        </summary>
        <returns>
          <para>クラスター マニフェストの内容。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterManifestAsync (System.Fabric.Description.ClusterManifestQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterManifestAsync(class System.Fabric.Description.ClusterManifestQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync(System.Fabric.Description.ClusterManifestQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterManifestAsync : System.Fabric.Description.ClusterManifestQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterManifestAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterManifestQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">
          <para>取得するには、どのクラスター マニフェストを決定する追加のパラメーターを指定します。</para>
        </param>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>クラスターの XML コンテンツがで指定されたマニフェストを取得<paramref name="queryDescription" />です。</para>
        </summary>
        <returns>
          <para>クラスター マニフェストの内容。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetFabricUpgradeProgressAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetFabricUpgradeProgressAsync () As Task(Of FabricUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetFabricUpgradeProgressAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;" Usage="clusterManagementClient.GetFabricUpgradeProgressAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Service Fabric アップグレード プロセスの進行状況を返します。</para>
        </summary>
        <returns>
          <para>Service Fabric の進行状況は、プロセスをアップグレードします。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetFabricUpgradeProgressAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetFabricUpgradeProgressAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;" Usage="clusterManagementClient.GetFabricUpgradeProgressAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>Service Fabric アップグレード プロセスの進行状況を返します。</para>
        </summary>
        <returns>
          <para>Service Fabric の進行状況は、プロセスをアップグレードします。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetUpgradeOrchestrationServiceStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUpgradeOrchestrationServiceStateAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetUpgradeOrchestrationServiceStateAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetUpgradeOrchestrationServiceStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Service Fabric アップグレード オーケストレーション サービスの状態を文字列として取得します。</para>
        </summary>
        <returns>
          <para>文字列として Service Fabric アップグレード オーケストレーション サービスの状態。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetUpgradeOrchestrationServiceStateAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetUpgradeOrchestrationServiceStateAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetUpgradeOrchestrationServiceStateAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>Service Fabric アップグレード オーケストレーション サービスの状態を文字列として指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>指定したタイムアウトとキャンセル トークンを使用して、文字列として Service Fabric アップグレード オーケストレーション サービスの状態。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveNextFabricUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync (System.Fabric.FabricUpgradeProgress upgradeProgress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync(class System.Fabric.FabricUpgradeProgress upgradeProgress) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress)" />
      <MemberSignature Language="VB.NET" Value="Public Function MoveNextFabricUpgradeDomainAsync (upgradeProgress As FabricUpgradeProgress) As Task" />
      <MemberSignature Language="F#" Value="member this.MoveNextFabricUpgradeDomainAsync : System.Fabric.FabricUpgradeProgress -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.MoveNextFabricUpgradeDomainAsync upgradeProgress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.FabricUpgradeProgress" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para>ファブリックは、使用するプロセス オブジェクトをアップグレードします。</para>
        </param>
        <summary>
          <para>Service Fabric を現在のアップグレード ドメインが完了した場合、クラスター内の次のアップグレード ドメインをアップグレードするように指示します。</para>
        </summary>
        <returns>
          <para>クラスターのアップグレード ドメイン。</para>
        </returns>
        <remarks>
          <para><see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" /> に似ています。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveNextFabricUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync (System.Fabric.FabricUpgradeProgress upgradeProgress, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync(class System.Fabric.FabricUpgradeProgress upgradeProgress, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveNextFabricUpgradeDomainAsync : System.Fabric.FabricUpgradeProgress * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.MoveNextFabricUpgradeDomainAsync (upgradeProgress, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.FabricUpgradeProgress" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para>ファブリックは、使用するプロセス オブジェクトをアップグレードします。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>Service Fabric 場合は、現在のアップグレード ドメインが完了したら、指定したタイムアウトとキャンセル トークンを使用して、クラスター内の次のアップグレード ドメインをアップグレードするように指示します。</para>
        </summary>
        <returns>
          <para>クラスターのアップグレード ドメイン。</para>
        </returns>
        <remarks>
          <para><see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" /> に似ています。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionFabricAsync (string patchFilePath, string clusterManifestFilePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionFabricAsync(string patchFilePath, string clusterManifestFilePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ProvisionFabricAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProvisionFabricAsync (patchFilePath As String, clusterManifestFilePath As String) As Task" />
      <MemberSignature Language="F#" Value="member this.ProvisionFabricAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ProvisionFabricAsync (patchFilePath, clusterManifestFilePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="patchFilePath" Type="System.String" />
        <Parameter Name="clusterManifestFilePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="patchFilePath">
          <para>更新の修正プログラム ファイルへのパス。</para>
        </param>
        <param name="clusterManifestFilePath">
          <para>クラスター マニフェストへのパス。</para>
        </param>
        <summary>
          <para>Service Fabric をプロビジョニングします。</para>
        </summary>
        <returns>
          <para>プロビジョニング済みの Service Fabric です。</para>
        </returns>
        <remarks>
          <para>A <languageKeyword>null</languageKeyword>のいずれかの値が許可されて、<paramref name="patchFilePath" />パラメーターまたは<paramref name="clusterManifestFilePath" />パラメーター。 A <languageKeyword>null</languageKeyword>両方のパラメーター値を使用することはできません。</para>
          <para>イメージ ストアの場所にこの修正プログラム ファイルおよびクラスター マニフェスト ファイルがアップロードされます。 イメージ ストアの場所は、クラスターの作成時に指定されたクラスター マニフェストで構成設定として指定されます。</para>
          <para>クラスター マニフェストの検証がこの呼び出しのコンテキスト内で発生します。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionFabricAsync (string patchFilePath, string clusterManifestFilePath, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionFabricAsync(string patchFilePath, string clusterManifestFilePath, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ProvisionFabricAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ProvisionFabricAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ProvisionFabricAsync (patchFilePath, clusterManifestFilePath, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="patchFilePath" Type="System.String" />
        <Parameter Name="clusterManifestFilePath" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="patchFilePath">
          <para>更新の修正プログラム ファイルへのパス。</para>
        </param>
        <param name="clusterManifestFilePath">
          <para>クラスター マニフェストへのパス。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定したタイムアウトとキャンセル トークンを使用して Service Fabric をプロビジョニングします。</para>
        </summary>
        <returns>
          <para>プロビジョニング済みの Service Fabric です。</para>
        </returns>
        <remarks>
          <para>A <languageKeyword>null</languageKeyword>のいずれかの値が許可されて、<paramref name="patchFilePath" />パラメーターまたは<paramref name="clusterManifestFilePath" />パラメーター。 A <languageKeyword>null</languageKeyword>両方のパラメーター値を使用することはできません。</para>
          <para>イメージ ストアの場所にこの修正プログラム ファイルおよびクラスター マニフェスト ファイルがアップロードされます。 イメージ ストアの場所は、クラスターの作成時に指定されたクラスター マニフェストで構成設定として指定されます。</para>
          <para>クラスター マニフェストの検証がこの呼び出しのコンテキスト内で発生します。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverPartitionAsync (partitionId As Guid) As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">パーティション id を回復するには</param>
        <summary>
          <para>Service Fabric クラスターをすることが現在クォーラム損失にスタックしている特定のパーティションの復元を試行ことを示します。</para>
        </summary>
        <returns>
          <para>目的の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。 この API を不適切に使用すると、データ損失が発生する可能性があります。 </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">パーティション id を回復するには</param>
        <param name="timeout">
          <para>返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>Service Fabric クラスターをすることが現在クォーラム損失にスタックしている特定のパーティションの復元を試行ことを示します。</para>
        </summary>
        <returns>
          <para>目的の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。 この API を不適切に使用すると、データ損失が発生する可能性があります。 </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverPartitionsAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionsAsync : unit -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Service Fabric クラスターをすることが、(システム サービスを含む) がクォーラム損失に現在スタックをサービスの回復を試行ことを示します。</para>
        </summary>
        <returns>
          <para>目的の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。 この API を不適切に使用すると、データ損失が発生する可能性があります。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionsAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionsAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionsAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionsAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionsAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>Service Fabric クラスターをすることが、(システム サービスを含む) がクォーラム損失に現在スタックをサービスの回復を試行ことを示します。</para>
        </summary>
        <returns>
          <para>目的の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。 この API を不適切に使用すると、データ損失が発生する可能性があります。 </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverServicePartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverServicePartitionsAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverServicePartitionsAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverServicePartitionsAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverServicePartitionsAsync (serviceName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverServicePartitionsAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverServicePartitionsAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>回復するサービスの名前。</para>
        </param>
        <summary>
          <para>Service Fabric クラスターをすることが、クォーラム損失に残っている現在、指定されたサービスの回復を試行ことを示します。</para>
        </summary>
        <returns>
          <para>目的の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。 この API を不適切に使用すると、データ損失が発生する可能性があります。 </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverServicePartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverServicePartitionsAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverServicePartitionsAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverServicePartitionsAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverServicePartitionsAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverServicePartitionsAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>回復するサービスの名前。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>Service Fabric クラスターをすること、べきでは、指定したタイムアウトとキャンセル トークンを使用して、クォーラム損失で現在停止しているが、指定したサービスを回復することを示します。</para>
        </summary>
        <returns>
          <para>目的の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。 この API を不適切に使用すると、データ損失が発生する可能性があります。 </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverSystemPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverSystemPartitionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverSystemPartitionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverSystemPartitionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverSystemPartitionsAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverSystemPartitionsAsync : unit -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverSystemPartitionsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Service Fabric クラスターをクォーラム損失にスタックしている現在のシステム サービスを回復しようと、必要があることを示します。</para>
        </summary>
        <returns>
          <para>目的の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。 この API を不適切に使用すると、データ損失が発生する可能性があります。 </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverSystemPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverSystemPartitionsAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverSystemPartitionsAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverSystemPartitionsAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverSystemPartitionsAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverSystemPartitionsAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>Service Fabric クラスターをクォーラム損失にスタックしている現在のシステム サービスを回復しようと、必要があることを示します。</para>
        </summary>
        <returns>
          <para>目的の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。 この API を不適切に使用すると、データ損失が発生する可能性があります。 </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveClusterPackage">
      <MemberSignature Language="C#" Value="public void RemoveClusterPackage (string imageStoreConnectionString, string clusterManifestPathInImageStore, string codePackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveClusterPackage(string imageStoreConnectionString, string clusterManifestPathInImageStore, string codePackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveClusterPackage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveClusterPackage (imageStoreConnectionString As String, clusterManifestPathInImageStore As String, codePackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveClusterPackage : string * string * string -&gt; unit" Usage="clusterManagementClient.RemoveClusterPackage (imageStoreConnectionString, clusterManifestPathInImageStore, codePackagePathInImageStore)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageStoreConnectionString" Type="System.String" />
        <Parameter Name="clusterManifestPathInImageStore" Type="System.String" />
        <Parameter Name="codePackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。 内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。 Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore" イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。 
            </para>
        </param>
        <param name="clusterManifestPathInImageStore">
          <para>時に指定されたイメージ ストア内のクラスター マニフェスト ファイルの相対パス<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />です。</para>
        </param>
        <param name="codePackagePathInImageStore">
          <para>Service Fabric コード パッケージ中に指定されたイメージ ストア内の相対パス<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />です。</para>
        </param>
        <summary>
          <para>クラスター マニフェストのファイルや Service Fabric コード パッケージをイメージ ストアから削除します。</para>
        </summary>
        <remarks>
          <para>ClusterManifestPathInImageStore または codePackagePathInImageStore のいずれかのパラメーターを指定できます<languageKeyword>null</languageKeyword>です。 ただし、これらの両方のできません<languageKeyword>null</languageKeyword>です。</para>
        </remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>イメージ ストア上のファイルへのアクセス エラーが発生しました。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodeStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveNodeStateAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveNodeStateAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveNodeStateAsync (nodeName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveNodeStateAsync : string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RemoveNodeStateAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>完全に失われたされているノードの名前。</para>
        </param>
        <summary>
          <para>その Service Fabric は失われ回復不可能なとしてサービスまたはそのノードの状態を扱う必要があります、ノードの永続化されたデータは (たとえば、ディスクの障害、または再イメージ化など)、によって失われることを示します。</para>
        </summary>
        <returns>
          <para>操作を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                ノードがダウンした後に Service Fabric はの追跡そのノードで永続化されたサービスのレプリカはそのノードの状態がいます。</para>
          <para>
                管理者がノードで永続化された状態が完全に失われたことを認識する場合、 <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" /> ... メソッドを呼び出す必要がありますに Service Fabric を通知するノードの状態が削除 (またはの状態をノードが返されることはないことができます)。</para>
          <para>
                これは、Service Fabric を回復するノード (とそのノード上の永続化されたレプリカ) の待機を停止を指示します。</para>
          <para>
                注: そのノードの状態が失われたことが決定したが後にのみ、この API を呼び出す必要があります。 </para>
          <para>
                この API を呼び出すし、ノードが付属戻るそのままの状態が未定義の動作</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodeStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveNodeStateAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveNodeStateAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveNodeStateAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RemoveNodeStateAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>完全に失われたされているノードの名前。</para>
        </param>
        <param name="timeout">
          <para>返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>(これはダウン) 特定のノードが失われている実際には、その Service Fabric は失われ回復不可能なとしてサービスまたはそのノードの状態を扱う必要があることを示します。</para>
        </summary>
        <returns>
          <para>操作を表すタスク。</para>
        </returns>
        <remarks>
          <para>
                ノードがダウンした後に Service Fabric はの追跡そのノードで永続化されたサービスのレプリカはそのノードの状態がいます。</para>
          <para>
                管理者がノード (とその状態) を完全に失われたことを認識する場合、<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" />メソッドを呼び出す必要があります。</para>
          <para>
                これは、Service Fabric を回復するノード (とそのノード上の永続化されたレプリカ) の待機を停止を指示します。</para>
          <para>
                注: そのノードの状態が失われたことが決定したが後にのみ、この API を呼び出す必要があります。 </para>
          <para>
                この API を呼び出すし、ノードが付属戻るそのままの状態が未定義の動作</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResetPartitionLoadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResetPartitionLoadAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResetPartitionLoadAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ResetPartitionLoadAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResetPartitionLoadAsync (partitionId As Guid) As Task" />
      <MemberSignature Language="F#" Value="member this.ResetPartitionLoadAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ResetPartitionLoadAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>パーティション Id を Guid として表されます。 </para>
        </param>
        <summary>
          <para> 
            特定のパーティションの負荷をリセットします。
            </para>
        </summary>
        <returns>
          <para>この async メソッドに関連付けられているタスク。 </para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetPartitionLoadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResetPartitionLoadAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResetPartitionLoadAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ResetPartitionLoadAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResetPartitionLoadAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ResetPartitionLoadAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>パーティション Id を Guid として表されます。 </para>
        </param>
        <param name="timeout">
          <para> Async メソッドをメソッドがタイムアウトする順序で完了する必要がありますを時間の長さ。</para>
        </param>
        <param name="cancellationToken">
          <para>このメソッドのキャンセル トークン。 </para>
        </param>
        <summary>
          <para> 
            特定のパーティションの負荷をリセットします。
            </para>
        </summary>
        <returns>
          <para>この async メソッドに関連付けられているタスク。 </para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollbackFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackFabricUpgradeAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackFabricUpgradeAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RollbackFabricUpgradeAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RollbackFabricUpgradeAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RollbackFabricUpgradeAsync : unit -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RollbackFabricUpgradeAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Service Fabric アップグレード操作をロールバックします。</para>
        </summary>
        <returns>
          <para>Service Fabric アップグレード操作をロールバックします。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollbackFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackFabricUpgradeAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackFabricUpgradeAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RollbackFabricUpgradeAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RollbackFabricUpgradeAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RollbackFabricUpgradeAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Service Fabric は、タイムアウト例外を返す前に続行するには、この操作を許可する時間の最大量を定義する timespan です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>Service Fabric アップグレード操作をロールバックします。</para>
        </summary>
        <returns>
          <para>Service Fabric アップグレード操作をロールバックします。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync (string state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync(string state) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.SetUpgradeOrchestrationServiceStateAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetUpgradeOrchestrationServiceStateAsync (state As String) As Task(Of FabricUpgradeOrchestrationServiceState)" />
      <MemberSignature Language="F#" Value="member this.SetUpgradeOrchestrationServiceStateAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;" Usage="clusterManagementClient.SetUpgradeOrchestrationServiceStateAsync state" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="state" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="state">状態の入力</param>
        <summary>
          <para>文字列として Service Fabric アップグレード オーケストレーション サービスの状態を設定します。</para>
        </summary>
        <returns>タスク</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync (string state, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync(string state, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.SetUpgradeOrchestrationServiceStateAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SetUpgradeOrchestrationServiceStateAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;" Usage="clusterManagementClient.SetUpgradeOrchestrationServiceStateAsync (state, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="state">状態の入力</param>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定したタイムアウトとキャンセル トークンを使用して、文字列として Service Fabric アップグレード オーケストレーション サービスの状態を設定します。</para>
        </summary>
        <returns>
          <para>指定したタイムアウトとキャンセル トークンを使用して Service Fabric アップグレード オーケストレーション サービスの状態。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToggleVerboseServicePlacementHealthReportingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync (bool enabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync(bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToggleVerboseServicePlacementHealthReportingAsync (enabled As Boolean) As Task" />
      <MemberSignature Language="F#" Value="member this.ToggleVerboseServicePlacementHealthReportingAsync : bool -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync enabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enabled">
          <para>ブール値が true の場合、レプリカが有効にする場合に報告します。 </para>
        </param>
        <summary>
          <para> 
            クラスター Resource Balancer はレプリカを配置することがない場合に警告する正常性を報告するかどうかを切り替えます。
            </para>
        </summary>
        <returns>
          <para>この async メソッドに関連付けられているタスク。 </para>
        </returns>
        <remarks>
          <para>このメソッドが値 false を 2 回呼び出されると、出力された可能性がありますが、レポートをメモリからクリアします。
            このメソッドは値 true で、レプリカを配置することがあるときに、クラスター Resource Balancer は、状態の警告が報告されます。
            このような正常性の警告は、監視対象のアップグレードの正常性チェックをブロックしている場合は、オフに切り替えを切り替えることができます。 </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToggleVerboseServicePlacementHealthReportingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync (bool enabled, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync(bool enabled, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync(System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ToggleVerboseServicePlacementHealthReportingAsync : bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync (enabled, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="enabled">
          <para>ブール値が true の場合、レプリカが有効にする場合に報告します。 </para>
        </param>
        <param name="timeout">
          <para> Async メソッドをメソッドがタイムアウトする順序で完了する必要がありますを時間の長さ。</para>
        </param>
        <param name="cancellationToken">
          <para>このメソッドのキャンセル トークン。 </para>
        </param>
        <summary>
          <para> 
            クラスター Resource Balancer はレプリカを配置することがない場合に警告する正常性を報告するかどうかを切り替えます。
            </para>
        </summary>
        <returns>
          <para>この async メソッドに関連付けられているタスク。 </para>
        </returns>
        <remarks>
          <para>このメソッドが値 false を 2 回呼び出されると、出力された可能性がありますが、レポートをメモリからクリアします。
            このメソッドは値 true で、レプリカを配置することがあるときに、クラスター Resource Balancer は、状態の警告が報告されます。
            このような正常性の警告は、監視対象のアップグレードの正常性チェックをブロックしている場合、オフに切り替えを切り替えることができます。 </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionFabricAsync (string codeVersion, string configVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionFabricAsync(string codeVersion, string configVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UnprovisionFabricAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnprovisionFabricAsync (codeVersion As String, configVersion As String) As Task" />
      <MemberSignature Language="F#" Value="member this.UnprovisionFabricAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UnprovisionFabricAsync (codeVersion, configVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersion" Type="System.String" />
        <Parameter Name="configVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codeVersion">
          <para>コードのバージョンのプロビジョニングを解除します。</para>
        </param>
        <param name="configVersion">
          <para>構成のバージョンのプロビジョニングを解除します。</para>
        </param>
        <summary>
          <para>サービス ファブリックの準備を解除します。</para>
        </summary>
        <returns>
          <para>プロビジョニングが解除された Service Fabric です。</para>
        </returns>
        <remarks>
          <para>A <languageKeyword>null</languageKeyword>のいずれかの値が許可されて、<paramref name="codeVersion" />パラメーターまたは<paramref name="configVersion" />パラメーター。 A <languageKeyword>null</languageKeyword>両方のパラメーター値を使用することはできません。</para>
          <para>修正プログラム ファイルおよびクラスター マニフェスト ファイルのイメージ ストアの場所から削除されます。 イメージ ストアの場所は、クラスターの作成時に指定されたクラスター マニフェストで構成設定として指定されます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionFabricAsync (string codeVersion, string configVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionFabricAsync(string codeVersion, string configVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UnprovisionFabricAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnprovisionFabricAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UnprovisionFabricAsync (codeVersion, configVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersion" Type="System.String" />
        <Parameter Name="configVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="codeVersion">
          <para>コードのバージョンのプロビジョニングを解除します。</para>
        </param>
        <param name="configVersion">
          <para>構成のバージョンのプロビジョニングを解除します。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定したタイムアウトとキャンセル トークンを使用してサービス ファブリックの準備を解除します。</para>
        </summary>
        <returns>
          <para>プロビジョニングが解除された Service Fabric です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateFabricUpgradeAsync (System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateFabricUpgradeAsync(class System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateFabricUpgradeAsync (updateDescription As FabricUpgradeUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateFabricUpgradeAsync : System.Fabric.Description.FabricUpgradeUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpdateFabricUpgradeAsync updateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.FabricUpgradeUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para>パラメーターの説明を新しいアップグレードを適用します。</para>
        </param>
        <summary>
          <para>現在のクラスターのアップグレードの動作を記述するアップグレード パラメーターを変更します。</para>
        </summary>
        <returns>
          <para>現在のクラスターのアップグレード。</para>
        </returns>
        <remarks />
      </Docs>
    </Member>
    <Member MemberName="UpdateFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateFabricUpgradeAsync (System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateFabricUpgradeAsync(class System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateFabricUpgradeAsync : System.Fabric.Description.FabricUpgradeUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpdateFabricUpgradeAsync (updateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.FabricUpgradeUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para> 適用する新しいパラメーターをアップグレードします。</para>
        </param>
        <param name="timeout">
          <para>最長時間 Service Fabric をスローする前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>現在のクラスターのアップグレードの動作を記述するアップグレード パラメーターを変更します。</para>
        </summary>
        <returns>
          <para>現在のクラスターのアップグレード。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeConfigurationAsync (description As ConfigurationUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="description">含まれています。 ClusterConfig HealthCheckRetryTimeout、HealthCheckWaitDuration、HealthCheckStableDuration、UpgradeDomainTimeout、UpgradeTimeout、MaxPercentUnhealthyApplications、MaxPercentUnhealthyNodes MaxPercentDeltaUnhealthyNodes、MaxPercentUpgradeDomainDeltaUnhealthyNodes
            </param>
        <summary>
            クラスターの構成ファイルを使用してアップグレードを開始します。
            </summary>
        <returns>タスク</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync (description, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">含まれています: ClusterConfigPath HealthCheckRetryTimeout、HealthCheckWaitDuration、HealthCheckStableDuration、UpgradeDomainTimeout、UpgradeTimeout、MaxPercentUnhealthyApplications、MaxPercentUnhealthyNodes MaxPercentDeltaUnhealthyNodes、MaxPercentUpgradeDomainDeltaUnhealthyNodes</param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
            クラスターの構成ファイルを使用してアップグレードを開始します。
            </summary>
        <returns>タスク</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeConfigurationAsync (description As ConfigurationUpgradeDescription, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync (description, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="description">含まれています。 ClusterConfig HealthCheckRetryTimeout、HealthCheckWaitDuration、HealthCheckStableDuration、UpgradeDomainTimeout、UpgradeTimeout、MaxPercentUnhealthyApplications、MaxPercentUnhealthyNodes MaxPercentDeltaUnhealthyNodes、MaxPercentUpgradeDomainDeltaUnhealthyNodes</param>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <summary>
            クラスターの構成ファイルを使用してアップグレードを開始します。
            </summary>
        <returns>タスク</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">含まれています。 ClusterConfig HealthCheckRetryTimeout、HealthCheckWaitDuration、HealthCheckStableDuration、UpgradeDomainTimeout、UpgradeTimeout、MaxPercentUnhealthyApplications、MaxPercentUnhealthyNodes MaxPercentDeltaUnhealthyNodes、MaxPercentUpgradeDomainDeltaUnhealthyNodes</param>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
            クラスターの構成ファイルを使用してアップグレードを開始します。
            </summary>
        <returns>タスク</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeFabricAsync (System.Fabric.Description.FabricUpgradeDescription upgradeDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeFabricAsync(class System.Fabric.Description.FabricUpgradeDescription upgradeDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeFabricAsync(System.Fabric.Description.FabricUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeFabricAsync (upgradeDescription As FabricUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeFabricAsync : System.Fabric.Description.FabricUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeFabricAsync upgradeDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.FabricUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para>アップグレードの説明です。</para>
        </param>
        <summary>
          <para>Service Fabric をアップグレードします。</para>
        </summary>
        <returns>
          <para>アップグレードされた Service Fabric です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeFabricAsync (System.Fabric.Description.FabricUpgradeDescription upgradeDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeFabricAsync(class System.Fabric.Description.FabricUpgradeDescription upgradeDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeFabricAsync(System.Fabric.Description.FabricUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeFabricAsync : System.Fabric.Description.FabricUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeFabricAsync (upgradeDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.FabricUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para>アップグレードの説明です。</para>
        </param>
        <param name="timeout">
          <para>最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定したタイムアウトとキャンセル トークンを使用して Service Fabric をアップグレードします。</para>
        </summary>
        <returns>
          <para>アップグレードされた Service Fabric です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>