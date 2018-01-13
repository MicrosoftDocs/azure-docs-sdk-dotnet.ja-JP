<Type Name="NodeRepairImpactDescription" FullName="System.Fabric.Repair.NodeRepairImpactDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeRepairImpactDescription : System.Fabric.Repair.RepairImpactDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeRepairImpactDescription extends System.Fabric.Repair.RepairImpactDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.NodeRepairImpactDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeRepairImpactDescription&#xA;Inherits RepairImpactDescription" />
  <TypeSignature Language="F#" Value="type NodeRepairImpactDescription = class&#xA;    inherit RepairImpactDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Repair.RepairImpactDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>一連のノードでは、修復の予想される影響を表します。</para>
      <para>このクラスは、Service Fabric プラットフォームをサポートしていますコードから直接呼び出されるものではありません。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRepairImpactDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairImpactDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.Repair.NodeRepairImpactDescription" />空影響リストを持つクラス。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImpactedNodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Repair.NodeImpact&gt; ImpactedNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Repair.NodeImpact&gt; ImpactedNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.NodeRepairImpactDescription.ImpactedNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ImpactedNodes As IList(Of NodeImpact)" />
      <MemberSignature Language="F#" Value="member this.ImpactedNodes : System.Collections.Generic.IList&lt;System.Fabric.Repair.NodeImpact&gt;" Usage="System.Fabric.Repair.NodeRepairImpactDescription.ImpactedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Repair.NodeImpact&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>影響を受けるノードの一覧を取得します。</para>
        </summary>
        <value>
          <para>一連の<see cref="T:System.Fabric.Repair.NodeImpact" />修理の影響を説明するオブジェクト。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairImpactDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeRepairImpactDescription.ToString " />
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
          <para>現在のオブジェクトの値を文字列形式に変換します。</para>
        </summary>
        <returns>
          <para>値の文字列表現<see cref="P:System.Fabric.Repair.NodeRepairImpactDescription.ImpactedNodes" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>