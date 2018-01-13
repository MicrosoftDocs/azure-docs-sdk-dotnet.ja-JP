<Type Name="ClusterHealth" FullName="System.Fabric.Health.ClusterHealth">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealth : System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealth extends System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealth" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealth&#xA;Inherits EntityHealth" />
  <TypeSignature Language="F#" Value="type ClusterHealth = class&#xA;    inherit EntityHealth" />
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
      <para>によって返される、クラスターの正常性を表す<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />です。
            集計されたクラスターのヘルス状態、アプリケーションのヘルス状態、ノードの正常性状態だけでなく正常性イベント、正常性評価および状態の統計が含まれます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthState&gt; ApplicationHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ApplicationHealthState&gt; ApplicationHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealth.ApplicationHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthStates As IList(Of ApplicationHealthState)" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthState&gt;" Usage="System.Fabric.Health.ClusterHealth.ApplicationHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ApplicationHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Health store にクラスターにあるアプリケーションの正常性状態を取得します。</para>
        </summary>
        <value>
          <para>Health store に検出されるようクラスター アプリケーションです。</para>
        </value>
        <remarks>To be added.</remarks>
        <para>すべてのアプリケーションを評価すると、集計されたクラスターの正常性を決定します。</para>
        <para>アプリケーションを尊重でのみ、 <see cref="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" /> (指定した場合) が返されます。 入力のフィルターが指定されていない場合は、すべてのアプリケーションが返されます。</para>
      </Docs>
    </Member>
    <Member MemberName="HealthStatistics">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStatistics HealthStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthStatistics HealthStatistics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealth.HealthStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthStatistics As HealthStatistics" />
      <MemberSignature Language="F#" Value="member this.HealthStatistics : System.Fabric.Health.HealthStatistics" Usage="System.Fabric.Health.ClusterHealth.HealthStatistics" />
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
            クラスター エンティティの数が、に関する情報を含むクラスター状態統計を取得<see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            </summary>
        <value>クラスターの正常性統計です。</value>
        <remarks>
          <para>
            クラスターの状態の統計情報にはクラスター エンティティの数が、 <see cref="F:System.Fabric.Health.HealthState.Ok" />、 <see cref="F:System.Fabric.Health.HealthState.Warning" />、および<see cref="F:System.Fabric.Health.HealthState.Error" />状態です。
            クエリを返す場合 null または空にすることできます、<see cref="T:System.Fabric.Health.ClusterHealth" />指定<see cref="T:System.Fabric.Health.ClusterHealthStatisticsFilter" />正常性の統計情報を除外します。
            既定では、正常性クエリには、システム アプリケーションに関する統計情報が含まれていない統計情報が返されます。 アプリケーション、サービス、パーティション、レプリカの数が、アプリケーションを展開し、展開済みサービス パッケージには、唯一のユーザー エンティティが含まれます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeHealthStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthState&gt; NodeHealthStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.NodeHealthState&gt; NodeHealthStates" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterHealth.NodeHealthStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeHealthStates As IList(Of NodeHealthState)" />
      <MemberSignature Language="F#" Value="member this.NodeHealthStates : System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthState&gt;" Usage="System.Fabric.Health.ClusterHealth.NodeHealthStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.NodeHealthState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Health store にクラスターにあるノードの正常性状態を取得します。</para>
        </summary>
        <value>
          <para>Health store に検出されるようクラスター ノードです。</para>
        </value>
        <remarks>To be added.</remarks>
        <para>すべてのノードを評価すると、集計されたクラスターの正常性を決定します。</para>
        <para>尊重いるノードに対してのみ、 <see cref="P:System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" /> (指定した場合) が返されます。 入力のフィルターが指定されていない場合は、すべてのノードが返されます。</para>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealth.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealth.ToString " />
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
            文字列表現を取得、<see cref="T:System.Fabric.Health.ClusterHealth" />です。
            </summary>
        <returns><see cref="T:System.Fabric.Health.ClusterHealth" /> の文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>