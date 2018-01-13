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
      <para><span data-ttu-id="78163-101">Service Fabric アプリケーションの管理機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="78163-101">Provides the functionality to manage Service Fabric applications.</span></span></para>
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
          <para><span data-ttu-id="78163-102">イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="78163-102">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="78163-103">内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。</span><span class="sxs-lookup"><span data-stu-id="78163-103">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="78163-104">Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore"</span><span class="sxs-lookup"><span data-stu-id="78163-104">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="78163-105">イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-105">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para><span data-ttu-id="78163-106">ソース アプリケーション パッケージの完全パスです。</span><span class="sxs-lookup"><span data-stu-id="78163-106">The full path to the source application package.</span></span></para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para><span data-ttu-id="78163-107">イメージ ストアに移行先の相対パス。</span><span class="sxs-lookup"><span data-stu-id="78163-107">The relative path for the destination in the Image Store.</span></span> <span data-ttu-id="78163-108">このパスが、イメージ ストアにルート ディレクトリに対して相対的な作成され、アプリケーション パッケージのコピーの送信先として使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-108">This path is created relative to the root directory in the image store and used as the destination for the application package copy.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-109">新しいアプリケーションの種類のプロビジョニングの準備、イメージ ストアにアプリケーション パッケージをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="78163-109">Uploads an application package to the Image Store in preparation for provisioning a new application type.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="78163-110">操作のタイムアウトは既定でネイティブ イメージ ストア用の 30 分にあり、XStore とファイル共有の容量のタイムアウトはありません。</span><span class="sxs-lookup"><span data-stu-id="78163-110">The timeout of the operation will default to 30 minutes for native image store and there is no timeout capacity for XStore and file share.</span></span> <span data-ttu-id="78163-111">オーバー ロード関数で適切なタイムアウト値を指定することも検討できます。<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" /></span><span class="sxs-lookup"><span data-stu-id="78163-111">Can also consider specifying proper timeout value in the overloading function <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" /></span></span></para>
        </remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-112">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-112">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="78163-113">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-113">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="78163-114">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-114">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="78163-115">イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="78163-115">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-116"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-116"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-117">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-117">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-118">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-118">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-119">イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="78163-119">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="78163-120">内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。</span><span class="sxs-lookup"><span data-stu-id="78163-120">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="78163-121">Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore"</span><span class="sxs-lookup"><span data-stu-id="78163-121">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="78163-122">イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-122">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para><span data-ttu-id="78163-123">ソース アプリケーション パッケージの完全パスです。</span><span class="sxs-lookup"><span data-stu-id="78163-123">The full path to the source application package.</span></span></para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para><span data-ttu-id="78163-124">イメージ ストアに移行先の相対パス。</span><span class="sxs-lookup"><span data-stu-id="78163-124">The relative path for the destination in the Image Store.</span></span> <span data-ttu-id="78163-125">このパスが、イメージ ストアにルート ディレクトリに対して相対的な作成され、アプリケーション パッケージのコピーの送信先として使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-125">This path is created relative to the root directory in the image store and used as the destination for the application package copy.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-126">アプリケーション パッケージの操作のコピーのタイムアウト</span><span class="sxs-lookup"><span data-stu-id="78163-126">The timeout of copying application package operation</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-127">新しいアプリケーションの種類のプロビジョニングの準備、イメージ ストアにアプリケーション パッケージをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="78163-127">Uploads an application package to the Image Store in preparation for provisioning a new application type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-128">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-128">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="78163-129">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-129">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="78163-130">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-130">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="78163-131">イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="78163-131">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-132"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-132"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-133">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-133">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-134">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-134">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-135">イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="78163-135">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="78163-136">内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。</span><span class="sxs-lookup"><span data-stu-id="78163-136">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="78163-137">Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore"</span><span class="sxs-lookup"><span data-stu-id="78163-137">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="78163-138">イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-138">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para><span data-ttu-id="78163-139">ソース アプリケーション パッケージの完全パスです。</span><span class="sxs-lookup"><span data-stu-id="78163-139">The full path to the source application package.</span></span></para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para><span data-ttu-id="78163-140">イメージ ストアに移行先の相対パス。</span><span class="sxs-lookup"><span data-stu-id="78163-140">The relative path for the destination in the Image Store.</span></span> <span data-ttu-id="78163-141">このパスが、イメージ ストアにルート ディレクトリに対して相対的な作成され、アプリケーション パッケージのコピーの送信先として使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-141">This path is created relative to the root directory in the image store and used as the destination for the application package copy.</span></span></para>
        </param>
        <param name="progressHandler">
          <para><span data-ttu-id="78163-142">リアルタイムの進行状況に関する情報を取得する進行状況ハンドラー</span><span class="sxs-lookup"><span data-stu-id="78163-142">The progress handler to retrieve real time progress information</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-143">アプリケーション パッケージの操作のコピーのタイムアウト</span><span class="sxs-lookup"><span data-stu-id="78163-143">The timeout of copying application package operation</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-144">新しいアプリケーションの種類のプロビジョニングの準備、イメージ ストアにアプリケーション パッケージをアップロードします。</span><span class="sxs-lookup"><span data-stu-id="78163-144">Uploads an application package to the Image Store in preparation for provisioning a new application type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-145">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-145">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="78163-146">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-146">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="78163-147">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-147">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="78163-148">イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="78163-148">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-149"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-149"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-150">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-150">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-151">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-151">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-152">アプリケーションの説明。</span><span class="sxs-lookup"><span data-stu-id="78163-152">The description of the application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-153">作成し、特定の Service Fabric アプリケーションのインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="78163-153">Creates and instantiates the specific Service Fabric application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-154">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-154">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-155"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-155">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-156">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-156">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-157"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />要求されたアプリケーションの種類用にプロビジョニングされたマニフェストに対して作成するアプリケーションの要求が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="78163-157"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: The create application request is not valid with respect to the provisioned manifests for the requested application type.</span></span></para>
          <para>
            <span data-ttu-id="78163-158"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</span><span class="sxs-lookup"><span data-stu-id="78163-158"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span></para>
          <para>
            <span data-ttu-id="78163-159"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: 破損したファイルは、イメージ ストアに見つかりました。</span><span class="sxs-lookup"><span data-stu-id="78163-159"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: A corrupted file was encountered on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="78163-160"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: アプリケーションは、既に作成されています。</span><span class="sxs-lookup"><span data-stu-id="78163-160"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: The application has already been created.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-161"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: 要求されたアプリケーションの種類はまだプロビジョニングされていません。</span><span class="sxs-lookup"><span data-stu-id="78163-161"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: The requested application type has not been provisioned yet.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-162">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-162">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="78163-163">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-163">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="78163-164">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-164">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="78163-165">イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="78163-165">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <span data-ttu-id="78163-166"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-166"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-167">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-167">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-168">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-168">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                <span data-ttu-id="78163-169">指定されたアプリケーション容量パラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="78163-169">The application capacity parameters specified are incorrect.</span></span> <span data-ttu-id="78163-170">参照してください<see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />、<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />と<see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" />アプリケーション容量パラメーターの正しい仕様です。</span><span class="sxs-lookup"><span data-stu-id="78163-170">Refer to <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> and <see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" /> for correct specification of application capacity parameters.</span></span>
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
          <para><span data-ttu-id="78163-171">アプリケーションの説明。</span><span class="sxs-lookup"><span data-stu-id="78163-171">The description of the application.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-172">時刻を返す前に続行するには、この操作により、システムの最大量を定義<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-172">Defines the maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-173">この CancellationToken は、操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="78163-173">The CancellationToken that the operation is observing.</span></span> <span data-ttu-id="78163-174">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-174">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-175">作成し、特定の Service Fabric アプリケーションのインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="78163-175">Creates and instantiates the specific Service Fabric application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-176">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-176">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-177"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-177">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-178">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-178">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-179"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />要求されたアプリケーションの種類用にプロビジョニングされたマニフェストに対して作成するアプリケーションの要求が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="78163-179"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: The create application request is not valid with respect to the provisioned manifests for the requested application type.</span></span></para>
          <para>
            <span data-ttu-id="78163-180"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</span><span class="sxs-lookup"><span data-stu-id="78163-180"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span></para>
          <para>
            <span data-ttu-id="78163-181"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: ImageStore ファイルの破損が発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-181"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: A corrupted file was encountered on the ImageStore.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="78163-182"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: アプリケーションは、既に作成されています。</span><span class="sxs-lookup"><span data-stu-id="78163-182"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: The application has already been created.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-183"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: 要求されたアプリケーションの種類はまだプロビジョニングされていません。</span><span class="sxs-lookup"><span data-stu-id="78163-183"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: The requested application type has not been provisioned yet.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-184">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-184">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="78163-185">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-185">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="78163-186">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-186">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="78163-187">イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="78163-187">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <span data-ttu-id="78163-188"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-188"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-189">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-189">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-190">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-190">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                <span data-ttu-id="78163-191">指定されたアプリケーション容量パラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="78163-191">The application capacity parameters specified are incorrect.</span></span> <span data-ttu-id="78163-192">参照してください<see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />、<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />と<see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" />アプリケーション容量パラメーターの正しい仕様です。</span><span class="sxs-lookup"><span data-stu-id="78163-192">Refer to <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> and <see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" /> for correct specification of application capacity parameters.</span></span>
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
          <para><span data-ttu-id="78163-193">削除するアプリケーションの説明です。</span><span class="sxs-lookup"><span data-stu-id="78163-193">The description of the application to be deleted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-194">アプリケーション インスタンスをクラスターから削除し、アプリケーションに属するすべてのサービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="78163-194">Deletes the application instance from the cluster and deletes all services belonging to the application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-195">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-195">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-196">すべてのアプリケーションの状態は失われ、アプリケーションを削除した後に回復できません。</span><span class="sxs-lookup"><span data-stu-id="78163-196">All application state will be lost and cannot be recovered after the application is deleted.</span></span></para>
          <para><span data-ttu-id="78163-197">強制的な削除の呼び出しは、強制的な 1 つを継続的に通常の削除を変換できます。</span><span class="sxs-lookup"><span data-stu-id="78163-197">A forceful deletion call can convert on-going normal deletion to forceful one.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-198"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-198">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-199">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-199">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-200"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-200"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="78163-201"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションをアップグレード中です。</span><span class="sxs-lookup"><span data-stu-id="78163-201"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is being upgraded.</span></span> </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-202">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-202">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-203">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-203">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-204">アプリケーション インスタンス名の URI。</span><span class="sxs-lookup"><span data-stu-id="78163-204">The URI of the application instance name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-205">アプリケーション インスタンスをクラスターから削除し、アプリケーションに属するすべてのサービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="78163-205">Deletes the application instance from the cluster and deletes all services belonging to the application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-206">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-206">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-207">すべてのアプリケーションの状態は失われ、アプリケーションを削除した後に回復できません。</span><span class="sxs-lookup"><span data-stu-id="78163-207">All application state will be lost and cannot be recovered after the application is deleted.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-208"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-208">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-209">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-209">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-210"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-210"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="78163-211"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションをアップグレード中です。</span><span class="sxs-lookup"><span data-stu-id="78163-211"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is being upgraded.</span></span> </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-212">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-212">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-213">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-213">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-214">削除するアプリケーションの説明です。</span><span class="sxs-lookup"><span data-stu-id="78163-214">The description of the application to be deleted.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-215">System.TimeoutException を返す前に続行するには、この操作により、システム時刻の最大量を定義します。</span><span class="sxs-lookup"><span data-stu-id="78163-215">Defines the maximum amount of time the system will allow this operation to continue before returning System.TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-216"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="78163-216">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="78163-217">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-217">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-218">アプリケーション インスタンスをクラスターから削除し、アプリケーションに属するすべてのサービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="78163-218">Deletes the application instance from the cluster and deletes all services belonging to the application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-219">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-219">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-220">すべてのアプリケーションの状態は失われ、アプリケーションを削除した後に回復できません。</span><span class="sxs-lookup"><span data-stu-id="78163-220">All application state will be lost and cannot be recovered after the application is deleted.</span></span></para>
          <para><span data-ttu-id="78163-221">強制的な削除の呼び出しは、強制的な 1 つを継続的に通常の削除を変換できます。</span><span class="sxs-lookup"><span data-stu-id="78163-221">A forceful deletion call can convert on-going normal deletion to forceful one.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-222"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-222">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-223">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-223">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-224"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-224"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="78163-225"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションをアップグレード中です。</span><span class="sxs-lookup"><span data-stu-id="78163-225"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is being upgraded.</span></span> </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-226">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-226">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-227">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-227">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-228">アプリケーション インスタンス名の URI。</span><span class="sxs-lookup"><span data-stu-id="78163-228">The URI of the application instance name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-229">System.TimeoutException を返す前に続行するには、この操作により、システム時刻の最大量を定義します。</span><span class="sxs-lookup"><span data-stu-id="78163-229">Defines the maximum amount of time the system will allow this operation to continue before returning System.TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-230"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="78163-230">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="78163-231">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-231">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-232">アプリケーション インスタンスをクラスターから削除し、アプリケーションに属するすべてのサービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="78163-232">Deletes the application instance from the cluster and deletes all services belonging to the application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-233">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-233">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-234">すべてのアプリケーションの状態は失われ、アプリケーションを削除した後に回復できません。</span><span class="sxs-lookup"><span data-stu-id="78163-234">All application state will be lost and cannot be recovered after the application is deleted.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-235"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-235">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-236">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-236">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-237"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-237"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="78163-238"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションをアップグレード中です。</span><span class="sxs-lookup"><span data-stu-id="78163-238"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is being upgraded.</span></span> </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-239">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-239">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-240">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-240">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-241">サービス マニフェストをダウンロードするに関連付けられている ApplicationTypeName</span><span class="sxs-lookup"><span data-stu-id="78163-241">ApplicationTypeName associated with service manifest to be downloaded</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="78163-242">ApplicationType のバージョン</span><span class="sxs-lookup"><span data-stu-id="78163-242">Version of ApplicationType</span></span> </para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="78163-243">パッケージをダウンロードする必要があるサービス マニフェストの名前</span><span class="sxs-lookup"><span data-stu-id="78163-243">Name of service manifest whose packages need to be downloaded</span></span></para>
        </param>
        <param name="sharingPolicies">
          <para><span data-ttu-id="78163-244">共有の共有フォルダーにコピーする必要があるパッケージを表すポリシー</span><span class="sxs-lookup"><span data-stu-id="78163-244">Sharing policy representing packages that need to be copied to shared folders</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="78163-245">パッケージがダウンロードする必要があるノードの名前です。</span><span class="sxs-lookup"><span data-stu-id="78163-245">Name of the node where packages need to be downloaded.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-246">時間の最大量システム T:System.TimeoutException を返す前に続行するには、この操作は許可されます。</span><span class="sxs-lookup"><span data-stu-id="78163-246">The maximum amount of time the system will allow this operation to continue before returning T:System.TimeoutException</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-247"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="78163-247">The <see cref="T:System.Threading.CancellationToken" />that the operation is observing.</span></span> <span data-ttu-id="78163-248">操作を取り消す必要がある通知を伝達するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="78163-248">It can be used to propagate notification that the operation should be canceled</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-249">指定したノードのイメージ キャッシュにサービス マニフェストに関連付けられているパッケージをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="78163-249">Downloads packages associated with service manifest to image cache on specified node.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-250">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-250">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
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
          <para><span data-ttu-id="78163-251">アプリケーション マニフェストで指定された型名。</span><span class="sxs-lookup"><span data-stu-id="78163-251">The type name as specified in the Application Manifest.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="78163-252">アプリケーション マニフェストで指定されたタイプのバージョン。</span><span class="sxs-lookup"><span data-stu-id="78163-252">The type version as specified in the Application Manifest.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-253">プロビジョニングされたアプリケーション マニフェストのクラスターに格納されている内容を取得します。</span><span class="sxs-lookup"><span data-stu-id="78163-253">Gets the contents of a provisioned Application Manifest stored in the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-254">A<see cref="T:System.Threading.Tasks.Task" />をアプリケーション マニフェストの生の XML 文字列の内容の結果。</span><span class="sxs-lookup"><span data-stu-id="78163-254">A <see cref="T:System.Threading.Tasks.Task" /> whose result is the raw XML string contents of the Application Manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound">
          <para><span data-ttu-id="78163-255">要求されたアプリケーションの種類とバージョンが提供されていません。</span><span class="sxs-lookup"><span data-stu-id="78163-255">The requested application type and version has not been provisioned.</span></span></para>
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
          <para><span data-ttu-id="78163-256">アプリケーション マニフェストで指定された型名。</span><span class="sxs-lookup"><span data-stu-id="78163-256">The type name as specified in the Application Manifest.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="78163-257">アプリケーション マニフェストで指定されたタイプのバージョン。</span><span class="sxs-lookup"><span data-stu-id="78163-257">The type version as specified in the Application Manifest.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-258">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-258">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-259"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="78163-259">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="78163-260">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-260">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-261">プロビジョニングされたアプリケーション マニフェストのクラスターに格納されている内容を取得します。</span><span class="sxs-lookup"><span data-stu-id="78163-261">Gets the contents of a provisioned Application Manifest stored in the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-262">A<see cref="T:System.Threading.Tasks.Task" />をアプリケーション マニフェストの生の XML 文字列の内容の結果。</span><span class="sxs-lookup"><span data-stu-id="78163-262">A <see cref="T:System.Threading.Tasks.Task" /> whose result is the raw XML string contents of the Application Manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound">
          <para><span data-ttu-id="78163-263">要求されたアプリケーションの種類とバージョンが提供されていません。</span><span class="sxs-lookup"><span data-stu-id="78163-263">The requested application type and version has not been provisioned.</span></span></para>
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
          <para><span data-ttu-id="78163-264">アプリケーション インスタンス名の URI。</span><span class="sxs-lookup"><span data-stu-id="78163-264">The URI of the application instance name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-265">指定したアプリケーション インスタンスのアップグレードの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="78163-265">Retrieves the upgrade progress of the specified application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-266">A<see cref="T:System.Threading.Tasks.Task" />を指定したアプリケーション インスタンスのアップグレードの進行状況の結果。</span><span class="sxs-lookup"><span data-stu-id="78163-266">A <see cref="T:System.Threading.Tasks.Task" /> whose result is the upgrade progress of the specified application instance.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-267"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-267">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-268">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-268">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-269"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-269"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-270">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-270">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-271">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-271">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-272">アプリケーション インスタンス名の URI。</span><span class="sxs-lookup"><span data-stu-id="78163-272">The URI of the application instance name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-273">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-273">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-274"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="78163-274">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="78163-275">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-275">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-276">指定したアプリケーション インスタンスのアップグレードの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="78163-276">Retrieves the upgrade progress of the specified application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-277">A<see cref="T:System.Threading.Tasks.Task" />を指定したアプリケーション インスタンスのアップグレードの進行状況の結果。</span><span class="sxs-lookup"><span data-stu-id="78163-277">A <see cref="T:System.Threading.Tasks.Task" /> whose result is the upgrade progress of the specified application instance.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-278"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-278">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-279">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-279">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-280"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-280"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-281">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-281">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-282">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-282">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-283">– アップグレードの進行状況関心のあるアプリケーション インスタンス。</span><span class="sxs-lookup"><span data-stu-id="78163-283">–The Upgrade progress of the application instance of interest.</span></span> <span data-ttu-id="78163-284">これは、アップグレード対象として次のアップグレード ドメインに関する情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="78163-284">This provides information about the next upgrade domain to be upgraded.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-285">Service Fabric を次のアップグレード ドメイン内のアプリケーション インスタンスをアップグレードするように指示します。</span><span class="sxs-lookup"><span data-stu-id="78163-285">Instructs the Service Fabric to upgrade the application instance in the next upgrade domain.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-286">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-286">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-287">Service Fabric は現在更新ドメインのアップグレードが完了した場合のみ次のアップグレード ドメインに移動します。</span><span class="sxs-lookup"><span data-stu-id="78163-287">Service Fabric would only move to the next upgrade domain if it has completed the upgrade domain it is currently updating.</span></span> <span data-ttu-id="78163-288">つまり、<see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" />プロパティが保留されている必要がありますこのメソッドを呼び出す前にします。</span><span class="sxs-lookup"><span data-stu-id="78163-288">In other words, <see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" /> property should be Pending before calling this method.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-289"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-289">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-290">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-290">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-291"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-291"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-292">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-292">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-293">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-293">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-294">目的のアプリケーション インスタンスのアップグレードの進行状況。</span><span class="sxs-lookup"><span data-stu-id="78163-294">The upgrade progress of the application instance of interest.</span></span> <span data-ttu-id="78163-295">これは、アップグレード対象として次のアップグレード ドメインに関する情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="78163-295">This provides information about the next upgrade domain to be upgraded.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-296">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-296">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-297"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="78163-297">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="78163-298">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-298">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-299">次のアップグレード ドメイン内のアプリケーション インスタンスの続行へのアップグレードに指示します。</span><span class="sxs-lookup"><span data-stu-id="78163-299">Instructs the upgrade to continue with the application instance in the next upgrade domain.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-300">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-300">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-301">Service Fabric は現在更新ドメインのアップグレードが完了した場合のみ次のアップグレード ドメインに移動します。</span><span class="sxs-lookup"><span data-stu-id="78163-301">Service Fabric would only move to the next upgrade domain if it has completed the upgrade domain it is currently updating.</span></span> <span data-ttu-id="78163-302">つまり、<see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" />プロパティが保留されている必要がありますこのメソッドを呼び出す前にします。</span><span class="sxs-lookup"><span data-stu-id="78163-302">In other words, <see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" /> property should be Pending before calling this method.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-303"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-303">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-304">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-304">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-305"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-305"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-306">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-306">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-307">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-307">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-308">説明、プロビジョニングの要求のです。</span><span class="sxs-lookup"><span data-stu-id="78163-308">Description of the of provision request.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-309">プロビジョニングまたはクラスターとアプリケーションの種類を登録します。</span><span class="sxs-lookup"><span data-stu-id="78163-309">Provision or register an application type with the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-310">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-310">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-311">アプリケーション インスタンスを作成する前に、これは必須です。</span><span class="sxs-lookup"><span data-stu-id="78163-311">This is mandatory before an application instance can be created.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-312"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-312">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-313">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-313">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-314"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-314"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="78163-315"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: アプリケーションの種類が既にプロビジョニングされています</span><span class="sxs-lookup"><span data-stu-id="78163-315"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: The application type has already been provisioned</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-316">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-316">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="78163-317">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-317">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="78163-318">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-318">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="78163-319">イメージ ストア ファイル/ディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="78163-319">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-320">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-320">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-321">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-321">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-322">時に指定されたイメージ ストアにアプリケーション パッケージの相対パス<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-322">The relative path for the application package in the image store specified during <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-323">Service Fabric アプリケーションの種類をプロビジョニングするか、クラスターに登録します。</span><span class="sxs-lookup"><span data-stu-id="78163-323">Provisions or registers a Service Fabric application type with the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-324">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-324">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-325">アプリケーション インスタンスを作成する前に、これは必須です。</span><span class="sxs-lookup"><span data-stu-id="78163-325">This is mandatory before an application instance can be created.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-326"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-326">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-327">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-327">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-328"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-328"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="78163-329"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: アプリケーションの種類が既にプロビジョニングされています</span><span class="sxs-lookup"><span data-stu-id="78163-329"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: The application type has already been provisioned</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-330">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-330">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="78163-331">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-331">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="78163-332">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-332">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="78163-333">イメージ ストア ファイル/ディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="78163-333">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-334">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-334">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-335">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-335">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-336">説明、プロビジョニングの要求のです。</span><span class="sxs-lookup"><span data-stu-id="78163-336">Description of the of provision request.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-337">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-337">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-338"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="78163-338">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="78163-339">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-339">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-340">プロビジョニングまたはクラスターとアプリケーションの種類を登録します。</span><span class="sxs-lookup"><span data-stu-id="78163-340">Provision or register an application type with the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-341">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-341">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-342">アプリケーション インスタンスを作成する前に、これは必須です。</span><span class="sxs-lookup"><span data-stu-id="78163-342">This is mandatory before an application instance can be created.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-343"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-343">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-344">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-344">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-345"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-345"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="78163-346"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: アプリケーションの種類が既にプロビジョニングされています</span><span class="sxs-lookup"><span data-stu-id="78163-346"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: The application type has already been provisioned</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-347">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-347">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="78163-348">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-348">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="78163-349">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-349">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="78163-350">イメージ ストア ファイル/ディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="78163-350">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-351">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-351">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-352">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-352">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-353">時に指定されたイメージ ストアにアプリケーション パッケージの相対パス<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-353">The relative path for the application package in the image store specified during <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-354">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-354">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-355"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="78163-355">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="78163-356">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-356">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-357">プロビジョニングまたはクラスターとアプリケーションの種類を登録します。</span><span class="sxs-lookup"><span data-stu-id="78163-357">Provision or register an application type with the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-358">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-358">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-359">アプリケーション インスタンスを作成する前に、これは必須です。</span><span class="sxs-lookup"><span data-stu-id="78163-359">This is mandatory before an application instance can be created.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-360"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-360">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-361">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-361">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-362"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-362"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="78163-363"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: アプリケーションの種類が既にプロビジョニングされています</span><span class="sxs-lookup"><span data-stu-id="78163-363"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: The application type has already been provisioned</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-364">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-364">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="78163-365">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-365">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="78163-366">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-366">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="78163-367">イメージ ストア ファイル/ディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="78163-367">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-368">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-368">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-369">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-369">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-370">イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="78163-370">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="78163-371">内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。</span><span class="sxs-lookup"><span data-stu-id="78163-371">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="78163-372">Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore"</span><span class="sxs-lookup"><span data-stu-id="78163-372">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="78163-373">イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-373">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para><span data-ttu-id="78163-374">時に指定されたイメージ ストアにアプリケーション パッケージの相対パス<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-374">The relative path for the application package in the image store specified during <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-375">アプリケーション パッケージをイメージ ストアから削除します。</span><span class="sxs-lookup"><span data-stu-id="78163-375">Deletes an application package from the Image Store.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-376">ImageStore でファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-376">There was an error accessing a file on the ImageStore.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-377"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-377"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-378">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-378">The request timed out but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-379">アプリケーションの名前</span><span class="sxs-lookup"><span data-stu-id="78163-379">Name of the application</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-380">現在のアプリケーションのアップグレードのロールバックを開始します。</span><span class="sxs-lookup"><span data-stu-id="78163-380">Starts rolling back the current application upgrade.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-381">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-381">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-382"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: 保留中のアップグレードのロールバックに指定されたアプリケーションはありません。</span><span class="sxs-lookup"><span data-stu-id="78163-382"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: There is no pending upgrade for the specified application to rollback.</span></span></para>
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
          <para><span data-ttu-id="78163-383">アプリケーションの名前</span><span class="sxs-lookup"><span data-stu-id="78163-383">Name of the application</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-384">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-384">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-385"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="78163-385">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="78163-386">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-386">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-387">現在のアプリケーションのアップグレードのロールバックを開始します。</span><span class="sxs-lookup"><span data-stu-id="78163-387">Starts rolling back the current application upgrade</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-388">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-388">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
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
          <para><span data-ttu-id="78163-389">サービスの提供解除操作のパラメーターについて説明します。</span><span class="sxs-lookup"><span data-stu-id="78163-389">Describes parameters for the unprovision operation.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-390">登録を解除し、Service Fabric アプリケーションの種類をクラスターから削除します。</span><span class="sxs-lookup"><span data-stu-id="78163-390">Unregisters and removes a Service Fabric application type from the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-391">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-391">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-392">このメソッドは、アプリケーションの種類のすべてのアプリケーション インスタンスが削除されている場合にのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="78163-392">This method can only be called if all application instance of the application type has been deleted.</span></span> <span data-ttu-id="78163-393">アプリケーションの種類が登録解除されると、この特定のアプリケーションの種類に対して新しいアプリケーション インスタンスを作成できません。</span><span class="sxs-lookup"><span data-stu-id="78163-393">Once the application type is unregistered, no new application instance can be created for this particular application type.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-394"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-394">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-395">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-395">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-396"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: アプリケーションの種類は、1 つまたは複数のアプリケーションによって使用されています。</span><span class="sxs-lookup"><span data-stu-id="78163-396"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: The application type is being used by one or more applications.</span></span> </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-397"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-397"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-398">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-398">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-399">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-399">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-400">アプリケーションの種類名。</span><span class="sxs-lookup"><span data-stu-id="78163-400">The name of the application type.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="78163-401">アプリケーションの種類のバージョン。</span><span class="sxs-lookup"><span data-stu-id="78163-401">The version of the application type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-402">登録を解除し、Service Fabric アプリケーションの種類をクラスターから削除します。</span><span class="sxs-lookup"><span data-stu-id="78163-402">Unregisters and removes a Service Fabric application type from the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-403">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-403">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-404">このメソッドは、アプリケーションの種類のすべてのアプリケーション インスタンスが削除されている場合にのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="78163-404">This method can only be called if all application instance of the application type has been deleted.</span></span> <span data-ttu-id="78163-405">アプリケーションの種類が登録解除されると、この特定のアプリケーションの種類に対して新しいアプリケーション インスタンスを作成できません。</span><span class="sxs-lookup"><span data-stu-id="78163-405">Once the application type is unregistered, no new application instance can be created for this particular application type.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-406"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-406">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-407">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-407">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-408"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: アプリケーションの種類は、1 つまたは複数のアプリケーションによって使用されています。</span><span class="sxs-lookup"><span data-stu-id="78163-408"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: The application type is being used by one or more applications.</span></span> </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-409"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-409"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-410">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-410">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-411">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-411">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-412">サービスの提供解除操作のパラメーターについて説明します。</span><span class="sxs-lookup"><span data-stu-id="78163-412">Describes parameters for the unprovision operation.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-413">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-413">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-414"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="78163-414">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="78163-415">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-415">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-416">登録を解除し、Service Fabric アプリケーションの種類をクラスターから削除します。</span><span class="sxs-lookup"><span data-stu-id="78163-416">Unregisters and removes a Service Fabric application type from the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-417">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-417">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-418">このメソッドは、アプリケーションの種類のすべてのアプリケーション インスタンスが削除されている場合にのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="78163-418">This method can only be called if all application instance of the application type has been deleted.</span></span> <span data-ttu-id="78163-419">アプリケーションの種類が登録解除されると、この特定のアプリケーションの種類に対して新しいアプリケーション インスタンスを作成できません。</span><span class="sxs-lookup"><span data-stu-id="78163-419">Once the application type is unregistered, no new application instance can be created for this particular application type.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-420"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-420">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-421">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-421">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-422"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: アプリケーションの種類は、1 つまたは複数のアプリケーションによって使用されています。</span><span class="sxs-lookup"><span data-stu-id="78163-422"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: The application type is being used by one or more applications.</span></span> </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-423"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-423"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-424">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-424">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-425">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-425">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-426">アプリケーションの種類名。</span><span class="sxs-lookup"><span data-stu-id="78163-426">The name of the application type.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="78163-427">アプリケーションの種類のバージョン。</span><span class="sxs-lookup"><span data-stu-id="78163-427">The version of the application type.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-428">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-428">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-429"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。</span><span class="sxs-lookup"><span data-stu-id="78163-429">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="78163-430">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-430">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-431">登録を解除し、Service Fabric アプリケーションの種類をクラスターから削除します。</span><span class="sxs-lookup"><span data-stu-id="78163-431">Unregisters and removes a Service Fabric application type from the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-432">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-432">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="78163-433">このメソッドは、アプリケーションの種類のすべてのアプリケーション インスタンスが削除されている場合にのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="78163-433">This method can only be called if all application instance of the application type has been deleted.</span></span> <span data-ttu-id="78163-434">アプリケーションの種類が登録解除されると、この特定のアプリケーションの種類に対して新しいアプリケーション インスタンスを作成できません。</span><span class="sxs-lookup"><span data-stu-id="78163-434">Once the application type is unregistered, no new application instance can be created for this particular application type.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-435"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-435">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-436">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-436">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-437"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: アプリケーションの種類は、1 つまたは複数のアプリケーションによって使用されています。</span><span class="sxs-lookup"><span data-stu-id="78163-437"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: The application type is being used by one or more applications.</span></span> </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-438"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-438"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-439">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-439">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-440">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-440">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
        <param name="applicationUpdateDescription"><span data-ttu-id="78163-441">アプリケーションの更新プログラムの説明。</span><span class="sxs-lookup"><span data-stu-id="78163-441">Application update description.</span></span></param>
        <summary>
            <span data-ttu-id="78163-442">Service Fabric アプリケーションを更新します。</span><span class="sxs-lookup"><span data-stu-id="78163-442">Updates a Service Fabric application.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="78163-443">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-443">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-444"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</span><span class="sxs-lookup"><span data-stu-id="78163-444"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span>
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-445"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-445"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span>
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="78163-446"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: 別のアプリケーションの更新プログラムが既に進行中です。</span><span class="sxs-lookup"><span data-stu-id="78163-446"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: Another application update is already in progress.</span></span>
                </para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                <span data-ttu-id="78163-447">指定されたアプリケーションの更新のパラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="78163-447">The application update parameters specified are incorrect.</span></span> <span data-ttu-id="78163-448">参照してください<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />、<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />と<see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />アプリケーション容量パラメーターの正しい仕様です。</span><span class="sxs-lookup"><span data-stu-id="78163-448">Refer to <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> and <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" /> for correct specification of application capacity parameters.</span></span>
                </para>
          <para>
                <span data-ttu-id="78163-449">可能であればそのパラメーターで<see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />が有効で、無効な組み合わせが生成される既存のアプリケーション容量パラメーターと組み合わせた場合がします。</span><span class="sxs-lookup"><span data-stu-id="78163-449">It is possible that parameters in <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> are valid, but when combined with existing application capacity parameters they produce an invalid combination.</span></span> <span data-ttu-id="78163-450">たとえば、設定<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />で指定されているものよりも大きい値に<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />アプリケーションの作成時にします。</span><span class="sxs-lookup"><span data-stu-id="78163-450">For example, setting <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" /> to a value that is higher than the one that was specified in <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> when application was created.</span></span>
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
        <param name="applicationUpdateDescription"><span data-ttu-id="78163-451">アプリケーションの更新プログラムの説明。</span><span class="sxs-lookup"><span data-stu-id="78163-451">Application update description.</span></span></param>
        <param name="timeout"><span data-ttu-id="78163-452">時刻を返す前に続行するには、この操作により、システムの最大量を定義<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-452">Defines the maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="78163-453">この CancellationToken は、操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="78163-453">The CancellationToken that the operation is observing.</span></span>
            <span data-ttu-id="78163-454">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-454">It can be used to propagate notification that the operation should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="78163-455">Service Fabric アプリケーションを更新します。</span><span class="sxs-lookup"><span data-stu-id="78163-455">Updates a Service Fabric application.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="78163-456">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-456">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-457"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</span><span class="sxs-lookup"><span data-stu-id="78163-457"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span>
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-458"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-458"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span>
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="78163-459"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: 別のアプリケーションの更新プログラムが既に進行中です。</span><span class="sxs-lookup"><span data-stu-id="78163-459"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: Another application update is already in progress.</span></span>
                </para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                <span data-ttu-id="78163-460">指定されたアプリケーションの更新のパラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="78163-460">The application update parameters specified are incorrect.</span></span> <span data-ttu-id="78163-461">参照してください<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />、<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />と<see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />アプリケーション容量パラメーターの正しい仕様です。</span><span class="sxs-lookup"><span data-stu-id="78163-461">Refer to <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> and <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" /> for correct specification of application capacity parameters.</span></span>
                </para>
          <para>
                <span data-ttu-id="78163-462">可能であればそのパラメーターで<see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />が有効で、無効な組み合わせが生成される既存のアプリケーション容量パラメーターと組み合わせた場合がします。</span><span class="sxs-lookup"><span data-stu-id="78163-462">It is possible that parameters in <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> are valid, but when combined with existing application capacity parameters they produce an invalid combination.</span></span> <span data-ttu-id="78163-463">たとえば、設定<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />で指定されているものよりも大きい値に<see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" />アプリケーションの作成時にします。</span><span class="sxs-lookup"><span data-stu-id="78163-463">For example, setting <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" /> to a value that is higher than the one that was specified in <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> when application was created.</span></span>
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
          <para><span data-ttu-id="78163-464">変更するパラメーターの説明です。</span><span class="sxs-lookup"><span data-stu-id="78163-464">Description of parameters to modify.</span></span> <span data-ttu-id="78163-465">パラメーターのままに指定されていない未変更の状態し、アップグレードで現在の値が保持されます。</span><span class="sxs-lookup"><span data-stu-id="78163-465">Unspecified parameters are left unmodified and will retain their current value in the upgrade.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-466">保留中のアプリケーションのアップグレードのアップグレード パラメーターを変更します。</span><span class="sxs-lookup"><span data-stu-id="78163-466">Modifies the upgrade parameters of a pending application upgrade.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-467">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-467">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-468"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: 変更を保留中のアプリケーションのアップグレードはありません。</span><span class="sxs-lookup"><span data-stu-id="78163-468"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: There is no pending application upgrade to modify.</span></span></para>
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
          <para><span data-ttu-id="78163-469">変更するパラメーターの説明です。</span><span class="sxs-lookup"><span data-stu-id="78163-469">Description of parameters to modify.</span></span> <span data-ttu-id="78163-470">パラメーターのままに指定されていない未変更の状態し、アップグレードで現在の値が保持されます。</span><span class="sxs-lookup"><span data-stu-id="78163-470">Unspecified parameters are left unmodified and will retain their current value in the upgrade.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-471">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-471">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-472">操作を確認するトークンです。</span><span class="sxs-lookup"><span data-stu-id="78163-472">The token that the operation is observing.</span></span> <span data-ttu-id="78163-473">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-473">It can be used to propagate a notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-474">保留中のアプリケーションのアップグレードのアップグレード パラメーターを変更します。</span><span class="sxs-lookup"><span data-stu-id="78163-474">Modifies the upgrade parameters of a pending application upgrade.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-475">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-475">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-476"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: 変更を保留中のアプリケーションのアップグレードはありません。</span><span class="sxs-lookup"><span data-stu-id="78163-476"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: There is no pending application upgrade to modify.</span></span></para>
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
          <para><span data-ttu-id="78163-477">アップグレード ポリシーとアプリケーションをアップグレードできる説明。</span><span class="sxs-lookup"><span data-stu-id="78163-477">The description of the upgrade policy and the application to be upgrade.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-478">アプリケーション インスタンスのアップグレードを実行します。</span><span class="sxs-lookup"><span data-stu-id="78163-478">Performs upgrade on an application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-479">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-479">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-480"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-480">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-481">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-481">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-482"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: アップグレードは、プロビジョニングされたマニフェストに対して無効です。</span><span class="sxs-lookup"><span data-stu-id="78163-482"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: The upgrade is invalid with respect to the provisioned manifests.</span></span> </para>
          <para>
            <span data-ttu-id="78163-483"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: アプリケーションの種類は存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-483"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: The application type does not exist.</span></span> </para>
          <para>
            <span data-ttu-id="78163-484"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</span><span class="sxs-lookup"><span data-stu-id="78163-484"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span></para>
          <para>
            <span data-ttu-id="78163-485"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: 破損したファイルは、イメージ ストアに見つかりました。</span><span class="sxs-lookup"><span data-stu-id="78163-485"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: A corrupted file was encountered on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-486"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-486"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="78163-487"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションは、要求されたバージョンに既にアップグレードされています。</span><span class="sxs-lookup"><span data-stu-id="78163-487"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is already being upgraded to the requested version.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-488">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-488">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="78163-489">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-489">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="78163-490">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-490">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="78163-491">イメージ ストア ファイル/ディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="78163-491">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <span data-ttu-id="78163-492"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-492"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-493">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-493">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-494">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-494">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="78163-495">アップグレードのポリシーとアプリケーションをアップグレードするの説明です。</span><span class="sxs-lookup"><span data-stu-id="78163-495">The description of the upgrade policy and the application to be upgraded.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="78163-496">システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="78163-496">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="78163-497">操作を確認するトークンです。</span><span class="sxs-lookup"><span data-stu-id="78163-497">The token that the operation is observing.</span></span> <span data-ttu-id="78163-498">操作を取り消す必要がある通知を伝達するために使用します。</span><span class="sxs-lookup"><span data-stu-id="78163-498">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="78163-499">アプリケーション インスタンスのアップグレードを実行します。</span><span class="sxs-lookup"><span data-stu-id="78163-499">Performs upgrade on an application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="78163-500">A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="78163-500">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="78163-501"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="78163-501">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="78163-502">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="78163-502">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="78163-503"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: アップグレードは、プロビジョニングされたマニフェストに対して無効です。</span><span class="sxs-lookup"><span data-stu-id="78163-503"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: The upgrade is invalid with respect to the provisioned manifests.</span></span> </para>
          <para>
            <span data-ttu-id="78163-504"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: アプリケーションの種類は存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-504"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: The application type does not exist.</span></span> </para>
          <para>
            <span data-ttu-id="78163-505"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</span><span class="sxs-lookup"><span data-stu-id="78163-505"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span></para>
          <para>
            <span data-ttu-id="78163-506"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: 破損したファイルは、イメージ ストアに見つかりました。</span><span class="sxs-lookup"><span data-stu-id="78163-506"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: A corrupted file was encountered on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="78163-507"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="78163-507"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="78163-508"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションは、要求されたバージョンに既にアップグレードされています。</span><span class="sxs-lookup"><span data-stu-id="78163-508"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is already being upgraded to the requested version.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="78163-509">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="78163-509">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="78163-510">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-510">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="78163-511">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="78163-511">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="78163-512">イメージ ストア ファイル/ディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="78163-512">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <span data-ttu-id="78163-513"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="78163-513"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="78163-514">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="78163-514">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="78163-515">タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="78163-515">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>