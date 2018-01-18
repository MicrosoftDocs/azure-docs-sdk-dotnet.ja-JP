<Type Name="Partition" FullName="System.Fabric.Query.Partition">
  <TypeSignature Language="C#" Value="public abstract class Partition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Partition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.Partition" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Partition" />
  <TypeSignature Language="F#" Value="type Partition = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatelessServicePartition))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatefulServicePartition))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="3e66b-101">パーティションを表します。</span><span class="sxs-lookup"><span data-stu-id="3e66b-101">Represents a partition.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Partition (System.Fabric.Query.ServiceKind serviceKind, System.Fabric.ServicePartitionInformation partitionInformation, System.Fabric.Health.HealthState healthState, System.Fabric.Query.ServicePartitionStatus partitionStatus);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Query.ServiceKind serviceKind, class System.Fabric.ServicePartitionInformation partitionInformation, valuetype System.Fabric.Health.HealthState healthState, valuetype System.Fabric.Query.ServicePartitionStatus partitionStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.Partition.#ctor(System.Fabric.Query.ServiceKind,System.Fabric.ServicePartitionInformation,System.Fabric.Health.HealthState,System.Fabric.Query.ServicePartitionStatus)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Query.Partition : System.Fabric.Query.ServiceKind * System.Fabric.ServicePartitionInformation * System.Fabric.Health.HealthState * System.Fabric.Query.ServicePartitionStatus -&gt; System.Fabric.Query.Partition" Usage="new System.Fabric.Query.Partition (serviceKind, partitionInformation, healthState, partitionStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceKind" Type="System.Fabric.Query.ServiceKind" />
        <Parameter Name="partitionInformation" Type="System.Fabric.ServicePartitionInformation" />
        <Parameter Name="healthState" Type="System.Fabric.Health.HealthState" />
        <Parameter Name="partitionStatus" Type="System.Fabric.Query.ServicePartitionStatus" />
      </Parameters>
      <Docs>
        <param name="serviceKind">
          <para><span data-ttu-id="3e66b-102">パーティションの種類</span><span class="sxs-lookup"><span data-stu-id="3e66b-102">The type of the partition</span></span></para>
        </param>
        <param name="partitionInformation">
          <para><span data-ttu-id="3e66b-103">パーティション情報</span><span class="sxs-lookup"><span data-stu-id="3e66b-103">The Partition Information</span></span></para>
        </param>
        <param name="healthState">
          <para><span data-ttu-id="3e66b-104">パーティションの正常性状態</span><span class="sxs-lookup"><span data-stu-id="3e66b-104">Health State of the partition</span></span></para>
        </param>
        <param name="partitionStatus">
          <para><span data-ttu-id="3e66b-105">パーティションの状態</span><span class="sxs-lookup"><span data-stu-id="3e66b-105">Status of the partition</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3e66b-106">パーティションの新しいインスタンスを初期化します</span><span class="sxs-lookup"><span data-stu-id="3e66b-106">Initializes a new instance of the partition</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Partition.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Query.Partition.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3e66b-107">パーティションのヘルス状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e66b-107">Gets the health state of the partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3e66b-108">パーティションの正常性状態。</span><span class="sxs-lookup"><span data-stu-id="3e66b-108">The health state of the partition.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionInformation">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation PartitionInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation PartitionInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Partition.PartitionInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionInformation As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.PartitionInformation : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.Query.Partition.PartitionInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3e66b-109">パーティション情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e66b-109">Gets the partition information.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3e66b-110">パーティションの情報です。</span><span class="sxs-lookup"><span data-stu-id="3e66b-110">The information of the partition.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServicePartitionStatus PartitionStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServicePartitionStatus PartitionStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Partition.PartitionStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionStatus As ServicePartitionStatus" />
      <MemberSignature Language="F#" Value="member this.PartitionStatus : System.Fabric.Query.ServicePartitionStatus" Usage="System.Fabric.Query.Partition.PartitionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServicePartitionStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3e66b-111">パーティションの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e66b-111">Gets the status of the partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3e66b-112">パーティションの状態です。</span><span class="sxs-lookup"><span data-stu-id="3e66b-112">The status of the partition.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind ServiceKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind ServiceKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Partition.ServiceKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceKind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.ServiceKind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Query.Partition.ServiceKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3e66b-113">パーティション (ステートフル/ステートレス) の種類</span><span class="sxs-lookup"><span data-stu-id="3e66b-113">The type of the partition (Stateful/Stateless)</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3e66b-114"><see cref="T:System.Fabric.Query.ServiceKind" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="3e66b-114">Returns <see cref="T:System.Fabric.Query.ServiceKind" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>