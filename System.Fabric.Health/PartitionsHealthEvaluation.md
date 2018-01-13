<Type Name="PartitionsHealthEvaluation" FullName="System.Fabric.Health.PartitionsHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class PartitionsHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionsHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionsHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionsHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type PartitionsHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>現在の集計された正常性状態に影響を与える問題のある各パーティションの正常性評価を含む、サービスのパーティションの正常性評価を表します。 いずれかのサービスのヘルスと、集計された正常性状態の評価が返されることが<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxPercentUnhealthyPartitionsPerService">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyPartitionsPerService { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyPartitionsPerService" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionsHealthEvaluation.MaxPercentUnhealthyPartitionsPerService" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxPercentUnhealthyPartitionsPerService As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyPartitionsPerService : byte" Usage="System.Fabric.Health.PartitionsHealthEvaluation.MaxPercentUnhealthyPartitionsPerService" />
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
          <para>許容される異常なパーティションからのサービスごとの割合の最大値を取得、<see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" />です。</para>
        </summary>
        <value>
          <para>サービスごとの問題のあるパーティションの割合が最大です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionsHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.PartitionsHealthEvaluation.TotalCount" />
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
          <para>正常性ストアからサービスのパーティションの合計数を取得します。</para>
        </summary>
        <value>
          <para>サービスのパーティションの合計数。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionsHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.PartitionsHealthEvaluation.UnhealthyEvaluations" />
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
          <para>集計された正常性状態を原因となった異常な評価の一覧を取得します。 すべての異常が含まれています<see cref="T:System.Fabric.Health.PartitionHealthEvaluation" />集計された正常性の影響を受けることです。</para>
        </summary>
        <value>
          <para>現在の集計された正常性状態を原因となった異常な評価。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>