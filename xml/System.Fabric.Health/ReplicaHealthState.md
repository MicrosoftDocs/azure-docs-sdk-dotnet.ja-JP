<Type Name="ReplicaHealthState" FullName="System.Fabric.Health.ReplicaHealthState">
  <TypeSignature Language="C#" Value="public abstract class ReplicaHealthState : System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ReplicaHealthState extends System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealthState" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ReplicaHealthState&#xA;Inherits EntityHealthState" />
  <TypeSignature Language="F#" Value="type ReplicaHealthState = class&#xA;    inherit EntityHealthState" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealthState</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.StatefulServiceReplicaHealthState))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.StatelessServiceInstanceHealthState))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="08fec-101">ステートフル サービス レプリカまたはステートレス サービス インスタンスのヘルス状態の基本クラスを表します。</span><span class="sxs-lookup"><span data-stu-id="08fec-101">Represents a base class for stateful service replica or stateless service instance health state.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ReplicaHealthState (System.Fabric.Query.ServiceKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Query.ServiceKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthState.#ctor(System.Fabric.Query.ServiceKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kind As ServiceKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.ReplicaHealthState : System.Fabric.Query.ServiceKind -&gt; System.Fabric.Health.ReplicaHealthState" Usage="new System.Fabric.Health.ReplicaHealthState kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.Query.ServiceKind" />
      </Parameters>
      <Docs>
        <param name="kind"><span data-ttu-id="08fec-102">ステートフルなまたはステートレス サービスは、かどうかを示すサービスの種類。</span><span class="sxs-lookup"><span data-stu-id="08fec-102">The service kind, which shows whether the service is stateful or stateless.</span></span></param>
        <summary>
          <para><span data-ttu-id="08fec-103"><see cref="T:System.Fabric.Health.ReplicaHealthState" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="08fec-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.ReplicaHealthState" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public long Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Id" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthState.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Long" />
      <MemberSignature Language="F#" Value="member this.Id : int64" Usage="System.Fabric.Health.ReplicaHealthState.Id" />
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
          <para><span data-ttu-id="08fec-104">ステートフルなレプリカ ID またはステートレス サービス インスタンス ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="08fec-104">Gets the stateful replica ID or stateless service instance ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="08fec-105">レプリカまたはインスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="08fec-105">The replica or instance ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthState.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Health.ReplicaHealthState.Kind" />
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
          <para><span data-ttu-id="08fec-106">サービス レプリカの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="08fec-106">Gets the kind of the service replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="08fec-107">サービス レプリカの種類。</span><span class="sxs-lookup"><span data-stu-id="08fec-107">The service replica kind.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthState.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.ReplicaHealthState.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="08fec-108">パーティション ID を取得します</span><span class="sxs-lookup"><span data-stu-id="08fec-108">Gets the partition ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="08fec-109">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="08fec-109">The partition ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthState.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="replicaHealthState.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="08fec-110">レプリカのヘルス状態について説明する文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="08fec-110">Creates a string description of the replica health state.</span></span>
            </summary>
        <returns><span data-ttu-id="08fec-111">ヘルス状態の説明の文字列を指定します。</span><span class="sxs-lookup"><span data-stu-id="08fec-111">String description of the health state.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>