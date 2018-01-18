<Type Name="PartitionManagerOptions" FullName="Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions">
  <TypeSignature Language="C#" Value="public class PartitionManagerOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartitionManagerOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionManagerOptions" />
  <TypeSignature Language="F#" Value="type PartitionManagerOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="599b3-101">パーティションの配布で起こっているかのさまざまな側面を制御するオプション<see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="599b3-101">Options to control various aspects of partition distribution happening within <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> instance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionManagerOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions.LeaseDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseDuration : TimeSpan with get, set" Usage="Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions.LeaseDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="599b3-102">対象のリースはで作成された Azure Blob EventHub パーティションを表す間隔です。</span><span class="sxs-lookup"><span data-stu-id="599b3-102">Interval for which the lease is taken on Azure Blob representing an EventHub partition.</span></span>  <span data-ttu-id="599b3-103">有効期限が切れると、そのリースは、この時間内で更新されていない場合と、パーティションの所有権は別に移動<see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="599b3-103">If the lease is not renewed within this interval, it will cause it to expire and ownership of the partition will move to another <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewInterval">
      <MemberSignature Language="C#" Value="public TimeSpan RenewInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RenewInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions.RenewInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RenewInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RenewInterval : TimeSpan with get, set" Usage="Microsoft.Azure.EventHubs.Processor.PartitionManagerOptions.RenewInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="599b3-104">更新によって現在保持されているパーティションのすべてのリースの間隔の<see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="599b3-104">Renew interval for all leases for partitions currently held by <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" /> instance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>