<Type Name="PartitionQuorumLossProgress" FullName="System.Fabric.PartitionQuorumLossProgress">
  <TypeSignature Language="C#" Value="public sealed class PartitionQuorumLossProgress : System.Fabric.TestCommandProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionQuorumLossProgress extends System.Fabric.TestCommandProgress" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PartitionQuorumLossProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionQuorumLossProgress&#xA;Inherits TestCommandProgress" />
  <TypeSignature Language="F#" Value="type PartitionQuorumLossProgress = class&#xA;    inherit TestCommandProgress" />
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
            <span data-ttu-id="38883-101">Invoke クォーラム損失進行中のオブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="38883-101">Returns Invoke quorum loss progress object.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="38883-102">このクラスは TestCommandProgressState、(完了、または Faulted の状態) のときに、結果を返しますと (Faulted 状態) のときに例外 invoke クォーラムが失われるアクションについて説明します。</span><span class="sxs-lookup"><span data-stu-id="38883-102">This class returns the TestCommandProgressState, Result (when in Completed or Faulted state), and Exception (when in Faulted state) information for the invoke quorum loss action.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public System.Fabric.Result.PartitionQuorumLossResult Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Result.PartitionQuorumLossResult Result" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PartitionQuorumLossProgress.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As PartitionQuorumLossResult" />
      <MemberSignature Language="F#" Value="member this.Result : System.Fabric.Result.PartitionQuorumLossResult" Usage="System.Fabric.PartitionQuorumLossProgress.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Result.PartitionQuorumLossResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="38883-103">Invoke クォーラム損失アクションの結果を取得しますこれは、アクションが完了または Faulted の状態になっている場合にのみ、使用可能なです。</span><span class="sxs-lookup"><span data-stu-id="38883-103">Gets the result of the invoke quorum loss action; this is avaliable only when the action is in Completed or Faulted state.</span></span>
            </summary>
        <value><span data-ttu-id="38883-104">PartitionQuorumLossResult オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="38883-104">The PartitionQuorumLossResult object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PartitionQuorumLossProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionQuorumLossProgress.ToString " />
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
            <span data-ttu-id="38883-105">含まれる情報の文字列表現を返します</span><span class="sxs-lookup"><span data-stu-id="38883-105">Returns a string representation of the contained information</span></span>
            </summary>
        <returns><span data-ttu-id="38883-106">状態、InvokeQuorumLossResult、および例外情報を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="38883-106">A string that has State, InvokeQuorumLossResult, and Exception information.</span></span>
            <span data-ttu-id="38883-107">状態は、常に presnt です。状態に応じて、結果と、例外いない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="38883-107">State is always presnt; but depending on State, the Result and the Exception may not be present.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>