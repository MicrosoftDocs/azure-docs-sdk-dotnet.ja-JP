<Type Name="NodeRepairTargetDescription" FullName="System.Fabric.Repair.NodeRepairTargetDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeRepairTargetDescription : System.Fabric.Repair.RepairTargetDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeRepairTargetDescription extends System.Fabric.Repair.RepairTargetDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.NodeRepairTargetDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeRepairTargetDescription&#xA;Inherits RepairTargetDescription" />
  <TypeSignature Language="F#" Value="type NodeRepairTargetDescription = class&#xA;    inherit RepairTargetDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Repair.RepairTargetDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>修復アクションの対象となるノードの一覧について説明します。</para>
      <para>このクラスは、Service Fabric プラットフォームをサポートしていますコードから直接呼び出されるものではありません。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRepairTargetDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairTargetDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.Repair.NodeRepairTargetDescription" />ノードの名前の空のリストを持つクラス。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRepairTargetDescription (System.Collections.Generic.IEnumerable&lt;string&gt; nodeNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; nodeNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairTargetDescription.#ctor(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeNames As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Repair.NodeRepairTargetDescription : seq&lt;string&gt; -&gt; System.Fabric.Repair.NodeRepairTargetDescription" Usage="new System.Fabric.Repair.NodeRepairTargetDescription nodeNames" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeNames" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeNames">
          <para>新しいリストに要素がコピーされたコレクション。</para>
        </param>
        <summary>
          <para>指定したコレクションからコピーされた要素を格納する、<see cref="T:System.Fabric.Repair.NodeRepairTargetDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeRepairTargetDescription (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairTargetDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Repair.NodeRepairTargetDescription : string -&gt; System.Fabric.Repair.NodeRepairTargetDescription" Usage="new System.Fabric.Repair.NodeRepairTargetDescription nodeName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>一覧に追加するノードの名前。</para>
        </param>
        <summary>
          <para>新しいインスタンスを初期化、<see cref="T:System.Fabric.Repair.NodeRepairTargetDescription" />をそのノードのリスト内の唯一の要素として指定したノード名を含むクラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Nodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Nodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Nodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Repair.NodeRepairTargetDescription.Nodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Nodes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Nodes : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.Repair.NodeRepairTargetDescription.Nodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ノード名の一覧を取得します。</para>
        </summary>
        <value>
          <para>ノード名の一覧。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.NodeRepairTargetDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeRepairTargetDescription.ToString " />
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
          <para>値の文字列表現<see cref="P:System.Fabric.Repair.NodeRepairTargetDescription.Nodes" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>