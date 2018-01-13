<Type Name="FaultType" FullName="System.Fabric.FaultType">
  <TypeSignature Language="C#" Value="public enum FaultType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed FaultType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FaultType" />
  <TypeSignature Language="VB.NET" Value="Public Enum FaultType" />
  <TypeSignature Language="F#" Value="type FaultType = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="57324-101">サービスを報告するエラーの種類を示します: 無効な一時的または永続的です。</span><span class="sxs-lookup"><span data-stu-id="57324-101">Indicates the type of fault that a service reports: invalid, transient or permanent.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="57324-102">サービスを使用して実行時にエラーを報告することができます、<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />フォールトの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="57324-102">Services can report faults during runtime by using the <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> method to indicate the type of fault.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.FaultType.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="57324-103">型が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="57324-103">The type is invalid.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Permanent">
      <MemberSignature Language="C#" Value="Permanent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Permanent = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Permanent" />
      <MemberSignature Language="VB.NET" Value="Permanent" />
      <MemberSignature Language="F#" Value="Permanent = 1" Usage="System.Fabric.FaultType.Permanent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="57324-104">永続的な障害は、レプリカがから回復できないエラーです。</span><span class="sxs-lookup"><span data-stu-id="57324-104">A permanent fault is a fault that the replica cannot recover from.</span></span> <span data-ttu-id="57324-105">この種類のエラーは、こと、レプリカでも、さらに進行状況とを削除して交換を示します。</span><span class="sxs-lookup"><span data-stu-id="57324-105">This type of fault indicates that the replica can make no further progress and should be removed and replaced.</span></span> </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="57324-106">永続的な障害の例は、情報をディスクに書き込もうし、ディスクが削除されていたか、使用可能なできなかったことを決定する永続的なステートフルなサービスになります。</span><span class="sxs-lookup"><span data-stu-id="57324-106">An example of a permanent fault would be a persistent stateful service that tries to write information to disk and determines that the disk had been removed or was unusable.</span></span> <span data-ttu-id="57324-107">呼び出す<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />経由で中止となるサービスに永続的な障害の結果を報告し、 <languageKeyword>IStatefulServiceReplica です。</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /></span><span class="sxs-lookup"><span data-stu-id="57324-107">Calling <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> and reporting a permanent fault result in the service to be Aborted via <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /></span></span> <span data-ttu-id="57324-108">または<languageKeyword>IStatelessServiceInstance です。</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /></span><span class="sxs-lookup"><span data-stu-id="57324-108">or <languageKeyword>IStatelessServiceInstance.</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /></span></span> <span data-ttu-id="57324-109">状態または完了操作を正常にクリーンアップする可能性です。</span><span class="sxs-lookup"><span data-stu-id="57324-109">without a chance to gracefully clean up state or complete operations.</span></span> <span data-ttu-id="57324-110">したがって、クリーンアップまたはその他の実行時間の長い作業が必要な場合が実行する前に<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />と呼びます。</span><span class="sxs-lookup"><span data-stu-id="57324-110">Therefore, if any cleanup or other long-running work is necessary, it should be performed before <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> is called.</span></span> <span data-ttu-id="57324-111">永続的なと一時的な障害の違いには、ステートフルなサービスの永続的なことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="57324-111">Note that the distinction between permanent and transient faults is useful mainly for persistent stateful services.</span></span> <span data-ttu-id="57324-112">呼び出しシーケンス以外の他のサービスの種類に与える影響については、同じ: レプリカまたはインスタンスが削除される、そのレプリカまたはインスタンスですべての状態は失われ、レプリカまたはインスタンスを再作成する可能性のある別の場所にします。</span><span class="sxs-lookup"><span data-stu-id="57324-112">Other than the call sequence, the effects on other service types are the same: the replica or instance is removed, all state at that replica or instance is lost, and the replica or instance is recreated, potentially in a different location.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Transient">
      <MemberSignature Language="C#" Value="Transient" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.FaultType Transient = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FaultType.Transient" />
      <MemberSignature Language="VB.NET" Value="Transient" />
      <MemberSignature Language="F#" Value="Transient = 2" Usage="System.Fabric.FaultType.Transient" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FaultType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="57324-113">一時的なエラーは、一時的な状態が原因で進行状況の詳細と、他のユーザーの要求を処理から、レプリカがあることを示します。</span><span class="sxs-lookup"><span data-stu-id="57324-113">A transient fault indicates that there is some temporary condition which prevents the replica from making further progress or from processing further user requests.</span></span> </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="57324-114">一時的なエラーの例は、サービスの状態またはいくつかの参照ファイルの一部が破損していますが、サービスが再初期化するされたときに修復できることを決定します。</span><span class="sxs-lookup"><span data-stu-id="57324-114">An example of a transient fault is a service that determines that a portion of its state or some reference file is corrupted, but can be repaired if the service were to be re-initialized.</span></span> <span data-ttu-id="57324-115">この場合、サービスを使用して、<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />に一時的なエラーを報告するメソッド。</span><span class="sxs-lookup"><span data-stu-id="57324-115">In this case, the service uses the <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> method to report a transient fault.</span></span> <span data-ttu-id="57324-116">経由でサービスを閉じる一時的なエラーを報告<languageKeyword>IStatefulServiceReplica です。</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)" /></span><span class="sxs-lookup"><span data-stu-id="57324-116">Reporting a transient fault closes the service via <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)" /></span></span> <span data-ttu-id="57324-117">または<languageKeyword>IStatelessServiceInstance</languageKeyword> 。<see cref="M:System.Fabric.IStatelessServiceInstance.CloseAsync(System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="57324-117">or <languageKeyword>IStatelessServiceInstance.</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.CloseAsync(System.Threading.CancellationToken)" />.</span></span> <span data-ttu-id="57324-118">ステートレスおよびステートフルなサービスのことに注意してください、揮発性の一時的なエラーは、エラー状態は維持されませんので非常に便利です。</span><span class="sxs-lookup"><span data-stu-id="57324-118">Note that for stateless and stateful services, volatile transient faults are not very useful because state is not preserved across the failure.</span></span> <span data-ttu-id="57324-119">これらのサービスでは、一時的または永続的なエラーを使用するかどうかは、サービスを正常にクリーンアップを非同期的に終了または異常終了されており、同期するかどうかに依存<languageKeyword>IStatefulServiceReplica です。</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /></span><span class="sxs-lookup"><span data-stu-id="57324-119">For these services, whether to use transient or permanent faults is dependent on whether the service should be gracefully closed asynchronously with cleanup or ungracefully closed with a synchronous <languageKeyword>IStatefulServiceReplica.</languageKeyword><see cref="M:System.Fabric.IStatefulServiceReplica.Abort" /></span></span> <span data-ttu-id="57324-120">または<languageKeyword>IStatelessServiceInstance です。</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /></span><span class="sxs-lookup"><span data-stu-id="57324-120">or <languageKeyword>IStatelessServiceInstance.</languageKeyword><see cref="M:System.Fabric.IStatelessServiceInstance.Abort" /></span></span> <span data-ttu-id="57324-121">メソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="57324-121">method.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>