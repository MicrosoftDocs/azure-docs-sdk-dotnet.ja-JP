<Type Name="JobScheduleExecutionInformation" FullName="Microsoft.Azure.Batch.JobScheduleExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobScheduleExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobScheduleExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobScheduleExecutionInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            ジョブ スケジュールの実行情報。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.JobScheduleExecutionInformation.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブ スケジュールの終了時刻を取得します。 このプロパティはの完了したジョブのスケジュールでのみ返されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextRunTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextRunTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextRunTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleExecutionInformation.NextRunTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextRunTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextRunTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.JobScheduleExecutionInformation.NextRunTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このジョブ スケジュールの下で、次のジョブをスケジュールする時間を取得します。 このプロパティはのアクティブなジョブのスケジュールでのみ返されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecentJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.RecentJob RecentJob { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.RecentJob RecentJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleExecutionInformation.RecentJob" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecentJob As RecentJob" />
      <MemberSignature Language="F#" Value="member this.RecentJob : Microsoft.Azure.Batch.RecentJob" Usage="Microsoft.Azure.Batch.JobScheduleExecutionInformation.RecentJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.RecentJob</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブ スケジュール の下の最近のジョブに関する情報を取得します。 この要素が、ジョブ スケジュールには、その下にある少なくとも 1 つのジョブが含まれている場合のみ返されることに注意してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>