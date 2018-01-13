<Type Name="TaskStatistics" FullName="Microsoft.Azure.Batch.TaskStatistics">
  <TypeSignature Language="C#" Value="public class TaskStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskStatistics" />
  <TypeSignature Language="F#" Value="type TaskStatistics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            タスクのリソース使用状況の統計。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="KernelCpuTime">
      <MemberSignature Language="C#" Value="public TimeSpan KernelCpuTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KernelCpuTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStatistics.KernelCpuTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KernelCpuTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KernelCpuTime : TimeSpan" Usage="Microsoft.Azure.Batch.TaskStatistics.KernelCpuTime" />
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
            カーネル モード CPU 時間の合計 (コア当たり) タスクによって使用を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime" Usage="Microsoft.Azure.Batch.TaskStatistics.LastUpdateTime" />
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
            これで、統計の最終更新時刻を取得します。 すべての統計情報は間の範囲に制限されて<see cref="P:Microsoft.Azure.Batch.TaskStatistics.StartTime" />とこの値。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOGiB">
      <MemberSignature Language="C#" Value="public double ReadIOGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 ReadIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStatistics.ReadIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.ReadIOGiB : double" Usage="Microsoft.Azure.Batch.TaskStatistics.ReadIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクによってディスクから読み取られた I/O の合計 gibibytes を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOps">
      <MemberSignature Language="C#" Value="public long ReadIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStatistics.ReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.ReadIOps : int64" Usage="Microsoft.Azure.Batch.TaskStatistics.ReadIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクによって実行された読み取り操作のディスクの合計数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.TaskStatistics.StartTime" />
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
            統計情報の時間範囲の開始時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStatistics.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.TaskStatistics.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクの統計情報の URL を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserCpuTime">
      <MemberSignature Language="C#" Value="public TimeSpan UserCpuTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UserCpuTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStatistics.UserCpuTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserCpuTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UserCpuTime : TimeSpan" Usage="Microsoft.Azure.Batch.TaskStatistics.UserCpuTime" />
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
            ユーザー モード CPU 時間の合計 (コア当たり)、タスクによって消費されるを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTime">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStatistics.WaitTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WaitTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTime : TimeSpan" Usage="Microsoft.Azure.Batch.TaskStatistics.WaitTime" />
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
            タスクの合計待機時間を取得します。 タスクの待機時間は、タスクの作成とタスクの実行の開始までの経過時間として定義されます。 (失敗したため、タスクが再試行された場合、待機時間は、最新のタスクの実行にかかる時間です。)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WallClockTime">
      <MemberSignature Language="C#" Value="public TimeSpan WallClockTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStatistics.WallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WallClockTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WallClockTime : TimeSpan" Usage="Microsoft.Azure.Batch.TaskStatistics.WallClockTime" />
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
            タスクの実行のウォール クロック時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOGiB">
      <MemberSignature Language="C#" Value="public double WriteIOGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 WriteIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStatistics.WriteIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.WriteIOGiB : double" Usage="Microsoft.Azure.Batch.TaskStatistics.WriteIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクによってディスクに書き込まれる I/O の合計 gibibytes を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOps">
      <MemberSignature Language="C#" Value="public long WriteIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 WriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStatistics.WriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.WriteIOps : int64" Usage="Microsoft.Azure.Batch.TaskStatistics.WriteIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクによって行われたディスク書き込み操作の合計数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>