<Type Name="ServiceReplicaStatus" FullName="System.Fabric.Query.ServiceReplicaStatus">
  <TypeSignature Language="C#" Value="public enum ServiceReplicaStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServiceReplicaStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ServiceReplicaStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServiceReplicaStatus" />
  <TypeSignature Language="F#" Value="type ServiceReplicaStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="1c8d3-101">レプリカの状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="1c8d3-101">Specifies the status of the replica.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Down">
      <MemberSignature Language="C#" Value="Down" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Down = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Down" />
      <MemberSignature Language="VB.NET" Value="Down" />
      <MemberSignature Language="F#" Value="Down = 4" Usage="System.Fabric.Query.ServiceReplicaStatus.Down" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1c8d3-102">レプリカがダウンしています。</span><span class="sxs-lookup"><span data-stu-id="1c8d3-102">Replica is down.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Dropped">
      <MemberSignature Language="C#" Value="Dropped" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Dropped = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Dropped" />
      <MemberSignature Language="VB.NET" Value="Dropped" />
      <MemberSignature Language="F#" Value="Dropped = 5" Usage="System.Fabric.Query.ServiceReplicaStatus.Dropped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1c8d3-103">レプリカが削除されます。</span><span class="sxs-lookup"><span data-stu-id="1c8d3-103">Replica is dropped.</span></span> <span data-ttu-id="1c8d3-104">これはレプリカ セットから、レプリカが削除されていることを意味します。</span><span class="sxs-lookup"><span data-stu-id="1c8d3-104">This means that the replica has been removed from the replica set.</span></span> <span data-ttu-id="1c8d3-105">場合は、永続化の状態が削除されました。</span><span class="sxs-lookup"><span data-stu-id="1c8d3-105">If it is persisted, its state has been deleted.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="InBuild">
      <MemberSignature Language="C#" Value="InBuild" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus InBuild = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.InBuild" />
      <MemberSignature Language="VB.NET" Value="InBuild" />
      <MemberSignature Language="F#" Value="InBuild = 1" Usage="System.Fabric.Query.ServiceReplicaStatus.InBuild" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1c8d3-106">レプリカをビルドしています。</span><span class="sxs-lookup"><span data-stu-id="1c8d3-106">Replica is being built.</span></span> <span data-ttu-id="1c8d3-107">これは、プライマリ レプリカがこのレプリカを実行していることを意味します。</span><span class="sxs-lookup"><span data-stu-id="1c8d3-107">This means that a primary replica is seeding this replica.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Query.ServiceReplicaStatus.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1c8d3-108">無効。</span><span class="sxs-lookup"><span data-stu-id="1c8d3-108">Invalid.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Ready">
      <MemberSignature Language="C#" Value="Ready" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Ready = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Ready" />
      <MemberSignature Language="VB.NET" Value="Ready" />
      <MemberSignature Language="F#" Value="Ready = 3" Usage="System.Fabric.Query.ServiceReplicaStatus.Ready" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1c8d3-109">レプリカ準備ができました。</span><span class="sxs-lookup"><span data-stu-id="1c8d3-109">Replica is ready.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Standby">
      <MemberSignature Language="C#" Value="Standby" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ServiceReplicaStatus Standby = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ServiceReplicaStatus.Standby" />
      <MemberSignature Language="VB.NET" Value="Standby" />
      <MemberSignature Language="F#" Value="Standby = 2" Usage="System.Fabric.Query.ServiceReplicaStatus.Standby" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="1c8d3-110">レプリカが再起動しは、スタンバイ状態として保持されています。</span><span class="sxs-lookup"><span data-stu-id="1c8d3-110">The replica has restarted and it is being kept as a standby.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>