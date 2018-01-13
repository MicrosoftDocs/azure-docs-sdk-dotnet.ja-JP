<Type Name="EntityHealthState" FullName="System.Fabric.Health.EntityHealthState">
  <TypeSignature Language="C#" Value="public abstract class EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit EntityHealthState extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class EntityHealthState" />
  <TypeSignature Language="F#" Value="type EntityHealthState = class" />
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
      <para>エンティティ ヘルス状態のすべてのクラスの基底クラスを表します。</para>
    </summary>
    <remarks>エンティティのヘルス状態には、エンティティの識別子とエンティティで集計された正常性状態が含まれています。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected EntityHealthState ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.EntityHealthState.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Health.EntityHealthState" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregatedHealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState AggregatedHealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState AggregatedHealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.EntityHealthState.AggregatedHealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AggregatedHealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.AggregatedHealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.EntityHealthState.AggregatedHealthState" />
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
          <para>報告されたすべてのイベントと、目的のポリシーに基づいて Health Manager によって計算された集計された正常性状態を取得します。</para>
        </summary>
        <value>
          <para>ヘルス マネージャーによって計算された集計の正常性状態。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>