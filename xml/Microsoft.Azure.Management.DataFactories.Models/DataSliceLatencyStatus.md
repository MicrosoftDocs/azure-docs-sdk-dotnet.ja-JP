<Type Name="DataSliceLatencyStatus" FullName="Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus">
  <TypeSignature Language="C#" Value="public static class DataSliceLatencyStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSliceLatencyStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSliceLatencyStatus" />
  <TypeSignature Language="F#" Value="type DataSliceLatencyStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1d97d-101">データ スライスの待機時間のステータス。</span><span class="sxs-lookup"><span data-stu-id="1d97d-101">The data slice latency status.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Late">
      <MemberSignature Language="C#" Value="public const string Late;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Late" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus.Late" />
      <MemberSignature Language="VB.NET" Value="Public Const Late As String " />
      <MemberSignature Language="F#" Value="val mutable Late : string" Usage="Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus.Late" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1d97d-102">データ スライスは遅れてスライスに達していない中断した状態で待機時間の長さが、ユーザーによって決定される場合</span><span class="sxs-lookup"><span data-stu-id="1d97d-102">The data slice is Late when the slice has not reached a terminated status by the latency length determined by the user.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTime">
      <MemberSignature Language="C#" Value="public const string OnTime;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string OnTime" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus.OnTime" />
      <MemberSignature Language="VB.NET" Value="Public Const OnTime As String " />
      <MemberSignature Language="F#" Value="val mutable OnTime : string" Usage="Microsoft.Azure.Management.DataFactories.Models.DataSliceLatencyStatus.OnTime" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1d97d-103">データ スライスは OnTime は、スライスは待機時間の長さが、ユーザーが決定する前に終了された状態 (準備完了/失敗/FailedValidation/TimedOut) に達した場合です。</span><span class="sxs-lookup"><span data-stu-id="1d97d-103">The data slice is OnTime when the slice has reached a terminated status (Ready/Failed/FailedValidation/TimedOut) before the latency length determined by the user.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>