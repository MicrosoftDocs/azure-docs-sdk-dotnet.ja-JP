<Type Name="ReplicaHealth" FullName="System.Fabric.Health.ReplicaHealth">
  <TypeSignature Language="C#" Value="public abstract class ReplicaHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ReplicaHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealth" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ReplicaHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ReplicaHealth = class&#xA;    inherit EntityHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.StatefulServiceReplicaHealth))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Health.StatelessServiceInstanceHealth))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="ee55d-101">によって返されるステートフル サービス レプリカまたはステートレス サービス インスタンスの正常性を示します<see cref="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription)" />です。</span><span class="sxs-lookup"><span data-stu-id="ee55d-101">Describes the health of a stateful service replica or a stateless service instance as returned by <see cref="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public long Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Id" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealth.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Long" />
      <MemberSignature Language="F#" Value="member this.Id : int64" Usage="System.Fabric.Health.ReplicaHealth.Id" />
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
          <para><span data-ttu-id="ee55d-102">ステートフルなレプリカ ID またはステートレス サービス インスタンス ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="ee55d-102">Gets the stateful replica ID or the stateless service instance ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ee55d-103">ステートフルなレプリカ ID またはステートレスなインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="ee55d-103">The stateful replica ID or stateless instance ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealth.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Health.ReplicaHealth.Kind" />
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
          <para><span data-ttu-id="ee55d-104">ステートレスまたはステートフルなレプリカの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="ee55d-104">Gets the kind of the replica, either stateless or stateful.</span></span> <span data-ttu-id="ee55d-105">これに基づき、レプリカの正常性に変換できるか<see cref="T:System.Fabric.Health.StatefulServiceReplicaHealth" />または<see cref="T:System.Fabric.Health.StatelessServiceInstanceHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="ee55d-105">Based on this, the replica health can be converted to either <see cref="T:System.Fabric.Health.StatefulServiceReplicaHealth" /> or <see cref="T:System.Fabric.Health.StatelessServiceInstanceHealth" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ee55d-106">サービスの種類、レプリカがステートフルなまたはステートレスかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="ee55d-106">The service kind, which indicates whether the replica is stateful or stateless.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealth.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.ReplicaHealth.PartitionId" />
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
          <para><span data-ttu-id="ee55d-107">パーティション識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="ee55d-107">Gets the partition identifier.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ee55d-108">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="ee55d-108">The partition ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="replicaHealth.ToString " />
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
            <span data-ttu-id="ee55d-109">文字列表現を取得、<see cref="T:System.Fabric.Health.ReplicaHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="ee55d-109">Gets a string representation of the <see cref="T:System.Fabric.Health.ReplicaHealth" />.</span></span>
            </summary>
        <returns><span data-ttu-id="ee55d-110"><see cref="T:System.Fabric.Health.ReplicaHealth" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="ee55d-110">A string representation of the <see cref="T:System.Fabric.Health.ReplicaHealth" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>