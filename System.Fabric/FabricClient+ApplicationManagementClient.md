<Type Name="FabricClient+ApplicationManagementClient" FullName="System.Fabric.FabricClient+ApplicationManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.ApplicationManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/ApplicationManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ApplicationManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.ApplicationManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ApplicationManagementClient = class" />
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
      <para>Service Fabric アプリケーションの管理機能を提供します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyApplicationPackage">
      <MemberSignature Language="C#" Value="public void CopyApplicationPackage (string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyApplicationPackage(string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyApplicationPackage (imageStoreConnectionString As String, applicationPackagePath As String, applicationPackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.CopyApplicationPackage : string * string * string -&gt; unit" Usage="applicationManagementClient.CopyApplicationPackage (imageStoreConnectionString, applicationPackagePath, applicationPackagePathInImageStore)" />
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
        <Parameter Name="applicationPackagePath" Type="System.String" />
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。 内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。 Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore" イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para>ソース アプリケーション パッケージの完全パスです。</para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para>イメージ ストアに移行先の相対パス。 このパスが、イメージ ストアにルート ディレクトリに対して相対的な作成され、アプリケーション パッケージのコピーの送信先として使用します。</para>
        </param>
        <summary>
          <para>新しいアプリケーションの種類のプロビジョニングの準備、イメージ ストアにアプリケーション パッケージをアップロードします。</para>
        </summary>
        <remarks>
          <para>操作のタイムアウトは既定でネイティブ イメージ ストア用の 30 分にあり、XStore とファイル共有の容量のタイムアウトはありません。 オーバー ロード関数で適切なタイムアウト値を指定することも検討できます。<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" /></para>
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
          <para>イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CopyApplicationPackage">
      <MemberSignature Language="C#" Value="public void CopyApplicationPackage (string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyApplicationPackage(string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyApplicationPackage (imageStoreConnectionString As String, applicationPackagePath As String, applicationPackagePathInImageStore As String, timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.CopyApplicationPackage : string * string * string * TimeSpan -&gt; unit" Usage="applicationManagementClient.CopyApplicationPackage (imageStoreConnectionString, applicationPackagePath, applicationPackagePathInImageStore, timeout)" />
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
        <Parameter Name="applicationPackagePath" Type="System.String" />
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。 内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。 Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore" イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para>ソース アプリケーション パッケージの完全パスです。</para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para>イメージ ストアに移行先の相対パス。 このパスが、イメージ ストアにルート ディレクトリに対して相対的な作成され、アプリケーション パッケージのコピーの送信先として使用します。</para>
        </param>
        <param name="timeout">
          <para>アプリケーション パッケージの操作のコピーのタイムアウト</para>
        </param>
        <summary>
          <para>新しいアプリケーションの種類のプロビジョニングの準備、イメージ ストアにアプリケーション パッケージをアップロードします。</para>
        </summary>
        <remarks>To be added.</remarks>
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
          <para>イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CopyApplicationPackage">
      <MemberSignature Language="C#" Value="public void CopyApplicationPackage (string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, System.Fabric.IImageStoreProgressHandler progressHandler, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyApplicationPackage(string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, class System.Fabric.IImageStoreProgressHandler progressHandler, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.Fabric.IImageStoreProgressHandler,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyApplicationPackage (imageStoreConnectionString As String, applicationPackagePath As String, applicationPackagePathInImageStore As String, progressHandler As IImageStoreProgressHandler, timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.CopyApplicationPackage : string * string * string * System.Fabric.IImageStoreProgressHandler * TimeSpan -&gt; unit" Usage="applicationManagementClient.CopyApplicationPackage (imageStoreConnectionString, applicationPackagePath, applicationPackagePathInImageStore, progressHandler, timeout)" />
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
        <Parameter Name="applicationPackagePath" Type="System.String" />
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
        <Parameter Name="progressHandler" Type="System.Fabric.IImageStoreProgressHandler" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。 内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。 Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore" イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para>ソース アプリケーション パッケージの完全パスです。</para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para>イメージ ストアに移行先の相対パス。 このパスが、イメージ ストアにルート ディレクトリに対して相対的な作成され、アプリケーション パッケージのコピーの送信先として使用します。</para>
        </param>
        <param name="progressHandler">
          <para>リアルタイムの進行状況に関する情報を取得する進行状況ハンドラー</para>
        </param>
        <param name="timeout">
          <para>アプリケーション パッケージの操作のコピーのタイムアウト</para>
        </param>
        <summary>
          <para>新しいアプリケーションの種類のプロビジョニングの準備、イメージ ストアにアプリケーション パッケージをアップロードします。</para>
        </summary>
        <remarks>To be added.</remarks>
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
          <para>イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateApplicationAsync (System.Fabric.Description.ApplicationDescription applicationDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateApplicationAsync(class System.Fabric.Description.ApplicationDescription applicationDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateApplicationAsync : System.Fabric.Description.ApplicationDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.CreateApplicationAsync applicationDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationDescription" Type="System.Fabric.Description.ApplicationDescription" />
      </Parameters>
      <Docs>
        <param name="applicationDescription">
          <para>アプリケーションの説明。</para>
        </param>
        <summary>
          <para>作成し、特定の Service Fabric アプリケーションのインスタンスを作成します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />要求されたアプリケーションの種類用にプロビジョニングされたマニフェストに対して作成するアプリケーションの要求が正しくありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: 破損したファイルは、イメージ ストアに見つかりました。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: アプリケーションは、既に作成されています。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: 要求されたアプリケーションの種類はまだプロビジョニングされていません。</para>
        </exception>
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
          <para>イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                指定されたアプリケーション容量パラメーターが正しくありません。 参照してください<see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />、<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />と<see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" />アプリケーション容量パラメーターの正しい仕様です。
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateApplicationAsync (System.Fabric.Description.ApplicationDescription applicationDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateApplicationAsync(class System.Fabric.Description.ApplicationDescription applicationDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateApplicationAsync : System.Fabric.Description.ApplicationDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.CreateApplicationAsync (applicationDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationDescription" Type="System.Fabric.Description.ApplicationDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationDescription">
          <para>アプリケーションの説明。</para>
        </param>
        <param name="timeout">
          <para>時刻を返す前に続行するには、この操作により、システムの最大量を定義<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>この CancellationToken は、操作を確認します。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>作成し、特定の Service Fabric アプリケーションのインスタンスを作成します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />要求されたアプリケーションの種類用にプロビジョニングされたマニフェストに対して作成するアプリケーションの要求が正しくありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: ImageStore ファイルの破損が発生しました。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: アプリケーションは、既に作成されています。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: 要求されたアプリケーションの種類はまだプロビジョニングされていません。</para>
        </exception>
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
          <para>イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                指定されたアプリケーション容量パラメーターが正しくありません。 参照してください<see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />、<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />と<see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" />アプリケーション容量パラメーターの正しい仕様です。
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Fabric.Description.DeleteApplicationDescription)" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : System.Fabric.Description.DeleteApplicationDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync deleteApplicationDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteApplicationDescription" Type="System.Fabric.Description.DeleteApplicationDescription" />
      </Parameters>
      <Docs>
        <param name="deleteApplicationDescription">
          <para>削除するアプリケーションの説明です。</para>
        </param>
        <summary>
          <para>アプリケーション インスタンスをクラスターから削除し、アプリケーションに属するすべてのサービスを削除します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>すべてのアプリケーションの状態は失われ、アプリケーションを削除した後に回復できません。</para>
          <para>強制的な削除の呼び出しは、強制的な 1 つを継続的に通常の削除を変換できます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションをアップグレード中です。 </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteApplicationAsync (applicationName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use overload taking DeleteApplicationDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション インスタンス名の URI。</para>
        </param>
        <summary>
          <para>アプリケーション インスタンスをクラスターから削除し、アプリケーションに属するすべてのサービスを削除します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>すべてのアプリケーションの状態は失われ、アプリケーションを削除した後に回復できません。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションをアップグレード中です。 </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Fabric.Description.DeleteApplicationDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : System.Fabric.Description.DeleteApplicationDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync (deleteApplicationDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteApplicationDescription" Type="System.Fabric.Description.DeleteApplicationDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deleteApplicationDescription">
          <para>削除するアプリケーションの説明です。</para>
        </param>
        <param name="timeout">
          <para>System.TimeoutException を返す前に続行するには、この操作により、システム時刻の最大量を定義します。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>アプリケーション インスタンスをクラスターから削除し、アプリケーションに属するすべてのサービスを削除します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>すべてのアプリケーションの状態は失われ、アプリケーションを削除した後に回復できません。</para>
          <para>強制的な削除の呼び出しは、強制的な 1 つを継続的に通常の削除を変換できます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションをアップグレード中です。 </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use overload taking DeleteApplicationDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション インスタンス名の URI。</para>
        </param>
        <param name="timeout">
          <para>System.TimeoutException を返す前に続行するには、この操作により、システム時刻の最大量を定義します。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>アプリケーション インスタンスをクラスターから削除し、アプリケーションに属するすべてのサービスを削除します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>すべてのアプリケーションの状態は失われ、アプリケーションを削除した後に回復できません。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションをアップグレード中です。 </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeployServicePackageToNode">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeployServicePackageToNode (string applicationTypeName, string applicationTypeVersion, string serviceManifestName, System.Fabric.PackageSharingPolicyList sharingPolicies, string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeployServicePackageToNode(string applicationTypeName, string applicationTypeVersion, string serviceManifestName, class System.Fabric.PackageSharingPolicyList sharingPolicies, string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeployServicePackageToNode(System.String,System.String,System.String,System.Fabric.PackageSharingPolicyList,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeployServicePackageToNode : string * string * string * System.Fabric.PackageSharingPolicyList * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeployServicePackageToNode (applicationTypeName, applicationTypeVersion, serviceManifestName, sharingPolicies, nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="sharingPolicies" Type="System.Fabric.PackageSharingPolicyList" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>サービス マニフェストをダウンロードするに関連付けられている ApplicationTypeName</para>
        </param>
        <param name="applicationTypeVersion">
          <para>ApplicationType のバージョン </para>
        </param>
        <param name="serviceManifestName">
          <para>パッケージをダウンロードする必要があるサービス マニフェストの名前</para>
        </param>
        <param name="sharingPolicies">
          <para>共有の共有フォルダーにコピーする必要があるパッケージを表すポリシー</para>
        </param>
        <param name="nodeName">
          <para>パッケージがダウンロードする必要があるノードの名前です。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量システム T:System.TimeoutException を返す前に続行するには、この操作は許可されます。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用できます。</para>
        </param>
        <summary>
          <para>指定したノードのイメージ キャッシュにサービス マニフェストに関連付けられているパッケージをダウンロードします。 </para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetApplicationManifestAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetApplicationManifestAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationManifestAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationManifestAsync (applicationTypeName As String, applicationTypeVersion As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationManifestAsync : string * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="applicationManagementClient.GetApplicationManifestAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>アプリケーション マニフェストで指定された型名。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>アプリケーション マニフェストで指定されたタイプのバージョン。</para>
        </param>
        <summary>
          <para>プロビジョニングされたアプリケーション マニフェストのクラスターに格納されている内容を取得します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />をアプリケーション マニフェストの生の XML 文字列の内容の結果。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound">
          <para>要求されたアプリケーションの種類とバージョンが提供されていません。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetApplicationManifestAsync (string applicationTypeName, string applicationTypeVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetApplicationManifestAsync(string applicationTypeName, string applicationTypeVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationManifestAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationManifestAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="applicationManagementClient.GetApplicationManifestAsync (applicationTypeName, applicationTypeVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>アプリケーション マニフェストで指定された型名。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>アプリケーション マニフェストで指定されたタイプのバージョン。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>プロビジョニングされたアプリケーション マニフェストのクラスターに格納されている内容を取得します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />をアプリケーション マニフェストの生の XML 文字列の内容の結果。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound">
          <para>要求されたアプリケーションの種類とバージョンが提供されていません。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationUpgradeProgressAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationUpgradeProgressAsync (applicationName As Uri) As Task(Of ApplicationUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationUpgradeProgressAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;" Usage="applicationManagementClient.GetApplicationUpgradeProgressAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション インスタンス名の URI。</para>
        </param>
        <summary>
          <para>指定したアプリケーション インスタンスのアップグレードの進行状況を取得します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />を指定したアプリケーション インスタンスのアップグレードの進行状況の結果。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationUpgradeProgressAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationUpgradeProgressAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;" Usage="applicationManagementClient.GetApplicationUpgradeProgressAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション インスタンス名の URI。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定したアプリケーション インスタンスのアップグレードの進行状況を取得します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />を指定したアプリケーション インスタンスのアップグレードの進行状況の結果。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveNextApplicationUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync (System.Fabric.ApplicationUpgradeProgress upgradeProgress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync(class System.Fabric.ApplicationUpgradeProgress upgradeProgress) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" />
      <MemberSignature Language="VB.NET" Value="Public Function MoveNextApplicationUpgradeDomainAsync (upgradeProgress As ApplicationUpgradeProgress) As Task" />
      <MemberSignature Language="F#" Value="member this.MoveNextApplicationUpgradeDomainAsync : System.Fabric.ApplicationUpgradeProgress -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.MoveNextApplicationUpgradeDomainAsync upgradeProgress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.ApplicationUpgradeProgress" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para>– アップグレードの進行状況関心のあるアプリケーション インスタンス。 これは、アップグレード対象として次のアップグレード ドメインに関する情報を提供します。</para>
        </param>
        <summary>
          <para>Service Fabric を次のアップグレード ドメイン内のアプリケーション インスタンスをアップグレードするように指示します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>Service Fabric は現在更新ドメインのアップグレードが完了した場合のみ次のアップグレード ドメインに移動します。 つまり、<see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" />プロパティが保留されている必要がありますこのメソッドを呼び出す前にします。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveNextApplicationUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync (System.Fabric.ApplicationUpgradeProgress upgradeProgress, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync(class System.Fabric.ApplicationUpgradeProgress upgradeProgress, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveNextApplicationUpgradeDomainAsync : System.Fabric.ApplicationUpgradeProgress * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.MoveNextApplicationUpgradeDomainAsync (upgradeProgress, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.ApplicationUpgradeProgress" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para>目的のアプリケーション インスタンスのアップグレードの進行状況。 これは、アップグレード対象として次のアップグレード ドメインに関する情報を提供します。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>次のアップグレード ドメイン内のアプリケーション インスタンスの続行へのアップグレードに指示します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>Service Fabric は現在更新ドメインのアップグレードが完了した場合のみ次のアップグレード ドメインに移動します。 つまり、<see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" />プロパティが保留されている必要がありますこのメソッドを呼び出す前にします。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (System.Fabric.Description.ProvisionApplicationTypeDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(class System.Fabric.Description.ProvisionApplicationTypeDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.Fabric.Description.ProvisionApplicationTypeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProvisionApplicationAsync (description As ProvisionApplicationTypeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : System.Fabric.Description.ProvisionApplicationTypeDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ProvisionApplicationTypeDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>説明、プロビジョニングの要求のです。</para>
        </param>
        <summary>
          <para>プロビジョニングまたはクラスターとアプリケーションの種類を登録します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>アプリケーション インスタンスを作成する前に、これは必須です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: アプリケーションの種類が既にプロビジョニングされています</para>
        </exception>
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
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (string applicationPackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(string applicationPackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProvisionApplicationAsync (applicationPackagePathInImageStore As String) As Task" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : string -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync applicationPackagePathInImageStore" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationPackagePathInImageStore">
          <para>時に指定されたイメージ ストアにアプリケーション パッケージの相対パス<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />です。</para>
        </param>
        <summary>
          <para>Service Fabric アプリケーションの種類をプロビジョニングするか、クラスターに登録します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>アプリケーション インスタンスを作成する前に、これは必須です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: アプリケーションの種類が既にプロビジョニングされています</para>
        </exception>
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
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (System.Fabric.Description.ProvisionApplicationTypeDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(class System.Fabric.Description.ProvisionApplicationTypeDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.Fabric.Description.ProvisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : System.Fabric.Description.ProvisionApplicationTypeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ProvisionApplicationTypeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>説明、プロビジョニングの要求のです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>プロビジョニングまたはクラスターとアプリケーションの種類を登録します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>アプリケーション インスタンスを作成する前に、これは必須です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: アプリケーションの種類が既にプロビジョニングされています</para>
        </exception>
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
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (string applicationPackagePathInImageStore, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(string applicationPackagePathInImageStore, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync (applicationPackagePathInImageStore, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationPackagePathInImageStore">
          <para>時に指定されたイメージ ストアにアプリケーション パッケージの相対パス<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />です。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>プロビジョニングまたはクラスターとアプリケーションの種類を登録します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>アプリケーション インスタンスを作成する前に、これは必須です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: アプリケーションの種類が既にプロビジョニングされています</para>
        </exception>
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
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveApplicationPackage">
      <MemberSignature Language="C#" Value="public void RemoveApplicationPackage (string imageStoreConnectionString, string applicationPackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveApplicationPackage(string imageStoreConnectionString, string applicationPackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.RemoveApplicationPackage(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveApplicationPackage (imageStoreConnectionString As String, applicationPackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveApplicationPackage : string * string -&gt; unit" Usage="applicationManagementClient.RemoveApplicationPackage (imageStoreConnectionString, applicationPackagePathInImageStore)" />
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
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。 内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。 Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore" イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。 
            </para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para>時に指定されたイメージ ストアにアプリケーション パッケージの相対パス<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />です。</para>
        </param>
        <summary>
          <para>アプリケーション パッケージをイメージ ストアから削除します。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>ImageStore でファイルへのアクセス エラーが発生しました。</para>
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
    <Member MemberName="RollbackApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackApplicationUpgradeAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackApplicationUpgradeAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.RollbackApplicationUpgradeAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RollbackApplicationUpgradeAsync (applicationName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.RollbackApplicationUpgradeAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.RollbackApplicationUpgradeAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーションの名前</para>
        </param>
        <summary>
          <para>現在のアプリケーションのアップグレードのロールバックを開始します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: 保留中のアップグレードのロールバックに指定されたアプリケーションはありません。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RollbackApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackApplicationUpgradeAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackApplicationUpgradeAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.RollbackApplicationUpgradeAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RollbackApplicationUpgradeAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.RollbackApplicationUpgradeAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーションの名前</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>現在のアプリケーションのアップグレードのロールバックを開始します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (System.Fabric.Description.UnprovisionApplicationTypeDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(class System.Fabric.Description.UnprovisionApplicationTypeDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.Fabric.Description.UnprovisionApplicationTypeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnprovisionApplicationAsync (description As UnprovisionApplicationTypeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : System.Fabric.Description.UnprovisionApplicationTypeDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.UnprovisionApplicationTypeDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>サービスの提供解除操作のパラメーターについて説明します。</para>
        </param>
        <summary>
          <para>登録を解除し、Service Fabric アプリケーションの種類をクラスターから削除します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>このメソッドは、アプリケーションの種類のすべてのアプリケーション インスタンスが削除されている場合にのみ呼び出すことができます。 アプリケーションの種類が登録解除されると、この特定のアプリケーションの種類に対して新しいアプリケーション インスタンスを作成できません。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: アプリケーションの種類は、1 つまたは複数のアプリケーションによって使用されています。 </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnprovisionApplicationAsync (applicationTypeName As String, applicationTypeVersion As String) As Task" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>アプリケーションの種類名。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>アプリケーションの種類のバージョン。</para>
        </param>
        <summary>
          <para>登録を解除し、Service Fabric アプリケーションの種類をクラスターから削除します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>このメソッドは、アプリケーションの種類のすべてのアプリケーション インスタンスが削除されている場合にのみ呼び出すことができます。 アプリケーションの種類が登録解除されると、この特定のアプリケーションの種類に対して新しいアプリケーション インスタンスを作成できません。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: アプリケーションの種類は、1 つまたは複数のアプリケーションによって使用されています。 </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (System.Fabric.Description.UnprovisionApplicationTypeDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(class System.Fabric.Description.UnprovisionApplicationTypeDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.Fabric.Description.UnprovisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : System.Fabric.Description.UnprovisionApplicationTypeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.UnprovisionApplicationTypeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>サービスの提供解除操作のパラメーターについて説明します。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>登録を解除し、Service Fabric アプリケーションの種類をクラスターから削除します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>このメソッドは、アプリケーションの種類のすべてのアプリケーション インスタンスが削除されている場合にのみ呼び出すことができます。 アプリケーションの種類が登録解除されると、この特定のアプリケーションの種類に対して新しいアプリケーション インスタンスを作成できません。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: アプリケーションの種類は、1 つまたは複数のアプリケーションによって使用されています。 </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (string applicationTypeName, string applicationTypeVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(string applicationTypeName, string applicationTypeVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync (applicationTypeName, applicationTypeVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>アプリケーションの種類名。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>アプリケーションの種類のバージョン。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>登録を解除し、Service Fabric アプリケーションの種類をクラスターから削除します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>このメソッドは、アプリケーションの種類のすべてのアプリケーション インスタンスが削除されている場合にのみ呼び出すことができます。 アプリケーションの種類が登録解除されると、この特定のアプリケーションの種類に対して新しいアプリケーション インスタンスを作成できません。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: アプリケーションの種類は、1 つまたは複数のアプリケーションによって使用されています。 </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationAsync (System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationAsync(class System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationAsync : System.Fabric.Description.ApplicationUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationAsync applicationUpdateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationUpdateDescription" Type="System.Fabric.Description.ApplicationUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="applicationUpdateDescription">アプリケーションの更新プログラムの説明。</param>
        <summary>
            Service Fabric アプリケーションを更新します。
            </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: 別のアプリケーションの更新プログラムが既に進行中です。
                </para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                指定されたアプリケーションの更新のパラメーターが正しくありません。 参照してください<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />、<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />と<see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />アプリケーション容量パラメーターの正しい仕様です。
                </para>
          <para>
                可能であればそのパラメーターで<see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />が有効で、無効な組み合わせが生成される既存のアプリケーション容量パラメーターと組み合わせた場合がします。 たとえば、設定<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />で指定されているものよりも大きい値に<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />アプリケーションの作成時にします。
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationAsync (System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationAsync(class System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationAsync : System.Fabric.Description.ApplicationUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationAsync (applicationUpdateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationUpdateDescription" Type="System.Fabric.Description.ApplicationUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationUpdateDescription">アプリケーションの更新プログラムの説明。</param>
        <param name="timeout">時刻を返す前に続行するには、この操作により、システムの最大量を定義<see cref="T:System.TimeoutException" />です。</param>
        <param name="cancellationToken">この CancellationToken は、操作を確認します。
            操作を取り消す必要がある通知を伝達するために使用します。</param>
        <summary>
            Service Fabric アプリケーションを更新します。
            </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: 別のアプリケーションの更新プログラムが既に進行中です。
                </para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                指定されたアプリケーションの更新のパラメーターが正しくありません。 参照してください<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />、<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />と<see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />アプリケーション容量パラメーターの正しい仕様です。
                </para>
          <para>
                可能であればそのパラメーターで<see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />が有効で、無効な組み合わせが生成される既存のアプリケーション容量パラメーターと組み合わせた場合がします。 たとえば、設定<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />で指定されているものよりも大きい値に<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />アプリケーションの作成時にします。
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationUpgradeAsync (System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationUpgradeAsync(class System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateApplicationUpgradeAsync (updateDescription As ApplicationUpgradeUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationUpgradeAsync : System.Fabric.Description.ApplicationUpgradeUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationUpgradeAsync updateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ApplicationUpgradeUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para>変更するパラメーターの説明です。 パラメーターのままに指定されていない未変更の状態し、アップグレードで現在の値が保持されます。</para>
        </param>
        <summary>
          <para>保留中のアプリケーションのアップグレードのアップグレード パラメーターを変更します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: 変更を保留中のアプリケーションのアップグレードはありません。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationUpgradeAsync (System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationUpgradeAsync(class System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationUpgradeAsync : System.Fabric.Description.ApplicationUpgradeUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationUpgradeAsync (updateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ApplicationUpgradeUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para>変更するパラメーターの説明です。 パラメーターのままに指定されていない未変更の状態し、アップグレードで現在の値が保持されます。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認するトークンです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>保留中のアプリケーションのアップグレードのアップグレード パラメーターを変更します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: 変更を保留中のアプリケーションのアップグレードはありません。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeApplicationAsync (System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeApplicationAsync(class System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpgradeApplicationAsync(System.Fabric.Description.ApplicationUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeApplicationAsync (upgradeDescription As ApplicationUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeApplicationAsync : System.Fabric.Description.ApplicationUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpgradeApplicationAsync upgradeDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.ApplicationUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para>アップグレード ポリシーとアプリケーションをアップグレードできる説明。</para>
        </param>
        <summary>
          <para>アプリケーション インスタンスのアップグレードを実行します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: アップグレードは、プロビジョニングされたマニフェストに対して無効です。 </para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: アプリケーションの種類は存在しません。 </para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: 破損したファイルは、イメージ ストアに見つかりました。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションは、要求されたバージョンに既にアップグレードされています。</para>
        </exception>
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
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeApplicationAsync (System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeApplicationAsync(class System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpgradeApplicationAsync(System.Fabric.Description.ApplicationUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeApplicationAsync : System.Fabric.Description.ApplicationUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpgradeApplicationAsync (upgradeDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.ApplicationUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para>アップグレードのポリシーとアプリケーションをアップグレードするの説明です。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認するトークンです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>アプリケーション インスタンスのアップグレードを実行します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: アップグレードは、プロビジョニングされたマニフェストに対して無効です。 </para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: アプリケーションの種類は存在しません。 </para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: 破損したファイルは、イメージ ストアに見つかりました。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションは、要求されたバージョンに既にアップグレードされています。</para>
        </exception>
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
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>