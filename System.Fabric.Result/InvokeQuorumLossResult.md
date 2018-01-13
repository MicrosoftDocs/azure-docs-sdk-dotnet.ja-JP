<Type Name="InvokeQuorumLossResult" FullName="System.Fabric.Result.InvokeQuorumLossResult">
  <TypeSignature Language="C#" Value="public class InvokeQuorumLossResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit InvokeQuorumLossResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.InvokeQuorumLossResult" />
  <TypeSignature Language="VB.NET" Value="Public Class InvokeQuorumLossResult" />
  <TypeSignature Language="F#" Value="type InvokeQuorumLossResult = class" />
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
            Invoke クォーラムが失われる結果のオブジェクトを返します。
            </summary>
    <remarks>
            このクラスは、クォーラムの損失を呼び出す操作の呼び出しの SelectedPartition 情報を返します。 
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.InvokeQuorumLossResult.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.Result.InvokeQuorumLossResult.SelectedPartition" />
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
            Selecetd パーティションを取得します。
            </summary>
        <value>テスト コマンドで選択したパーティション。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.InvokeQuorumLossResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="invokeQuorumLossResult.ToString " />
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