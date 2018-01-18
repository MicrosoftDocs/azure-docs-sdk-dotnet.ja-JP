<Type Name="ICheckpointManager" FullName="Microsoft.Azure.EventHubs.Processor.ICheckpointManager">
  <TypeSignature Language="C#" Value="public interface ICheckpointManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICheckpointManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.ICheckpointManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICheckpointManager" />
  <TypeSignature Language="F#" Value="type ICheckpointManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8870c-101">EventProcessorHost Azure Storage 以外の場所のチェックポイントを保存する場合は、このインターフェイスを使用して、独自のチェックポイント マネージャーを作成できます。</span><span class="sxs-lookup"><span data-stu-id="8870c-101">If you wish to have EventProcessorHost store checkpoints somewhere other than Azure Storage, you can write your own checkpoint manager using this interface.</span></span>  
            
            <span data-ttu-id="8870c-102"><para>Azure の記憶域マネージャーは、両方のインターフェイスは、同じクラスによって実装されて、リースと、チェックポイントの両方を同じ記憶域を使用します。自由に統一されたストアの両方の種類のデータがある場合は、同じ処理を行います。</para><para>お実装には、どのような情報を知ることがあるないために、このインターフェイスが初期化メソッドを指定できません。</para></span><span class="sxs-lookup"><span data-stu-id="8870c-102"><para>The Azure Storage managers use the same storage for both lease and checkpoints, so both interfaces are implemented by the same class. You are free to do the same thing if you have a unified store for both types of data.</para><para>This interface does not specify initialization methods because we have no way of knowing what information your implementation will require.</para></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckpointStoreExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; CheckpointStoreExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CheckpointStoreExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.CheckpointStoreExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CheckpointStoreExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CheckpointStoreExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iCheckpointManager.CheckpointStoreExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8870c-103">チェックポイント ストアが存在しますか。</span><span class="sxs-lookup"><span data-stu-id="8870c-103">Does the checkpoint store exist?</span></span>
            </summary>
        <returns><span data-ttu-id="8870c-104">存在する場合、false 以外の場合は true</span><span class="sxs-lookup"><span data-stu-id="8870c-104">true if it exists, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCheckpointIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; CreateCheckpointIfNotExistsAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; CreateCheckpointIfNotExistsAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.CreateCheckpointIfNotExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCheckpointIfNotExistsAsync (partitionId As String) As Task(Of Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member CreateCheckpointIfNotExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;" Usage="iCheckpointManager.CreateCheckpointIfNotExistsAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="8870c-105">チェックポイントを作成するパーティションの id です。</span><span class="sxs-lookup"><span data-stu-id="8870c-105">Id of partition to create the checkpoint for.</span></span></param>
        <summary>
            <span data-ttu-id="8870c-106">存在しない場合は、特定のパーティションのチェックポイントを作成します。</span><span class="sxs-lookup"><span data-stu-id="8870c-106">Create the checkpoint for the given partition if it doesn't exist.</span></span> <span data-ttu-id="8870c-107">何も存在する場合は。</span><span class="sxs-lookup"><span data-stu-id="8870c-107">Do nothing if it does exist.</span></span>
            <span data-ttu-id="8870c-108">新しく作成されたチェックポイントのオフセット/sequenceNumber は、StartOfStream/0 に設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8870c-108">The offset/sequenceNumber for a freshly-created checkpoint should be set to StartOfStream/0.</span></span>
            </summary>
        <returns><span data-ttu-id="8870c-109">特定のパーティションのチェックポイントを新しく作成されたか、既に存在するかどうか。</span><span class="sxs-lookup"><span data-stu-id="8870c-109">The checkpoint for the given partition, whether newly created or already existing.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCheckpointStoreIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; CreateCheckpointStoreIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateCheckpointStoreIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.CreateCheckpointStoreIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCheckpointStoreIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateCheckpointStoreIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iCheckpointManager.CreateCheckpointStoreIfNotExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8870c-110">存在しない場合は、チェックポイントのストアを作成します。</span><span class="sxs-lookup"><span data-stu-id="8870c-110">Create the checkpoint store if it doesn't exist.</span></span> <span data-ttu-id="8870c-111">何も存在する場合は。</span><span class="sxs-lookup"><span data-stu-id="8870c-111">Do nothing if it does exist.</span></span>
            </summary>
        <returns><span data-ttu-id="8870c-112">チェックポイントのストアは既に存在するか、[ok]、エラーが発生した場合は false が作成された場合は true。</span><span class="sxs-lookup"><span data-stu-id="8870c-112">true if the checkpoint store already exists or was created OK, false if there was a failure</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteCheckpointAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteCheckpointAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.DeleteCheckpointAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteCheckpointAsync (partitionId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteCheckpointAsync : string -&gt; System.Threading.Tasks.Task" Usage="iCheckpointManager.DeleteCheckpointAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="8870c-113">ストアからチェックポイントを削除するパーティションの id</span><span class="sxs-lookup"><span data-stu-id="8870c-113">id of partition to delete checkpoint from store</span></span></param>
        <summary>
            <span data-ttu-id="8870c-114">特定のパーティションに対してストアド チェックポイントを削除します。</span><span class="sxs-lookup"><span data-stu-id="8870c-114">Delete the stored checkpoint for the given partition.</span></span> <span data-ttu-id="8870c-115">ストアドのチェックポイントを成功として扱われる特定のパーティションがない場合。</span><span class="sxs-lookup"><span data-stu-id="8870c-115">If there is no stored checkpoint for the given partition, that is treated as success.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; GetCheckpointAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; GetCheckpointAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.GetCheckpointAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCheckpointAsync (partitionId As String) As Task(Of Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member GetCheckpointAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;" Usage="iCheckpointManager.GetCheckpointAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="8870c-116">チェックポイント情報を取得するパーティションの id。</span><span class="sxs-lookup"><span data-stu-id="8870c-116">Id of partition to get checkpoint info for.</span></span></param>
        <summary>
            <span data-ttu-id="8870c-117">特定のパーティションに関連付けられているチェックポイント データを取得します。</span><span class="sxs-lookup"><span data-stu-id="8870c-117">Get the checkpoint data associated with the given partition.</span></span> <span data-ttu-id="8870c-118">そのパーティションのチェックポイントが作成されていない場合は null を返す可能性があります。</span><span class="sxs-lookup"><span data-stu-id="8870c-118">Could return null if no checkpoint has been created for that partition.</span></span>
            </summary>
        <returns><span data-ttu-id="8870c-119">特定のパーティション、または none 以前格納されている場合は null のチェックポイント情報です。</span><span class="sxs-lookup"><span data-stu-id="8870c-119">Checkpoint info for the given partition, or null if none has been previously stored.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateCheckpointAsync (Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateCheckpointAsync(class Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.UpdateCheckpointAsync(Microsoft.Azure.EventHubs.Processor.Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCheckpointAsync : Microsoft.Azure.EventHubs.Processor.Checkpoint -&gt; System.Threading.Tasks.Task" Usage="iCheckpointManager.UpdateCheckpointAsync checkpoint" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use UpdateCheckpointAsync(Lease lease, Checkpoint checkpoint) instead", true)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="checkpoint" Type="Microsoft.Azure.EventHubs.Processor.Checkpoint" />
      </Parameters>
      <Docs>
        <param name="checkpoint"><span data-ttu-id="8870c-120">オフセット sequeceNumber でを使用してストアを更新します。</span><span class="sxs-lookup"><span data-stu-id="8870c-120">offset/sequeceNumber to update the store with.</span></span></param>
        <summary>
            <span data-ttu-id="8870c-121">指定されたチェックポイントのオフセット/sequenceNumber をストア内のチェックポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="8870c-121">Update the checkpoint in the store with the offset/sequenceNumber in the provided checkpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateCheckpointAsync (Microsoft.Azure.EventHubs.Processor.Lease lease, Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateCheckpointAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease, class Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.UpdateCheckpointAsync(Microsoft.Azure.EventHubs.Processor.Lease,Microsoft.Azure.EventHubs.Processor.Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCheckpointAsync : Microsoft.Azure.EventHubs.Processor.Lease * Microsoft.Azure.EventHubs.Processor.Checkpoint -&gt; System.Threading.Tasks.Task" Usage="iCheckpointManager.UpdateCheckpointAsync (lease, checkpoint)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
        <Parameter Name="checkpoint" Type="Microsoft.Azure.EventHubs.Processor.Checkpoint" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="8870c-122">チェックポイントを実行する対象のパーティション情報。</span><span class="sxs-lookup"><span data-stu-id="8870c-122">Partition information against which to perform a checkpoint.</span></span></param>
        <param name="checkpoint"><span data-ttu-id="8870c-123">オフセット sequeceNumber でを使用してストアを更新します。</span><span class="sxs-lookup"><span data-stu-id="8870c-123">offset/sequeceNumber to update the store with.</span></span></param>
        <summary>
            <span data-ttu-id="8870c-124">指定されたチェックポイントのオフセット/sequenceNumber をストア内のチェックポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="8870c-124">Update the checkpoint in the store with the offset/sequenceNumber in the provided checkpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>