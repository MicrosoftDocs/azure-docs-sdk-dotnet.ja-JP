<Type Name="RestartPartitionResult" FullName="System.Fabric.Result.RestartPartitionResult">
  <TypeSignature Language="C#" Value="public class RestartPartitionResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit RestartPartitionResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.RestartPartitionResult" />
  <TypeSignature Language="VB.NET" Value="Public Class RestartPartitionResult" />
  <TypeSignature Language="F#" Value="type RestartPartitionResult = class" />
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
            <span data-ttu-id="b10c1-101">再起動パーティションの結果オブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="b10c1-101">Returns Restart partition result object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="b10c1-102">このクラスは、パーティションの操作が呼び出されたする再起動の選択したパーティションを返します。</span><span class="sxs-lookup"><span data-stu-id="b10c1-102">This class returns the Selected partition for which restart partition action was called.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.RestartPartitionResult.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.Result.RestartPartitionResult.SelectedPartition" />
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
            <span data-ttu-id="b10c1-103">選択したパーティションを取得します。</span><span class="sxs-lookup"><span data-stu-id="b10c1-103">Gets selected partition.</span></span>
            </summary>
        <value><span data-ttu-id="b10c1-104">テスト コマンドで選択したパーティション。</span><span class="sxs-lookup"><span data-stu-id="b10c1-104">The partition selected by the test command.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.RestartPartitionResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="restartPartitionResult.ToString " />
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
            <span data-ttu-id="b10c1-105">含まれる情報の文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="b10c1-105">Returns the string representation of the contained information.</span></span>
            </summary>
        <returns><span data-ttu-id="b10c1-106">約 (条件付きで)、SelectedPartition に関する情報を含む文字列、例外</span><span class="sxs-lookup"><span data-stu-id="b10c1-106">A string containing information about the SelectedPartition and (conditionally) about the Exception</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>