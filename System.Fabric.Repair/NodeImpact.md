<Type Name="NodeImpact" FullName="System.Fabric.Repair.NodeImpact">
  <TypeSignature Language="C#" Value="public sealed class NodeImpact" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeImpact extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.NodeImpact" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeImpact" />
  <TypeSignature Language="F#" Value="type NodeImpact = class" />
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
      <para>特定のノードの修復の予想される影響をについて説明します。</para>
      <para>このクラスは、Service Fabric プラットフォームをサポートしていますコードから直接呼び出されるものではありません。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeImpact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeImpact.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Repair.NodeImpact" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeImpact (string nodeName, System.Fabric.Repair.NodeImpactLevel impactLevel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeName, valuetype System.Fabric.Repair.NodeImpactLevel impactLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeImpact.#ctor(System.String,System.Fabric.Repair.NodeImpactLevel)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeName As String, impactLevel As NodeImpactLevel)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Repair.NodeImpact : string * System.Fabric.Repair.NodeImpactLevel -&gt; System.Fabric.Repair.NodeImpact" Usage="new System.Fabric.Repair.NodeImpact (nodeName, impactLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="impactLevel" Type="System.Fabric.Repair.NodeImpactLevel" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>影響を受けるノードの名前。</para>
        </param>
        <param name="impactLevel">
          <para>予想影響のレベルです。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Repair.NodeImpact" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImpactLevel">
      <MemberSignature Language="C#" Value="public System.Fabric.Repair.NodeImpactLevel ImpactLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Repair.NodeImpactLevel ImpactLevel" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.NodeImpact.ImpactLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ImpactLevel As NodeImpactLevel" />
      <MemberSignature Language="F#" Value="member this.ImpactLevel : System.Fabric.Repair.NodeImpactLevel with get, set" Usage="System.Fabric.Repair.NodeImpact.ImpactLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.NodeImpactLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または期待どおりの影響のレベルを設定します。</para>
        </summary>
        <value>
          <para>予想影響のレベルです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.NodeImpact.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string with get, set" Usage="System.Fabric.Repair.NodeImpact.NodeName" />
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
          <para>取得または影響を受けるノードの名前を設定します。</para>
        </summary>
        <value>
          <para>影響を受けるノードの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeImpact.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeImpact.ToString " />
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
          <para>ノードの名前、影響のレベルの文字列形式。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>