<Type Name="ReliableStateManager" FullName="Microsoft.ServiceFabric.Data.ReliableStateManager">
  <TypeSignature Language="C#" Value="public class ReliableStateManager : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;, Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi ReliableStateManager extends System.Object implements class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt;, class Microsoft.ServiceFabric.Data.IReliableStateManager, class Microsoft.ServiceFabric.Data.IReliableStateManagerReplica, class Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2, class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ReliableStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Class ReliableStateManager&#xA;Implements IAsyncEnumerable(Of IReliableState), IReliableStateManagerReplica2" />
  <TypeSignature Language="F#" Value="type ReliableStateManager = class&#xA;    interface IReliableStateManagerReplica2&#xA;    interface IReliableStateManagerReplica&#xA;    interface IStateProviderReplica&#xA;    interface IReliableStateManager&#xA;    interface IAsyncEnumerable&lt;IReliableState&gt;&#xA;    interface IStateProviderReplica2" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="eb75b-101">ReliableStateManager クラスが管理を担当<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />サービス レプリカにします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-101">The ReliableStateManager class is responsible for managing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> for a service replica.</span></span>
            <span data-ttu-id="eb75b-102">サービス内の各レプリカで独自<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と<see cref="T:Microsoft.ServiceFabric.Data.ReliableStateManager" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-102">Each replica in a service has its own <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> and <see cref="T:Microsoft.ServiceFabric.Data.ReliableStateManager" />.</span></span> 
            <span data-ttu-id="eb75b-103"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />含めることができます<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />、 <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />、または any<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />型です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-103"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> can include <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />, <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />, or any <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" /> types.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReliableStateManager (System.Fabric.StatefulServiceContext serviceContext, Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration configuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext serviceContext, class Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.#ctor(System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serviceContext As StatefulServiceContext, Optional configuration As ReliableStateManagerConfiguration = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.ReliableStateManager : System.Fabric.StatefulServiceContext * Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration -&gt; Microsoft.ServiceFabric.Data.ReliableStateManager" Usage="new Microsoft.ServiceFabric.Data.ReliableStateManager (serviceContext, configuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
        <Parameter Name="configuration" Type="Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration" />
      </Parameters>
      <Docs>
        <param name="serviceContext"><span data-ttu-id="eb75b-104">A<see cref="T:System.Fabric.StatefulServiceContext" />サービス コンテキストをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-104">A <see cref="T:System.Fabric.StatefulServiceContext" /> that describes the service context.</span></span></param>
        <param name="configuration"><span data-ttu-id="eb75b-105">構成パラメーター。</span><span class="sxs-lookup"><span data-stu-id="eb75b-105">Configuration parameters.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-106">新しい ReliableStateManager を作成します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-106">Create a new ReliableStateManager.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BackupAsync(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function BackupAsync (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))) As Task" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.BackupAsync : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.BackupAsync backupCallback" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupCallback"><span data-ttu-id="eb75b-107">バックアップ フォルダーがローカルで作成された、ノード外に移動する準備ができているときに呼び出されるコールバック。</span><span class="sxs-lookup"><span data-stu-id="eb75b-107">Callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-108">これによって管理されるすべての信頼性の高い状態の完全バックアップを実行<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-108">Performs a full backup of all reliable state managed by this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-109">非同期のバックアップ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-109">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-110">完全バックアップは、1 時間のタイムアウトを設定して実行されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-110">A FULL backup will be performed with a one-hour timeout.</span></span>
            <span data-ttu-id="eb75b-111">BackupCallback によって返されるブール値では、サービスが正常に外部の場所に、バックアップ フォルダーを移動するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-111">Boolean returned by the backupCallback indicate whether the service was able to successfully move the backup folder to an external location.</span></span>
            <span data-ttu-id="eb75b-112">False が返される場合は BackupAsync backupCallback false が返されたことを示す関連するメッセージに InvalidOperationException がスローされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-112">If false is returned, BackupAsync throws InvalidOperationException with the relevant message indicating backupCallback returned false.</span></span>
            <span data-ttu-id="eb75b-113">また、バックアップはマークされます失敗とします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-113">Also, backup will be marked as unsuccessful.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupOption option, TimeSpan timeout, System.Threading.CancellationToken cancellationToken, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Microsoft.ServiceFabric.Data.BackupOption * TimeSpan * System.Threading.CancellationToken * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.BackupAsync : Microsoft.ServiceFabric.Data.BackupOption * TimeSpan * System.Threading.CancellationToken * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.BackupAsync (option, timeout, cancellationToken, backupCallback)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="option"><span data-ttu-id="eb75b-114">実行するバックアップの種類。</span><span class="sxs-lookup"><span data-stu-id="eb75b-114">The type of backup to perform.</span></span></param>
        <param name="timeout"><span data-ttu-id="eb75b-115">この操作のタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="eb75b-115">The timeout for this operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="eb75b-116">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="eb75b-116">The token to monitor for cancellation requests.</span></span></param>
        <param name="backupCallback"><span data-ttu-id="eb75b-117">バックアップ フォルダーがローカルで作成された、ノード外に移動する準備ができているときに呼び出されるコールバック。</span><span class="sxs-lookup"><span data-stu-id="eb75b-117">Callback to be called when the backup folder has been created locally and is ready to be moved out of the node.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-118">これによって管理されるすべての信頼性の高い状態のバックアップを実行<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-118">Performs a backup of all reliable state managed by this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-119">非同期のバックアップ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-119">Task that represents the asynchronous backup operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-120">BackupCallback によって返されるブール値では、サービスが正常に外部の場所に、バックアップ フォルダーを移動するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-120">Boolean returned by the backupCallback indicate whether the service was able to successfully move the backup folder to an external location.</span></span>
            <span data-ttu-id="eb75b-121">False が返される場合は BackupAsync backupCallback false が返されたことを示す関連するメッセージに InvalidOperationException がスローされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-121">If false is returned, BackupAsync throws InvalidOperationException with the relevant message indicating backupCallback returned false.</span></span>
            <span data-ttu-id="eb75b-122">また、バックアップはマークされます失敗とします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-122">Also, backup will be marked as unsuccessful.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsyncEnumerator">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt; GetAsyncEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.IAsyncEnumerator`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt; GetAsyncEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.GetAsyncEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAsyncEnumerator () As IAsyncEnumerator(Of IReliableState)" />
      <MemberSignature Language="F#" Value="abstract member GetAsyncEnumerator : unit -&gt; Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;&#xA;override this.GetAsyncEnumerator : unit -&gt; Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;" Usage="reliableStateManager.GetAsyncEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="eb75b-123">コレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-123">Returns an enumerator that iterates through the collection.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb75b-124">コレクションを反復処理するために使用できる <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="eb75b-124">An <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" /> object that can be used to iterate through the collection.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <filterpriority><span data-ttu-id="eb75b-125">1</span><span class="sxs-lookup"><span data-stu-id="eb75b-125">1</span></span></filterpriority>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction">
      <MemberSignature Language="C#" Value="Microsoft.ServiceFabric.Data.ITransaction IReliableStateManager.CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.ITransaction Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Function CreateTransaction () As ITransaction Implements IReliableStateManager.CreateTransaction" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.ITransaction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="eb75b-126">作成し、原子的に実行する操作をグループ化に使用できる新しいトランザクションを開始します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-126">Create and start a new transaction that can be used to group operations to be performed atomically.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-127">新しいトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-127">A new transaction.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-128">操作は、トランザクションに渡すことによって追加されます、<see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />信頼性の高い状態メソッド内のオブジェクトします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-128">Operations are added to the transaction by passing the <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" /> object in to reliable state methods.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As String) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="eb75b-129">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-129">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="eb75b-130"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="eb75b-130"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="eb75b-131"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-131">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="eb75b-132">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="eb75b-132">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb75b-133">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-133">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-134">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-134">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="eb75b-135">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-135">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-136">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-136">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-137">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-137">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-138"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-138"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-139">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-139">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-140">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-140">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-141">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-141">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-142">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-142">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As Uri) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="eb75b-143">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-143">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="eb75b-144"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="eb75b-144"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="eb75b-145"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-145">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="eb75b-146">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="eb75b-146">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb75b-147">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-147">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-148">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-148">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="eb75b-149">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-149">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-150">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-150">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-151">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-151">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-152"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-152"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-153">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-153">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-154">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-154">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-155">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-155">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-156">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-156">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="eb75b-157">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-157">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="eb75b-158"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="eb75b-158"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="eb75b-159">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-159">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="eb75b-160"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-160">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="eb75b-161">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="eb75b-161">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb75b-162">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-162">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-163">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-163">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="eb75b-164">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-164">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-165">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-165">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-166">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-166">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="eb75b-167">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-167">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-168"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-168"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-169">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-169">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-170">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-170">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-171">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-171">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="eb75b-172">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-172">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="eb75b-173">たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-173">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-174">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-174">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="eb75b-175">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-175">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="eb75b-176"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="eb75b-176"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="eb75b-177">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-177">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="eb75b-178"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-178">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="eb75b-179">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="eb75b-179">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb75b-180">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-180">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-181">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-181">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="eb75b-182">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-182">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-183">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-183">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-184">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-184">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="eb75b-185">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-185">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-186"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-186"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-187">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-187">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-188">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-188">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-189">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-189">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="eb75b-190">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-190">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="eb75b-191">たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-191">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-192">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-192">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As String, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="eb75b-193">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-193">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="eb75b-194"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="eb75b-194"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="eb75b-195"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-195">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="eb75b-196">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="eb75b-196">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="eb75b-197">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="eb75b-197">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="eb75b-198">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-198">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="eb75b-199">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-199">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-200">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-200">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-201">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-201">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="eb75b-202">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-202">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-203">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-203">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-204">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-204">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-205"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-205"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-206">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="eb75b-206">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-207">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="eb75b-207">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-208">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-208">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-209">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-209">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As Uri, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="eb75b-210">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-210">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="eb75b-211"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="eb75b-211"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="name">
            <span data-ttu-id="eb75b-212"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-212">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="eb75b-213">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="eb75b-213">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="eb75b-214">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="eb75b-214">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="eb75b-215">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-215">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="eb75b-216">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-216">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-217">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-217">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-218">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-218">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="eb75b-219">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-219">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-220">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-220">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-221">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-221">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-222"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-222"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-223">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="eb75b-223">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-224">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="eb75b-224">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-225">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-225">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-226">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-226">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="eb75b-227">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-227">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="eb75b-228"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="eb75b-228"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="eb75b-229">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-229">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="eb75b-230"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-230">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="eb75b-231">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="eb75b-231">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="eb75b-232">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="eb75b-232">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="eb75b-233">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-233">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="eb75b-234">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-234">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-235">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-235">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-236">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-236">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="eb75b-237">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-237">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-238">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-238">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-239">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-239">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="eb75b-240">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-240">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-241"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-241"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-242">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="eb75b-242">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-243">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="eb75b-243">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-244">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-244">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="eb75b-245">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-245">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="eb75b-246">たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-246">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-247">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-247">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="eb75b-248">指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-248">When specifying the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> type, you may ask for either a class type or an interface type.</span></span>
            <span data-ttu-id="eb75b-249"><para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></span><span class="sxs-lookup"><span data-stu-id="eb75b-249"><para> If specifying a class type, the system will attempt to return an instance of that type. If an instance of that type cannot be instantiated (e.g., abstract class, no suitable constructor), an ArgumentException is thrown. </para><para> If specifying an interface type, the manager will attempt to resolve the interface to a concrete type. If type mapping is specified by the user, this method will use the user-specified mapping to resolve the type (not yet supported). If type mapping is not specified by the user this method will select the default implementation for the interface given. If the given interface type does not have a default implementation, or a user-specified mapping for the type is not provided or the type is invalid, this method will throw ArgumentException. </para></span></span></typeparam>
        <param name="tx"><span data-ttu-id="eb75b-250">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-250">Transaction to associate this operation with.</span></span></param>
        <param name="name">
            <span data-ttu-id="eb75b-251"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-251">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="eb75b-252">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="eb75b-252">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <param name="timeout"><span data-ttu-id="eb75b-253">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="eb75b-253">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="eb75b-254">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-254">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="eb75b-255">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-255">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-256">取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-256">Gets an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name if it exists, or creates one and returns it if it doesn't already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-257">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-257">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="eb75b-258">タスクの結果は、信頼性の高い状態のインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-258">The task result is the reliable state instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-259">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-259">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-260">ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-260">When an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> needs to be created, it will either complete and return successfully or it will not be created.</span></span> <span data-ttu-id="eb75b-261">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-261">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-262"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-262"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-263">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="eb75b-263">An instance of the type <typeparamref name="T" /> cannot be created, or the existing <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not of type <typeparamref name="T" />, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-264">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="eb75b-264">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-265">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-265">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="eb75b-266">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-266">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="eb75b-267">たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-267">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-268">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-268">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (string name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As String) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="eb75b-269">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-269">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-270">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-270">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="eb75b-271">状態が永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-271">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-272">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-272">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-273">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-273">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-274"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-274">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-275"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-275"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-276"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-276">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-277">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-277">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-278">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-278">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-279">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-279">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As Uri) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="eb75b-280">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-280">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-281">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-281">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="eb75b-282">状態が永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-282">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-283">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-283">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-284">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-284">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-285"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-285">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-286"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-286"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-287"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-287">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-288">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-288">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-289">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-289">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-290">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-290">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As String) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="eb75b-291">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-291">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="eb75b-292">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-292">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-293">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-293">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="eb75b-294">トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-294">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-295">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-295">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-296">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-296">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-297"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-297">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="eb75b-298">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-298">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-299"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-299"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-300"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-300">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-301">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-301">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-302">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-302">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="eb75b-303">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-303">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="eb75b-304">たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-304">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-305">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-305">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As Uri) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="eb75b-306">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-306">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="eb75b-307">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-307">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-308">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-308">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="eb75b-309">トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-309">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-310">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-310">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-311">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-311">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-312"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-312">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="eb75b-313">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-313">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-314"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-314"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-315"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-315">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-316">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-316">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-317">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-317">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="eb75b-318">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-318">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="eb75b-319">たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-319">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-320">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-320">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As String, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="eb75b-321">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-321">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="eb75b-322">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="eb75b-322">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="eb75b-323">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-323">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="eb75b-324">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-324">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-325">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-325">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="eb75b-326">状態が永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-326">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-327">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-327">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-328">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-328">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-329"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-329">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-330"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-330"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-331"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="eb75b-331">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-332">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="eb75b-332">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-333">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-333">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-334">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-334">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As Uri, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="eb75b-335">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-335">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="eb75b-336">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="eb75b-336">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="eb75b-337">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-337">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="eb75b-338">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-338">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-339">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-339">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="eb75b-340">状態が永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-340">The state is permanently removed from persistent storage and all replicas.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-341">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-341">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-342">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-342">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-343"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-343">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-344"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-344"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-345"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="eb75b-345">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-346">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="eb75b-346">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-347">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-347">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-348">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-348">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As String, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="eb75b-349">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-349">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="eb75b-350">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-350">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="eb75b-351">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="eb75b-351">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="eb75b-352">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-352">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="eb75b-353">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-353">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-354">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-354">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="eb75b-355">トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-355">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-356">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-356">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-357">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-357">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-358"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-358">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="eb75b-359">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-359">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-360"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-360"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-361"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="eb75b-361">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-362">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="eb75b-362">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-363">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-363">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="eb75b-364">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-364">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="eb75b-365">たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-365">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-366">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-366">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="eb75b-367">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="eb75b-367">Transaction to associate this operation with.</span></span></param>
        <param name="name"><span data-ttu-id="eb75b-368">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-368">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="eb75b-369">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="eb75b-369">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="eb75b-370">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-370">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="eb75b-371">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-371">The default is 4 seconds.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-372">削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-372">Removes the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name from this state manager.</span></span> <span data-ttu-id="eb75b-373">トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-373">The state is permanently removed from persistent storage and all replicas when the transaction is committed.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-374">非同期の削除操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-374">Task that represents the asynchronous remove operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-375">これは、分割不可能な操作です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-375">This is an atomic operation.</span></span> <span data-ttu-id="eb75b-376"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-376">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> will be successfully removed along with all state or be left in-tact.</span></span> <span data-ttu-id="eb75b-377">このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-377">If this method throws an exception, the transaction must be aborted.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-378"><paramref name="tx" />null、または<paramref name="name" />が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-378"><paramref name="tx" /> is null, or <paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-379"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="eb75b-379">An <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> with the given name does not exist, or <paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="eb75b-380">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="eb75b-380">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="eb75b-381">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-381">Thrown when the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> is not in <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="eb75b-382">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-382">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="eb75b-383">たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-383">For example, transaction used is already terminated: committed or aborted.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-384">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-384">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer&lt;T&gt;">
      <MemberSignature Language="C#" Value="bool IReliableStateManager.TryAddStateSerializer&lt;T&gt; (Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt; stateSerializer);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer&lt;T&gt;(class Microsoft.ServiceFabric.Data.IStateSerializer`1&lt;!!T&gt; stateSerializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" />
      <MemberSignature Language="VB.NET" Value="Function TryAddStateSerializer(Of T) (stateSerializer As IStateSerializer(Of T)) As Boolean Implements IReliableStateManager.TryAddStateSerializer" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateSerializer" Type="Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="eb75b-385">シリアル化および逆シリアル化される型。</span><span class="sxs-lookup"><span data-stu-id="eb75b-385">Type that will be serialized and de-serialized.</span></span></typeparam>
        <param name="stateSerializer">
            <span data-ttu-id="eb75b-386">追加する状態シリアライザー。</span><span class="sxs-lookup"><span data-stu-id="eb75b-386">The state serializer to be added.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb75b-387">状態のシリアライザーを追加します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-387">Adds a state serializer.</span></span>
            <span data-ttu-id="eb75b-388">すべての信頼性の高いコレクション インスタンスに対して追加されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-388">Adds it for all reliable collection instances.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb75b-389">True の場合、シリアライザーが追加されました。</span><span class="sxs-lookup"><span data-stu-id="eb75b-389">True if the serializer was added.</span></span>
            <span data-ttu-id="eb75b-390">Serailizer は既に登録されている場合は false。</span><span class="sxs-lookup"><span data-stu-id="eb75b-390">False if a serailizer is already registered.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="eb75b-391">このメソッドは、InitializeStateSerializers でのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-391">This method can only be called in InitializeStateSerializers.</span></span>
            <span data-ttu-id="eb75b-392">インスタンスの特定の状態のシリアライザー常に優先されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-392">Instance specific state serializers always take precedence.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; IReliableStateManager.TryGetAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryGetAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function TryGetAsync(Of T As IReliableState) (name As String) As Task(Of ConditionalValue(Of T)) Implements IReliableStateManager.TryGetAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="eb75b-393">型を指定する場合は、具象型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-393">When specifying the type, you may ask for either a concrete type or an interface type.</span></span> <span data-ttu-id="eb75b-394">取得したオブジェクトは、指定された型にキャストされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-394">The retrieved object will be cast to the given type.</span></span>
            </typeparam>
        <param name="name">
            <span data-ttu-id="eb75b-395"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-395">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="eb75b-396">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="eb75b-396">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb75b-397">取得を試みます、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-397">Attempts to get an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-398">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-398">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="eb75b-399">タスクの結果は、信頼性の高い状態が見つかったかどうかを示す組とそのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="eb75b-399">The task result is a tuple indicating whether the reliable state was found, and if so the instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-400"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-400"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-401"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスは型に変換できません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-401">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not convertible to type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="eb75b-402">例外は、状態マネージャーに信頼性の高いコレクションを取得できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-402">Exception indicates that the State Manager cannot retrive a reliable collection.</span></span>
            <span data-ttu-id="eb75b-403"><see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="eb75b-403"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="eb75b-404">たとえば、ときに、<see cref="F:System.Fabric.ReplicaRole.Primary" />または<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />を失った<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-404">For example, when a <see cref="F:System.Fabric.ReplicaRole.Primary" /> or <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> looses <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-405">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-405">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; IReliableStateManager.TryGetAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryGetAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function TryGetAsync(Of T As IReliableState) (name As Uri) As Task(Of ConditionalValue(Of T)) Implements IReliableStateManager.TryGetAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="eb75b-406">型を指定する場合は、具象型またはインターフェイス型のいずれかを要求することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-406">When specifying the type, you may ask for either a concrete type or an interface type.</span></span> <span data-ttu-id="eb75b-407">取得したオブジェクトは、指定された型にキャストされます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-407">The retrieved object will be cast to the given type.</span></span>
            </typeparam>
        <param name="name">
            <span data-ttu-id="eb75b-408"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</span><span class="sxs-lookup"><span data-stu-id="eb75b-408">The name of the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />.</span></span> <span data-ttu-id="eb75b-409">この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。</span><span class="sxs-lookup"><span data-stu-id="eb75b-409">This name must be unique in this <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" /> across <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> types, including unrelated types.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb75b-410">取得を試みます、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と指定した名前です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-410">Attempts to get an <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> of the given type <typeparamref name="T" /> and with the given name.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-411">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-411">Task that represents the asynchronous operation.</span></span> <span data-ttu-id="eb75b-412">タスクの結果は、信頼性の高い状態が見つかったかどうかを示す組とそのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="eb75b-412">The task result is a tuple indicating whether the reliable state was found, and if so the instance.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="eb75b-413"><paramref name="name" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-413"><paramref name="name" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="eb75b-414"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスは型に変換できません<typeparamref name="T" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-414">The <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> instance is not convertible to type <typeparamref name="T" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="eb75b-415">例外は、状態マネージャーに信頼性の高いコレクションを取得できないことを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-415">Exception indicates that the State Manager cannot retrive a reliable collection.</span></span>
            <span data-ttu-id="eb75b-416"><see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="eb75b-416"><see cref="T:System.Fabric.FabricNotReadableException" /> can be thrown in all <see cref="T:System.Fabric.ReplicaRole" />s.</span></span>
            <span data-ttu-id="eb75b-417">たとえば、ときに、<see cref="F:System.Fabric.ReplicaRole.Primary" />または<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />を失った<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-417">For example, when a <see cref="F:System.Fabric.ReplicaRole.Primary" /> or <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> looses <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-418">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-418">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements IStateProviderReplica.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="eb75b-419">状態プロバイダーのレプリカを強制的に中止します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-419">Forcefully abort the state provider replica.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="eb75b-420">これは一般に、ノードで、永続的な障害が検出されたときに、または Service Fabric は、内部エラーのため、レプリカのライフ サイクルを確実に管理できませんに発生します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-420">This generally occurs when a permanent fault is detected on the node, or when Service Fabric cannot reliably manage the replica's lifecycle due to internal failures.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole"><span data-ttu-id="eb75b-421">プライマリまたはセカンダリなど、新しいレプリカ ロール。</span><span class="sxs-lookup"><span data-stu-id="eb75b-421">The new replica role, such as primary or secondary.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="eb75b-422">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="eb75b-422">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-423">そのロールが変更される、たとえばプライマリまたはセカンダリに、状態プロバイダーのレプリカを通知します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-423">Notify the state provider replica that its role is changing, for example to Primary or Secondary.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-424">非同期の変更の役割の操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-424">Task that represents the asynchronous change role operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="eb75b-425">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="eb75b-425">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-426">状態プロバイダーの複製が正常にクローズします。</span><span class="sxs-lookup"><span data-stu-id="eb75b-426">Gracefully close the state provider replica.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-427">非同期の close 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-427">Task that represents the asynchronous close operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-428">これは一般に、レプリカのコードにアップグレードされている、負荷分散のため、レプリカが移動されてまたは一時的なエラーが検出されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-428">This generally occurs when the replica's code is being upgrade, the replica is being moved due to load balancing, or a transient fault is detected.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Sub Initialize (initializationParameters As StatefulServiceInitializationParameters) Implements IStateProviderReplica.Initialize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters"><span data-ttu-id="eb75b-429">サービス名、パーティション id、レプリカの id、およびコード パッケージ情報などのサービスの初期化情報。</span><span class="sxs-lookup"><span data-stu-id="eb75b-429">Service initialization information such as service name, partition id, replica id, and code package information.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-430">サービスの初期化情報を使用して、状態プロバイダーのレプリカを初期化します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-430">Initialize the state provider replica using the service initialization information.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="eb75b-431">複雑な処理を初期化中に行う必要はありません。</span><span class="sxs-lookup"><span data-stu-id="eb75b-431">No complex processing should be done during Initialize.</span></span> <span data-ttu-id="eb75b-432">OpenAsync では、高価なまたは実行時間の長いの初期化を行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-432">Expensive or long-running initialization should be done in OpenAsync.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; IStateProviderReplica.OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
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
        <param name="openMode"><span data-ttu-id="eb75b-433">これが新規または既存のレプリカであるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-433">Indicates whether this is a new or existing replica.</span></span></param>
        <param name="partition"><span data-ttu-id="eb75b-434">このレプリカが属しているパーティション。</span><span class="sxs-lookup"><span data-stu-id="eb75b-434">The partition this replica belongs to.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="eb75b-435">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="eb75b-435">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-436">使用するため、状態プロバイダーのレプリカを開きます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-436">Open the state provider replica for use.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb75b-437">非同期の open 操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-437">Task that represents the asynchronous open operation.</span></span> <span data-ttu-id="eb75b-438">結果には、パーティション内の他の状態プロバイダーのレプリカ間で状態のレプリケーションを担当するレプリケーターが含まれています。</span><span class="sxs-lookup"><span data-stu-id="eb75b-438">The result contains the replicator responsible for replicating state between other state provider replicas in the partition.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="eb75b-439">この時点でのタスクを開始状態プロバイダーの初期化を拡張します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-439">Extended state provider initialization tasks can be started at this time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; OnDataLossAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; OnDataLossAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManager.OnDataLossAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnDataLossAsync As Func(Of CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.OnDataLossAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Data.ReliableStateManager.OnDataLossAsync" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Data.IStateProviderReplica.OnDataLossAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eb75b-440">通知を受信するには、このプロパティを設定するときにこの<see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" />データが失われると予想できます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-440">Set this property to receive notification when this <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" /> suspects data loss.</span></span>
            </summary>
        <value>
            <span data-ttu-id="eb75b-441">疑いのあるデータ損失の処理の一部として呼び出される関数。</span><span class="sxs-lookup"><span data-stu-id="eb75b-441">Function called as part of suspected data loss processing.</span></span>
            </value>
        <remarks>
          <para>
            <span data-ttu-id="eb75b-442">OnDataLossAsync 関数は、CancellationToken はし、イベントの非同期処理を表すタスクを返す必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-442">OnDataLossAsync function takes in CancellationToken and needs to return a Task that represents the asynchronous processing of the event.</span></span>
            <span data-ttu-id="eb75b-443">True を返すには、信頼性の高い状態マネージャーの状態が復元されていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-443">Returning true indicates that the reliable state manager's state has been restored.</span></span>
            <span data-ttu-id="eb75b-444">False を返すことは、信頼性の高い状態マネージャーの状態が変更されていないことを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-444">Returning false indicates that the reliable state manager's state has not been changed.</span></span>
            </para>
          <para>
            <span data-ttu-id="eb75b-445">渡されたデリゲートは、キャンセル要求に指定されたキャンセル トークンを監視する必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-445">The passed delegate should monitor the given cancellation token for cancellation requests.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManager.OnRestoreCompletedAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnRestoreCompletedAsync As Func(Of CancellationToken, Task)" />
      <MemberSignature Language="F#" Value="member this.OnRestoreCompletedAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Data.ReliableStateManager.OnRestoreCompletedAsync" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Data.IStateProviderReplica2.OnRestoreCompletedAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eb75b-446">Post 復元が呼び出される関数はレプリカで実行されています。</span><span class="sxs-lookup"><span data-stu-id="eb75b-446">Function called post restore has been performed on the replica.</span></span>
            </summary>
        <value>
            <span data-ttu-id="eb75b-447">フレームワークによって、レプリカの状態が正常に復元された場合に呼び出される関数</span><span class="sxs-lookup"><span data-stu-id="eb75b-447">Function called when the replica's state has been restored successfully by the framework</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestoreAsync (backupFolderPath As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.RestoreAsync : string -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.RestoreAsync backupFolderPath" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="eb75b-448">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="eb75b-448">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="eb75b-449">このパラメーターを null にすることはできませんを空または空白のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="eb75b-449">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="eb75b-450">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-450">UNC paths may also be provided.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb75b-451">によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-451">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-452">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-452">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="eb75b-453">つまり、復元するデータが、現在のレプリカの状態より進んでいる場合、復元は完了のみ、安全なバックアップが実行されます。</span><span class="sxs-lookup"><span data-stu-id="eb75b-453">A safe backup will be performed, meaning the restore will only be completed if the data to restore is ahead of state of the current replica.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string * Microsoft.ServiceFabric.Data.RestorePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RestoreAsync : string * Microsoft.ServiceFabric.Data.RestorePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.RestoreAsync (backupFolderPath, restorePolicy, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
        <Parameter Name="restorePolicy" Type="Microsoft.ServiceFabric.Data.RestorePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            <span data-ttu-id="eb75b-454">レプリカがから復元するディレクトリ。</span><span class="sxs-lookup"><span data-stu-id="eb75b-454">The directory where the replica is to be restored from.</span></span>
            <span data-ttu-id="eb75b-455">このパラメーターを null にすることはできませんを空または空白のみが含まれています。</span><span class="sxs-lookup"><span data-stu-id="eb75b-455">This parameter cannot be null, empty or contain just whitespace.</span></span> <span data-ttu-id="eb75b-456">UNC パスも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="eb75b-456">UNC paths may also be provided.</span></span>
            </param>
        <param name="restorePolicy"><span data-ttu-id="eb75b-457">復元のポリシー。</span><span class="sxs-lookup"><span data-stu-id="eb75b-457">The restore policy.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="eb75b-458">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="eb75b-458">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="eb75b-459">によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。</span><span class="sxs-lookup"><span data-stu-id="eb75b-459">Restore a backup taken by <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" /> or <see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />.</span></span>
            </summary>
        <returns><span data-ttu-id="eb75b-460">非同期の復元操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="eb75b-460">Task that represents the asynchronous restore operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateManagerChanged">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.ReliableStateManager.StateManagerChanged" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event StateManagerChanged As EventHandler(Of NotifyStateManagerChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.StateManagerChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " Usage="member this.StateManagerChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Data.IReliableStateManager.StateManagerChanged</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eb75b-461">状態マネージャーが変更されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-461">Occurs when the state manager changes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-462">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-462">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TransactionChanged">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.ReliableStateManager.TransactionChanged" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event TransactionChanged As EventHandler(Of NotifyTransactionChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.TransactionChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " Usage="member this.TransactionChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Data.IReliableStateManager.TransactionChanged</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="eb75b-463">トランザクションが変更されたときに発生します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-463">Occurs when a transaction changes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="eb75b-464">信頼性の高い状態マネージャーが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="eb75b-464">Indicates that the Reliable State Manager is closed.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>