<Type Name="FabricClient+HealthClient" FullName="System.Fabric.FabricClient+HealthClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.HealthClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/HealthClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.HealthClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.HealthClient" />
  <TypeSignature Language="F#" Value="type FabricClient.HealthClient = class" />
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
      <para>正常性を実行する機能を提供に関連するレポートおよびクエリの状態と同様に、操作します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (System.Fabric.Description.ApplicationHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Fabric.Description.ApplicationHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationHealthAsync (queryDescription As ApplicationHealthQueryDescription) As Task(Of ApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : System.Fabric.Description.ApplicationHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ApplicationHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" />アプリケーションの正常性を取得するクエリを記述するインスタンス。</param>
        <summary>
          <para>指定されたクエリの説明を使用して、指定した Service Fabric アプリケーションの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>指定した Service Fabric アプリケーションの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationHealthAsync (applicationName As Uri) As Task(Of ApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <summary>
          <para>指定した Service Fabric アプリケーションの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>指定した Service Fabric アプリケーションの正常性。</para>
        </returns>
        <remarks>
          <para>次の例では、アプリケーションの状態を取得します。</para>
          <code language="c#">パブリック静的 bool GetApplicationHealth(string clusterConnection) {ApplicationHealth applicationHealth です。Uri applicationName = 新しい Uri("fabric:/myapp/todo") です。
            
                クラスターに接続します。
                FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。
            
                アプリケーションの正常性を取得します。
                再試行してください {applicationHealth fabricClient.HealthManager.GetApplicationHealthAsync(applicationName) を = です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。
            
                場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。
                
                返す場合は false です。}
                    
                アプリケーションの正常性の情報を表示します。
                Console.WriteLine ("アプリケーションの正常性の取得:") です。Console.WriteLine ("アプリケーション {0}: {1}"、applicationHealth.ApplicationName、applicationHealth.AggregatedHealthState) です。
                
                    展開済みアプリケーションのヘルス状態を一覧表示します。
            Console.WriteLine ("配置済みのアプリケーション:") です。IList&lt;DeployedApplicationHealthState&gt; deployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedAppHealthState でdeployedAppHealthStateList) {Console.WriteLine ("アプリケーション:"+ deployedAppHealthState.ApplicationName) です。Console.WriteLine ("ヘルス状態を集計します。"+ deployedAppHealthState.AggregatedHealthState) です。Console.WriteLine ("ノード名:"+ deployedAppHealthState.NodeName);}
                    
            デプロイ済みサービスのヘルス状態を一覧表示します。
            Console.WriteLine ("サービスの正常性状態:") です。IList&lt;ServiceHealthState&gt; deployedSvcsHealthStateList = applicationHealth.ServiceHealthStates; foreach (deployedSvcsHealthStateList で ServiceHealthState serviceHealthState) {Console.WriteLine ("サービス {0}: {1}"、serviceHealthState.ServiceName、serviceHealthState.AggregatedHealthState) です。}
                    
                正常性イベントを一覧表示します。
            Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = applicationHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}
                
                Console.WriteLine() です。true を返す}
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationHealthAsync (applicationName As Uri, healthPolicy As ApplicationHealthPolicy) As Task(Of ApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (applicationName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <param name="healthPolicy"><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />インスタンス アプリケーションを評価するために使用します。</param>
        <summary>
          <para>非同期的に、アプリケーション URI と正常性ポリシーを使用して、指定した Service Fabric アプリケーションの正常性を取得します。</para>
        </summary>
        <returns>
          <para>指定した Service Fabric アプリケーションの正常性レポートします。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (System.Fabric.Description.ApplicationHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Fabric.Description.ApplicationHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : System.Fabric.Description.ApplicationHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ApplicationHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription"><see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" />アプリケーションの正常性を取得するクエリを記述するインスタンス。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に指定されたクエリの入力、タイムアウトおよび取り消しを使用して、指定した Service Fabric アプリケーションの正常性をトークンの取得します。</para>
        </summary>
        <returns>
          <para>指定した Service Fabric アプリケーションの正常性レポートします。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>トークン、指定したアプリケーション URI、タイムアウトや取り消しを使用して、指定した Service Fabric アプリケーションの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>指定した Service Fabric アプリケーションの正常性レポートします。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (applicationName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <param name="healthPolicy">アプリケーションの正常性ポリシーはアプリケーションの正常性を評価するために使用します。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作が観察するキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、指定した Service Fabric アプリケーションの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>指定した Service Fabric アプリケーションの正常性レポートします。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthAsync () As Task(Of ClusterHealth)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Service Fabric クラスターの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric クラスターの正常性。</para>
        </returns>
        <remarks>
          <para>次の例では、クラスターの正常性を取得します。</para>
          <code language="c#">パブリック静的 bool GetClusterHealth(string clusterConnection) {ClusterHealth clusterHealth です。
            
                クラスターに接続します。
            FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。
                
                クラスターの正常性を取得します。
            再試行してください {clusterHealth fabricClient.HealthManager.GetClusterHealthAsync() を = です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。
                
                場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。
                
                    返す場合は false です。}
                
                クラスターの正常性状態を表示します。
                Console.WriteLine ("クラスターの正常性:") です。Console.WriteLine ("ヘルス状態を集計します。"+ clusterHealth.AggregatedHealthState) です。Console.WriteLine() です。
                    
            クラスター上のアプリケーションのヘルス状態を表示します。
                    Console.WriteLine ("アプリケーションの正常性状態:") です。IList&lt;ApplicationHealthState&gt; applicationHealthStateList = clusterHealth.ApplicationHealthStates; foreach (applicationHealthStateList で ApplicationHealthState applicationHealthState) {Console.WriteLine ("   アプリケーション {0}: {1}"、applicationHealthState.ApplicationName、applicationHealthState.AggregatedHealthState) です。}
            
            クラスター上には、ノード ヘルス状態を表示します。
                    Console.WriteLine ("ノードの正常性状態:") です。IList&lt;NodeHealthState&gt; nodeHealthStateList = clusterHealth.NodeHealthStates; foreach (nodeHealthStateList で NodeHealthState nodeHealthState) {Console.WriteLine ("ノード名:"+ nodeHealthState.NodeName) です。Console.WriteLine ("ヘルス状態を集計します"+ nodeHealthState.AggregatedHealthState);}。
                
            正常性イベントを表示します。
                Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEventList = clusterHealth.HealthEvents; foreach (healthEventList で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}
                
                Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = clusterHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+ healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}
                
            true を返す}
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Description.ClusterHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Description.ClusterHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthAsync (queryDescription As ClusterHealthQueryDescription) As Task(Of ClusterHealth)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Description.ClusterHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">正常性ポリシーのようにクエリ パラメーターを定義するクエリの説明がなどにフィルター処理します。</param>
        <summary>
          <para>非同期的にクエリの説明を使用して、Service Fabric クラスターの正常性を取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric クラスターの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Health.ClusterHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Health.ClusterHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Health.ClusterHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthAsync (healthPolicy As ClusterHealthPolicy) As Task(Of ClusterHealth)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Health.ClusterHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync healthPolicy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="healthPolicy">クラスターの正常性ポリシーはクラスターの正常性を評価するために使用します。</param>
        <summary>
          <para>指定したポリシーを使用して評価する、Service Fabric クラスターの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric クラスターの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に Service Fabric クラスターの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric クラスターの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Description.ClusterHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Description.ClusterHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Description.ClusterHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">正常性ポリシーのようにクエリ パラメーターを定義するクエリの説明がなどにフィルター処理します。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に Service Fabric クラスターの正常性クエリの説明、タイムアウトおよび取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric クラスターの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Health.ClusterHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Health.ClusterHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Health.ClusterHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Health.ClusterHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync (healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="healthPolicy">クラスターの正常性ポリシーはクラスターの正常性を評価するために使用します。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に Service Fabric クラスターの正常性の指定した正常性ポリシー、タイムアウトと取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric クラスターの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthChunkAsync () As Task(Of ClusterHealthChunk)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Service Fabric クラスターの正常性を取得します。
            </summary>
        <returns>クラスターの正常性を表すヘルス チャンクです。</returns>
        <remarks>集計されたクラスターの正常性状態は、クラスター内のすべてのエンティティに基づいて計算されます。
            コンソール アプリケーションは、フィルターが指定されていないため、結果で、子は含まれません。</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync (System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync(class System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthChunkAsync (queryDescription As ClusterHealthChunkQueryDescription) As Task(Of ClusterHealthChunk)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : System.Fabric.Description.ClusterHealthChunkQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthChunkQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">正常性評価を実行する方法とにどのようなエンティティを含めるかを定義するクエリの説明、<see cref="T:System.Fabric.Health.ClusterHealthChunk" />です。</param>
        <summary>
            クエリの説明で要求されるとおり、クラスターのエンティティを含む、Service Fabric クラスターの正常性を取得します。
            </summary>
        <returns>クラスターの正常性を表すヘルス チャンクです。</returns>
        <remarks>集計されたクラスターの正常性状態は、クラスター内のすべてのエンティティに基づいて計算されます。 結果には、入力クエリの説明 (該当する場合) からのフィルターを適用する子のみが含まれています。</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</param>
        <param name="cancellationToken">操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</param>
        <summary>
            Service Fabric クラスターの正常性を取得します。
            </summary>
        <returns>クラスターの正常性を表すヘルス チャンクです。</returns>
        <remarks>集計されたクラスターの正常性状態は、クラスター内のすべてのエンティティに基づいて計算されます。 コンソール アプリケーションは、フィルターが指定されていないため、結果で、子は含まれません。</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync (System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync(class System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : System.Fabric.Description.ClusterHealthChunkQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthChunkQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">正常性評価を実行する方法とにどのようなエンティティを含めるかを定義するクエリの説明、<see cref="T:System.Fabric.Health.ClusterHealthChunk" />です。</param>
        <param name="timeout">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</param>
        <param name="cancellationToken">操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</param>
        <summary>
            クエリの説明で要求されるとおり、クラスターのエンティティを含む、Service Fabric クラスターの正常性を取得します。
            </summary>
        <returns>クラスターの正常性を表すヘルス チャンクです。</returns>
        <remarks>集計されたクラスターの正常性状態は、クラスター内のすべてのエンティティに基づいて計算されます。 結果には、入力クエリの説明 (該当する場合) からのフィルターを適用する子のみが含まれています。</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationHealthAsync (queryDescription As DeployedApplicationHealthQueryDescription) As Task(Of DeployedApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : System.Fabric.Description.DeployedApplicationHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedApplicationHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">クエリの説明。</param>
        <summary>
          <para>非同期的に、展開済みの Service Fabric アプリケーションの正常性、指定したノードに指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationHealthAsync (applicationName As Uri, nodeName As String) As Task(Of DeployedApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <param name="nodeName">
          <para>Service Fabric アプリケーションの配置先となるノードの名前。</para>
        </param>
        <summary>
          <para>指定されたノードで、展開済みの Service Fabric アプリケーションの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>展開済みの Service Fabric アプリケーションの正常性。</para>
        </returns>
        <remarks>
          <para>次の例では、配置済みのアプリケーションの正常性を取得します。</para>
          <code language="c#">パブリック静的 bool GetDeployedApplicationsHealth(string clusterConnection) {//DeployedApplicationHealth deployedApplicationHealth;//ApplicationHealth applicationHealth です。Uri applicationName = 新しい Uri("fabric:/myapp/todo") です。
            
                クラスターに接続します。
                FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。
                
            Console.WriteLine ("アプリケーションの正常性を展開します。") です。
                
                再試行してください {//アプリケーションが配置されているノードを決定します。
            ApplicationHealth applicationHealth fabricClient.HealthManager.GetApplicationHealthAsync(applicationName) を = です。結果です。
                
            各ノードの展開済みアプリケーションの正常性を取得します。
                IList&lt;DeployedApplicationHealthState&gt; deployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedAppHealthState でdeployedAppHealthStateList) {DeployedApplicationHealth deployedApplicationHealth fabricClient.HealthManager.GetDeployedApplicationHealthAsync (applicationName、deployedAppHealthState.NodeName) を = です。結果です。
                
                    各ノードの展開済みアプリケーションのヘルス情報を表示します。
                    
            Console.WriteLine ("アプリケーション {0}: {1}"、deployedApplicationHealth.ApplicationName、deployedApplicationHealth.AggregatedHealthState) です。Console.WriteLine ("ノード名:"+ deployedApplicationHealth.NodeName) です。
                    
                    展開済みアプリケーションのヘルス状態を一覧表示します。
                    Console.WriteLine ("配置済みのアプリケーション:") です。IList&lt;DeployedServicePackageHealthState&gt; deployedSPHealthStateList = deployedApplicationHealth.DeployedServicePackageHealthStates; foreach (DeployedServicePackageHealthState deployedSPHealthState でdeployedSPHealthStateList) {Console.WriteLine ("アプリケーション:"+ deployedSPHealthState.ApplicationName) です。Console.WriteLine ("ヘルス状態を集計します。"+ deployedSPHealthState.AggregatedHealthState) です。Console.WriteLine ("ノード名:"+ deployedSPHealthState.NodeName) です。Console.WriteLine ("サービス マニフェスト名:"+ deployedSPHealthState.ServiceManifestName);}
                    
            正常性イベントを一覧表示します。
                Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = deployedApplicationHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}
            
            異常な評価を一覧表示します。
            Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = deployedApplicationHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}
            
            Console.WriteLine() です。}} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。
            
            場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。
            
            返す場合は false です。}
            
            true を返す}
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : System.Fabric.Description.DeployedApplicationHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedApplicationHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">クエリの説明。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、展開済みの Service Fabric アプリケーションの正常性、指定したノードに指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationHealthAsync (applicationName As Uri, nodeName As String, healthPolicy As ApplicationHealthPolicy) As Task(Of DeployedApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <param name="nodeName">
          <para>Service Fabric アプリケーションの配置先となるノードの名前。</para>
        </param>
        <param name="healthPolicy">アプリケーションの正常性ポリシーはエンティティのヘルスを評価するために使用します。</param>
        <summary>
          <para>指定されたノードで、展開済みの Service Fabric アプリケーションの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>展開済みの Service Fabric アプリケーションの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <param name="nodeName">
          <para>Service Fabric アプリケーションの配置先となるノードの名前。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、展開済みの Service Fabric アプリケーションの正常性、指定したノードに指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <param name="nodeName">
          <para>Service Fabric アプリケーションの配置先となるノードの名前。</para>
        </param>
        <param name="healthPolicy">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、展開済みの Service Fabric アプリケーションの正常性、指定したノードに指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageHealthAsync (queryDescription As DeployedServicePackageHealthQueryDescription) As Task(Of DeployedServicePackageHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : System.Fabric.Description.DeployedServicePackageHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">クエリの説明。</param>
        <summary>
          <para>非同期的に展開されている Service Fabric サービス パッケージの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>展開済みの Service Fabric サービス パッケージの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : System.Fabric.Description.DeployedServicePackageHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">クエリの説明。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に展開されている Service Fabric サービス パッケージの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>展開済みの Service Fabric サービス パッケージの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageHealthAsync (applicationName As Uri, serviceManifestName As String, nodeName As String) As Task(Of DeployedServicePackageHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <param name="serviceManifestName">
          <para>サービスの名前は、この Service Fabric サービスのファイルをマニフェストします。</para>
        </param>
        <param name="nodeName">
          <para>Service Fabric サービスが展開されているノードの名前。</para>
        </param>
        <summary>
          <para>展開済みの Service Fabric サービス パッケージの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>展開済みの Service Fabric サービス パッケージの正常性。</para>
        </returns>
        <remarks>
          <para>次の例では、展開済みサービス パッケージの正常性を取得します。</para>
          <code language="c#">パブリック静的 bool GetDeployedServicePackageHealth(string clusterConnection) {DeployedApplicationHealth deployedApplicationHealth です。DeployedServicePackageHealth deployedServicePackageHealth です。ApplicationHealth applicationHealth です。Uri applicationName = 新しい Uri("fabric:/myapp/todo") です。
            
                クラスターに接続します。
                FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。
                
                Console.WriteLine ("サービス パッケージのヘルスを展開します。") です。
            
                再試行してください {//アプリケーションが配置されているノードを決定します。
                applicationHealth fabricClient.HealthManager.GetApplicationHealthAsync(applicationName) を = です。結果です。
            
                各ノードの展開済みサービス パッケージの正常性を取得します。
            IList&lt;DeployedApplicationHealthState&gt; deployedApplicationHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedApplicationHealthState でdeployedApplicationHealthStateList) {//サービス マニフェスト名を含む展開されたアプリケーションのヘルスを取得し、/、ノードの名前、サービスの場所が展開されている/。
                deployedApplicationHealth fabricClient.HealthManager.GetDeployedApplicationHealthAsync (applicationName、deployedApplicationHealthState.NodeName) を = です。結果です。
                
                    空の場合を返します。
                    場合 (deployedApplicationHealth.DeployedServicePackageHealthStates.Count = = 0); false を返します
            
                    展開済みサービス パッケージの正常性を取得します。
                    deployedServicePackageHealth = fabricClient.HealthManager.GetDeployedServicePackageHealthAsync (applicationName、deployedApplicationHealth.DeployedServicePackageHealthStates[0] です。ServiceManifestName、deployedApplicationHealthState.NodeName)。結果です。
                    
                    展開済みサービス パッケージの正常性の情報を表示します。
            Console.WriteLine ("アプリケーション名:"+ deployedServicePackageHealth.ApplicationName) です。Console.WriteLine ("ノード名:"+ deployedServicePackageHealth.NodeName) です。Console.WriteLine ("ヘルス状態を集計します。"+ deployedServicePackageHealth.AggregatedHealthState) です。Console.WriteLine ("サービス マニフェスト名:"+ deployedServicePackageHealth.ServiceManifestName) です。
            
            正常性イベントを一覧表示します。
                Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = deployedServicePackageHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}
            
            異常な評価を一覧表示します。
            Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = deployedServicePackageHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}
                
            Console.WriteLine() です。}} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。
            
            場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。
                
                返す場合は false です。} です true を返す。}
            </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageHealthAsync (applicationName As Uri, serviceManifestName As String, nodeName As String, healthPolicy As ApplicationHealthPolicy) As Task(Of DeployedServicePackageHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <param name="serviceManifestName">
          <para>サービスの名前は、この Service Fabric サービスのファイルをマニフェストします。</para>
        </param>
        <param name="nodeName">
          <para>Service Fabric サービスが展開されているノードの名前。</para>
        </param>
        <param name="healthPolicy">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</param>
        <summary>
          <para>展開済みの Service Fabric サービス パッケージの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>展開済みの Service Fabric サービス パッケージの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <param name="serviceManifestName">
          <para>サービスの名前は、この Service Fabric サービスのファイルをマニフェストします。</para>
        </param>
        <param name="nodeName">
          <para>Service Fabric サービスが展開されているノードの名前。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に展開されている Service Fabric サービス パッケージの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>展開済みの Service Fabric サービス パッケージの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Service Fabric アプリケーションの URI。</para>
        </param>
        <param name="serviceManifestName">
          <para>サービスの名前は、この Service Fabric サービスのファイルをマニフェストします。</para>
        </param>
        <param name="nodeName">
          <para>Service Fabric サービスが展開されているノードの名前。</para>
        </param>
        <param name="healthPolicy">アプリケーションの正常性ポリシーはエンティティのヘルスを評価するために使用します。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に展開されている Service Fabric サービス パッケージの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>展開済みの Service Fabric サービス パッケージの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="applicationName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (System.Fabric.Description.NodeHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(class System.Fabric.Description.NodeHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeHealthAsync (queryDescription As NodeHealthQueryDescription) As Task(Of NodeHealth)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : System.Fabric.Description.NodeHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.NodeHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">正常性ポリシーのようにパラメーターを定義するクエリの説明がなどにフィルター処理します。</param>
        <summary>
          <para>非同期的に Service Fabric ノードの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric ノードの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeHealthAsync (nodeName As String) As Task(Of NodeHealth)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Service Fabric ノード名です。</para>
        </param>
        <summary>
          <para>Service Fabric ノードの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric ノードの正常性。</para>
        </returns>
        <remarks>
          <para>次の例では、ノードの正常性を取得します。</para>
          <code language="c#">パブリック静的 bool GetNodeHealth(string clusterConnection) {NodeHealth nodeHealth です。
            
                クラスターに接続します。
            FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。
                
                ノードの正常性を取得します。
            再試行してください {nodeHealth fabricClient.HealthManager.GetNodeHealthAsync("Node1") を = です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。
                
                場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。
                
                    返す場合は false です。}
                
                ノードの正常性の情報を表示します。
                Console.WriteLine ("ノードの正常性:") です。Console.WriteLine ("ノード {0}: {1}"、nodeHealth.NodeName、nodeHealth.AggregatedHealthState) です。
                    
            正常性イベントを一覧表示します。
                    Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = nodeHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}
            
            異常な評価を一覧表示します。
                    Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = nodeHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+ healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}
                
            Console.WriteLine() です。true を返す}
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName, System.Fabric.Health.ClusterHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName, class System.Fabric.Health.ClusterHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String,System.Fabric.Health.ClusterHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeHealthAsync (nodeName As String, healthPolicy As ClusterHealthPolicy) As Task(Of NodeHealth)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string * System.Fabric.Health.ClusterHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (nodeName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Service Fabric ノード名です。</para>
        </param>
        <param name="healthPolicy">クラスターの正常性ポリシーはノードの正常性を評価するために使用します。</param>
        <summary>
          <para>Service Fabric ノードの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric ノードの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (System.Fabric.Description.NodeHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(class System.Fabric.Description.NodeHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : System.Fabric.Description.NodeHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.NodeHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">正常性ポリシーのようにパラメーターを定義するクエリの説明がなどにフィルター処理します。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に Service Fabric ノードの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric ノードの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Service Fabric ノードです。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に Service Fabric ノードの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric ノードの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName, System.Fabric.Health.ClusterHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName, class System.Fabric.Health.ClusterHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String,System.Fabric.Health.ClusterHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string * System.Fabric.Health.ClusterHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (nodeName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Service Fabric ノードです。</para>
        </param>
        <param name="healthPolicy">クラスターの正常性ポリシーはノードの正常性を評価するために使用します。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に Service Fabric ノードの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric ノードの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (System.Fabric.Description.PartitionHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(class System.Fabric.Description.PartitionHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionHealthAsync (queryDescription As PartitionHealthQueryDescription) As Task(Of PartitionHealth)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : System.Fabric.Description.PartitionHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PartitionHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">クエリの説明。</param>
        <summary>
          <para>非同期的に、Service Fabric パーティションの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric パーティションの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionHealthAsync (partitionId As Guid) As Task(Of PartitionHealth)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Service Fabric パーティションの ID。</para>
        </param>
        <summary>
          <para>Service Fabric パーティションの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric パーティションの正常性。</para>
        </returns>
        <remarks>
          <para>次の例では、パーティションの正常性を取得します。</para>
          <code language="c#">パブリック静的 bool GetPartitionHealth(string clusterConnection) {PartitionHealth partitionHealth です。
            
                クラスターに接続します。
            FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。
                
                パーティションの正常性を取得します。
            再試行してください {partitionHealth = fabricClient.HealthManager.GetPartitionHealthAsync (新しい Guid("a7206315-e53b-4d05-b59c-e210caa28893")) です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。
                
                場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。
                
                    返す場合は false です。}
                
                パーティションの正常性の情報を表示します。
                Console.WriteLine ("正常性をパーティション分割:") です。Console.WriteLine ("パーティション ID:"+ partitionHealth.PartitionId) です。Console.WriteLine ("ヘルス状態を集計します。"+ partitionHealth.AggregatedHealthState) です。
                    
            正常性イベントを一覧表示します。
                    Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = partitionHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}
                        
            レプリカの正常性状態を一覧表示します。
                    Console.WriteLine ("レプリカの正常性状態:") です。IList&lt;ReplicaHealthState&gt; replicaHealthStates = partitionHealth.ReplicaHealthStates; foreach (replicaHealthStates で ReplicaHealthState replicaHealthState) {Console.WriteLine ("ID:"+ replicaHealthState.Id) です。Console.WriteLine ("種類:"+ replicaHealthState.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ replicaHealthState.AggregatedHealthState) です。Console.WriteLine ("パーティション ID:"+ replicaHealthState.PartitionId);}
                
            異常な評価を一覧表示します。
                Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = partitionHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+ healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}
                
                Console.WriteLine() です。true を返す}
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionHealthAsync (partitionId As Guid, healthPolicy As ApplicationHealthPolicy) As Task(Of PartitionHealth)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (partitionId, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Service Fabric パーティションの ID。</para>
        </param>
        <param name="healthPolicy">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</param>
        <summary>
          <para>Service Fabric パーティションの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric パーティションの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (System.Fabric.Description.PartitionHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(class System.Fabric.Description.PartitionHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : System.Fabric.Description.PartitionHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PartitionHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">クエリの説明。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、Service Fabric パーティションの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric パーティションの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Service Fabric パーティションの ID。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、Service Fabric パーティションの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric パーティションの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (partitionId, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Service Fabric パーティションの ID。</para>
        </param>
        <param name="healthPolicy">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、Service Fabric パーティションの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric パーティションの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (System.Fabric.Description.ReplicaHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(class System.Fabric.Description.ReplicaHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaHealthAsync (queryDescription As ReplicaHealthQueryDescription) As Task(Of ReplicaHealth)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : System.Fabric.Description.ReplicaHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ReplicaHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">クエリの説明。</param>
        <summary>
          <para>クエリの説明で指定された Service Fabric レプリカの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric レプリカの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaHealthAsync (partitionId As Guid, replicaId As Long) As Task(Of ReplicaHealth)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Service Fabric パーティションの ID。</para>
        </param>
        <param name="replicaId">
          <para>Service Fabric レプリカの ID。</para>
        </param>
        <summary>
          <para>Service Fabric レプリカの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric レプリカの正常性。</para>
        </returns>
        <remarks>
          <para>次の例では、レプリカの正常性を取得します。</para>
          <code language="c#">パブリック静的 bool GetReplicaHealth(string clusterConnection) {ReplicaHealth replicaHealth です。
            
                クラスターに接続します。
            FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。
                
                レプリカの正常性を取得します。
            再試行してください {replicaHealth fabricClient.HealthManager.GetReplicaHealthAsync (新しい Guid("a7206315-e53b-4d05-b59c-e210caa28893") 130538257146083818 など) を = です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。
                
                場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。
                
                    返す場合は false です。}
            
                Console.WriteLine ("レプリカの正常性:") です。Console.WriteLine ("ID:"+ replicaHealth.Id) です。Console.WriteLine ("ヘルス状態を集計します。"+ replicaHealth.AggregatedHealthState) です。Console.WriteLine ("種類:"+ replicaHealth.Kind) です。Console.WriteLine ("パーティション ID:"+ replicaHealth.PartitionId) です。
                
                正常性イベントを一覧表示します。
                    Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = replicaHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}
            
                    異常な評価を一覧表示します。
            Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = replicaHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+ healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}
            
                    Console.WriteLine() です。true を返す}
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (System.Fabric.Description.ReplicaHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(class System.Fabric.Description.ReplicaHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : System.Fabric.Description.ReplicaHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ReplicaHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">クエリの説明。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、Service Fabric レプリカの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric レプリカの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaHealthAsync (partitionId As Guid, replicaId As Long, healthPolicy As ApplicationHealthPolicy) As Task(Of ReplicaHealth)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Service Fabric パーティションの ID。</para>
        </param>
        <param name="replicaId">
          <para>Service Fabric レプリカの ID。</para>
        </param>
        <param name="healthPolicy">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</param>
        <summary>
          <para>Service Fabric レプリカの正常性を非同期に取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric レプリカの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Service Fabric パーティションの ID。</para>
        </param>
        <param name="replicaId">
          <para>Service Fabric レプリカの ID。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、Service Fabric レプリカの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric レプリカの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Service Fabric パーティションの ID。</para>
        </param>
        <param name="replicaId">
          <para>Service Fabric レプリカの ID。</para>
        </param>
        <param name="healthPolicy">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、Service Fabric レプリカの正常性、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric レプリカの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (System.Fabric.Description.ServiceHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Fabric.Description.ServiceHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceHealthAsync (queryDescription As ServiceHealthQueryDescription) As Task(Of ServiceHealth)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : System.Fabric.Description.ServiceHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ServiceHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">クエリの説明。</param>
        <summary>
          <para>非同期的に、Service Fabric サービスのヘルス、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric サービスの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceHealthAsync (serviceName As Uri) As Task(Of ServiceHealth)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Service Fabric サービスの名前。</para>
        </param>
        <summary>
          <para>Service Fabric サービスのヘルスを非同期に取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric サービスの正常性。</para>
        </returns>
        <remarks>
          <para>次の例では、サービスの正常性を取得します。</para>
          <code language="c#">パブリック静的 bool GetServiceHealth(string clusterConnection) {ServiceHealth serviceHealth です。Uri の serviceName = 新しい Uri("fabric:/myapp/todo/svc1") です。
            
                クラスターに接続します。
                FabricClient fabricClient = 新しい FabricClient(clusterConnection) です。
            
                サービスのヘルス状態を取得します。
                再試行してください {serviceHealth fabricClient.HealthManager.GetServiceHealthAsync(serviceName) を = です。結果です。} catch (Exception e) {Console.WriteLine ("エラー:"+ されて) です。
            
                場合 (e.InnerException! = null) Console.WriteLine ("は、内部例外:"+ e.InnerException.Message) です。
                
                返す場合は false です。}
                    
                Console.WriteLine ("サービスのヘルス:") です。Console.WriteLine ("サービス {0}: {1}"、serviceHealth.ServiceName、serviceHealth.AggregatedHealthState) です。
                
                正常性の状態を一覧表示します。
                    Console.WriteLine ("パーティションの正常性状態:") です。IList&lt;PartitionHealthState&gt; partitionHealthStates = serviceHealth.PartitionHealthStates; foreach (partitionHealthStates で PartitionHealthState partitionHealthState) {Console.WriteLine ("集計された正常性状態。"+ partitionHealthState.AggregatedHealthState) です。Console.WriteLine ("パーティション ID:"+ partitionHealthState.PartitionId);}
            
                    正常性イベントを一覧表示します。
            Console.WriteLine ("正常性イベント:") です。IList&lt;HealthEvent&gt; healthEvents = serviceHealth.HealthEvents; foreach (healthEvents で HealthEvent healthEvent) {Console.WriteLine ("正常性イベント:") です。Console.WriteLine ("最終更新日:"+ healthEvent.LastModifiedUtcTimestamp) です。Console.WriteLine ("UTC タイムスタンプをソース:"+ healthEvent.SourceUtcTimestamp) です。Console.WriteLine ("有効期限が切れました。"+ healthEvent.IsExpired) です。Console.WriteLine ("正常性の情報:") です。Console.WriteLine ("説明:"+ healthEvent.HealthInformation.Description) です。Console.WriteLine ("ソース ID:"+ healthEvent.HealthInformation.SourceId) です。Console.WriteLine ("正常性状態:"+ healthEvent.HealthInformation.HealthState) です。Console.WriteLine ("プロパティ:"+ healthEvent.HealthInformation.Property) です。Console.WriteLine ("有効期限が切れるを削除します"+ healthEvent.HealthInformation.RemoveWhenExpired);。Console.WriteLine ("シーケンス番号:"+ healthEvent.HealthInformation.SequenceNumber) です。Console.WriteLine ("Time to Live:"+ healthEvent.HealthInformation.TimeToLive);}
            
                    異常な評価を一覧表示します。
                Console.WriteLine ("異常な評価:") です。IList&lt;HealthEvaluation&gt; healthEvaluationList = serviceHealth.UnhealthyEvaluations; foreach (healthEvaluationList で HealthEvaluation healthEvaluation) {Console.WriteLine ("種類:"+ healthEvaluation.Kind) です。Console.WriteLine ("ヘルス状態を集計します。"+ healthEvaluation.AggregatedHealthState) です。Console.WriteLine ("説明:"+ healthEvaluation.Description);}
            
                Console.WriteLine() です。true を返す}
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="serviceName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceHealthAsync (serviceName As Uri, healthPolicy As ApplicationHealthPolicy) As Task(Of ServiceHealth)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (serviceName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Service Fabric サービスの名前。</para>
        </param>
        <param name="healthPolicy">アプリケーションの正常性ポリシーはサービスのヘルスを評価するために使用します。</param>
        <summary>
          <para>Service Fabric サービスのヘルスを非同期に取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric サービスの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作では、完了までに指定した時間より長くかかる場合が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="serviceName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (System.Fabric.Description.ServiceHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Fabric.Description.ServiceHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : System.Fabric.Description.ServiceHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ServiceHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">クエリの説明。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、Service Fabric サービスのヘルス、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric サービスの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Service Fabric サービスの名前。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、Service Fabric サービスのヘルス、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric サービスの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="serviceName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (serviceName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Service Fabric サービスの名前。</para>
        </param>
        <param name="healthPolicy">アプリケーションの正常性ポリシーは、エンティティのヘルスを評価するために使用します。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。
            キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的に、Service Fabric サービスのヘルス、指定したタイムアウト時間および取り消しを使用してトークン取得します。</para>
        </summary>
        <returns>
          <para>Service Fabric サービスの正常性。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />操作は、ユーザーによって指定されたときに返される<paramref name="timeout" />を完了します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="serviceName" />サービス ファブリック名として有効ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />通信エラーによって操作が失敗したときに返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />サービスがビジー状態のため、操作を処理するときに返されます。</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportHealth">
      <MemberSignature Language="C#" Value="public void ReportHealth (System.Fabric.Health.HealthReport healthReport);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReportHealth(class System.Fabric.Health.HealthReport healthReport) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />
      <MemberSignature Language="F#" Value="member this.ReportHealth : System.Fabric.Health.HealthReport -&gt; unit" Usage="healthClient.ReportHealth healthReport" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthReport" Type="System.Fabric.Health.HealthReport" />
      </Parameters>
      <Docs>
        <param name="healthReport">
          <para>送信するための <see cref="T:System.Fabric.Health.HealthReport" />。</para>
        </param>
        <summary>
          <para>Service Fabric エンティティのヘルスをレポートします。</para>
        </summary>
        <remarks>
          <para>
             クラスターを保護すると、正常性のクライアント管理者のアクセス許可をレポートを送信できるようにする必要があります。
             詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">FabricClient Api を使用してクラスターに接続する</see>です。
            </para>
          <para>
             正常性レポートの詳細については、次を参照してください。 <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric の正常性の監視</see>です。
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportHealth">
      <MemberSignature Language="C#" Value="public void ReportHealth (System.Fabric.Health.HealthReport healthReport, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReportHealth(class System.Fabric.Health.HealthReport healthReport, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="member this.ReportHealth : System.Fabric.Health.HealthReport * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="healthClient.ReportHealth (healthReport, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthReport" Type="System.Fabric.Health.HealthReport" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthReport">
          <para>送信するための <see cref="T:System.Fabric.Health.HealthReport" />。</para>
        </param>
        <param name="sendOptions">
          <para><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</para>
        </param>
        <summary>
          <para>Service Fabric エンティティおよびパス上のレポートの正常性は、レポートを送信する方法を制御するオプションを送信します。</para>
        </summary>
        <remarks>
          <para>
             クラスターを保護すると、正常性のクライアント管理者のアクセス許可をレポートを送信できるようにする必要があります。
             詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">FabricClient Api を使用してクラスターに接続します。</see></para>
          <para>
             正常性レポートの詳細については、次を参照してください。 <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric の正常性の監視</see>です。
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>メソッドに null 参照を渡したときに返されるを受け付けないとして有効な引数。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" /></para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" /></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>次のいずれかによって発生します。</para>
          <para>この操作に対してアクセス チェックが失敗したときに、E_ACCESSDENIED が返されます。</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>