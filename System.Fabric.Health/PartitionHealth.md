<Type Name="PartitionHealth" FullName="System.Fabric.Health.PartitionHealth">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type PartitionHealth = class&#xA;    inherit EntityHealth" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealth</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>によって返されるパーティションの正常性を説明<see cref="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.PartitionHealth.HealthStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            レプリカの数が、に関する情報を含むパーティションの正常性統計を取得<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            </summary>
        <value>パーティションのヘルスの統計情報。</value>
        <remarks>
          <para>
            パーティションの状態の統計情報にはレプリカの数が、 <see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            クエリを返す場合 null または空にすることできます、<see cref="T:System.Fabric.Health.PartitionHealth" />指定<see cref="T:System.Fabric.Health.PartitionHealthStatisticsFilter" />正常性の統計情報を除外します。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealth.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.PartitionHealth.PartitionId" />
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
          <para>パーティションを一意に識別する、パーティション ID を取得します。</para>
        </summary>
        <value>
          <para>パーティションの id。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthState&gt; ReplicaHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ReplicaHealthState&gt; ReplicaHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealth.ReplicaHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaHealthStates As IList(Of ReplicaHealthState)" />
      <MemberSignature Language="F#" Value="member this.ReplicaHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthState&gt;" Usage="System.Fabric.Health.PartitionHealth.ReplicaHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Health store に、検出されるように、現在のパーティションのレプリカの正常性状態を取得します。</para>
        </summary>
        <value>
          <para>Health store に検出されるよう、現在のパーティションのレプリカです。</para>
        </value>
        <remarks>To be added.</remarks>
        <para>すべてのレプリカを評価すると、集計されたパーティションの正常性を決定します。</para>
        <para>尊重レプリカのみ、 <see cref="P:System.Fabric.Description.PartitionHealthQueryDescription.ReplicasFilter" /> (指定した場合) が返されます。 入力のフィルターが指定されていない場合は、すべてのレプリカが返されます。</para>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealth.ToString " />
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
            文字列表現を取得、<see cref="T:System.Fabric.Health.PartitionHealth" />です。
            </summary>
        <returns><see cref="T:System.Fabric.Health.PartitionHealth" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>