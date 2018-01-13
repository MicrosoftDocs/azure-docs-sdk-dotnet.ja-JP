<Type Name="PartitionHealthState" FullName="System.Fabric.Health.PartitionHealthState">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthState : System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthState extends System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthState" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthState&#xA;Inherits EntityHealthState" />
  <TypeSignature Language="F#" Value="type PartitionHealthState = class&#xA;    inherit EntityHealthState" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealthState</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>パーティション識別子および集計された正常性状態を含むパーティションのヘルス状態を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthState.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Health.PartitionHealthState.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>パーティション ID を取得します</para>
        </summary>
        <value>
          <para>パーティションの id。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthState.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthState.ToString " />
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
            パーティションのヘルス状態について説明する文字列を作成します。
            </summary>
        <returns>説明の文字列、<see cref="T:System.Fabric.Health.PartitionHealthState" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>