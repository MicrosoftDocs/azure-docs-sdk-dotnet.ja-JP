<Type Name="NodeHealthState" FullName="System.Fabric.Health.NodeHealthState">
  <TypeSignature Language="C#" Value="public sealed class NodeHealthState : System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealthState extends System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodeHealthState" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealthState&#xA;Inherits EntityHealthState" />
  <TypeSignature Language="F#" Value="type NodeHealthState = class&#xA;    inherit EntityHealthState" />
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
      <para>ノードの id および集計された正常性状態を含むノードのヘルス状態を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthState.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Health.NodeHealthState.NodeName" />
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
          <para>ノードの名前を取得します。</para>
        </summary>
        <value>
          <para>ノード名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthState.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeHealthState.ToString " />
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
            ノードのヘルス状態について説明する文字列を作成します。
            </summary>
        <returns>説明の文字列、<see cref="T:System.Fabric.Health.NodeHealthState" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>