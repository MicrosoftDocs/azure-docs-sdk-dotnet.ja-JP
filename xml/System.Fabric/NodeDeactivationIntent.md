<Type Name="NodeDeactivationIntent" FullName="System.Fabric.NodeDeactivationIntent">
  <TypeSignature Language="C#" Value="public enum NodeDeactivationIntent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed NodeDeactivationIntent extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeDeactivationIntent" />
  <TypeSignature Language="VB.NET" Value="Public Enum NodeDeactivationIntent" />
  <TypeSignature Language="F#" Value="type NodeDeactivationIntent = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="706eb-101">なぜ、ノードが非アクティブに理由を説明します。</span><span class="sxs-lookup"><span data-stu-id="706eb-101">Describes the reason why the node is being deactivated.</span></span></para>
    </summary>
    <remarks>
      <para>
                <span data-ttu-id="706eb-102"><see cref="T:System.Fabric.NodeDeactivationIntent" />列挙型がの一部として提供される、<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="706eb-102">The <see cref="T:System.Fabric.NodeDeactivationIntent" /> enumeration is provided as a part of the <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent)" /> method.</span></span> </para>
      <para>
                <span data-ttu-id="706eb-103">Service Fabric では、この情報を使用して、ノードの正常なシャット ダウンを提供するノードに適切なアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="706eb-103">Service Fabric uses this information to take the correct actions at the node to provide a graceful shutdown of the node.</span></span> <span data-ttu-id="706eb-104">インテントは、一般的な進行または重要度があります。</span><span class="sxs-lookup"><span data-stu-id="706eb-104">The intents have a general progression or severity.</span></span> </para>
      <para>
                <span data-ttu-id="706eb-105">1 つのインテントを指定して起動し、非アクティブ化は、後続の上位レベルのインテントを増やすことができます。</span><span class="sxs-lookup"><span data-stu-id="706eb-105">A deactivation that is started with one intent can be increased to subsequent higher levels of intent.</span></span> <span data-ttu-id="706eb-106">この進行の一般的な順序は、: 一時停止、再開、停止、強制停止です。</span><span class="sxs-lookup"><span data-stu-id="706eb-106">The general order of this progression is: Pause, Restart, Stop, ForceStop.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.NodeDeactivationIntent.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="706eb-107">非アクティブ化インテントが無効であることを示します。</span><span class="sxs-lookup"><span data-stu-id="706eb-107">Indicates that a deactivation intent is invalid.</span></span> <span data-ttu-id="706eb-108">この値は使用されません。</span><span class="sxs-lookup"><span data-stu-id="706eb-108">This value is not used.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Pause">
      <MemberSignature Language="C#" Value="Pause" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Pause = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Pause" />
      <MemberSignature Language="VB.NET" Value="Pause" />
      <MemberSignature Language="F#" Value="Pause = 1" Usage="System.Fabric.NodeDeactivationIntent.Pause" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="706eb-109">ノードを一時停止することを示します。</span><span class="sxs-lookup"><span data-stu-id="706eb-109">Indicates that the node should be paused.</span></span> </para>
        </summary>
        <remarks>
          <para>
                <span data-ttu-id="706eb-110">この目的は、使用すると、Service Fabric は、指定したノードを変更できなくなります。</span><span class="sxs-lookup"><span data-stu-id="706eb-110">When this intent is used, Service Fabric prevents changes to the specified node.</span></span> <span data-ttu-id="706eb-111">新しいレプリカが、ノードに配置されないと、既存のレプリカの移動またはシャット ダウンされていません。</span><span class="sxs-lookup"><span data-stu-id="706eb-111">No new replicas are placed on the node, and existing replicas are not moved or shut down.</span></span></para>
          <para>
                <span data-ttu-id="706eb-112"><see cref="F:System.Fabric.NodeDeactivationIntent.Pause" />目的は、1 つの場合に便利ですまたはノード上の複数のレプリカの問題が発生し、そのノードでは、詳しい調査のために分離</span><span class="sxs-lookup"><span data-stu-id="706eb-112">The <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> intent is useful when one or more replicas on a node encounter issues and that node has to be isolated for further investigation</span></span></para>
          <para> 
                <span data-ttu-id="706eb-113">この調査では、ローカル ログを確認することを許可をメモリ ダンプを取得し、その他の情報を確認するには、このようなアクティビティを調査するために、リモート コンピューターへのアクセスなどがあります。</span><span class="sxs-lookup"><span data-stu-id="706eb-113">This investigation could include accessing the remote machine to investigate such activities as reviewing local logs, taking memory dumps, and observing other information.</span></span> </para>
          <para>
                <span data-ttu-id="706eb-114">このモードの目的は、エラーが発生したときに存在していた同じ条件で追加のデバッグを実行できるように、ノードを保持しようとします。</span><span class="sxs-lookup"><span data-stu-id="706eb-114">The purpose of this mode is to attempt to preserve the node so that additional debugging can be performed under the same conditions that existed when the error occurred.</span></span></para>
          <para>
                <span data-ttu-id="706eb-115">このモードを指定することは保証されませんノードにすべての変更を防止できますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="706eb-115">Note that specifying this mode does not guarantee that all changes to the node can be prevented.</span></span> </para>
          <para>
                <span data-ttu-id="706eb-116">たとえば、ノードを一時停止することを目的の受信後に、ノード上のレプリカがクラッシュする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="706eb-116">For example, replicas on the node might crash after the intent to pause the node has been received.</span></span> </para>
          <para>
                <span data-ttu-id="706eb-117">別の例として、クラスター内の別の場所で発生した障害は、プライマリ レプリカに昇格するノードで、セカンダリ レプリカ可能性があります。</span><span class="sxs-lookup"><span data-stu-id="706eb-117">As another example, failures in another location in the cluster might cause a Secondary replica on the node to be promoted to the Primary replica.</span></span></para>
          <para>
                <span data-ttu-id="706eb-118">このモードでは、Service Fabric が無効になる配置とリソースのバランスのターゲット ノード上</span><span class="sxs-lookup"><span data-stu-id="706eb-118">In this mode, Service Fabric will disable Placement and Resource Balancing on the target node</span></span></para>
          <para>
                <span data-ttu-id="706eb-119">さらに安全性チェックが (を参照してください<see cref="T:System.Fabric.SafetyCheckKind" />) Service Fabric によって実行されます。</span><span class="sxs-lookup"><span data-stu-id="706eb-119">In addition Safety Checks (see <see cref="T:System.Fabric.SafetyCheckKind" />) will be performed by Service Fabric</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveData">
      <MemberSignature Language="C#" Value="RemoveData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent RemoveData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.RemoveData" />
      <MemberSignature Language="VB.NET" Value="RemoveData" />
      <MemberSignature Language="F#" Value="RemoveData = 3" Usage="System.Fabric.NodeDeactivationIntent.RemoveData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="706eb-120">その目的は、ノードを再イメージ化することを示します。</span><span class="sxs-lookup"><span data-stu-id="706eb-120">Indicates that the intent is to reimage the node.</span></span> <span data-ttu-id="706eb-121">Service Fabric にノード再イメージ化できません - この操作は Service Fabric の外部で行われます。</span><span class="sxs-lookup"><span data-stu-id="706eb-121">Service Fabric does not reimage the node - this action is done outside of Service Fabric.</span></span></para>
        </summary>
        <remarks>
          <para>
                <span data-ttu-id="706eb-122">Service Fabric 受信すると、この目的としたことを確認します。</span><span class="sxs-lookup"><span data-stu-id="706eb-122">When Service Fabric receives this intent, it ensures that:</span></span> </para>
          <para>
                <span data-ttu-id="706eb-123">このモードでは Service Fabric を防ぎます新しいレプリカ ノードに配置されます。</span><span class="sxs-lookup"><span data-stu-id="706eb-123">In this mode, Service Fabric prevents new replicas from being placed on the node.</span></span> <span data-ttu-id="706eb-124">さらに、Service Fabric は、次のアクションを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="706eb-124">Additionally, Service Fabric takes the following actions:</span></span> </para>
          <para>
                <span data-ttu-id="706eb-125">配置とリソースのターゲット ノードで負荷分散を無効にします。</span><span class="sxs-lookup"><span data-stu-id="706eb-125">Disable Placement and Resource balancing on the target node</span></span></para>
          <para>
                <span data-ttu-id="706eb-126">すべてのノードからのレプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="706eb-126">Move all Up replicas out of the node.</span></span> </para>
          <para>
                <span data-ttu-id="706eb-127">ステートレスなインスタンスのつまり、別のノードに別のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="706eb-127">For stateless instances this implies creating another instance on another node</span></span></para>
          <para>
                <span data-ttu-id="706eb-128">ステートフル サービス レプリカ置換レプリカがビルドされた別のノード (クラスターのための十分な容量がある) 場合</span><span class="sxs-lookup"><span data-stu-id="706eb-128">For replicas of stateful services a replacement replica is built on another node (if there is sufficient capacity in the cluster)</span></span></para>
          <para>
                <span data-ttu-id="706eb-129">パーティションの他のアクティブなセカンダリの交換を作成する前に、プライマリが行われます、レプリカがプライマリである場合は、</span><span class="sxs-lookup"><span data-stu-id="706eb-129">If the replica is a primary, some other active secondary of the partition is made the primary prior to creating the replacement</span></span></para>
          <para>
                <span data-ttu-id="706eb-130">ノードでのステートフルなレプリカは、状態をクリーンアップして終了する通知を受信します。</span><span class="sxs-lookup"><span data-stu-id="706eb-130">Stateful replicas on the node receive notifications to clean up their state and close.</span></span></para>
          <para>
                <span data-ttu-id="706eb-131">データなしのこのノードを取得した結果としてが失われることができます発生ように安全性チェックのサブセットを実行します。</span><span class="sxs-lookup"><span data-stu-id="706eb-131">Performs a subset of safety checks that ensure that as a result of taking this node down no data loss can occur.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNode">
      <MemberSignature Language="C#" Value="RemoveNode" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent RemoveNode = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.RemoveNode" />
      <MemberSignature Language="VB.NET" Value="RemoveNode" />
      <MemberSignature Language="F#" Value="RemoveNode = 4" Usage="System.Fabric.NodeDeactivationIntent.RemoveNode" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="706eb-132">ノードを返す必要はありませんが廃止されていることを示します。</span><span class="sxs-lookup"><span data-stu-id="706eb-132">Indicates that the node is being decommissioned and is not expected to return.</span></span> <span data-ttu-id="706eb-133">Service Fabric は、ノードを停止できません - この操作は Service Fabric の外部で行われます。</span><span class="sxs-lookup"><span data-stu-id="706eb-133">Service Fabric does not decommission the node - this action is done outside of Service Fabric.</span></span></para>
        </summary>
        <remarks>
          <para>
                <span data-ttu-id="706eb-134">Service Fabric 受信すると、この目的としたことを確認します。</span><span class="sxs-lookup"><span data-stu-id="706eb-134">When Service Fabric receives this intent, it ensures that:</span></span> </para>
          <para>
                <span data-ttu-id="706eb-135">このモードでは Service Fabric を防ぎます新しいレプリカ ノードに配置されます。</span><span class="sxs-lookup"><span data-stu-id="706eb-135">In this mode, Service Fabric prevents new replicas from being placed on the node.</span></span> <span data-ttu-id="706eb-136">さらに、Service Fabric は、次のアクションを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="706eb-136">Additionally, Service Fabric takes the following actions:</span></span> </para>
          <para>
                <span data-ttu-id="706eb-137">配置とリソースのターゲット ノードで負荷分散を無効にします。</span><span class="sxs-lookup"><span data-stu-id="706eb-137">Disable Placement and Resource balancing on the target node</span></span></para>
          <para>
                <span data-ttu-id="706eb-138">すべてのノードからのレプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="706eb-138">Move all Up replicas out of the node.</span></span> </para>
          <para>
                <span data-ttu-id="706eb-139">ステートレスなインスタンスのつまり、別のノードに別のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="706eb-139">For stateless instances this implies creating another instance on another node</span></span></para>
          <para>
                <span data-ttu-id="706eb-140">ステートフル サービス レプリカ置換レプリカがビルドされた別のノード (クラスターのための十分な容量がある) 場合</span><span class="sxs-lookup"><span data-stu-id="706eb-140">For replicas of stateful services a replacement replica is built on another node (if there is sufficient capacity in the cluster)</span></span></para>
          <para>
                <span data-ttu-id="706eb-141">パーティションの他のアクティブなセカンダリの交換を作成する前に、プライマリが行われます、レプリカがプライマリである場合は、</span><span class="sxs-lookup"><span data-stu-id="706eb-141">If the replica is a primary, some other active secondary of the partition is made the primary prior to creating the replacement</span></span></para>
          <para>
                <span data-ttu-id="706eb-142">ノードでのステートフルなレプリカは、状態をクリーンアップして終了する通知を受信します。</span><span class="sxs-lookup"><span data-stu-id="706eb-142">Stateful replicas on the node receive notifications to clean up their state and close.</span></span></para>
          <para>
                <span data-ttu-id="706eb-143">データなしのこのノードを取得した結果としてが失われることができます発生ように安全性チェックのサブセットを実行します。</span><span class="sxs-lookup"><span data-stu-id="706eb-143">Performs a subset of safety checks that ensure that as a result of taking this node down no data loss can occur.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="Restart" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeDeactivationIntent Restart = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeDeactivationIntent.Restart" />
      <MemberSignature Language="VB.NET" Value="Restart" />
      <MemberSignature Language="F#" Value="Restart = 2" Usage="System.Fabric.NodeDeactivationIntent.Restart" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="706eb-144">ノードを短時間の後に再起動するインテントであることを示します。</span><span class="sxs-lookup"><span data-stu-id="706eb-144">Indicates that the intent is for the node to be restarted after a short period of time.</span></span> <span data-ttu-id="706eb-145">Service Fabric は、ノードを再起動できません - この操作は Service Fabric の外部で行われます。</span><span class="sxs-lookup"><span data-stu-id="706eb-145">Service Fabric does not restart the node - this action is done outside of Service Fabric.</span></span></para>
        </summary>
        <remarks>
          <para>
                <span data-ttu-id="706eb-146">ノードがシャット ダウンするなど、OS 更新プログラムまたは Service Fabric コードの更新を実行します。</span><span class="sxs-lookup"><span data-stu-id="706eb-146">A node might be shut down, for example, to perform an OS update or a Service Fabric code update.</span></span> </para>
          <para>
                <span data-ttu-id="706eb-147">このモードでは Service Fabric を防ぎます新しいレプリカ ノードに配置されます。</span><span class="sxs-lookup"><span data-stu-id="706eb-147">In this mode, Service Fabric prevents new replicas from being placed on the node.</span></span> <span data-ttu-id="706eb-148">さらに、Service Fabric は、次のアクションを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="706eb-148">Additionally, Service Fabric takes the following actions:</span></span> </para>
          <para>
                <span data-ttu-id="706eb-149">配置とリソースのターゲット ノードで負荷分散を無効にします。</span><span class="sxs-lookup"><span data-stu-id="706eb-149">Disable Placement and Resource balancing on the target node</span></span></para>
          <para>
                <span data-ttu-id="706eb-150">安全性チェックを実行します。</span><span class="sxs-lookup"><span data-stu-id="706eb-150">Performs safety checks.</span></span> <span data-ttu-id="706eb-151"><see cref="F:System.Fabric.SafetyCheckKind.WaitForPrimaryPlacement" />この目的の安全性チェックは実行されません。</span><span class="sxs-lookup"><span data-stu-id="706eb-151">The <see cref="F:System.Fabric.SafetyCheckKind.WaitForPrimaryPlacement" /> safety check is not performed for this intent.</span></span> </para>
          <para>
                <span data-ttu-id="706eb-152">すべてのレプリカと、ノードで実行されているインスタンスを閉じます。</span><span class="sxs-lookup"><span data-stu-id="706eb-152">Close all replicas and instances running on the node.</span></span></para>
          <para>
                <span data-ttu-id="706eb-153">注: レプリカとインスタンスが閉じられると、Service Fabric は事後対応的作成ステートフル揮発性サービスとステートレス サービスのレプリカを置換します。</span><span class="sxs-lookup"><span data-stu-id="706eb-153">NOTE: Once replicas and instances are closed, Service Fabric will reactively create replacements for replicas of stateful volatile services and stateless services.</span></span> </para>
          <para>
                <span data-ttu-id="706eb-154">新しいレプリカは、Persisted レプリカ ノード上で<b>いない</b>という意図がこのノードを再起動して、再起動後に永続的な状態を回復するために構築します。</span><span class="sxs-lookup"><span data-stu-id="706eb-154">For Persisted replicas on the node, new replicas are <b>not</b> be built, because the intention is to restart this node and to recover the persistent state after the restart.</span></span> <span data-ttu-id="706eb-155">ノードがアクティブになると、レプリカが開かれます。</span><span class="sxs-lookup"><span data-stu-id="706eb-155">The replicas are opened once the node is activated.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>