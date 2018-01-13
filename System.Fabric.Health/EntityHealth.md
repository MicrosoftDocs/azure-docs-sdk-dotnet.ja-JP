<Type Name="EntityHealth" FullName="System.Fabric.Health.EntityHealth">
  <TypeSignature Language="C#" Value="public abstract class EntityHealth" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EntityHealth extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.EntityHealth" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EntityHealth" />
  <TypeSignature Language="F#" Value="type EntityHealth = class" />
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
      <para>関連するクラスをすべてのエンティティのヘルスの基本クラスを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected EntityHealth ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.EntityHealth.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Health.EntityHealth" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregatedHealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState AggregatedHealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState AggregatedHealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityHealth.AggregatedHealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AggregatedHealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.AggregatedHealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.EntityHealth.AggregatedHealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>エンティティで集計された正常性状態を取得します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.HealthState" />に基づいて Health Manager によって計算された集計された正常性状態を表す (存在する場合)、エンティティとその子でイベントを報告し、正常性ポリシーを必要に応じて。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthEvents">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvent&gt; HealthEvents { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvent&gt; HealthEvents" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityHealth.HealthEvents" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthEvents As IList(Of HealthEvent)" />
      <MemberSignature Language="F#" Value="member this.HealthEvents : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvent&gt;" Usage="System.Fabric.Health.EntityHealth.HealthEvents" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvent&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>エンティティで報告される正常性イベントを取得します。</para>
        </summary>
        <value>
          <para>エンティティの正常性イベントが報告されました。</para>
        </value>
        <remarks>正常性イベントは、正常性ストアに送信される正常性レポートに基づいて作成されます。 正常性ストアによって追加された追加のメタデータが含まれます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityHealth.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.Health.EntityHealth.UnhealthyEvaluations" />
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
          <para>現在の集計された正常性状態が正常性マネージャーによってに返された理由を示す異常な評価を取得します。</para>
        </summary>
        <value>
          <para>現在の集計された正常性状態が正常性マネージャーによってに返された理由を説明する異常な評価。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>