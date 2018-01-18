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
      <para><span data-ttu-id="6fb74-101">ノードの id および集計された正常性状態を含むノードのヘルス状態を表します。</span><span class="sxs-lookup"><span data-stu-id="6fb74-101">Represents the health state of a node, which contains the node identifier and its aggregated health state.</span></span></para>
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
          <para><span data-ttu-id="6fb74-102">ノードの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="6fb74-102">Gets the name of the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6fb74-103">ノード名。</span><span class="sxs-lookup"><span data-stu-id="6fb74-103">The name of the node.</span></span></para>
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
            <span data-ttu-id="6fb74-104">ノードのヘルス状態について説明する文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="6fb74-104">Creates a string description of the node health state.</span></span>
            </summary>
        <returns><span data-ttu-id="6fb74-105">説明の文字列、<see cref="T:System.Fabric.Health.NodeHealthState" />です。</span><span class="sxs-lookup"><span data-stu-id="6fb74-105">String description of the <see cref="T:System.Fabric.Health.NodeHealthState" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>