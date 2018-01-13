<Type Name="ClusterRepairTask" FullName="System.Fabric.Repair.ClusterRepairTask">
  <TypeSignature Language="C#" Value="public sealed class ClusterRepairTask : System.Fabric.Repair.RepairTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterRepairTask extends System.Fabric.Repair.RepairTask" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.ClusterRepairTask" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterRepairTask&#xA;Inherits RepairTask" />
  <TypeSignature Language="F#" Value="type ClusterRepairTask = class&#xA;    inherit RepairTask" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Repair.RepairTask</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>クラスターのスコープを持つ修復タスクを表します。</para>
      <para>このクラスは、Service Fabric プラットフォームをサポートしていますコードから直接呼び出されるものではありません。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterRepairTask (string taskId, string action);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string taskId, string action) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Repair.ClusterRepairTask.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (taskId As String, action As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Repair.ClusterRepairTask : string * string -&gt; System.Fabric.Repair.ClusterRepairTask" Usage="new System.Fabric.Repair.ClusterRepairTask (taskId, action)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="action" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="taskId">
          <para>修復タスクの ID。</para>
        </param>
        <param name="action">
          <para>要求された修復操作。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Repair.ClusterRepairTask" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>