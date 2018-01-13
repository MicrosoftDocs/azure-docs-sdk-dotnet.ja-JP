<Type Name="UsageStatistics" FullName="Microsoft.Azure.Batch.UsageStatistics">
  <TypeSignature Language="C#" Value="public class UsageStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UsageStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.UsageStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class UsageStatistics" />
  <TypeSignature Language="F#" Value="type UsageStatistics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="c1c4e-101">プールの使用状況データに関連する統計。</span><span class="sxs-lookup"><span data-stu-id="c1c4e-101">Statistics related to pool usage data.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DedicatedCoreTime">
      <MemberSignature Language="C#" Value="public TimeSpan DedicatedCoreTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DedicatedCoreTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UsageStatistics.DedicatedCoreTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DedicatedCoreTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DedicatedCoreTime : TimeSpan" Usage="Microsoft.Azure.Batch.UsageStatistics.DedicatedCoreTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1c4e-102">プールの一部である専用のコンピューティング ノードの集計されたウォール クロック時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1c4e-102">Gets the aggregated wall-clock time of the dedicated compute nodes being part of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UsageStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime" Usage="Microsoft.Azure.Batch.UsageStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1c4e-103">これで、統計の最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1c4e-103">Gets the time at which the statistics were last updated.</span></span> <span data-ttu-id="c1c4e-104">すべての統計情報は間の範囲に制限されて<see cref="P:Microsoft.Azure.Batch.UsageStatistics.StartTime" />とこの値。</span><span class="sxs-lookup"><span data-stu-id="c1c4e-104">All statistics are limited to the range between <see cref="P:Microsoft.Azure.Batch.UsageStatistics.StartTime" /> and this value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.UsageStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.UsageStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1c4e-105">統計情報の時間範囲の開始時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1c4e-105">Gets the start time of the time range covered by the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>