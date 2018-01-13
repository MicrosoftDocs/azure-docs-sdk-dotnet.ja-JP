<Type Name="DeltaNodesCheckHealthEvaluation" FullName="System.Fabric.Health.DeltaNodesCheckHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class DeltaNodesCheckHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeltaNodesCheckHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeltaNodesCheckHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeltaNodesCheckHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type DeltaNodesCheckHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthEvaluation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>現在の集計された正常性状態の影響を受ける各の異常なノードの正常性評価を含む、デルタ ノード正常性評価を表します。 返されることがクラスターのアップグレード中に、クラスターの集計された正常性状態が<see cref="F:System.Fabric.Health.HealthState.Error" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BaselineErrorCount">
      <MemberSignature Language="C#" Value="public long BaselineErrorCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BaselineErrorCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeltaNodesCheckHealthEvaluation.BaselineErrorCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaselineErrorCount As Long" />
      <MemberSignature Language="F#" Value="member this.BaselineErrorCount : int64" Usage="System.Fabric.Health.DeltaNodesCheckHealthEvaluation.BaselineErrorCount" />
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
          <para>集計された正常性状態を持つノードの数を取得<see cref="F:System.Fabric.Health.HealthState.Error" />正常性をクラスターのアップグレードの先頭に格納します。</para>
        </summary>
        <value>
          <para>集計された正常性状態を持つノードの数<see cref="F:System.Fabric.Health.HealthState.Error" />正常性をクラスターのアップグレードの先頭に格納します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaselineTotalCount">
      <MemberSignature Language="C#" Value="public long BaselineTotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 BaselineTotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeltaNodesCheckHealthEvaluation.BaselineTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaselineTotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.BaselineTotalCount : int64" Usage="System.Fabric.Health.DeltaNodesCheckHealthEvaluation.BaselineTotalCount" />
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
          <para>クラスターのアップグレードの開始時の正常性ストア内のノードの合計数を取得します。</para>
        </summary>
        <value>
          <para>クラスターのアップグレードの開始時の正常性ストア内のノードの合計数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentDeltaUnhealthyNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeltaNodesCheckHealthEvaluation.MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentDeltaUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentDeltaUnhealthyNodes : byte" Usage="System.Fabric.Health.DeltaNodesCheckHealthEvaluation.MaxPercentDeltaUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>最大デルタの比率から異常なノードを取得、<see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />です。</para>
        </summary>
        <value>
          <para>最大デルタの割合異常なノードです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeltaNodesCheckHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.DeltaNodesCheckHealthEvaluation.TotalCount" />
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
          <para>Health store にノードの現在の合計数を取得します。</para>
        </summary>
        <value>
          <para>正常性ストア内のノードの現在の合計数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeltaNodesCheckHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.DeltaNodesCheckHealthEvaluation.UnhealthyEvaluations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>集計された正常性状態を原因となった異常な評価の一覧を取得します。 すべての異常が含まれています<see cref="T:System.Fabric.Health.NodeHealthEvaluation" />集計された正常性の影響を受けることです。</para>
        </summary>
        <value>
          <para>現在の集計された正常性状態を原因となった異常な評価の一覧を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>