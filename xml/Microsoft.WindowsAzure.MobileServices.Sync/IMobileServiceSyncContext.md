<Type Name="IMobileServiceSyncContext" FullName="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext">
  <TypeSignature Language="C#" Value="public interface IMobileServiceSyncContext" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceSyncContext" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceSyncContext" />
  <TypeSignature Language="F#" Value="type IMobileServiceSyncContext = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="83b7d-101">リモート データベースとローカル データベースを同期する方法を提供します。</span><span class="sxs-lookup"><span data-stu-id="83b7d-101">Provides a way to synchronize local database with remote database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Handler">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler Handler { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler Handler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Handler" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Handler As IMobileServiceSyncHandler" />
      <MemberSignature Language="F#" Value="member this.Handler : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Handler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83b7d-102"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="83b7d-102">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InitializeAsync (Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InitializeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.InitializeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore,Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function InitializeAsync (store As IMobileServiceLocalStore, handler As IMobileServiceSyncHandler) As Task" />
      <MemberSignature Language="F#" Value="abstract member InitializeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore * Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncContext.InitializeAsync (store, handler)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="store" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
        <Parameter Name="handler" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" />
      </Parameters>
      <Docs>
        <param name="store"><span data-ttu-id="83b7d-103"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="83b7d-103">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />.</span></span></param>
        <param name="handler"><span data-ttu-id="83b7d-104"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="83b7d-104">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /></span></span></param>
        <summary>
            <span data-ttu-id="83b7d-105">同期コンテキストを初期化します。</span><span class="sxs-lookup"><span data-stu-id="83b7d-105">Initializes the sync context.</span></span>
            </summary>
        <returns><span data-ttu-id="83b7d-106">完了するタスクを同期コンテキストが初期化されたときにします。</span><span class="sxs-lookup"><span data-stu-id="83b7d-106">A task that completes when sync context has initialized.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InitializeAsync (Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler, Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions trackingOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InitializeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler, valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions trackingOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.InitializeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore,Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler,Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function InitializeAsync (store As IMobileServiceLocalStore, handler As IMobileServiceSyncHandler, trackingOptions As StoreTrackingOptions) As Task" />
      <MemberSignature Language="F#" Value="abstract member InitializeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore * Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler * Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncContext.InitializeAsync (store, handler, trackingOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="store" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
        <Parameter Name="handler" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" />
        <Parameter Name="trackingOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions" />
      </Parameters>
      <Docs>
        <param name="store"><span data-ttu-id="83b7d-107"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="83b7d-107">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />.</span></span></param>
        <param name="handler"><span data-ttu-id="83b7d-108"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="83b7d-108">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /></span></span></param>
        <param name="trackingOptions"><span data-ttu-id="83b7d-109">A<see cref="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.StoreTrackingOptions" />値ストア操作を追跡する方法を示す、どのストア イベントが発生する影響を与えることです。</span><span class="sxs-lookup"><span data-stu-id="83b7d-109">A <see cref="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.StoreTrackingOptions" /> value indicating how store operations will be tracked, impacting which store events are raised.</span></span></param>
        <summary>
            <span data-ttu-id="83b7d-110">同期コンテキストを初期化します。</span><span class="sxs-lookup"><span data-stu-id="83b7d-110">Initializes the sync context.</span></span>
            </summary>
        <returns><span data-ttu-id="83b7d-111">完了するタスクを同期コンテキストが初期化されたときにします。</span><span class="sxs-lookup"><span data-stu-id="83b7d-111">A task that completes when sync context has initialized.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsInitialized">
      <MemberSignature Language="C#" Value="public bool IsInitialized { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsInitialized" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.IsInitialized" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsInitialized As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsInitialized : bool" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.IsInitialized" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83b7d-112">同期コンテキストが初期化されているかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="83b7d-112">Indicates whether sync context has been initialized or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingOperations">
      <MemberSignature Language="C#" Value="public long PendingOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PendingOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.PendingOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PendingOperations As Long" />
      <MemberSignature Language="F#" Value="member this.PendingOperations : int64" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.PendingOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83b7d-113">保留中のリモート テーブルにまだはプッシュされません操作の数を返します。</span><span class="sxs-lookup"><span data-stu-id="83b7d-113">Returns the number of pending operations that are not yet pushed to remote table.</span></span>
            </summary>
        <value><span data-ttu-id="83b7d-114">保留中のリモート テーブルに対する操作の数を返します。</span><span class="sxs-lookup"><span data-stu-id="83b7d-114">Returns the number of pending operations against the remote table.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PushAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PushAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PushAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.PushAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PushAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncContext.PushAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="83b7d-115"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="83b7d-115">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="83b7d-116">リモート テーブルまで保留中のすべての操作をプッシュします。</span><span class="sxs-lookup"><span data-stu-id="83b7d-116">Pushes all pending operations up to the remote table.</span></span>
            </summary>
        <returns><span data-ttu-id="83b7d-117">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="83b7d-117">A task that completes when pull operation has finished.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Store">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore Store { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore Store" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Store" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Store As IMobileServiceLocalStore" />
      <MemberSignature Language="F#" Value="member this.Store : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Store" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83b7d-118"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="83b7d-118">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreTrackingOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions StoreTrackingOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions StoreTrackingOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.StoreTrackingOptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreTrackingOptions As StoreTrackingOptions" />
      <MemberSignature Language="F#" Value="member this.StoreTrackingOptions : Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.StoreTrackingOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83b7d-119">ストアの追跡オプションが現在有効になっていることを示すフラグです。</span><span class="sxs-lookup"><span data-stu-id="83b7d-119">A flag indicating which store tracking options are currently enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>