<Type Name="NodeTransitionProgress" FullName="System.Fabric.NodeTransitionProgress">
  <TypeSignature Language="C#" Value="public sealed class NodeTransitionProgress : System.Fabric.TestCommandProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeTransitionProgress extends System.Fabric.TestCommandProgress" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeTransitionProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeTransitionProgress&#xA;Inherits TestCommandProgress" />
  <TypeSignature Language="F#" Value="type NodeTransitionProgress = class&#xA;    inherit TestCommandProgress" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.TestCommandProgress</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a9ebb-101">NodeTransitionProgress オブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="a9ebb-101">Returns NodeTransitionProgress object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="a9ebb-102">このクラスは TestCommandProgressState、(完了、または Faulted の状態) のときに、結果を返します (Faulted 状態) のときに例外およびノード遷移コマンドに関する情報。</span><span class="sxs-lookup"><span data-stu-id="a9ebb-102">This class returns the TestCommandProgressState, Result (when in Completed or Faulted state), and Exception (when in Faulted state) information for the node transition command.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public System.Fabric.Result.NodeCommandResult Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Result.NodeCommandResult Result" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeTransitionProgress.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As NodeCommandResult" />
      <MemberSignature Language="F#" Value="member this.Result : System.Fabric.Result.NodeCommandResult" Usage="System.Fabric.NodeTransitionProgress.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Result.NodeCommandResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a9ebb-103">ノードの移行コマンドの結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="a9ebb-103">Gets the result of the node transition command.</span></span>
            <span data-ttu-id="a9ebb-104">これは、アクションが完了または Faulted の状態になっている場合にのみ、使用可能なです。</span><span class="sxs-lookup"><span data-stu-id="a9ebb-104">This is avaliable only when the action is in Completed or Faulted state.</span></span>
            </summary>
        <value><span data-ttu-id="a9ebb-105">NodeCommandResult オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="a9ebb-105">The NodeCommandResult object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeTransitionProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeTransitionProgress.ToString " />
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
            <span data-ttu-id="a9ebb-106">含まれる情報の文字列表現を返します</span><span class="sxs-lookup"><span data-stu-id="a9ebb-106">Returns a string representation of the contained information</span></span>
            </summary>
        <returns><span data-ttu-id="a9ebb-107">状態、InvokeDataLossResult、および例外情報を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="a9ebb-107">A string that has State, InvokeDataLossResult, and Exception information.</span></span>
            <span data-ttu-id="a9ebb-108">状態は、常に presnt です。状態に応じて、結果と、例外いない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="a9ebb-108">State is always presnt; but depending on State, the Result and the Exception may not be present.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>