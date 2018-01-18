<Type Name="ServicePartitionStatus" FullName="System.Fabric.Query.ServicePartitionStatus">
  <TypeSignature Language="C#" Value="public enum ServicePartitionStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServicePartitionStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServicePartitionStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServicePartitionStatus" />
  <TypeSignature Language="F#" Value="type ServicePartitionStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="6ebf8-101">サービス パーティションの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="6ebf8-101">Specifies the service partition status.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus Deleting = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 5" Usage="System.Fabric.Query.ServicePartitionStatus.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6ebf8-102">パーティションが削除されます。</span><span class="sxs-lookup"><span data-stu-id="6ebf8-102">Partition is getting deleted.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="InQuorumLoss">
      <MemberSignature Language="C#" Value="InQuorumLoss" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus InQuorumLoss = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.InQuorumLoss" />
      <MemberSignature Language="VB.NET" Value="InQuorumLoss" />
      <MemberSignature Language="F#" Value="InQuorumLoss = 3" Usage="System.Fabric.Query.ServicePartitionStatus.InQuorumLoss" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6ebf8-103">パーティションはクォーラム損失です。</span><span class="sxs-lookup"><span data-stu-id="6ebf8-103">Partition is in quorum loss.</span></span> <span data-ttu-id="6ebf8-104">つまり、クォーラムに参加しているレプリカの MinReplicaSetSize 数未満です。</span><span class="sxs-lookup"><span data-stu-id="6ebf8-104">This means that less than MinReplicaSetSize number of replicas are participating in quorum.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Query.ServicePartitionStatus.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6ebf8-105">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="6ebf8-105">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NotReady">
      <MemberSignature Language="C#" Value="NotReady" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus NotReady = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.NotReady" />
      <MemberSignature Language="VB.NET" Value="NotReady" />
      <MemberSignature Language="F#" Value="NotReady = 2" Usage="System.Fabric.Query.ServicePartitionStatus.NotReady" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6ebf8-106">パーティション準備ができていません。</span><span class="sxs-lookup"><span data-stu-id="6ebf8-106">Partition is not ready.</span></span> <span data-ttu-id="6ebf8-107">他の状態のいずれにも該当する場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="6ebf8-107">This is returned when none of the other states apply.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Ready">
      <MemberSignature Language="C#" Value="Ready" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus Ready = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.Ready" />
      <MemberSignature Language="VB.NET" Value="Ready" />
      <MemberSignature Language="F#" Value="Ready = 1" Usage="System.Fabric.Query.ServicePartitionStatus.Ready" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
                <span data-ttu-id="6ebf8-108">パーティション準備ができました。</span><span class="sxs-lookup"><span data-stu-id="6ebf8-108">Partition is ready.</span></span></para>
          <para>
                <span data-ttu-id="6ebf8-109">ステートレスなサービスが 1 つのレプリカを</span><span class="sxs-lookup"><span data-stu-id="6ebf8-109">For stateless services there is one up replica</span></span></para>
          <para>
                <span data-ttu-id="6ebf8-110">ステートフル サービスの準備がレプリカの数より大きいまたは等しい、<see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /></span><span class="sxs-lookup"><span data-stu-id="6ebf8-110">For stateful services the number of ready replicas is greater than or equal to the <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /></span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Reconfiguring">
      <MemberSignature Language="C#" Value="Reconfiguring" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServicePartitionStatus Reconfiguring = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServicePartitionStatus.Reconfiguring" />
      <MemberSignature Language="VB.NET" Value="Reconfiguring" />
      <MemberSignature Language="F#" Value="Reconfiguring = 4" Usage="System.Fabric.Query.ServicePartitionStatus.Reconfiguring" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6ebf8-111">パーティションは再構成を実行中です。</span><span class="sxs-lookup"><span data-stu-id="6ebf8-111">Partition is undergoing a reconfiguration.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>