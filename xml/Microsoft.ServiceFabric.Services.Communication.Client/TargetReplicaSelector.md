<Type Name="TargetReplicaSelector" FullName="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector">
  <TypeSignature Language="C#" Value="public enum TargetReplicaSelector" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TargetReplicaSelector extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector" />
  <TypeSignature Language="VB.NET" Value="Public Enum TargetReplicaSelector" />
  <TypeSignature Language="F#" Value="type TargetReplicaSelector = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="a54d2-101">この列挙体は、どのように、ターゲット レプリカまたはインスタンスを選択する特定のパーティション用の通信チャネルを作成するときに指定します。</span><span class="sxs-lookup"><span data-stu-id="a54d2-101">This enumeration specifies how the target replica or instance should be chosen when creating a communication channel for a particular partition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a54d2-102">これには、この列挙型の既定のオプションを指定します。</span><span class="sxs-lookup"><span data-stu-id="a54d2-102">This specifies the default option for this enum.</span></span>
            <span data-ttu-id="a54d2-103">サービス パーティションがステートフルの場合は、プライマリ レプリカにその通信チャネルを確立する必要がありますを示します。</span><span class="sxs-lookup"><span data-stu-id="a54d2-103">If the service partition is stateful, this indicates that communication channel should be established to the primary replica.</span></span>
            <span data-ttu-id="a54d2-104">サービス パーティションがステートレスの場合は、ランダム ステートレスなインスタンスに通信チャネルを確立する必要があることを示します。</span><span class="sxs-lookup"><span data-stu-id="a54d2-104">If the service partition is stateless, this indicates that the communication channel should be established to a random stateless instance.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PrimaryReplica">
      <MemberSignature Language="C#" Value="PrimaryReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector PrimaryReplica = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica" />
      <MemberSignature Language="VB.NET" Value="PrimaryReplica" />
      <MemberSignature Language="F#" Value="PrimaryReplica = 0" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a54d2-105">これには、ステートフルなサービスのパーティションに対して、この列挙型の既定値を指定します。</span><span class="sxs-lookup"><span data-stu-id="a54d2-105">This specifies the default value of this enum for stateful service partitions.</span></span> <span data-ttu-id="a54d2-106">これは、プライマリ レプリカに通信チャネルを確立する必要があることを示します。</span><span class="sxs-lookup"><span data-stu-id="a54d2-106">This indicates that the communication channel should be established to the primary replica.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RandomInstance">
      <MemberSignature Language="C#" Value="RandomInstance" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector RandomInstance = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomInstance" />
      <MemberSignature Language="VB.NET" Value="RandomInstance" />
      <MemberSignature Language="F#" Value="RandomInstance = 0" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomInstance" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a54d2-107">これには、ステートレス サービスのパーティションに対して、この列挙型の既定値を指定します。</span><span class="sxs-lookup"><span data-stu-id="a54d2-107">This specifies the default value of this enum for stateless service partitions.</span></span> <span data-ttu-id="a54d2-108">これは、ランダムのステートレス インスタンスへの通信チャネルを確立する必要があることを示します。</span><span class="sxs-lookup"><span data-stu-id="a54d2-108">This indicates that the communication channel should be established to a random stateless instance.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RandomReplica">
      <MemberSignature Language="C#" Value="RandomReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector RandomReplica = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomReplica" />
      <MemberSignature Language="VB.NET" Value="RandomReplica" />
      <MemberSignature Language="F#" Value="RandomReplica = 1" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a54d2-109">ステートフルなサービス パーティション、これには、通信チャネルを確立できるので選択された任意のレプリカを示します - ランダムな (つまり、) プライマリまたはセカンダリ。</span><span class="sxs-lookup"><span data-stu-id="a54d2-109">For stateful service partitions, this indicates that communication channel can be established for to any replica chosen in random - (i.e) primary or secondary.</span></span>
            <span data-ttu-id="a54d2-110">これはステートレスなサービスのパーティションに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="a54d2-110">This is not valid for stateless service partitions</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RandomSecondaryReplica">
      <MemberSignature Language="C#" Value="RandomSecondaryReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector RandomSecondaryReplica = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomSecondaryReplica" />
      <MemberSignature Language="VB.NET" Value="RandomSecondaryReplica" />
      <MemberSignature Language="F#" Value="RandomSecondaryReplica = 2" Usage="Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.RandomSecondaryReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a54d2-111">ステートフルなサービスでは、パーティションの通信チャネルを確立できるのランダムに選択した任意のセカンダリ レプリカを示します。</span><span class="sxs-lookup"><span data-stu-id="a54d2-111">For stateful service partitions, this indicates that communication channel can be established for to any secondary replica chosen in random.</span></span>
            <span data-ttu-id="a54d2-112">これはステートレスなサービスのパーティションに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="a54d2-112">This is not valid for stateless service partitions</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>