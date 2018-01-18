<Type Name="InvokeDataLossResult" FullName="System.Fabric.Result.InvokeDataLossResult">
  <TypeSignature Language="C#" Value="public sealed class InvokeDataLossResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit InvokeDataLossResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.InvokeDataLossResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class InvokeDataLossResult" />
  <TypeSignature Language="F#" Value="type InvokeDataLossResult = class" />
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
            <span data-ttu-id="3add3-101">Invoke データが失われる結果のオブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="3add3-101">Returns Invoke data loss result object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="3add3-102">このクラスを返しますが、SelectedPartition 情報データが失われるアクションの起動が呼び出されました。</span><span class="sxs-lookup"><span data-stu-id="3add3-102">This class returns the SelectedPartition information for which invoke data loss action was called.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="SelectedPartition">
      <MemberSignature Language="C#" Value="public System.Fabric.SelectedPartition SelectedPartition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SelectedPartition SelectedPartition" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.InvokeDataLossResult.SelectedPartition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelectedPartition As SelectedPartition" />
      <MemberSignature Language="F#" Value="member this.SelectedPartition : System.Fabric.SelectedPartition" Usage="System.Fabric.Result.InvokeDataLossResult.SelectedPartition" />
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
            <span data-ttu-id="3add3-103">選択したパーティションを取得します。</span><span class="sxs-lookup"><span data-stu-id="3add3-103">Gets the selected partition.</span></span>
            </summary>
        <value><span data-ttu-id="3add3-104">テスト コマンドで選択したパーティション。</span><span class="sxs-lookup"><span data-stu-id="3add3-104">The partition selected by the test command.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.InvokeDataLossResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="invokeDataLossResult.ToString " />
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
            <span data-ttu-id="3add3-105">含まれる情報の文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="3add3-105">Returns the string representation of the contained information.</span></span>
            </summary>
        <returns><span data-ttu-id="3add3-106">約 (条件付きで)、SelectedPartition に関する情報を含む文字列、例外</span><span class="sxs-lookup"><span data-stu-id="3add3-106">A string containing information about the SelectedPartition and (conditionally) about the Exception</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>