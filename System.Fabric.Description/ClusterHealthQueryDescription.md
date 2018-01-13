<Type Name="ClusterHealthQueryDescription" FullName="System.Fabric.Description.ClusterHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ClusterHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ClusterHealthQueryDescription = class" />
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
      <para>取得するためのクエリの入力を提供<see cref="T:System.Fabric.Health.ClusterHealth" />です。 <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" /> で使用されます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterHealthQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthPolicyMap As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicyMap : System.Fabric.Health.ApplicationHealthPolicyMap" Usage="System.Fabric.Description.ClusterHealthQueryDescription.ApplicationHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>クラスターからのアプリケーションの正常性を評価するために使用するアプリケーションの正常性ポリシーを取得します。 各エントリは、アプリケーションの名前をキーとして、および値を指定します、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />アプリケーションの正常性を評価するために使用します。</para>
        </summary>
        <value>
          <para>アプリケーションの正常性ポリシーは、クラスターからのアプリケーションの正常性を評価するために使用します。</para>
        </value>
        <remarks>
          <para>マップでは、アプリケーションが指定されていない場合、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />見つかった評価のためのアプリケーションでマニフェストが使用されます。 マップは、既定では空です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthStatesFilter ApplicationsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthStatesFilter ApplicationsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationsFilter As ApplicationHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.ApplicationsFilter : System.Fabric.Health.ApplicationHealthStatesFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>フィルター設定を取得または<see cref="T:System.Fabric.Health.ApplicationHealthState" />子。 フィルターに一致する子のみが返されます。</para>
        </summary>
        <value>
          <para>フィルター<see cref="T:System.Fabric.Health.ApplicationHealthState" />子。</para>
        </value>
        <remarks>
          <para> フィルターに一致するアプリケーションのみが返されます。 すべてのアプリケーションは、集計されたクラスターの正常性状態の評価に使用されます。
            フィルターが指定されていない場合は、クラスターのすべてのアプリケーションが返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.EventsFilter" />
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
          <para>取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />クラスターに報告します。</para>
        </summary>
        <value>
          <para>コレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />クラスターに報告します。</para>
        </value>
        <remarks>
          <para> フィルターに一致するイベントのみが返されます。 すべてのイベントは、集計されたクラスターの正常性状態の評価に使用されます。
            フィルターが指定されていない場合は、すべてのイベントが返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定、<see cref="T:System.Fabric.Health.ClusterHealthPolicy" />クラスターの正常性を評価するために使用します。 ポリシーは、クラスターおよびノードの集計された正常性状態に報告されるイベントの集計された正常性状態の評価に使用されます。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.ClusterHealthPolicy" />クラスターの正常性を評価するために使用します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As ClusterHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.ClusterHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または正常性の統計情報のフィルターを設定します。
            </summary>
        <value>正常性の統計情報のフィルターです。</value>
        <remarks>
          <para>
            正常性の統計情報のフィルター コントロールかどうか、<see cref="T:System.Fabric.Health.ClusterHealth" />によって返される、クエリには、クラスターの状態の統計が含まれています。 指定しない場合、統計情報が含まれます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.NodeHealthStatesFilter NodesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.NodeHealthStatesFilter NodesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property NodesFilter As NodeHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.NodesFilter : System.Fabric.Health.NodeHealthStatesFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.NodeHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>フィルター設定を取得または<see cref="T:System.Fabric.Health.NodeHealthState" />子。 フィルターに一致する子のみが返されます。</para>
        </summary>
        <value>
          <para>フィルター<see cref="T:System.Fabric.Health.NodeHealthState" />子。</para>
        </value>
        <remarks>
          <para> フィルターに一致するノードだけが返されます。 すべてのノードは、集計されたクラスターの正常性状態の評価に使用されます。
            フィルターが指定されていない場合は、すべてのクラスター ノードが返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthQueryDescription.ToString " />
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