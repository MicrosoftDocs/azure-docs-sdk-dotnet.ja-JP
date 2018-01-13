<Type Name="ServiceHealth" FullName="System.Fabric.Health.ServiceHealth">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ServiceHealth = class&#xA;    inherit EntityHealth" />
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
      <para>によって返されるように、サービスのヘルスをについて説明します<see cref="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.ServiceHealth.HealthStatistics" />
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
            パーティションとレプリカの数が、に関する情報を含むサービス正常性の統計を取得<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            </summary>
        <value>サービス正常性の統計。</value>
        <remarks>
          <para>
            サービスの状態の統計はパーティションの数に関する情報を格納し、レプリカがで<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            クエリを返す場合 null または空にすることできます、<see cref="T:System.Fabric.Health.ServiceHealth" />指定<see cref="T:System.Fabric.Health.ServiceHealthStatisticsFilter" />正常性の統計情報を除外します。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthState&gt; PartitionHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.PartitionHealthState&gt; PartitionHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealth.PartitionHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionHealthStates As IList(Of PartitionHealthState)" />
      <MemberSignature Language="F#" Value="member this.PartitionHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthState&gt;" Usage="System.Fabric.Health.ServiceHealth.PartitionHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>現在のサービスのパーティションの正常性状態を取得します。</para>
        </summary>
        <value>
          <para>現在のサービスのパーティションの正常性の状態。</para>
        </value>
        <remarks>
          <para>その点をパーティション分割のみ、 <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.PartitionsFilter" /> (指定した場合) が返されます。 入力のフィルターが指定されていない場合は、すべてのパーティションが返されます。</para>
          <para>すべてのパーティションを評価すると、集計されたサービスの正常性を決定します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealth.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Health.ServiceHealth.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス正常性エンティティを一意に識別するサービス名を取得します。</para>
        </summary>
        <value>
          <para>サービス正常性エンティティを一意に識別するサービスの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealth.ToString " />
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
            文字列表現を取得、<see cref="T:System.Fabric.Health.ServiceHealth" />です。
            </summary>
        <returns><see cref="T:System.Fabric.Health.ServiceHealth" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>