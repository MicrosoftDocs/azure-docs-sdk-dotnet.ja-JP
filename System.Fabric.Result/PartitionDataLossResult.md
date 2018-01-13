<Type Name="PartitionDataLossResult" FullName="System.Fabric.Result.PartitionDataLossResult">
  <TypeSignature Language="C#" Value="public sealed class PartitionDataLossResult : System.Fabric.Result.TestCommandResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit PartitionDataLossResult extends System.Fabric.Result.TestCommandResult" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.PartitionDataLossResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionDataLossResult&#xA;Inherits TestCommandResult" />
  <TypeSignature Language="F#" Value="type PartitionDataLossResult = class&#xA;    inherit TestCommandResult" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Result.TestCommandResult</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Invoke データが失われる結果のオブジェクトを返します。
            </summary>
    <remarks>
            このクラスを返しますが、SelectedPartition 情報データが失われるアクションの起動が呼び出されました。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.PartitionDataLossResult.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.Result.PartitionDataLossResult.SelectedPartition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SelectedPartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            選択したパーティションを取得します。
            </summary>
        <value>SelectedPartition オブジェクトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.PartitionDataLossResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionDataLossResult.ToString " />
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
            含まれる情報の文字列表現を返します。
            </summary>
        <returns>約 (条件付きで)、SelectedPartition に関する情報を含む文字列、例外 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>