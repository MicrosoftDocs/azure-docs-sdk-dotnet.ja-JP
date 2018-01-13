<Type Name="PartitionHealthQueryDescription" FullName="System.Fabric.Description.PartitionHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.PartitionHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type PartitionHealthQueryDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>説明を取得するためのクエリ入力<see cref="T:System.Fabric.Health.PartitionHealth" />です。 <see cref="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription)" /> で使用されます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionHealthQueryDescription (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PartitionHealthQueryDescription.#ctor(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionId As Guid)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.PartitionHealthQueryDescription : Guid -&gt; System.Fabric.Description.PartitionHealthQueryDescription" Usage="new System.Fabric.Description.PartitionHealthQueryDescription partitionId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>パーティションの識別子です。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Description.PartitionHealthQueryDescription" /> クラスの新しいインスタンスを生成します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.EventsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEventsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />パーティションに報告します。 フィルターに一致するイベントのみが返されます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.HealthEventsFilter" />返されるイベントをフィルター処理するために使用します。</para>
        </value>
        <remarks>
          <para> フィルターに一致するイベントのみが返されます。 すべてのイベントは、パーティションの集計された正常性状態の評価に使用されます。
            フィルターが指定されていない場合は、すべてのイベントが返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />正常性を評価するために使用します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />パーティションの正常性を評価するために使用します。</para>
        </value>
        <remarks>指定されていない場合、正常性ストアは、パーティションの正常性を評価する親アプリケーションのアプリケーションの正常性ポリシーを使用します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.PartitionHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.PartitionHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As PartitionHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.PartitionHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.PartitionHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または正常性の統計情報のフィルターを設定します。
            </summary>
        <value>正常性の統計情報のフィルターです。</value>
        <remarks>
          <para>
            正常性の統計情報のフィルター コントロールかどうか、<see cref="T:System.Fabric.Health.PartitionHealth" />によって返される、クエリには、パーティションの正常性の統計情報が含まれています。 指定しない場合、統計情報が含まれます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Description.PartitionHealthQueryDescription.PartitionId" />
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
          <para>取得またはパーティションの識別子を設定します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Guid" />パーティションの id を表すです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicasFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ReplicaHealthStatesFilter ReplicasFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ReplicaHealthStatesFilter ReplicasFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.ReplicasFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicasFilter As ReplicaHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.ReplicasFilter : System.Fabric.Health.ReplicaHealthStatesFilter with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.ReplicasFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ReplicaHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>フィルター設定を取得または<see cref="T:System.Fabric.Health.ReplicaHealthState" />子。 フィルターに一致する子のみが返されます。 すべての子は、パーティションの集計された正常性状態の評価に使用されます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.ReplicaHealthStatesFilter" />返されたレプリカをフィルター処理するために使用します。</para>
        </value>
        <remarks>
          <para> フィルターに一致する子のみが返されます。 すべての子は、パーティションの集計された正常性状態の評価に使用されます。
            フィルターが指定されていない場合は、パーティションのすべての子が返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PartitionHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthQueryDescription.ToString " />
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
            正常性クエリの説明の文字列表現を取得します。
            </summary>
        <returns>正常性クエリの説明の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>