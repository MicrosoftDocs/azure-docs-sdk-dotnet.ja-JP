<Type Name="DeployedServicePackagesHealthEvaluation" FullName="System.Fabric.Health.DeployedServicePackagesHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackagesHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackagesHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackagesHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackagesHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type DeployedServicePackagesHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>現在の集計された正常性状態の影響を受ける各異常な展開済みサービス パッケージの正常性評価を含む、展開済みサービス パッケージの正常性評価を表します。 いずれかが配置されたアプリケーションの正常性と、集計された正常性状態を評価するときに返される<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackagesHealthEvaluation.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="System.Fabric.Health.DeployedServicePackagesHealthEvaluation.TotalCount" />
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
          <para>Health store に配置したアプリケーションの展開済みサービス パッケージの合計数を取得します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Int64" />の合計数を表す health store に配置されたアプリケーションのサービス パッケージを展開します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackagesHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.DeployedServicePackagesHealthEvaluation.UnhealthyEvaluations" />
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
          <para>集計された正常性状態を原因となった異常な評価の一覧を取得します。 すべての異常が含まれています<see cref="T:System.Fabric.Health.DeployedServicePackageHealthEvaluation" />集計された正常性の影響を受けることです。</para>
        </summary>
        <value>
          <para>現在の集計された正常性状態を原因となった異常な評価。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>