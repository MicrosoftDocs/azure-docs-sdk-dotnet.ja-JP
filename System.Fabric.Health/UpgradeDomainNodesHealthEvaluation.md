<Type Name="UpgradeDomainNodesHealthEvaluation" FullName="System.Fabric.Health.UpgradeDomainNodesHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class UpgradeDomainNodesHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UpgradeDomainNodesHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.UpgradeDomainNodesHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UpgradeDomainNodesHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type UpgradeDomainNodesHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>現在の集計された正常性状態の影響を受ける各の異常なノードの正常性評価を含む、アップグレード ドメイン内のクラスター ノードの正常性評価を表します。
            いずれかがクラスターのアップグレードと、集計された正常性状態の中にクラスターの正常性を評価するときに返される<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainNodesHealthEvaluation.MaxPercentUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyNodes : byte" Usage="System.Fabric.Health.UpgradeDomainNodesHealthEvaluation.MaxPercentUnhealthyNodes" />
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
          <para>許容される異常なノードからの割合の最大値を取得、<see cref="T:System.Fabric.Health.ClusterHealthPolicy" />です。</para>
        </summary>
        <value>
          <para>許容される異常なノードの割合の最大値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainNodesHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.UpgradeDomainNodesHealthEvaluation.TotalCount" />
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
          <para>現在のアップグレード ドメイン内のノードの合計数を取得します。</para>
        </summary>
        <value>
          <para>現在のアップグレード ドメイン内のノードの合計数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainNodesHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.UpgradeDomainNodesHealthEvaluation.UnhealthyEvaluations" />
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
          <para>集計された正常性状態を原因となった異常な評価の一覧を取得します。
            すべての異常が含まれています<see cref="T:System.Fabric.Health.NodeHealthEvaluation" />集計された正常性の影響を受けることです。</para>
        </summary>
        <value>
          <para>現在の集計された正常性状態を原因となった異常な評価。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainName">
      <MemberSignature Language="C#" Value="public string UpgradeDomainName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeDomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.UpgradeDomainNodesHealthEvaluation.UpgradeDomainName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainName As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainName : string" Usage="System.Fabric.Health.UpgradeDomainNodesHealthEvaluation.UpgradeDomainName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ノードの正常性が評価される現在のアップグレード ドメインの名前を取得します。</para>
        </summary>
        <value>
          <para>アップグレード ドメインの名前です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>