<Type Name="CloudJobSchedule" FullName="Microsoft.Azure.Batch.CloudJobSchedule">
  <TypeSignature Language="C#" Value="public class CloudJobSchedule : Microsoft.Azure.Batch.IInheritedBehaviors, Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudJobSchedule extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors, class Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CloudJobSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudJobSchedule&#xA;Implements IInheritedBehaviors, IRefreshable" />
  <TypeSignature Language="F#" Value="type CloudJobSchedule = class&#xA;    interface IRefreshable&#xA;    interface ITransportObjectProvider&lt;JobScheduleAddParameter&gt;&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IRefreshable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="26ef7-101">定期的なジョブのジョブと各ジョブの作成に使用される仕様を実行するタイミングを指定することにより、ジョブ スケジュールです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-101">A job schedule that allows recurring jobs by specifying when to run jobs and a specification used to create each job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public void Commit (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Commit(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Commit (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Commit : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJobSchedule.Commit additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-102">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-102">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-103">このコミット<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />Azure Batch のサービスにします。</span><span class="sxs-lookup"><span data-stu-id="26ef7-103">Commits this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> to the Azure Batch service.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="26ef7-104">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-104">This is a blocking operation.</span></span> <span data-ttu-id="26ef7-105">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-105">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJobSchedule.CommitAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJobSchedule/&lt;CommitAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-106">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-106">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="26ef7-107">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-107">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-108">このコミット<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />Azure Batch のサービスにします。</span><span class="sxs-lookup"><span data-stu-id="26ef7-108">Commits this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> to the Azure Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="26ef7-109">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="26ef7-109">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="26ef7-110">コミット操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-110">The commit operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChanges">
      <MemberSignature Language="C#" Value="public void CommitChanges (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CommitChanges(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.CommitChanges(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CommitChanges (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CommitChanges : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJobSchedule.CommitChanges additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-111">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-111">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-112">これをすべて保留中の変更をコミット<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />Azure Batch のサービスにします。</span><span class="sxs-lookup"><span data-stu-id="26ef7-112">Commits all pending changes to this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> to the Azure Batch service.</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="26ef7-113">既存の更新<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />のこのプロパティをそのプロパティを置き換えることで、バッチ サービスで<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />が変更されました。</span><span class="sxs-lookup"><span data-stu-id="26ef7-113">Updates an existing <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> on the Batch service by replacing its properties with the properties of this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> which have been changed.</span></span>
            <span data-ttu-id="26ef7-114">変更されていないプロパティは無視されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-114">Unchanged properties are ignored.</span></span>
            <span data-ttu-id="26ef7-115">このエンティティの前回のすべての変更は、バッチ サービスから取得されました (のいずれかによって<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、 <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobSchedule(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、または<see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.ListJobSchedules(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) 適用されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-115">All changes since the last time this entity was retrieved from the Batch service (either via <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobSchedule(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, or <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.ListJobSchedules(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) are applied.</span></span>
            <span data-ttu-id="26ef7-116">Null が明示的に設定されているプロパティでは、バッチ サービスは、プロパティを null に設定する部分的な更新をサポートしていないため、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-116">Properties which are explicitly set to null will cause an exception because the Batch service does not support partial updates which set a property to null.</span></span>
            <span data-ttu-id="26ef7-117">プロパティを null に設定する必要がある場合を使用して<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-117">If you need to set a property to null, use <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="26ef7-118">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-118">This is a blocking operation.</span></span> <span data-ttu-id="26ef7-119">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-119">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChangesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitChangesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitChangesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitChangesAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJobSchedule.CommitChangesAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJobSchedule/&lt;CommitChangesAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-120">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-120">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="26ef7-121">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-121">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-122">これをすべて保留中の変更をコミット<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />Azure Batch のサービスにします。</span><span class="sxs-lookup"><span data-stu-id="26ef7-122">Commits all pending changes to this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> to the Azure Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="26ef7-123">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="26ef7-123">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="26ef7-124">既存の更新<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />のこのプロパティをそのプロパティを置き換えることで、バッチ サービスで<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />が変更されました。</span><span class="sxs-lookup"><span data-stu-id="26ef7-124">Updates an existing <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> on the Batch service by replacing its properties with the properties of this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> which have been changed.</span></span>
            <span data-ttu-id="26ef7-125">変更されていないプロパティは無視されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-125">Unchanged properties are ignored.</span></span>
            <span data-ttu-id="26ef7-126">このエンティティの前回のすべての変更は、バッチ サービスから取得されました (のいずれかによって<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、 <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobSchedule(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、または<see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.ListJobSchedules(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) 適用されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-126">All changes since the last time this entity was retrieved from the Batch service (either via <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobSchedule(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, or <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.ListJobSchedules(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) are applied.</span></span>
            <span data-ttu-id="26ef7-127">Null が明示的に設定されているプロパティでは、バッチ サービスは、プロパティを null に設定する部分的な更新をサポートしていないため、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-127">Properties which are explicitly set to null will cause an exception because the Batch service does not support partial updates which set a property to null.</span></span>
            <span data-ttu-id="26ef7-128">プロパティを null に設定する必要がある場合を使用して<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-128">If you need to set a property to null, use <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="26ef7-129">この操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-129">This operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJobSchedule.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-130">ジョブのスケジュールの作成時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-130">Gets the creation time of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-131">取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-131">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="26ef7-132">これらの動作は、子オブジェクトによって継承されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-132">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="26ef7-133">変更は、コレクションの順序で適用されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-133">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="26ef7-134">最後には、wins を記述します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-134">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Delete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJobSchedule.Delete additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-135">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-135">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-136">この <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> を削除します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-136">Deletes this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="26ef7-137">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="26ef7-137">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="26ef7-138">削除操作は、ジョブのスケジュールが削除されることを要求します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-138">The delete operation requests that the job schedule be deleted.</span></span>  <span data-ttu-id="26ef7-139">要求は、スケジュールに格納、<see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-139">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" /> state.</span></span>
            <span data-ttu-id="26ef7-140">Batch service は既存のジョブとタスクは、アクティブなジョブを含め、スケジュールをすべて削除し、さらにクライアント操作をしなくても、実際のジョブ スケジュールの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-140">The Batch service will delete any existing jobs and tasks under the schedule, including any active job, and perform the actual job schedule deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="26ef7-141">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-141">This is a blocking operation.</span></span> <span data-ttu-id="26ef7-142">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-142">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJobSchedule.DeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJobSchedule/&lt;DeleteAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-143">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-143">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="26ef7-144">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-144">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-145">この <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> を削除します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-145">Deletes this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="26ef7-146">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="26ef7-146">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="26ef7-147">削除操作は、ジョブのスケジュールが削除されることを要求します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-147">The delete operation requests that the job schedule be deleted.</span></span>  <span data-ttu-id="26ef7-148">要求は、スケジュールに格納、<see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-148">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" /> state.</span></span>
            <span data-ttu-id="26ef7-149">Batch service は既存のジョブとタスクは、アクティブなジョブを含め、スケジュールをすべて削除し、さらにクライアント操作をしなくても、実際のジョブ スケジュールの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-149">The Batch service will delete any existing jobs and tasks under the schedule, including any active job, and perform the actual job schedule deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="26ef7-150">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-150">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public void Disable (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Disable(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.Disable(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Disable (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Disable : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJobSchedule.Disable additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-151">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-151">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-152">これを無効に<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-152">Disables this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>  <span data-ttu-id="26ef7-153">無効になっているスケジュール、新しいジョブを作成しないでくださいけれども、後で再度有効ことがあります。</span><span class="sxs-lookup"><span data-stu-id="26ef7-153">Disabled schedules do not create new jobs, but may be re-enabled later.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="26ef7-154">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-154">This is a blocking operation.</span></span> <span data-ttu-id="26ef7-155">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.DisableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-155">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.DisableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="26ef7-156">スケジュールを再度有効にするを呼び出す<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.Enable(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-156">To re-enable the schedule, call <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.Enable(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.DisableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJobSchedule.DisableAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-157">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-157">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="26ef7-158">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-158">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-159">これを無効に<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-159">Disables this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>  <span data-ttu-id="26ef7-160">無効になっているスケジュール、新しいジョブを作成しないでくださいけれども、後で再度有効ことがあります。</span><span class="sxs-lookup"><span data-stu-id="26ef7-160">Disabled schedules do not create new jobs, but may be re-enabled later.</span></span>
            </summary>
        <returns><span data-ttu-id="26ef7-161">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="26ef7-161">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="26ef7-162">無効化操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-162">The disable operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="26ef7-163">スケジュールを再度有効にするを呼び出す<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-163">To re-enable the schedule, call <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.CloudJobSchedule.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-164">取得またはジョブ スケジュールの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-164">Gets or sets the display name of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public void Enable (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Enable(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.Enable(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Enable (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Enable : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJobSchedule.Enable additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-165">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-165">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-166">これにより、 <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />、に従って作成されたジョブを許可する、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-166">Enables this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />, allowing jobs to be created according to the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="26ef7-167">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="26ef7-167">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="26ef7-168">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-168">This is a blocking operation.</span></span> <span data-ttu-id="26ef7-169">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-169">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJobSchedule.EnableAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-170">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-170">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="26ef7-171">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-171">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-172">これにより、 <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />、に従って作成されたジョブを許可する、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-172">Enables this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />, allowing jobs to be created according to the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="26ef7-173">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="26ef7-173">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="26ef7-174">有効にする操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-174">The enable operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Batch.CloudJobSchedule.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-175">ジョブ スケジュールの ETag を取得します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-175">Gets the ETag of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobScheduleExecutionInformation ExecutionInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobScheduleExecutionInformation ExecutionInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.ExecutionInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExecutionInformation As JobScheduleExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ExecutionInformation : Microsoft.Azure.Batch.JobScheduleExecutionInformation" Usage="Microsoft.Azure.Batch.CloudJobSchedule.ExecutionInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobScheduleExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-176">ジョブのスケジュールの実行情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-176">Gets the execution information for the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.CloudJobSchedule.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-177">取得またはジョブ スケジュールの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-177">Gets or sets the id of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobSpecification JobSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobSpecification JobSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.JobSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property JobSpecification As JobSpecification" />
      <MemberSignature Language="F#" Value="member this.JobSpecification : Microsoft.Azure.Batch.JobSpecification with get, set" Usage="Microsoft.Azure.Batch.CloudJobSchedule.JobSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-178">取得または設定、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.JobSpecification" />に従って作成するジョブの詳細を含む、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-178">Gets or sets a <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.JobSpecification" /> containing details of the jobs to be created according to the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJobSchedule.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-179">ジョブ スケジュールの最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-179">Gets the last modified time of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt; ListJobs (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudJob&gt; ListJobs(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListJobs : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt;" Usage="cloudJobSchedule.ListJobs (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="26ef7-180">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-180">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-181">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-181">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-182">列挙、<see cref="T:Microsoft.Azure.Batch.CloudJob">ジョブ</see>これの下に作成<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-182">Enumerates the <see cref="T:Microsoft.Azure.Batch.CloudJob">jobs</see> created under this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="26ef7-183"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を非同期的または同期的に、ジョブを列挙を使用できます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-183">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate jobs asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="26ef7-184">このメソッドがすぐに戻るジョブは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-184">This method returns immediately; the jobs are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="26ef7-185">検索は非アトミックなです。ジョブは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-185">Retrieval is non-atomic; jobs are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJobSchedule.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-186">取得またはメタデータとしてスケジュールに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-186">Gets or sets a list of name-value pairs associated with the schedule as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.JobScheduleState&gt; PreviousState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.JobScheduleState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousState As Nullable(Of JobScheduleState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Common.JobScheduleState&gt;" Usage="Microsoft.Azure.Batch.CloudJobSchedule.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.JobScheduleState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-187">ジョブのスケジュールの以前の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-187">Gets the previous state of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="26ef7-188">スケジュールが、初期の場合<see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Active" />状態、PreviousState プロパティが定義されていません。</span><span class="sxs-lookup"><span data-stu-id="26ef7-188">If the schedule is in its initial <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Active" /> state, the PreviousState property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJobSchedule.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-189">ジョブのスケジュールが以前の状態を入力する時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-189">Gets the time at which the job schedule entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="26ef7-190">スケジュールが、初期の場合<see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Active" />状態、PreviousStateTransitionTime プロパティが定義されていません。</span><span class="sxs-lookup"><span data-stu-id="26ef7-190">If the schedule is in its initial <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Active" /> state, the PreviousStateTransitionTime property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJobSchedule.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="26ef7-191">最新の更新の詳細レベルです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-191">The detail level for the refresh.</span></span>  <span data-ttu-id="26ef7-192">詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Id" />プロパティを指定すると、更新は失敗します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-192">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-193">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-193">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-194">現在の更新<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-194">Refreshes the current <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJobSchedule.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJobSchedule/&lt;RefreshAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="26ef7-195">最新の更新の詳細レベルです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-195">The detail level for the refresh.</span></span>  <span data-ttu-id="26ef7-196">詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Id" />プロパティを指定すると、更新は失敗します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-196">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-197">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-197">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="26ef7-198">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-198">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-199">現在の更新<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-199">Refreshes the current <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="26ef7-200">A<see cref="T:System.Threading.Tasks.Task" />非同期更新操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-200">A <see cref="T:System.Threading.Tasks.Task" /> representing the asynchronous refresh operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Schedule Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Schedule Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As Schedule" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Batch.Schedule with get, set" Usage="Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Schedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-201">取得またはジョブを作成する場合を決定するスケジュールを設定します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-201">Gets or sets the schedule that determines when jobs will be created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.JobScheduleState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.JobScheduleState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of JobScheduleState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.JobScheduleState&gt;" Usage="Microsoft.Azure.Batch.CloudJobSchedule.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.JobScheduleState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-202">ジョブのスケジュールの現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-202">Gets the current state of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJobSchedule.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-203">時間を取得、<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />現在の状態を入力します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-203">Gets the time at which the <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobScheduleStatistics Statistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobScheduleStatistics Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Statistics As JobScheduleStatistics" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Batch.JobScheduleStatistics" Usage="Microsoft.Azure.Batch.CloudJobSchedule.Statistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobScheduleStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-204">取得、<see cref="T:Microsoft.Azure.Batch.JobScheduleStatistics" />ジョブ スケジュールの有効期間にわたってのリソース使用状況の統計を含むです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-204">Gets a <see cref="T:Microsoft.Azure.Batch.JobScheduleStatistics" /> containing resource usage statistics for the entire lifetime of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="26ef7-205">場合にのみ、このプロパティが設定されます、<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />で取得した、 <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> 'stats' 属性を含むそれ以外の場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-205">This property is populated only if the <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> was retrieved with an <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> including the 'stats' attribute; otherwise it is null.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public void Terminate (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Terminate(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.Terminate(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Terminate (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Terminate : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJobSchedule.Terminate additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-206">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-206">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-207">これが終了<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-207">Terminates this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>  <span data-ttu-id="26ef7-208">終了されたスケジュールは、システムに残りますが、新しいジョブを作成しないでください。</span><span class="sxs-lookup"><span data-stu-id="26ef7-208">Terminated schedules remain in the system but do not create new jobs.</span></span>
            </summary>
        <returns><span data-ttu-id="26ef7-209">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="26ef7-209">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="26ef7-210">終了操作は、ジョブのスケジュールが終了することを要求します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-210">The terminate operation requests that the job schedule be terminated.</span></span>  <span data-ttu-id="26ef7-211">要求は、スケジュールに格納、<see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" />状態です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-211">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" /> state.</span></span>
            <span data-ttu-id="26ef7-212">バッチ サービスは任意のアクティブなジョブ、終了するまで待機し、その他のクライアント操作しなくても、実際のジョブ スケジュールの終了を実行します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-212">The Batch service will wait for any active job to terminate, and perform the actual job schedule termination without any further client action.</span></span></para>
          <para><span data-ttu-id="26ef7-213">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-213">This is a blocking operation.</span></span> <span data-ttu-id="26ef7-214">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.TerminateAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-214">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJobSchedule.TerminateAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJobSchedule.TerminateAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJobSchedule.TerminateAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJobSchedule/&lt;TerminateAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="26ef7-215">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-215">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="26ef7-216">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="26ef7-216">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="26ef7-217">これが終了<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-217">Terminates this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>  <span data-ttu-id="26ef7-218">終了されたスケジュールは、システムに残りますが、新しいジョブを作成しないでください。</span><span class="sxs-lookup"><span data-stu-id="26ef7-218">Terminated schedules remain in the system but do not create new jobs.</span></span>
            </summary>
        <returns><span data-ttu-id="26ef7-219">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="26ef7-219">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="26ef7-220">終了操作は、ジョブのスケジュールが終了することを要求します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-220">The terminate operation requests that the job schedule be terminated.</span></span>  <span data-ttu-id="26ef7-221">要求は、スケジュールに格納、<see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" />状態です。</span><span class="sxs-lookup"><span data-stu-id="26ef7-221">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" /> state.</span></span>
            <span data-ttu-id="26ef7-222">バッチ サービスは任意のアクティブなジョブ、終了するまで待機し、その他のクライアント操作しなくても、実際のジョブ スケジュールの終了を実行します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-222">The Batch service will wait for any active job to terminate, and perform the actual job schedule termination without any further client action.</span></span></para>
          <para><span data-ttu-id="26ef7-223">終了操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="26ef7-223">The terminate operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJobSchedule.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.CloudJobSchedule.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26ef7-224">ジョブ スケジュールの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="26ef7-224">Gets the URL of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>