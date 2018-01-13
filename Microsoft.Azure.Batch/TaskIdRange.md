<Type Name="TaskIdRange" FullName="Microsoft.Azure.Batch.TaskIdRange">
  <TypeSignature Language="C#" Value="public class TaskIdRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskIdRange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskIdRange" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskIdRange" />
  <TypeSignature Language="F#" Value="type TaskIdRange = class&#xA;    interface ITransportObjectProvider&lt;TaskIdRange&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            タスク id の範囲を<see cref="T:Microsoft.Azure.Batch.CloudTask" />によって異なります。 依存タスクをスケジュールする前に、範囲内の id を持つすべてのタスクが正常に完了する必要があります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskIdRange (int start, int end);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 start, int32 end) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskIdRange.#ctor(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (start As Integer, end As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.TaskIdRange : int * int -&gt; Microsoft.Azure.Batch.TaskIdRange" Usage="new Microsoft.Azure.Batch.TaskIdRange (start, end)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="start">範囲の最初のタスクの id。</param>
        <param name="end">範囲の最後のタスクの id。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.TaskIdRange" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>
            範囲は、包括的です。 たとえば、タスクは、8 の開始と終了 10 の範囲に依存し、タスクの「8」、「9」、「10」する必要があります前に完了場合タスクをスケジュールすることができます。
            </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <paramref name="start" /> または <paramref name="end" /> が負の値です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="end" /> は <paramref name="start" /> より小さい。</exception>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public int End { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskIdRange.End" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property End As Integer" />
      <MemberSignature Language="F#" Value="member this.End : int" Usage="Microsoft.Azure.Batch.TaskIdRange.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            範囲の最後のタスクの id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            範囲は、包括的です。 たとえば、タスクは、終了の 12 の範囲に依存し、タスク「12」する必要があります前に完了場合タスクをスケジュールすることができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public int Start { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskIdRange.Start" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Start As Integer" />
      <MemberSignature Language="F#" Value="member this.Start : int" Usage="Microsoft.Azure.Batch.TaskIdRange.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            範囲の最初のタスクの id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            範囲は、包括的です。 たとえば、タスクは、8 の開始範囲に依存し、タスク「8」する必要があります前に完了場合タスクをスケジュールすることができます。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>