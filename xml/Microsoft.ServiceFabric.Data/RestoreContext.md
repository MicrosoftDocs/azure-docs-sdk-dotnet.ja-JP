<Type Name="RestoreContext" FullName="Microsoft.ServiceFabric.Data.RestoreContext">
  <TypeSignature Language="C#" Value="public struct RestoreContext" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit RestoreContext extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.RestoreContext" />
  <TypeSignature Language="VB.NET" Value="Public Structure RestoreContext" />
  <TypeSignature Language="F#" Value="type RestoreContext = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <span data-ttu-id="6ad51-101"><cref name="RestoreContext" />含まれています、<cref name="RestoreContext.RestoreAsync(RestoreDescription)" />を使用して、レプリカの状態をバックアップから復元をことができます。</span><span class="sxs-lookup"><span data-stu-id="6ad51-101"><cref name="RestoreContext" /> contains the <cref name="RestoreContext.RestoreAsync(RestoreDescription)" /> that can be used to restore the state of the replica from a backup.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreContext (Microsoft.ServiceFabric.Data.IStateProviderReplica stateProviderReplica);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.IStateProviderReplica stateProviderReplica) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.#ctor(Microsoft.ServiceFabric.Data.IStateProviderReplica)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (stateProviderReplica As IStateProviderReplica)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreContext : Microsoft.ServiceFabric.Data.IStateProviderReplica -&gt; Microsoft.ServiceFabric.Data.RestoreContext" Usage="new Microsoft.ServiceFabric.Data.RestoreContext stateProviderReplica" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stateProviderReplica" Type="Microsoft.ServiceFabric.Data.IStateProviderReplica" />
      </Parameters>
      <Docs>
        <param name="stateProviderReplica">
            <span data-ttu-id="6ad51-102"><see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" />信頼性の高い状態プロバイダーの複製を表すです。</span><span class="sxs-lookup"><span data-stu-id="6ad51-102">An <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" /> representing a reliable state provider replica.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6ad51-103"><cref name="RestoreContext" /> 構造体の新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-103">Initializes a new instance of the <cref name="RestoreContext" /> structure.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(valuetype Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.RestoreAsync(Microsoft.ServiceFabric.Data.RestoreDescription)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : Microsoft.ServiceFabric.Data.RestoreDescription -&gt; System.Threading.Tasks.Task" Usage="restoreContext.RestoreAsync restoreDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreDescription" Type="Microsoft.ServiceFabric.Data.RestoreDescription" />
      </Parameters>
      <Docs>
        <param name="restoreDescription"><span data-ttu-id="6ad51-104">復元要求の説明です。</span><span class="sxs-lookup"><span data-stu-id="6ad51-104">Description for the restore request.</span></span></param>
        <summary>
            <span data-ttu-id="6ad51-105">により記述されたバックアップを復元<see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="6ad51-105">Restores a backup described by <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6ad51-106">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6ad51-106">Task that represents the asynchronous restore operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="6ad51-107">この API は、OnDataLossAsync メソッドから呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="6ad51-107">This API must be called from OnDataLossAsync method.</span></span> <span data-ttu-id="6ad51-108">によってシリアル化 API の 1 つだけでは、時間の特定の時点のレプリカあたりの転送を指定できます。</span><span class="sxs-lookup"><span data-stu-id="6ad51-108">Only one RestoreAsync API can be inflight per replica at any given point of time.</span></span>
            
            <span data-ttu-id="6ad51-109">この API によってスローされた例外が基になる状態プロバイダーのに応じてが異なることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="6ad51-109">Note that exceptions thrown by this API differ depending on of underlying state provider.</span></span> <span data-ttu-id="6ad51-110">この API は、信頼性の高いサービスや Reliable Actors サービス ファブリックにより提供される既定の状態プロバイダーにのみ適用されます用のドキュメントに記載されて現在の例外。</span><span class="sxs-lookup"><span data-stu-id="6ad51-110">The exceptions that are currently documented for this API applies only to out-of-box state providers provided by Service Fabric for Reliable Services and Reliable Actors.</span></span>
            <span data-ttu-id="6ad51-111"><para>次の例外は、信頼性の高いサービスで呼び出されたときに、この API によってスローされた: <list type="bullet"> <item> <description> <see cref="T:System.Fabric.FabricMissingFullBackupException" /> </description> </item> <item> <description> <see cref="T:System.ArgumentException" /> </description> </item> </list></para> <para> KvsActorStateProvider にアクター サービスで、状態プロバイダー (Reliable Actors に対する既定の状態プロバイダーは、) として呼び出されたときに、この API によって次の例外がスローされます。<list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></span><span class="sxs-lookup"><span data-stu-id="6ad51-111"><para> Following exceptions are thrown by this API when invoked in Reliable Service: <list type="bullet"><item><description><see cref="T:System.Fabric.FabricMissingFullBackupException" /></description></item><item><description><see cref="T:System.ArgumentException" /></description></item></list></para><para> Following exceptions are thrown by this API when invoked in Actor Service with KvsActorStateProvider as its state provider (which is the default state provider for Reliable Actors): <list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></span></span></remarks>
        <exception cref="T:System.Fabric.FabricMissingFullBackupException">
            <span data-ttu-id="6ad51-112">入力のバックアップ フォルダーに完全バックアップが含まれていないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-112">Indicates that the input backup folder does not contain a full backup.</span></span>
            <span data-ttu-id="6ad51-113">復元するバックアップ フォルダーの 1 つの完全バックアップと増分バックアップの任意の数でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="6ad51-113">For a backup folder to be restorable, it must contain exactly one full backup and any number of incremental backups.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="6ad51-114">引数のいずれかが無効であることを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-114">Indicates that one of the arguments is not valid.</span></span> <span data-ttu-id="6ad51-115">たとえば、RestorePolicy が安全な場所が入力のバックアップ フォルダーに設定されている場合は、信頼性の高いサービスを復元する含まれている場合、状態を現在のレプリカで維持よりも古い状態のバージョン。</span><span class="sxs-lookup"><span data-stu-id="6ad51-115">For example, when restoring a Reliable Service if RestorePolicy is set to Safe, but the input backup folder contains a version of the state that is older than the state maintained in the current replica.</span></span>
            
            <span data-ttu-id="6ad51-116">指定した場合に、この例外をスローするアクター サービスを復元するときに<see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />が空です。</span><span class="sxs-lookup"><span data-stu-id="6ad51-116">When restoring an Actor Service this exception is thrown if specified <see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" /> is empty.</span></span>
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
            <span data-ttu-id="6ad51-117">指定された復元ディレクトリが存在しないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-117">Indicates that the supplied restore directory does not exist.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
            <span data-ttu-id="6ad51-118">レプリカを終了することを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-118">Indicates that the replica is closing.</span></span>
            </exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6ad51-119">現在の復元操作が無効であることを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-119">Indicates that current restore operation is not valid.</span></span> <span data-ttu-id="6ad51-120">たとえば、<see cref="T:System.Fabric.ServicePartitionKind" />からバックアップが作成されたパーティションの現在のパーティションを復元中のものとは異なるがします。</span><span class="sxs-lookup"><span data-stu-id="6ad51-120">For example, the <see cref="T:System.Fabric.ServicePartitionKind" /> of the partition from where backup was taken is different than that of current partition being restored.</span></span>
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            <span data-ttu-id="6ad51-121">指定された復元ディレクトリ下にある予想されるバックアップ ファイルが見つからないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-121">Indicates the expected backup files under the supplied restore directory is not found.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="6ad51-122">復元操作には、予期しないエラーが発生しました。 または、バックアップ ディレクトリ内のファイル復元が無効のいずれかを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-122">Indicates either the restore operation encountered an unexpected error or the backup files in restore directory are not valid.</span></span>
            <span data-ttu-id="6ad51-123"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティが発生したエラーの種類を示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-123">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property indicates the type of error that occurred.</span></span>
            <span data-ttu-id="6ad51-124"><list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description>復元ディレクトリで指定されたバックアップ ファイルが不足しているファイルがいずれかまたはことを示します余分な予期しないファイル。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description>メタデータ ファイル (restore.dat) 復元ディレクトリ内に存在するかが破損しているか、無効な情報が含まれています。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description>示します、バックアップのチェーン (つまり 1 つの完全バックアップと 0 個以上連続する差分バックアップ後に実行された) 指定されたディレクトリが壊れている、復元中です。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description>示します、バックアップのチェーン (つまり 1 つの完全バックアップと 0 個以上連続する差分バックアップ後に実行された) 指定したディレクトリには復元には重複しているバックアップが含まれています。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description>場合<see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" />の一部として指定<see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />復元に指定されたバックアップは、サービス内に現存のよりも古いデータであることを示します。</description></item></list></span><span class="sxs-lookup"><span data-stu-id="6ad51-124"><list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description> Indicates that the backup files supplied in the restore directory are either missing files or have extra unexpected files. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description> Indicates that metadata files (restore.dat) present in restore directory is either corrupt or contains invalid information. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description> Indicates that the backup chain (i.e. one full backup and zero or more contiguous incremental backups that were taken after it) supplied in the restore directory is broken. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description> Indicates that the backup chain (i.e. one full backup and zero or more contiguous incremental backups that were taken after it) supplied in the restore directory contains duplicate backups. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description> If <see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" /> is specified as part of <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />, it indicates that the backup provided for restore has older data than currently present in service. </description></item></list></span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(valuetype Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.RestoreAsync(Microsoft.ServiceFabric.Data.RestoreDescription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : Microsoft.ServiceFabric.Data.RestoreDescription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="restoreContext.RestoreAsync (restoreDescription, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreDescription" Type="Microsoft.ServiceFabric.Data.RestoreDescription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="restoreDescription"><span data-ttu-id="6ad51-125">復元要求の説明です。</span><span class="sxs-lookup"><span data-stu-id="6ad51-125">Description for the restore request.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6ad51-126">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="6ad51-126">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="6ad51-127">により記述されたバックアップを復元<see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="6ad51-127">Restore a backup described by <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6ad51-128">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="6ad51-128">Task that represents the asynchronous restore operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="6ad51-129">この API は、OnDataLossAsync メソッドから呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="6ad51-129">This API must be called from OnDataLossAsync method.</span></span> <span data-ttu-id="6ad51-130">によってシリアル化 API の 1 つだけでは、時間の特定の時点のレプリカあたりの転送を指定できます。</span><span class="sxs-lookup"><span data-stu-id="6ad51-130">Only one RestoreAsync API can be inflight per replica at any given point of time.</span></span>
            
            <span data-ttu-id="6ad51-131">この API によってスローされた例外が基になる状態プロバイダーのに応じてが異なることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="6ad51-131">Note that exceptions thrown by this API differ depending on of underlying state provider.</span></span> <span data-ttu-id="6ad51-132">この API は、信頼性の高いサービスや Reliable Actors サービス ファブリックにより提供される既定の状態プロバイダーにのみ適用されます用のドキュメントに記載されて現在の例外。</span><span class="sxs-lookup"><span data-stu-id="6ad51-132">The exceptions that are currently documented for this API applies only to out-of-box state providers provided by Service Fabric for Reliable Services and Reliable Actors.</span></span>
            <span data-ttu-id="6ad51-133"><para>次の例外は、信頼性の高いサービスで呼び出されたときに、この API によってスローされた: <list type="bullet"> <item> <description> <see cref="T:System.Fabric.FabricMissingFullBackupException" /> </description> </item> <item> <description> <see cref="T:System.ArgumentException" /> </description> </item> </list></para> <para> KvsActorStateProvider にアクター サービスで、状態プロバイダー (Reliable Actors に対する既定の状態プロバイダーは、) として呼び出されたときに、この API によって次の例外がスローされます。<list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></span><span class="sxs-lookup"><span data-stu-id="6ad51-133"><para> Following exceptions are thrown by this API when invoked in Reliable Service: <list type="bullet"><item><description><see cref="T:System.Fabric.FabricMissingFullBackupException" /></description></item><item><description><see cref="T:System.ArgumentException" /></description></item></list></para><para> Following exceptions are thrown by this API when invoked in Actor Service with KvsActorStateProvider as its state provider (which is the default state provider for Reliable Actors): <list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></span></span></remarks>
        <exception cref="T:System.Fabric.FabricMissingFullBackupException">
            <span data-ttu-id="6ad51-134">入力のバックアップ フォルダーに完全バックアップが含まれていないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-134">Indicates that the input backup folder does not contain a full backup.</span></span>
            <span data-ttu-id="6ad51-135">復元するバックアップ フォルダーの 1 つの完全バックアップと増分バックアップの任意の数でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="6ad51-135">For a backup folder to be restorable, it must contain exactly one full backup and any number of incremental backups.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="6ad51-136">引数のいずれかが無効であることを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-136">Indicates that one of the arguments is not valid.</span></span> <span data-ttu-id="6ad51-137">たとえば、RestorePolicy が安全な場所が入力のバックアップ フォルダーに設定されている場合は、信頼性の高いサービスを復元する含まれている場合、状態を現在のレプリカで維持よりも古い状態のバージョン。</span><span class="sxs-lookup"><span data-stu-id="6ad51-137">For example, when restoring a Reliable Service if RestorePolicy is set to Safe, but the input backup folder contains a version of the state that is older than the state maintained in the current replica.</span></span>
            
            <span data-ttu-id="6ad51-138">指定した場合に、この例外をスローするアクター サービスを復元するときに<see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" />が空です。</span><span class="sxs-lookup"><span data-stu-id="6ad51-138">When restoring an Actor Service this exception is thrown if specified <see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" /> is empty.</span></span>
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
            <span data-ttu-id="6ad51-139">指定された復元ディレクトリが存在しないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-139">Indicates that the supplied restore directory does not exist.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
            <span data-ttu-id="6ad51-140">レプリカを終了することを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-140">Indicates that the replica is closing.</span></span>
            </exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="6ad51-141">現在の復元操作が無効であることを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-141">Indicates that current restore operation is not valid.</span></span> <span data-ttu-id="6ad51-142">たとえば、<see cref="T:System.Fabric.ServicePartitionKind" />からバックアップが作成されたパーティションの現在のパーティションを復元中のものとは異なるがします。</span><span class="sxs-lookup"><span data-stu-id="6ad51-142">For example, the <see cref="T:System.Fabric.ServicePartitionKind" /> of the partition from where backup was taken is different than that of current partition being restored.</span></span>
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            <span data-ttu-id="6ad51-143">指定された復元ディレクトリ下にある予想されるバックアップ ファイルが見つからないことを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-143">Indicates the expected backup files under the supplied restore directory is not found.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="6ad51-144">復元操作には、予期しないエラーが発生しました。 または、バックアップ ディレクトリ内のファイル復元が無効のいずれかを示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-144">Indicates either the restore operation encountered an unexpected error or the backup files in restore directory are not valid.</span></span>
            <span data-ttu-id="6ad51-145"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティが発生したエラーの種類を示します。</span><span class="sxs-lookup"><span data-stu-id="6ad51-145">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property indicates the type of error that occurred.</span></span>
            <span data-ttu-id="6ad51-146"><list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description>復元ディレクトリで指定されたバックアップ ファイルが不足しているファイルがいずれかまたはことを示します余分な予期しないファイル。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description>メタデータ ファイル (restore.dat) 復元ディレクトリ内に存在するかが破損しているか、無効な情報が含まれています。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description>示します、バックアップのチェーン (つまり 1 つの完全バックアップと 0 個以上連続する差分バックアップ後に実行された) 指定されたディレクトリが壊れている、復元中です。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description>示します、バックアップのチェーン (つまり 1 つの完全バックアップと 0 個以上連続する差分バックアップ後に実行された) 指定したディレクトリには復元には重複しているバックアップが含まれています。</description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description>場合<see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" />の一部として指定<see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />復元に指定されたバックアップは、サービス内に現存のよりも古いデータであることを示します。</description></item></list></span><span class="sxs-lookup"><span data-stu-id="6ad51-146"><list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description> Indicates that the backup files supplied in the restore directory are either missing files or have extra unexpected files. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description> Indicates that metadata files (restore.dat) present in restore directory is either corrupt or contains invalid information. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description> Indicates that the backup chain (i.e. one full backup and zero or more contiguous incremental backups that were taken after it) supplied in the restore directory is broken. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description> Indicates that the backup chain (i.e. one full backup and zero or more contiguous incremental backups that were taken after it) supplied in the restore directory contains duplicate backups. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description> If <see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" /> is specified as part of <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />, it indicates that the backup provided for restore has older data than currently present in service. </description></item></list></span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>