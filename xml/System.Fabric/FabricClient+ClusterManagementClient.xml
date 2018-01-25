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
      <para><span data-ttu-id="46eb3-101">クラスターのメンテナンス操作を実行するには、クラスター管理クライアントを表します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-101">Represents the cluster management client for performing cluster maintenance operations.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="46eb3-102"><see cref="T:System.Fabric.FabricClient.ClusterManagementClient" />クラスター全体の管理に役立つ Api を提供します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-102">The <see cref="T:System.Fabric.FabricClient.ClusterManagementClient" /> provides APIs which help to manage the cluster as a whole.</span></span> <span data-ttu-id="46eb3-103">これらは、ノードおよび重大な障害の場合のサービスを回復しなければならないの損失などの主要なクラスター イベントに関連する通常の管理コマンドです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-103">These are typically administrative commands which relate to major cluster events such as the loss of nodes and the need to recover services in the case of major failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-104">アクティブ化するノードです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-104">The Node to be Activated.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-105">現在非アクティブ化されている Service Fabric クラスター ノードをアクティブにします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-105">Activates a Service Fabric cluster node which is currently deactivated.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-106">要求の非同期受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-106">A Task that represents the asynchronous acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-107">アクティブ化すると、ノードはもう一度、新しいレプリカを配置するための有効なターゲットなり、残りのノードで閉じられたレプリカでもは開かれます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-107">Once activated, the node will again become a viable target for placing new replicas, and any closed replicas remaining on the node will be opened.</span></span></para>
          <para>
                <span data-ttu-id="46eb3-108">この API の完了時にアクティブ化することを目的は、システムによって登録されていることを意味します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-108">When this API completes it implies that the intent to activate has been registered by the system.</span></span> <span data-ttu-id="46eb3-109">アクティブ化が完了したことは限りません。</span><span class="sxs-lookup"><span data-stu-id="46eb3-109">It does not mean that the activation is complete.</span></span> <span data-ttu-id="46eb3-110">使用して、操作の進行状況を決定できます、 <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span><span class="sxs-lookup"><span data-stu-id="46eb3-110">The progress of the operation can be determined by using the <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-111">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-111">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-112">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-112">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-113">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-113">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-114">アクティブ化するノードです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-114">The Node to be Activated.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-115">返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-115">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-116">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-116">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-117">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-117">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-118">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-118">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-119">現在非アクティブ化されている Service Fabric クラスター ノードをアクティブにします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-119">Activates a Service Fabric cluster node which is currently deactivated.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-120">要求の非同期受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-120">A Task that represents the asynchronous acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-121">アクティブ化すると、ノードはもう一度、新しいレプリカを配置するための有効なターゲットなり、残りのノードで閉じられたレプリカでもは開かれます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-121">Once activated, the node will again become a viable target for placing new replicas, and any closed replicas remaining on the node will be opened.</span></span></para>
          <para>
                <span data-ttu-id="46eb3-122">この API の完了時にアクティブ化することを目的は、システムによって登録されていることを意味します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-122">When this API completes it implies that the intent to activate has been registered by the system.</span></span> <span data-ttu-id="46eb3-123">アクティブ化が完了したことは限りません。</span><span class="sxs-lookup"><span data-stu-id="46eb3-123">It does not mean that the activation is complete.</span></span> <span data-ttu-id="46eb3-124">使用して、操作の進行状況を決定できます、 <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span><span class="sxs-lookup"><span data-stu-id="46eb3-124">The progress of the operation can be determined by using the <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-125">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-125">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-126">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-126">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-127">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-127">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-128">イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="46eb3-128">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="46eb3-129">内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-129">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="46eb3-130">Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore"</span><span class="sxs-lookup"><span data-stu-id="46eb3-130">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="46eb3-131">イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-131">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="clusterManifestPath">
          <para><span data-ttu-id="46eb3-132">クラスターへの完全パスでは、コピーするファイルをマニフェストします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-132">The full path to the cluster manifest file to be copied.</span></span></para>
        </param>
        <param name="clusterManifestPathInImageStore">
          <para><span data-ttu-id="46eb3-133">イメージ ストアに変換先のファイル名を指定の相対パス。</span><span class="sxs-lookup"><span data-stu-id="46eb3-133">The relative path along with the file name of the destination in the image store.</span></span> <span data-ttu-id="46eb3-134">ClusterManifestPath が指定されている場合に、このパラメーターを使用することが必要です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-134">This parameter is required when clusterManifestPath is specified.</span></span> <span data-ttu-id="46eb3-135">このパスが、イメージ ストアにルート ディレクトリに対して相対的な作成され、クラスター マニフェストのコピーの送信先として使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-135">This path is created relative to the root directory in the image store and used as the destination for the cluster manifest copy.</span></span></para>
        </param>
        <param name="codePackagePath">
          <para><span data-ttu-id="46eb3-136">Service Fabric コード パッケージをコピーするへの完全パス。</span><span class="sxs-lookup"><span data-stu-id="46eb3-136">The full path to the Service Fabric code package to be copied.</span></span></para>
        </param>
        <param name="codePackagePathInImageStore">
          <para><span data-ttu-id="46eb3-137">イメージ ストアに変換先のファイル名を指定の相対パス。</span><span class="sxs-lookup"><span data-stu-id="46eb3-137">The relative path along with the file name of the destination in the image store.</span></span> <span data-ttu-id="46eb3-138">CodePackagePathInImageStore が指定されている場合に、このパラメーターを使用することが必要です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-138">This parameter is required when codePackagePathInImageStore is specified.</span></span> <span data-ttu-id="46eb3-139">このパスが、イメージ ストアにルート ディレクトリに対して相対的な作成され、コード パッケージのコピーの送信先として使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-139">This path is created relative to the root directory in the image store and used as the destination for the code package copy.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-140">クラスター マニフェストのファイルや Service Fabric コード パッケージをイメージ ストアにコピーします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-140">Copies the cluster manifest file and/or Service Fabric code package to the image store.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="46eb3-141">ソース クラスター マニフェストのパスとソース コードのパスの両方を null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="46eb3-141">Both source cluster manifest path and source code path cannot be null.</span></span></para>
        </remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="46eb3-142">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="46eb3-142">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="46eb3-143">必要なファイルが、イメージ ストアに見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="46eb3-143">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="46eb3-144">イメージ ストアに必要なディレクトリが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="46eb3-144">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="46eb3-145">イメージ ストア ファイル/ディレクトリへのパスが長すぎます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-145">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="46eb3-146"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-146"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="46eb3-147">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="46eb3-147">The request timed out but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="46eb3-148">非アクティブ化するノードの名前。</span><span class="sxs-lookup"><span data-stu-id="46eb3-148">The name of the node to deactivate.</span></span></para>
        </param>
        <param name="deactivationIntent">
          <para><span data-ttu-id="46eb3-149"><see cref="T:System.Fabric.NodeDeactivationIntent" />をノードを非アクティブ化します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-149">The <see cref="T:System.Fabric.NodeDeactivationIntent" /> for deactivating the node.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-150">指定した特定のノードを非アクティブ化<see cref="T:System.Fabric.NodeDeactivationIntent" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-150">Deactivates a particular node with the specified <see cref="T:System.Fabric.NodeDeactivationIntent" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-151">要求の非同期受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-151">A Task that represents the asynchronous acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-152">この API の完了時に、非アクティブ化することを目的は、システムによって登録されていることを意味します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-152">When this API completes it implies that the intent to deactivate has been registered by the system.</span></span> <span data-ttu-id="46eb3-153">非アクティブ化が完了したことは限りません。</span><span class="sxs-lookup"><span data-stu-id="46eb3-153">It does not mean that the deactivation is complete.</span></span> <span data-ttu-id="46eb3-154">使用して、操作の進行状況を決定できます、 <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span><span class="sxs-lookup"><span data-stu-id="46eb3-154">The progress of the operation can be determined by using the <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span></span> </para>
          <para>
                <span data-ttu-id="46eb3-155">非アクティブ化インテントの「高く」が減少しない、非アクティブ化が進行中は、いったん (であるノードが非アクティブ化など、<see cref="F:System.Fabric.NodeDeactivationIntent.Pause" />インテントを非アクティブ化を指定できます<see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />、です逆はできなくします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-155">Once the deactivation is in progress, the deactivation intent can be “increased” but not decreased (for example, a node which is was deactivated with the <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> intent can be deactivated further with <see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />, but not the other way around.</span></span> <span data-ttu-id="46eb3-156">使用してノードを再びアクティブにすることがあります<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" />が非アクティブ化した後にいちます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-156">Nodes may be reactivated via <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" /> any time after they are deactivated.</span></span> <span data-ttu-id="46eb3-157">非アクティブ化が完了していない場合、非アクティブ化を取り消します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-157">If the deactivation is not complete this will cancel the deactivation.</span></span> <span data-ttu-id="46eb3-158">ノードがダウンし、その復帰を非アクティブ化中には、サービスがそのノードに配置される前に再アクティブ化する必要があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-158">A node which goes down and comes back up while deactivated will still need to be reactivated before services will be placed on that node.</span></span></para>
          <para>
                <span data-ttu-id="46eb3-159">Service Fabric を非アクティブ化が 'セーフ' プロセスことを確認します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-159">Service Fabric ensures that deactivation is a 'safe' process.</span></span> <span data-ttu-id="46eb3-160">いくつかの安全性チェックが実行されます (を参照してください<see cref="T:System.Fabric.SafetyCheckKind" />) 可用性またはデータの損失がないことを確認するには</span><span class="sxs-lookup"><span data-stu-id="46eb3-160">It performs several safety checks (see <see cref="T:System.Fabric.SafetyCheckKind" />) to ensure that there is no loss of availability or data</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-161">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-161">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-162">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-162">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-163">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-163">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-164">非アクティブ化するノードの名前。</span><span class="sxs-lookup"><span data-stu-id="46eb3-164">The name of the node to deactivate.</span></span></para>
        </param>
        <param name="deactivationIntent">
          <para><span data-ttu-id="46eb3-165"><see cref="T:System.Fabric.NodeDeactivationIntent" />をノードを非アクティブ化します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-165">The <see cref="T:System.Fabric.NodeDeactivationIntent" /> for deactivating the node.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-166">返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-166">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-167">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-167">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-168">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-168">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-169">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-169">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-170">指定した特定のノードを非アクティブ化<see cref="T:System.Fabric.NodeDeactivationIntent" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-170">Deactivates a particular node with the specified <see cref="T:System.Fabric.NodeDeactivationIntent" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-171">要求の非同期受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-171">A Task that represents the asynchronous acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-172">この API の完了時に、非アクティブ化することを目的は、システムによって登録されていることを意味します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-172">When this API completes it implies that the intent to deactivate has been registered by the system.</span></span> <span data-ttu-id="46eb3-173">非アクティブ化が完了したことは限りません。</span><span class="sxs-lookup"><span data-stu-id="46eb3-173">It does not mean that the deactivation is complete.</span></span> <span data-ttu-id="46eb3-174">使用して、操作の進行状況を決定できます、 <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span><span class="sxs-lookup"><span data-stu-id="46eb3-174">The progress of the operation can be determined by using the <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span></span> </para>
          <para>
                <span data-ttu-id="46eb3-175">非アクティブ化インテントの「高く」が減少しない、非アクティブ化が進行中は、いったん (であるノードが非アクティブ化など、<see cref="F:System.Fabric.NodeDeactivationIntent.Pause" />インテントを非アクティブ化を指定できます<see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />、です逆はできなくします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-175">Once the deactivation is in progress, the deactivation intent can be “increased” but not decreased (for example, a node which is was deactivated with the <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> intent can be deactivated further with <see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />, but not the other way around.</span></span> <span data-ttu-id="46eb3-176">使用してノードを再びアクティブにすることがあります<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" />が非アクティブ化した後にいちます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-176">Nodes may be reactivated via <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" /> any time after they are deactivated.</span></span> <span data-ttu-id="46eb3-177">非アクティブ化が完了していない場合、非アクティブ化を取り消します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-177">If the deactivation is not complete this will cancel the deactivation.</span></span> <span data-ttu-id="46eb3-178">ノードがダウンし、その復帰を非アクティブ化中には、サービスがそのノードに配置される前に再アクティブ化する必要があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-178">A node which goes down and comes back up while deactivated will still need to be reactivated before services will be placed on that node.</span></span></para>
          <para>
                <span data-ttu-id="46eb3-179">Service Fabric を非アクティブ化が 'セーフ' プロセスことを確認します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-179">Service Fabric ensures that deactivation is a 'safe' process.</span></span> <span data-ttu-id="46eb3-180">いくつかの安全性チェックが実行されます (を参照してください<see cref="T:System.Fabric.SafetyCheckKind" />) 可用性またはデータの損失がないことを確認するには</span><span class="sxs-lookup"><span data-stu-id="46eb3-180">It performs several safety checks (see <see cref="T:System.Fabric.SafetyCheckKind" />) to ensure that there is no loss of availability or data</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-181">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-181">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-182">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-182">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-183">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-183">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-184">Service Fabric クラスターの構成ファイルを文字列として取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-184">Gets the Service Fabric cluster configuration file as a string.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-185">Service Fabric クラスターを文字列としての構成ファイル。</span><span class="sxs-lookup"><span data-stu-id="46eb3-185">The Service Fabric cluster configuration file as a string.</span></span></para>
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
        <param name="apiVersion"><span data-ttu-id="46eb3-186">Api のバージョン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-186">Api version.</span></span></param>
        <summary>
          <para><span data-ttu-id="46eb3-187">Service Fabric クラスターの構成ファイルを文字列として取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-187">Gets the Service Fabric cluster configuration file as a string.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-188">Service Fabric クラスターを文字列としての構成ファイル。</span><span class="sxs-lookup"><span data-stu-id="46eb3-188">The Service Fabric cluster configuration file as a string.</span></span></para>
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
          <para><span data-ttu-id="46eb3-189">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-189">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-190">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-190">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-191">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-191">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-192">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-192">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-193">Service Fabric クラスターの構成ファイルを文字列として指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-193">Gets the Service Fabric cluster configuration file as a string, by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-194">指定したタイムアウトとキャンセル トークンを使用して、文字列として Service Fabric クラスターの構成ファイル。</span><span class="sxs-lookup"><span data-stu-id="46eb3-194">The Service Fabric cluster configuration file as a string, by using the specified timeout and cancellation token.</span></span></para>
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
        <param name="apiVersion"><span data-ttu-id="46eb3-195">Api バージョン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-195">Api verison.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-196">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-196">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-197">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-197">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-198">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-198">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-199">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-199">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-200">Service Fabric クラスターの構成ファイルを文字列として指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-200">Gets the Service Fabric cluster configuration file as a string, by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-201">指定したタイムアウトとキャンセル トークンを使用して、文字列として Service Fabric クラスターの構成ファイル。</span><span class="sxs-lookup"><span data-stu-id="46eb3-201">The Service Fabric cluster configuration file as a string, by using the specified timeout and cancellation token.</span></span></para>
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
            <span data-ttu-id="46eb3-202">アップグレードが進行中の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-202">Obtains the status of an upgrade in progress.</span></span>
            </summary>
        <returns><span data-ttu-id="46eb3-203">FabricOrchestrationUpgradeProgress</span><span class="sxs-lookup"><span data-stu-id="46eb3-203">FabricOrchestrationUpgradeProgress</span></span></returns>
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
            <span data-ttu-id="46eb3-204">アップグレードが進行中の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-204">Obtains the status of an upgrade in progress.</span></span>
            </summary>
        <returns><span data-ttu-id="46eb3-205">FabricOrchestrationUpgradeProgress</span><span class="sxs-lookup"><span data-stu-id="46eb3-205">FabricOrchestrationUpgradeProgress</span></span></returns>
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
          <para><span data-ttu-id="46eb3-206">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-206">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="46eb3-207">アップグレードが進行中の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-207">Obtains the status of an upgrade in progress.</span></span>
            </summary>
        <returns><span data-ttu-id="46eb3-208">FabricOrchestrationUpgradeProgress</span><span class="sxs-lookup"><span data-stu-id="46eb3-208">FabricOrchestrationUpgradeProgress</span></span></returns>
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
          <para><span data-ttu-id="46eb3-209">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-209">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-210">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-210">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-211">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-211">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-212">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-212">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="46eb3-213">アップグレードが進行中の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-213">Obtains the status of an upgrade in progress.</span></span>
            </summary>
        <returns><span data-ttu-id="46eb3-214">FabricOrchestrationUpgradeProgress</span><span class="sxs-lookup"><span data-stu-id="46eb3-214">FabricOrchestrationUpgradeProgress</span></span></returns>
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
          <para><span data-ttu-id="46eb3-215">現在の実行中のクラスター マニフェストの XML コンテンツを取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-215">Gets the XML contents of the current running cluster manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-216">クラスター マニフェストの内容。</span><span class="sxs-lookup"><span data-stu-id="46eb3-216">The cluster manifest contents.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-217"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-217">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-218">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-218">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
          <para><span data-ttu-id="46eb3-219">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-219">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-220">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-220">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-221">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-221">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-222">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-222">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-223">現在の実行中のクラスター マニフェストの XML コンテンツを取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-223">Gets the XML contents of the current running cluster manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-224">クラスター マニフェストの内容。</span><span class="sxs-lookup"><span data-stu-id="46eb3-224">The cluster manifest contents.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-225"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-225">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-226">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-226">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
          <para><span data-ttu-id="46eb3-227">取得するには、どのクラスター マニフェストを決定する追加のパラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-227">Specifies additional parameters to determine which cluster manifest to retrieve.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-228">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-228">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-229">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-229">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-230">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-230">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-231">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-231">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-232">クラスターの XML コンテンツがで指定されたマニフェストを取得<paramref name="queryDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-232">Gets the XML contents of a cluster manifest as specified by <paramref name="queryDescription" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-233">クラスター マニフェストの内容。</span><span class="sxs-lookup"><span data-stu-id="46eb3-233">The cluster manifest contents.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-234"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-234">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-235">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-235">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
          <para><span data-ttu-id="46eb3-236">Service Fabric アップグレード プロセスの進行状況を返します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-236">Returns the progress of a Service Fabric upgrade process.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-237">Service Fabric の進行状況は、プロセスをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-237">The progress of a Service Fabric upgrade process.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-238"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-238">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-239">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-239">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
          <para><span data-ttu-id="46eb3-240">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-240">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-241">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-241">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-242">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-242">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-243">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-243">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-244">Service Fabric アップグレード プロセスの進行状況を返します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-244">Returns the progress of a Service Fabric upgrade process.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-245">Service Fabric の進行状況は、プロセスをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-245">The progress of a Service Fabric upgrade process.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-246"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-246">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-247">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-247">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
          <para><span data-ttu-id="46eb3-248">Service Fabric アップグレード オーケストレーション サービスの状態を文字列として取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-248">Gets the Service Fabric Upgrade Orchestration Service state as a string.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-249">文字列として Service Fabric アップグレード オーケストレーション サービスの状態。</span><span class="sxs-lookup"><span data-stu-id="46eb3-249">The Service Fabric Upgrade Orchestration Service state as a string.</span></span></para>
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
          <para><span data-ttu-id="46eb3-250">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-250">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-251">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-251">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-252">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-252">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-253">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-253">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-254">Service Fabric アップグレード オーケストレーション サービスの状態を文字列として指定したタイムアウト時間および取り消しを使用してトークン取得します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-254">Gets the Service Fabric Upgrade Orchestration Service state as a string, by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-255">指定したタイムアウトとキャンセル トークンを使用して、文字列として Service Fabric アップグレード オーケストレーション サービスの状態。</span><span class="sxs-lookup"><span data-stu-id="46eb3-255">The Service Fabric Upgrade Orchestration Service state as a string, by using the specified timeout and cancellation token.</span></span></para>
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
          <para><span data-ttu-id="46eb3-256">ファブリックは、使用するプロセス オブジェクトをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-256">The fabric upgrade process object to use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-257">Service Fabric を現在のアップグレード ドメインが完了した場合、クラスター内の次のアップグレード ドメインをアップグレードするように指示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-257">Instructs the Service Fabric to upgrade the next upgrade domain in the cluster if the current upgrade domain has been completed.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-258">クラスターのアップグレード ドメイン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-258">The upgraded domain in the cluster.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="46eb3-259"><see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" /> に似ています。</span><span class="sxs-lookup"><span data-stu-id="46eb3-259">Similar to <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" />.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-260"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-260">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-261">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-261">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
          <para><span data-ttu-id="46eb3-262">ファブリックは、使用するプロセス オブジェクトをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-262">The fabric upgrade process object to use.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-263">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-263">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-264">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-264">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-265">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-265">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-266">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-266">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-267">Service Fabric 場合は、現在のアップグレード ドメインが完了したら、指定したタイムアウトとキャンセル トークンを使用して、クラスター内の次のアップグレード ドメインをアップグレードするように指示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-267">Instructs Service Fabric to upgrade the next upgrade domain in the cluster if the current upgrade domain has been completed, by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-268">クラスターのアップグレード ドメイン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-268">The upgraded domain in the cluster.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="46eb3-269"><see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" /> に似ています。</span><span class="sxs-lookup"><span data-stu-id="46eb3-269">Similar to <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-270"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-270">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-271">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-271">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
          <para><span data-ttu-id="46eb3-272">更新の修正プログラム ファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="46eb3-272">The path to the update patch file.</span></span></para>
        </param>
        <param name="clusterManifestFilePath">
          <para><span data-ttu-id="46eb3-273">クラスター マニフェストへのパス。</span><span class="sxs-lookup"><span data-stu-id="46eb3-273">The path to the cluster manifest.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-274">Service Fabric をプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-274">Provisions the Service Fabric.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-275">プロビジョニング済みの Service Fabric です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-275">The provisioned Service Fabric.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="46eb3-276">A <languageKeyword>null</languageKeyword>のいずれかの値が許可されて、<paramref name="patchFilePath" />パラメーターまたは<paramref name="clusterManifestFilePath" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="46eb3-276">A <languageKeyword>null</languageKeyword> value is permitted for either the <paramref name="patchFilePath" /> parameter or the <paramref name="clusterManifestFilePath" /> parameter.</span></span> <span data-ttu-id="46eb3-277">A <languageKeyword>null</languageKeyword>両方のパラメーター値を使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="46eb3-277">A <languageKeyword>null</languageKeyword> value cannot be used for both parameters.</span></span></para>
          <para><span data-ttu-id="46eb3-278">イメージ ストアの場所にこの修正プログラム ファイルおよびクラスター マニフェスト ファイルがアップロードされます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-278">This will upload the patch file and/or cluster manifest file to the image store location.</span></span> <span data-ttu-id="46eb3-279">イメージ ストアの場所は、クラスターの作成時に指定されたクラスター マニフェストで構成設定として指定されます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-279">The image store location is specified as a configuration setting in the cluster manifest that was provided when the cluster was created.</span></span></para>
          <para><span data-ttu-id="46eb3-280">クラスター マニフェストの検証がこの呼び出しのコンテキスト内で発生します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-280">Cluster manifest validation will occur within the context of this call.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-281"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-281">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-282">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-282">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
          <para><span data-ttu-id="46eb3-283">更新の修正プログラム ファイルへのパス。</span><span class="sxs-lookup"><span data-stu-id="46eb3-283">The path to the update patch file.</span></span></para>
        </param>
        <param name="clusterManifestFilePath">
          <para><span data-ttu-id="46eb3-284">クラスター マニフェストへのパス。</span><span class="sxs-lookup"><span data-stu-id="46eb3-284">The path to the cluster manifest.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-285">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-285">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-286">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-286">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-287">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-287">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-288">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-288">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-289">指定したタイムアウトとキャンセル トークンを使用して Service Fabric をプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-289">Provisions the Service Fabric by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-290">プロビジョニング済みの Service Fabric です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-290">The provisioned Service Fabric.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="46eb3-291">A <languageKeyword>null</languageKeyword>のいずれかの値が許可されて、<paramref name="patchFilePath" />パラメーターまたは<paramref name="clusterManifestFilePath" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="46eb3-291">A <languageKeyword>null</languageKeyword> value is permitted for either the <paramref name="patchFilePath" /> parameter or the <paramref name="clusterManifestFilePath" /> parameter.</span></span> <span data-ttu-id="46eb3-292">A <languageKeyword>null</languageKeyword>両方のパラメーター値を使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="46eb3-292">A <languageKeyword>null</languageKeyword> value cannot be used for both parameters.</span></span></para>
          <para><span data-ttu-id="46eb3-293">イメージ ストアの場所にこの修正プログラム ファイルおよびクラスター マニフェスト ファイルがアップロードされます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-293">This will upload the patch file and/or cluster manifest file to the image store location.</span></span> <span data-ttu-id="46eb3-294">イメージ ストアの場所は、クラスターの作成時に指定されたクラスター マニフェストで構成設定として指定されます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-294">The image store location is specified as a configuration setting in the cluster manifest that was provided when the cluster was created.</span></span></para>
          <para><span data-ttu-id="46eb3-295">クラスター マニフェストの検証がこの呼び出しのコンテキスト内で発生します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-295">Cluster manifest validation will occur within the context of this call.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-296"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-296">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-297">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-297">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
        <param name="partitionId"><span data-ttu-id="46eb3-298">パーティション id を回復するには</span><span class="sxs-lookup"><span data-stu-id="46eb3-298">The partition id to recover</span></span></param>
        <summary>
          <para><span data-ttu-id="46eb3-299">Service Fabric クラスターをすることが現在クォーラム損失にスタックしている特定のパーティションの復元を試行ことを示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-299">Indicates to the Service Fabric cluster that it should attempt to recover a specific partition which is currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-300">目的の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-300">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-301">この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-301">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="46eb3-302">この API を不適切に使用すると、データ損失が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-302">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-303">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-303">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-304">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-304">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-305">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-305">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
        <param name="partitionId"><span data-ttu-id="46eb3-306">パーティション id を回復するには</span><span class="sxs-lookup"><span data-stu-id="46eb3-306">The partition id to recover</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-307">返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-307">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-308">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-308">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-309">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-309">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-310">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-310">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-311">Service Fabric クラスターをすることが現在クォーラム損失にスタックしている特定のパーティションの復元を試行ことを示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-311">Indicates to the Service Fabric cluster that it should attempt to recover a specific partition which is currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-312">目的の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-312">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-313">この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-313">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="46eb3-314">この API を不適切に使用すると、データ損失が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-314">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-315">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-315">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-316">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-316">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-317">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-317">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-318">Service Fabric クラスターをすることが、(システム サービスを含む) がクォーラム損失に現在スタックをサービスの回復を試行ことを示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-318">Indicates to the Service Fabric cluster that it should attempt to recover any services (including system services) which are currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-319">目的の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-319">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-320">この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-320">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="46eb3-321">この API を不適切に使用すると、データ損失が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-321">Incorrect use of this API can cause potential data loss.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-322">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-322">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-323">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-323">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-324">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-324">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-325">返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-325">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-326">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-326">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-327">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-327">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-328">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-328">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-329">Service Fabric クラスターをすることが、(システム サービスを含む) がクォーラム損失に現在スタックをサービスの回復を試行ことを示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-329">Indicates to the Service Fabric cluster that it should attempt to recover any services (including system services) which are currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-330">目的の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-330">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-331">この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-331">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="46eb3-332">この API を不適切に使用すると、データ損失が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-332">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-333">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-333">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-334">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-334">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-335">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-335">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-336">回復するサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="46eb3-336">The name of the service to recover.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-337">Service Fabric クラスターをすることが、クォーラム損失に残っている現在、指定されたサービスの回復を試行ことを示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-337">Indicates to the Service Fabric cluster that it should attempt to recover the specified service which is currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-338">目的の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-338">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-339">この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-339">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="46eb3-340">この API を不適切に使用すると、データ損失が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-340">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-341">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-341">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-342">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-342">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-343">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-343">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-344">回復するサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="46eb3-344">The name of the service to recover.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-345">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-345">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-346">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-346">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-347">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-347">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-348">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-348">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-349">Service Fabric クラスターをすること、べきでは、指定したタイムアウトとキャンセル トークンを使用して、クォーラム損失で現在停止しているが、指定したサービスを回復することを示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-349">Indicates to the Service Fabric cluster that it should attempt to recover the specified service which is currently stuck in quorum loss by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-350">目的の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-350">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-351">この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-351">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="46eb3-352">この API を不適切に使用すると、データ損失が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-352">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-353">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-353">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-354">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-354">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-355">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-355">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-356">Service Fabric クラスターをクォーラム損失にスタックしている現在のシステム サービスを回復しようと、必要があることを示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-356">Indicates to the Service Fabric cluster that it should attempt to recover the system services which are currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-357">目的の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-357">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-358">この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-358">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="46eb3-359">この API を不適切に使用すると、データ損失が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-359">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-360">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-360">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-361">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-361">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-362">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-362">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-363">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-363">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-364">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-364">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-365">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-365">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-366">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-366">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-367">Service Fabric クラスターをクォーラム損失にスタックしている現在のシステム サービスを回復しようと、必要があることを示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-367">Indicates to the Service Fabric cluster that it should attempt to recover the system services which are currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-368">目的の受信確認を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-368">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-369">この操作は、停止しているレプリカを復旧できないことがわかっている場合にのみ実行してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-369">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="46eb3-370">この API を不適切に使用すると、データ損失が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-370">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-371">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-371">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-372">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-372">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-373">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-373">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-374">イメージ ストアでは、「imagestoreconnectionstring は、」、ターゲット クラスターのクラスター マニフェストで検出された値の設定に一致する必要がありますの接続文字列。</span><span class="sxs-lookup"><span data-stu-id="46eb3-374">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="46eb3-375">内部設置型クラスターは、値は、クラスター管理者が初期の展開時に選択されます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-375">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="46eb3-376">Azure リソース マネージャーによって作成 Azure クラスターは、この値は"fabric: ImageStore"</span><span class="sxs-lookup"><span data-stu-id="46eb3-376">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="46eb3-377">イメージ ストア接続文字列の値によって返されるクラスター マニフェストの内容を調べることでチェックできる<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-377">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="clusterManifestPathInImageStore">
          <para><span data-ttu-id="46eb3-378">時に指定されたイメージ ストア内のクラスター マニフェスト ファイルの相対パス<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-378">The relative path of cluster manifest file in the image store specified during <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />.</span></span></para>
        </param>
        <param name="codePackagePathInImageStore">
          <para><span data-ttu-id="46eb3-379">Service Fabric コード パッケージ中に指定されたイメージ ストア内の相対パス<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-379">The relative path of Service Fabric code package in the image store specified during <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-380">クラスター マニフェストのファイルや Service Fabric コード パッケージをイメージ ストアから削除します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-380">Deletes the cluster manifest file and/or Service Fabric code package from the image store.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="46eb3-381">ClusterManifestPathInImageStore または codePackagePathInImageStore のいずれかのパラメーターを指定できます<languageKeyword>null</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-381">Either clusterManifestPathInImageStore or codePackagePathInImageStore parameter can be <languageKeyword>null</languageKeyword>.</span></span> <span data-ttu-id="46eb3-382">ただし、これらの両方のできません<languageKeyword>null</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-382">However, both of them cannot be <languageKeyword>null</languageKeyword>.</span></span></para>
        </remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="46eb3-383">イメージ ストア上のファイルへのアクセス エラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="46eb3-383">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="46eb3-384"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-384"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="46eb3-385">要求がタイムアウトしましたが許可されている処理のため、システムによって。</span><span class="sxs-lookup"><span data-stu-id="46eb3-385">The request timed out but may have already been accepted for processing by the system.</span></span></para>
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
          <para><span data-ttu-id="46eb3-386">完全に失われたされているノードの名前。</span><span class="sxs-lookup"><span data-stu-id="46eb3-386">The name of the node which has been permanently lost.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-387">その Service Fabric は失われ回復不可能なとしてサービスまたはそのノードの状態を扱う必要があります、ノードの永続化されたデータは (たとえば、ディスクの障害、または再イメージ化など)、によって失われることを示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-387">Indicates that the persisted data of a node is lost (e.g., due to disk failure, or reimage, etc.), and that Service Fabric should treat any services or state on that node as lost and unrecoverable.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-388">操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-388">A task representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-389">ノードがダウンした後に Service Fabric はの追跡そのノードで永続化されたサービスのレプリカはそのノードの状態がいます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-389">After a node goes down, Service Fabric will keep track of replicas of persisted services on that node as they have state on that node.</span></span></para>
          <para>
                <span data-ttu-id="46eb3-390">管理者がノードで永続化された状態が完全に失われたことを認識する場合、 <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" /> ... メソッドを呼び出す必要がありますに Service Fabric を通知するノードの状態が削除 (またはの状態をノードが返されることはないことができます)。</span><span class="sxs-lookup"><span data-stu-id="46eb3-390">In cases where the administrator knows that the persisted state on a node has been permanently lost the <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" /> method should be called ... to notify Service Fabric that the state on the node is gone (or the node can never come back with the state it had).</span></span></para>
          <para>
                <span data-ttu-id="46eb3-391">これは、Service Fabric を回復するノード (とそのノード上の永続化されたレプリカ) の待機を停止を指示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-391">This instructs Service Fabric to stop waiting for that node (and any persisted replicas on that node) to recover.</span></span></para>
          <para>
                <span data-ttu-id="46eb3-392">注: そのノードの状態が失われたことが決定したが後にのみ、この API を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-392">NOTE: This API must be called only after it has been determined that the state on that node has been lost.</span></span> </para>
          <para>
                <span data-ttu-id="46eb3-393">この API を呼び出すし、ノードが付属戻るそのままの状態が未定義の動作</span><span class="sxs-lookup"><span data-stu-id="46eb3-393">If this API is called and then the node comes back with its state intact it is Undefined Behavior</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-394">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-394">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-395">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-395">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-396">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-396">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-397">完全に失われたされているノードの名前。</span><span class="sxs-lookup"><span data-stu-id="46eb3-397">The name of the node which has been permanently lost.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-398">返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-398">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-399">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-399">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-400">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-400">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-401">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-401">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-402">(これはダウン) 特定のノードが失われている実際には、その Service Fabric は失われ回復不可能なとしてサービスまたはそのノードの状態を扱う必要があることを示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-402">Indicates that a particular node (which is down) has actually been lost, and that Service Fabric should treat any services or state on that node as lost and unrecoverable.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-403">操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-403">A task representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="46eb3-404">ノードがダウンした後に Service Fabric はの追跡そのノードで永続化されたサービスのレプリカはそのノードの状態がいます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-404">After a node goes down, Service Fabric will keep track of replicas of persisted services on that node as they have state on that node.</span></span></para>
          <para>
                <span data-ttu-id="46eb3-405">管理者がノード (とその状態) を完全に失われたことを認識する場合、<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" />メソッドを呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-405">In cases where the administrator knows that a node (and its state) has been permanently lost the <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" /> method should be called.</span></span></para>
          <para>
                <span data-ttu-id="46eb3-406">これは、Service Fabric を回復するノード (とそのノード上の永続化されたレプリカ) の待機を停止を指示します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-406">This instructs Service Fabric to stop waiting for that node (and any persisted replicas on that node) to recover.</span></span></para>
          <para>
                <span data-ttu-id="46eb3-407">注: そのノードの状態が失われたことが決定したが後にのみ、この API を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="46eb3-407">NOTE: This API must be called only after it has been determined that the state on that node has been lost.</span></span> </para>
          <para>
                <span data-ttu-id="46eb3-408">この API を呼び出すし、ノードが付属戻るそのままの状態が未定義の動作</span><span class="sxs-lookup"><span data-stu-id="46eb3-408">If this API is called and then the node comes back with its state intact it is Undefined Behavior</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="46eb3-409">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-409">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="46eb3-410">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-410">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="46eb3-411">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="46eb3-411">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
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
          <para><span data-ttu-id="46eb3-412">パーティション Id を Guid として表されます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-412">The partition Id represented as a Guid</span></span> </para>
        </param>
        <summary>
          <para> 
            <span data-ttu-id="46eb3-413">特定のパーティションの負荷をリセットします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-413">Resets a given partition's load</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-414">この async メソッドに関連付けられているタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-414">The task associated with this async method.</span></span> </para>
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
          <para><span data-ttu-id="46eb3-415">パーティション Id を Guid として表されます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-415">The partition Id represented as a Guid</span></span> </para>
        </param>
        <param name="timeout">
          <para> <span data-ttu-id="46eb3-416">Async メソッドをメソッドがタイムアウトする順序で完了する必要がありますを時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="46eb3-416">The length of time within which the async method must complete in order for the method to not time out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-417">このメソッドのキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-417">A cancellation token for this method.</span></span> </para>
        </param>
        <summary>
          <para> 
            <span data-ttu-id="46eb3-418">特定のパーティションの負荷をリセットします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-418">Resets a given partition's load</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-419">この async メソッドに関連付けられているタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-419">The task associated with this async method.</span></span> </para>
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
          <para><span data-ttu-id="46eb3-420">Service Fabric アップグレード操作をロールバックします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-420">Rolls back the Service Fabric to upgrade the operation.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-421">Service Fabric アップグレード操作をロールバックします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-421">The rollback Service Fabric to upgrade the operation.</span></span></para>
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
          <para><span data-ttu-id="46eb3-422">Service Fabric は、タイムアウト例外を返す前に続行するには、この操作を許可する時間の最大量を定義する timespan です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-422">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a timeout exception.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-423">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-423">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-424">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-424">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-425">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-425">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-426">Service Fabric アップグレード操作をロールバックします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-426">Rolls back the Service Fabric to upgrade the operation.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-427">Service Fabric アップグレード操作をロールバックします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-427">The rollback Service Fabric to upgrade the operation.</span></span></para>
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
        <param name="state"><span data-ttu-id="46eb3-428">状態の入力</span><span class="sxs-lookup"><span data-stu-id="46eb3-428">state input</span></span></param>
        <summary>
          <para><span data-ttu-id="46eb3-429">文字列として Service Fabric アップグレード オーケストレーション サービスの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-429">Sets the Service Fabric Upgrade Orchestration Service state as a string.</span></span></para>
        </summary>
        <returns><span data-ttu-id="46eb3-430">タスク</span><span class="sxs-lookup"><span data-stu-id="46eb3-430">Task</span></span></returns>
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
        <param name="state"><span data-ttu-id="46eb3-431">状態の入力</span><span class="sxs-lookup"><span data-stu-id="46eb3-431">state input</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-432">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-432">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-433">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-433">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-434">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-434">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-435">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-435">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-436">指定したタイムアウトとキャンセル トークンを使用して、文字列として Service Fabric アップグレード オーケストレーション サービスの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-436">Sets the Service Fabric Upgrade Orchestration Service state as a string, by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-437">指定したタイムアウトとキャンセル トークンを使用して Service Fabric アップグレード オーケストレーション サービスの状態。</span><span class="sxs-lookup"><span data-stu-id="46eb3-437">The Service Fabric Upgrade Orchestration Service state, by using the specified timeout and cancellation token.</span></span></para>
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
          <para><span data-ttu-id="46eb3-438">ブール値が true の場合、レプリカが有効にする場合に報告します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-438">A boolean value, which if true causes reporting when a replica is unabled to be placed.</span></span> </para>
        </param>
        <summary>
          <para> 
            <span data-ttu-id="46eb3-439">クラスター Resource Balancer はレプリカを配置することがない場合に警告する正常性を報告するかどうかを切り替えます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-439">Toggles whether the Cluster Resource Balancer will report a health warning when it's unable to place a replica.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-440">この async メソッドに関連付けられているタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-440">The task associated with this async method.</span></span> </para>
        </returns>
        <remarks>
          <para><span data-ttu-id="46eb3-441">このメソッドが値 false を 2 回呼び出されると、出力された可能性がありますが、レポートをメモリからクリアします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-441">If this method is called twice with the value false, it clears from memory the reports that would potentially have been emitted.</span></span>
            <span data-ttu-id="46eb3-442">このメソッドは値 true で、レプリカを配置することがあるときに、クラスター Resource Balancer は、状態の警告が報告されます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-442">If this method is called with the value true, the Cluster Resource Balancer will report a health warning when it's unable to place a replica.</span></span>
            <span data-ttu-id="46eb3-443">このような正常性の警告は、監視対象のアップグレードの正常性チェックをブロックしている場合は、オフに切り替えを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-443">If such health warnings are blocking a monitored upgrade's health checks the toggle can be switched off.</span></span> </para>
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
          <para><span data-ttu-id="46eb3-444">ブール値が true の場合、レプリカが有効にする場合に報告します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-444">A boolean value, which if true causes reporting when a replica is unabled to be placed.</span></span> </para>
        </param>
        <param name="timeout">
          <para> <span data-ttu-id="46eb3-445">Async メソッドをメソッドがタイムアウトする順序で完了する必要がありますを時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="46eb3-445">The length of time within which the async method must complete in order for the method to not time out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-446">このメソッドのキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-446">A cancellation token for this method.</span></span> </para>
        </param>
        <summary>
          <para> 
            <span data-ttu-id="46eb3-447">クラスター Resource Balancer はレプリカを配置することがない場合に警告する正常性を報告するかどうかを切り替えます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-447">Toggles whether the Cluster Resource Balancer will report a health warning when it's unable to place a replica.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-448">この async メソッドに関連付けられているタスク。</span><span class="sxs-lookup"><span data-stu-id="46eb3-448">The task associated with this async method.</span></span> </para>
        </returns>
        <remarks>
          <para><span data-ttu-id="46eb3-449">このメソッドが値 false を 2 回呼び出されると、出力された可能性がありますが、レポートをメモリからクリアします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-449">If this method is called twice with the value false, it clears from memory the reports that would potentially have been emitted.</span></span>
            <span data-ttu-id="46eb3-450">このメソッドは値 true で、レプリカを配置することがあるときに、クラスター Resource Balancer は、状態の警告が報告されます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-450">If this method is called with the value true, the Cluster Resource Balancer will report a health warning when it's unable to place a replica.</span></span>
            <span data-ttu-id="46eb3-451">このような正常性の警告は、監視対象のアップグレードの正常性チェックをブロックしている場合、オフに切り替えを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-451">If such health warnings are blocking a monitored upgrade's health checks, the toggle can be switched off.</span></span> </para>
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
          <para><span data-ttu-id="46eb3-452">コードのバージョンのプロビジョニングを解除します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-452">The code version to unprovision.</span></span></para>
        </param>
        <param name="configVersion">
          <para><span data-ttu-id="46eb3-453">構成のバージョンのプロビジョニングを解除します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-453">The configuration version to unprovision.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-454">サービス ファブリックの準備を解除します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-454">Unprovisions the Service Fabric.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-455">プロビジョニングが解除された Service Fabric です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-455">The unprovisioned Service Fabric.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="46eb3-456">A <languageKeyword>null</languageKeyword>のいずれかの値が許可されて、<paramref name="codeVersion" />パラメーターまたは<paramref name="configVersion" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="46eb3-456">A <languageKeyword>null</languageKeyword> value is permitted for either the <paramref name="codeVersion" /> parameter or the <paramref name="configVersion" /> parameter.</span></span> <span data-ttu-id="46eb3-457">A <languageKeyword>null</languageKeyword>両方のパラメーター値を使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="46eb3-457">A <languageKeyword>null</languageKeyword> value cannot be used for both parameters.</span></span></para>
          <para><span data-ttu-id="46eb3-458">修正プログラム ファイルおよびクラスター マニフェスト ファイルのイメージ ストアの場所から削除されます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-458">This will delete the patch file and/or cluster manifest file from the image store location.</span></span> <span data-ttu-id="46eb3-459">イメージ ストアの場所は、クラスターの作成時に指定されたクラスター マニフェストで構成設定として指定されます。</span><span class="sxs-lookup"><span data-stu-id="46eb3-459">The image store location is specified as a configuration setting in the cluster manifest that was provided when the cluster was created.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-460"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-460">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-461">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-461">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
          <para><span data-ttu-id="46eb3-462">コードのバージョンのプロビジョニングを解除します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-462">The code version to unprovision.</span></span></para>
        </param>
        <param name="configVersion">
          <para><span data-ttu-id="46eb3-463">構成のバージョンのプロビジョニングを解除します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-463">The configuration version to unprovision.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-464">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-464">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-465">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-465">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-466">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-466">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-467">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-467">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-468">指定したタイムアウトとキャンセル トークンを使用してサービス ファブリックの準備を解除します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-468">Unprovisions the Service Fabric by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-469">プロビジョニングが解除された Service Fabric です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-469">The unprovisioned Service Fabric.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-470"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-470">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-471">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-471">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
          <para><span data-ttu-id="46eb3-472">パラメーターの説明を新しいアップグレードを適用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-472">Description of the new upgrade parameters to apply.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-473">現在のクラスターのアップグレードの動作を記述するアップグレード パラメーターを変更します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-473">Modifies the upgrade parameters that describe the behavior of the current cluster upgrade.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-474">現在のクラスターのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="46eb3-474">The current cluster upgrade.</span></span></para>
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
          <para> <span data-ttu-id="46eb3-475">適用する新しいパラメーターをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-475">The new upgrade parameters to apply.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-476">最長時間 Service Fabric をスローする前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-476">The maximum amount of time Service Fabric will allow this operation to continue before throwing a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-477">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-477">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-478">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-478">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-479">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-479">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-480">現在のクラスターのアップグレードの動作を記述するアップグレード パラメーターを変更します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-480">Modifies the upgrade parameters that describe the behavior of the current cluster upgrade.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-481">現在のクラスターのアップグレード。</span><span class="sxs-lookup"><span data-stu-id="46eb3-481">The current cluster upgrade.</span></span></para>
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
        <param name="description"><span data-ttu-id="46eb3-482">含まれています。 ClusterConfig HealthCheckRetryTimeout、HealthCheckWaitDuration、HealthCheckStableDuration、UpgradeDomainTimeout、UpgradeTimeout、MaxPercentUnhealthyApplications、MaxPercentUnhealthyNodes MaxPercentDeltaUnhealthyNodes、MaxPercentUpgradeDomainDeltaUnhealthyNodes</span><span class="sxs-lookup"><span data-stu-id="46eb3-482">Contains: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span></span>
            </param>
        <summary>
            <span data-ttu-id="46eb3-483">クラスターの構成ファイルを使用してアップグレードを開始します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-483">Initiate an Upgrade using a cluster configuration file.</span></span>
            </summary>
        <returns><span data-ttu-id="46eb3-484">タスク</span><span class="sxs-lookup"><span data-stu-id="46eb3-484">Task</span></span></returns>
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
        <param name="description"><span data-ttu-id="46eb3-485">含まれています: ClusterConfigPath HealthCheckRetryTimeout、HealthCheckWaitDuration、HealthCheckStableDuration、UpgradeDomainTimeout、UpgradeTimeout、MaxPercentUnhealthyApplications、MaxPercentUnhealthyNodes MaxPercentDeltaUnhealthyNodes、MaxPercentUpgradeDomainDeltaUnhealthyNodes</span><span class="sxs-lookup"><span data-stu-id="46eb3-485">Contains: ClusterConfigPath, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span></span></param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-486">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-486">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-487">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-487">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-488">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-488">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="46eb3-489">クラスターの構成ファイルを使用してアップグレードを開始します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-489">Initiate an Upgrade using a cluster configuration file.</span></span>
            </summary>
        <returns><span data-ttu-id="46eb3-490">タスク</span><span class="sxs-lookup"><span data-stu-id="46eb3-490">Task</span></span></returns>
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
        <param name="description"><span data-ttu-id="46eb3-491">含まれています。 ClusterConfig HealthCheckRetryTimeout、HealthCheckWaitDuration、HealthCheckStableDuration、UpgradeDomainTimeout、UpgradeTimeout、MaxPercentUnhealthyApplications、MaxPercentUnhealthyNodes MaxPercentDeltaUnhealthyNodes、MaxPercentUpgradeDomainDeltaUnhealthyNodes</span><span class="sxs-lookup"><span data-stu-id="46eb3-491">Contains: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-492">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-492">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="46eb3-493">クラスターの構成ファイルを使用してアップグレードを開始します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-493">Initiate an Upgrade using a cluster configuration file.</span></span>
            </summary>
        <returns><span data-ttu-id="46eb3-494">タスク</span><span class="sxs-lookup"><span data-stu-id="46eb3-494">Task</span></span></returns>
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
        <param name="description"><span data-ttu-id="46eb3-495">含まれています。 ClusterConfig HealthCheckRetryTimeout、HealthCheckWaitDuration、HealthCheckStableDuration、UpgradeDomainTimeout、UpgradeTimeout、MaxPercentUnhealthyApplications、MaxPercentUnhealthyNodes MaxPercentDeltaUnhealthyNodes、MaxPercentUpgradeDomainDeltaUnhealthyNodes</span><span class="sxs-lookup"><span data-stu-id="46eb3-495">Contains: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-496">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-496">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-497">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-497">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-498">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-498">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-499">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-499">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="46eb3-500">クラスターの構成ファイルを使用してアップグレードを開始します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-500">Initiate an Upgrade using a cluster configuration file.</span></span>
            </summary>
        <returns><span data-ttu-id="46eb3-501">タスク</span><span class="sxs-lookup"><span data-stu-id="46eb3-501">Task</span></span></returns>
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
          <para><span data-ttu-id="46eb3-502">アップグレードの説明です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-502">The description of the upgrade.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-503">Service Fabric をアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-503">Upgrades the Service Fabric.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-504">アップグレードされた Service Fabric です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-504">The upgraded Service Fabric.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-505"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-505">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-506">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-506">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
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
          <para><span data-ttu-id="46eb3-507">アップグレードの説明です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-507">The description of the upgrade.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="46eb3-508">最長時間を定義する timespan Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-508">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="46eb3-509">操作が観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46eb3-509">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="46eb3-510">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="46eb3-510">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="46eb3-511">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46eb3-511">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="46eb3-512">指定したタイムアウトとキャンセル トークンを使用して Service Fabric をアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-512">Upgrades the Service Fabric by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="46eb3-513">アップグレードされた Service Fabric です。</span><span class="sxs-lookup"><span data-stu-id="46eb3-513">The upgraded Service Fabric.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="46eb3-514"><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。</span><span class="sxs-lookup"><span data-stu-id="46eb3-514">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="46eb3-515">破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="46eb3-515">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>