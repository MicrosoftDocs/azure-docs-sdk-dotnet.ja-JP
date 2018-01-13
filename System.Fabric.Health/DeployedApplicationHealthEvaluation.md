<Type Name="DeployedApplicationHealthEvaluation" FullName="System.Fabric.Health.DeployedApplicationHealthEvaluation">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthEvaluation : System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthEvaluation extends System.Fabric.Health.HealthEvaluation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthEvaluation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthEvaluation&#xA;Inherits HealthEvaluation" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthEvaluation = class&#xA;    inherit HealthEvaluation" />
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
      <para>展開済みアプリケーションの場合、データと正常性を評価する正常性ストアによって使用されるアルゴリズムに関する情報を含む正常性評価を表します。 </para>
    </summary>
    <remarks>集計された正常性状態は、いずれかの場合にのみ、評価が返される<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthEvaluation.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.DeployedApplicationHealthEvaluation.ApplicationName" />
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
          <para>アプリケーションの名前を取得します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Uri" />アプリケーション名を表すです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthEvaluation.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.DeployedApplicationHealthEvaluation.NodeName" />
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
          <para>展開済みアプリケーションが実行されているノードの名前を取得します。</para>
        </summary>
        <value>
          <para><see cref="T:System.String" />ノード名を表すです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthEvaluation.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.DeployedApplicationHealthEvaluation.UnhealthyEvaluations" />
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
          <para>展開済みアプリケーションの現在の集計された正常性状態に原因となった異常な評価を取得します。 異常な評価の種類を指定できます<see cref="T:System.Fabric.Health.DeployedServicePackagesHealthEvaluation" />または<see cref="T:System.Fabric.Health.EventHealthEvaluation" />です。</para>
        </summary>
        <value>
          <para>現在の集計された正常性状態を原因となった異常な評価の一覧。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>