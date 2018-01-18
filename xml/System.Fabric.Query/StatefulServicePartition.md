<Type Name="StatefulServicePartition" FullName="System.Fabric.Query.StatefulServicePartition">
  <TypeSignature Language="C#" Value="public sealed class StatefulServicePartition : System.Fabric.Query.Partition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServicePartition extends System.Fabric.Query.Partition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.StatefulServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServicePartition&#xA;Inherits Partition" />
  <TypeSignature Language="F#" Value="type StatefulServicePartition = class&#xA;    inherit Partition" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.Partition</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="bcee9-101">ステートフルなサービス パーティションを表します。</span><span class="sxs-lookup"><span data-stu-id="bcee9-101">Represents a stateful service partition.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LastQuorumLossDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LastQuorumLossDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LastQuorumLossDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.StatefulServicePartition.LastQuorumLossDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastQuorumLossDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LastQuorumLossDuration : TimeSpan" Usage="System.Fabric.Query.StatefulServicePartition.LastQuorumLossDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="bcee9-102">最後のクォーラムが失われる期間を取得します。</span><span class="sxs-lookup"><span data-stu-id="bcee9-102">Gets the last quorum loss duration.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="bcee9-103"><see cref="T:System.TimeSpan" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="bcee9-103">Returns <see cref="T:System.TimeSpan" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinReplicaSetSize">
      <MemberSignature Language="C#" Value="public long MinReplicaSetSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MinReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.StatefulServicePartition.MinReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinReplicaSetSize As Long" />
      <MemberSignature Language="F#" Value="member this.MinReplicaSetSize : int64" Usage="System.Fabric.Query.StatefulServicePartition.MinReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="bcee9-104">進行状況を保持するパーティションに対して許容される最小レプリカ設定サイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="bcee9-104">Gets the minimum replica set size allowed for the partition to keep making progress.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="bcee9-105"><see cref="T:System.Int64" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="bcee9-105">Returns <see cref="T:System.Int64" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryEpoch">
      <MemberSignature Language="C#" Value="public System.Fabric.Epoch PrimaryEpoch { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Epoch PrimaryEpoch" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.StatefulServicePartition.PrimaryEpoch" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryEpoch As Epoch" />
      <MemberSignature Language="F#" Value="member this.PrimaryEpoch : System.Fabric.Epoch" Usage="System.Fabric.Query.StatefulServicePartition.PrimaryEpoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Epoch</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="bcee9-106">レプリカに表示されるパーティションのエポックを取得します</span><span class="sxs-lookup"><span data-stu-id="bcee9-106">Gets the epoch of the partition as seen by the replica</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="bcee9-107">パーティションのエポック</span><span class="sxs-lookup"><span data-stu-id="bcee9-107">The epoch of the partition</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplicaSetSize">
      <MemberSignature Language="C#" Value="public long TargetReplicaSetSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TargetReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.StatefulServicePartition.TargetReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetReplicaSetSize As Long" />
      <MemberSignature Language="F#" Value="member this.TargetReplicaSetSize : int64" Usage="System.Fabric.Query.StatefulServicePartition.TargetReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="bcee9-108">ターゲット レプリカ セットのサイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="bcee9-108">Gets the target replica set size.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="bcee9-109"><see cref="T:System.Int64" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="bcee9-109">Returns <see cref="T:System.Int64" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>