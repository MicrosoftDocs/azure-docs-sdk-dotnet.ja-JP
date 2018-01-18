<Type Name="TaskSchedulingPolicy" FullName="Microsoft.Azure.Batch.TaskSchedulingPolicy">
  <TypeSignature Language="C#" Value="public class TaskSchedulingPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskSchedulingPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskSchedulingPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskSchedulingPolicy" />
  <TypeSignature Language="F#" Value="type TaskSchedulingPolicy = class&#xA;    interface ITransportObjectProvider&lt;TaskSchedulingPolicy&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dca91-101">コンピューティング ノードのスケジューリング ポリシーです。</span><span class="sxs-lookup"><span data-stu-id="dca91-101">A scheduling policy for a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskSchedulingPolicy (Microsoft.Azure.Batch.Common.ComputeNodeFillType computeNodeFillType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Common.ComputeNodeFillType computeNodeFillType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskSchedulingPolicy.#ctor(Microsoft.Azure.Batch.Common.ComputeNodeFillType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.TaskSchedulingPolicy : Microsoft.Azure.Batch.Common.ComputeNodeFillType -&gt; Microsoft.Azure.Batch.TaskSchedulingPolicy" Usage="new Microsoft.Azure.Batch.TaskSchedulingPolicy computeNodeFillType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computeNodeFillType" Type="Microsoft.Azure.Batch.Common.ComputeNodeFillType" />
      </Parameters>
      <Docs>
        <param name="computeNodeFillType"><span data-ttu-id="dca91-102">ポリシーのスケジュール設定の塗りつぶしの種類。</span><span class="sxs-lookup"><span data-stu-id="dca91-102">The fill type of scheduling policy.</span></span></param>
        <summary>
            <span data-ttu-id="dca91-103"><see cref="T:Microsoft.Azure.Batch.TaskSchedulingPolicy" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dca91-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.TaskSchedulingPolicy" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeNodeFillType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.ComputeNodeFillType ComputeNodeFillType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.ComputeNodeFillType ComputeNodeFillType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskSchedulingPolicy.ComputeNodeFillType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeNodeFillType As ComputeNodeFillType" />
      <MemberSignature Language="F#" Value="member this.ComputeNodeFillType : Microsoft.Azure.Batch.Common.ComputeNodeFillType" Usage="Microsoft.Azure.Batch.TaskSchedulingPolicy.ComputeNodeFillType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeFillType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dca91-104">ポリシーのスケジュール設定の塗りつぶしの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="dca91-104">Gets the fill type of scheduling policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>