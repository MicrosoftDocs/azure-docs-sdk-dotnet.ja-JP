<Type Name="SystemApplicationHealthEvaluation" FullName="System.Fabric.Health.SystemApplicationHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class SystemApplicationHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SystemApplicationHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.SystemApplicationHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SystemApplicationHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type SystemApplicationHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>ファブリックの正常性評価を表します。/正常性を評価する正常性ストアによって使用されるシステム アプリケーションは、データと、アルゴリズムに関する情報を格納します。 クラスターの集計された正常性状態は、いずれかの場合にのみ、評価が返される<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.SystemApplicationHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.SystemApplicationHealthEvaluation.UnhealthyEvaluations" />
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
          <para>システム アプリケーションの現在の集計された正常性状態に原因となった異常な評価を取得します。 異常な評価の種類を指定できます<see cref="T:System.Fabric.Health.DeployedApplicationsHealthEvaluation" />、<see cref="T:System.Fabric.Health.ServicesHealthEvaluation" />または<see cref="T:System.Fabric.Health.EventHealthEvaluation" />です。</para>
        </summary>
        <value>
          <para>現在の集計された正常性状態を原因となった異常な評価。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>