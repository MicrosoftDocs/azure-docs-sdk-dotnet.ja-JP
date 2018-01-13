<Type Name="FabricClient+RepairManagementClient" FullName="System.Fabric.FabricClient+RepairManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.RepairManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/RepairManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.RepairManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.RepairManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.RepairManagementClient = class" />
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
      <para>修復タスクを管理するためのメソッドを提供します。</para>
      <para>このクラスは、Service Fabric プラットフォームをサポートしていますコードから直接呼び出されるものではありません。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CancelRepairTaskAsync (string repairTaskId, long version, bool requestAbort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CancelRepairTaskAsync(string repairTaskId, int64 version, bool requestAbort) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CancelRepairTaskAsync(System.String,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelRepairTaskAsync (repairTaskId As String, version As Long, requestAbort As Boolean) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CancelRepairTaskAsync : string * int64 * bool -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CancelRepairTaskAsync (repairTaskId, version, requestAbort)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="requestAbort" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>キャンセルできる修復タスクの ID。</para>
        </param>
        <param name="version">
          <para>修復タスクの現在のバージョン番号。 0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。 0 の場合、バージョン チェックは実行されません。</para>
        </param>
        <param name="requestAbort">
          <para>
            <languageKeyword>True</languageKeyword>かどうか、修復を停止するかできるだけ早く場合でも、実行が既に開始します。 <languageKeyword>False</languageKeyword>実行がまだ開始されていない場合にのみ、修復を取り消す必要がある場合。</para>
        </param>
        <summary>
          <para>指定した修復タスクのキャンセルを要求します。</para>
        </summary>
        <returns>
          <para>修復タスクの新しいバージョン番号。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CancelRepairTaskAsync (string repairTaskId, long version, bool requestAbort, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CancelRepairTaskAsync(string repairTaskId, int64 version, bool requestAbort, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CancelRepairTaskAsync(System.String,System.Int64,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelRepairTaskAsync : string * int64 * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CancelRepairTaskAsync (repairTaskId, version, requestAbort, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="requestAbort" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>キャンセルできる修復タスクの ID。</para>
        </param>
        <param name="version">
          <para>修復タスクの現在のバージョン番号。 0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。 0 の場合、バージョン チェックは実行されません。</para>
        </param>
        <param name="requestAbort">
          <para>
            <languageKeyword>True</languageKeyword>かどうか、修復を停止するかできるだけ早く場合でも、実行が既に開始します。 <languageKeyword>False</languageKeyword>実行がまだ開始されていない場合にのみ、修復を取り消す必要がある場合。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定した修復タスクのキャンセルを要求します。</para>
        </summary>
        <returns>
          <para>修復タスクの新しいバージョン番号。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CreateRepairTaskAsync (System.Fabric.Repair.RepairTask repairTask);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CreateRepairTaskAsync(class System.Fabric.Repair.RepairTask repairTask) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CreateRepairTaskAsync(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="F#" Value="member this.CreateRepairTaskAsync : System.Fabric.Repair.RepairTask -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CreateRepairTaskAsync repairTask" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="repairTask">
          <para> 作成する修復タスクの説明です。</para>
        </param>
        <summary>
          <para>新しい修復タスクを作成します。</para>
        </summary>
        <returns>
          <para>修復の新しく作成されたタスクのバージョン番号。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CreateRepairTaskAsync (System.Fabric.Repair.RepairTask repairTask, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CreateRepairTaskAsync(class System.Fabric.Repair.RepairTask repairTask, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CreateRepairTaskAsync(System.Fabric.Repair.RepairTask,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateRepairTaskAsync : System.Fabric.Repair.RepairTask * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CreateRepairTaskAsync (repairTask, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTask">
          <para> 作成する修復タスクの説明です。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para> 操作を確認する省略可能なキャンセル トークン。操作を取り消す必要がある通知を送信するために使用します。
            キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>新しい修復タスクを作成します。</para>
        </summary>
        <returns>
          <para>修復の新しく作成されたタスクのバージョン番号。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRepairTaskAsync (string repairTaskId, long version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRepairTaskAsync(string repairTaskId, int64 version) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.DeleteRepairTaskAsync(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRepairTaskAsync (repairTaskId As String, version As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRepairTaskAsync : string * int64 -&gt; System.Threading.Tasks.Task" Usage="repairManagementClient.DeleteRepairTaskAsync (repairTaskId, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>削除する完了した修復タスクの ID。</para>
        </param>
        <param name="version">
          <para>修復タスクの現在のバージョン番号。 0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。 0 の場合、バージョン チェックは実行されません。</para>
        </param>
        <summary>
          <para>指定した修復タスクを削除します。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRepairTaskAsync (string repairTaskId, long version, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRepairTaskAsync(string repairTaskId, int64 version, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.DeleteRepairTaskAsync(System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteRepairTaskAsync : string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="repairManagementClient.DeleteRepairTaskAsync (repairTaskId, version, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>削除する完了した修復タスクの ID。</para>
        </param>
        <param name="version">
          <para>修復タスクの現在のバージョン番号。 0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。 0 の場合、バージョン チェックは実行されません。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定した修復タスクを削除します。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceApproveRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ForceApproveRepairTaskAsync (string repairTaskId, long version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ForceApproveRepairTaskAsync(string repairTaskId, int64 version) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.ForceApproveRepairTaskAsync(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ForceApproveRepairTaskAsync (repairTaskId As String, version As Long) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ForceApproveRepairTaskAsync : string * int64 -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.ForceApproveRepairTaskAsync (repairTaskId, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>承認修復タスクの ID。</para>
        </param>
        <param name="version">
          <para>修復タスクの現在のバージョン番号。 0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。 0 の場合、バージョン チェックは実行されません。</para>
        </param>
        <summary>
          <para>指定した修復タスクの承認を強制します。</para>
        </summary>
        <returns>
          <para>修復タスクの新しいバージョン番号。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceApproveRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ForceApproveRepairTaskAsync (string repairTaskId, long version, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ForceApproveRepairTaskAsync(string repairTaskId, int64 version, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.ForceApproveRepairTaskAsync(System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ForceApproveRepairTaskAsync : string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.ForceApproveRepairTaskAsync (repairTaskId, version, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>承認修復タスクの ID。</para>
        </param>
        <param name="version">
          <para>修復タスクの現在のバージョン番号。 0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。 0 の場合、バージョン チェックは実行されません。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定した修復タスクの承認を強制します。</para>
        </summary>
        <returns>
          <para>修復タスクの新しいバージョン番号。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRepairTaskListAsync () As Task(Of RepairTaskList)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>修復のすべてのタスクの一覧を取得します。</para>
        </summary>
        <returns>
          <para>修復のすべてのタスクの一覧。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>修復のすべてのタスクの一覧を取得します。</para>
        </summary>
        <returns>
          <para>修復のすべてのタスクの一覧。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (string taskIdFilter, System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(string taskIdFilter, valuetype System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.String,System.Fabric.Repair.RepairTaskStateFilter,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRepairTaskListAsync (taskIdFilter As String, stateFilter As RepairTaskStateFilter, executorFilter As String) As Task(Of RepairTaskList)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : string * System.Fabric.Repair.RepairTaskStateFilter * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (taskIdFilter, stateFilter, executorFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskIdFilter" Type="System.String" />
        <Parameter Name="stateFilter" Type="System.Fabric.Repair.RepairTaskStateFilter" />
        <Parameter Name="executorFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="taskIdFilter">
          <para>照合される修復タスク ID プレフィックス。  タスク ID にフィルターが適用されていない null の場合、</para>
        </param>
        <param name="stateFilter">
          <para>タスクの状態を指定する状態フィルター値のビットごとの組み合わせは、リストに含まれる必要があります。</para>
        </param>
        <param name="executorFilter">
          <para>要求されたタスクが含まれる一覧に含めるか修復の実行子の名前。 Null の場合、実行プログラム名にフィルターは適用されません。</para>
        </param>
        <summary>
          <para>すべての指定したフィルターに一致する修復作業の一覧を取得します。</para>
        </summary>
        <returns>
          <para>すべての指定したフィルターに一致する修復作業の一覧。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (string taskIdFilter, System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(string taskIdFilter, valuetype System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.String,System.Fabric.Repair.RepairTaskStateFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : string * System.Fabric.Repair.RepairTaskStateFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (taskIdFilter, stateFilter, executorFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskIdFilter" Type="System.String" />
        <Parameter Name="stateFilter" Type="System.Fabric.Repair.RepairTaskStateFilter" />
        <Parameter Name="executorFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskIdFilter">
          <para>照合される修復タスク ID プレフィックス。  タスク ID にフィルターが適用されていない null の場合、</para>
        </param>
        <param name="stateFilter">
          <para>タスクの状態を指定する状態フィルター値のビットごとの組み合わせは、リストに含まれる必要があります。</para>
        </param>
        <param name="executorFilter">
          <para>要求されたタスクが含まれる一覧に含めるか修復の実行子の名前。 Null の場合、実行プログラム名にフィルターは適用されません。</para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>すべての指定したフィルターに一致する修復作業の一覧を取得します。</para>
        </summary>
        <returns>
          <para>すべての指定したフィルターに一致する修復作業の一覧。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairExecutionStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairExecutionStateAsync (System.Fabric.Repair.RepairTask repairTask);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairExecutionStateAsync(class System.Fabric.Repair.RepairTask repairTask) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairExecutionStateAsync(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairExecutionStateAsync : System.Fabric.Repair.RepairTask -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairExecutionStateAsync repairTask" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="repairTask">変更後の修復作業します。</param>
        <summary>
            修復タスクを更新します。
            </summary>
        <returns>
          <para>修復タスクの新しいバージョン番号。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairExecutionStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairExecutionStateAsync (System.Fabric.Repair.RepairTask repairTask, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairExecutionStateAsync(class System.Fabric.Repair.RepairTask repairTask, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairExecutionStateAsync(System.Fabric.Repair.RepairTask,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairExecutionStateAsync : System.Fabric.Repair.RepairTask * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairExecutionStateAsync (repairTask, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTask">変更後の修復作業します。</param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
            修復タスクを更新します。
            </summary>
        <returns>
          <para>修復タスクの新しいバージョン番号。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairTaskHealthPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairTaskHealthPolicyAsync (string repairTaskId, long version, Nullable&lt;bool&gt; performPreparingHealthCheck, Nullable&lt;bool&gt; performRestoringHealthCheck);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairTaskHealthPolicyAsync(string repairTaskId, int64 version, valuetype System.Nullable`1&lt;bool&gt; performPreparingHealthCheck, valuetype System.Nullable`1&lt;bool&gt; performRestoringHealthCheck) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairTaskHealthPolicyAsync(System.String,System.Int64,System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRepairTaskHealthPolicyAsync (repairTaskId As String, version As Long, performPreparingHealthCheck As Nullable(Of Boolean), performRestoringHealthCheck As Nullable(Of Boolean)) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairTaskHealthPolicyAsync : string * int64 * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairTaskHealthPolicyAsync (repairTaskId, version, performPreparingHealthCheck, performRestoringHealthCheck)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="performPreparingHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="performRestoringHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>正常性ポリシーが更新される修復タスクの ID。</para>
        </param>
        <param name="version">
          <para>修復タスクの現在のバージョン番号。 0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。 0 の場合、バージョン チェックは実行されません。</para>
        </param>
        <param name="performPreparingHealthCheck">
          <para>
            正常性チェックが修復作業の準備段階で実行するかどうかを示す null 許容のブール値。
            指定<c>null</c>このパラメーターの場合は、既存の値を変更しないようにします。 それ以外の場合、目的の新しい値を指定します。 
            </para>
        </param>
        <param name="performRestoringHealthCheck">
          <para>
            正常性チェックが修復作業の復元段階で実行するかどうかを示す null 許容のブール値。
            指定<c>null</c>このパラメーターの場合は、既存の値を変更しないようにします。 それ以外の場合、目的の新しい値を指定します。 
            </para>
        </param>
        <summary>
          <para>指定した修復タスクの正常性ポリシーを更新します。</para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairTaskHealthPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairTaskHealthPolicyAsync (string repairTaskId, long version, Nullable&lt;bool&gt; performPreparingHealthCheck, Nullable&lt;bool&gt; performRestoringHealthCheck, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairTaskHealthPolicyAsync(string repairTaskId, int64 version, valuetype System.Nullable`1&lt;bool&gt; performPreparingHealthCheck, valuetype System.Nullable`1&lt;bool&gt; performRestoringHealthCheck, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairTaskHealthPolicyAsync(System.String,System.Int64,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairTaskHealthPolicyAsync : string * int64 * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairTaskHealthPolicyAsync (repairTaskId, version, performPreparingHealthCheck, performRestoringHealthCheck, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="performPreparingHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="performRestoringHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para>正常性ポリシーが更新される修復タスクの ID。</para>
        </param>
        <param name="version">
          <para>修復タスクの現在のバージョン番号。 0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。 0 の場合、バージョン チェックは実行されません。</para>
        </param>
        <param name="performPreparingHealthCheck">
          <para>
            正常性チェックが修復作業の準備段階で実行するかどうかを示す null 許容のブール値。
            指定<c>null</c>このパラメーターの場合は、既存の値を変更しないようにします。 それ以外の場合、適切な指定<c>bool</c>値。 
            </para>
        </param>
        <param name="performRestoringHealthCheck">
          <para>
            正常性チェックが修復作業の復元段階で実行するかどうかを示す null 許容のブール値。
            指定<c>null</c>このパラメーターの場合は、既存の値を変更しないようにします。 それ以外の場合、適切な指定<c>bool</c>値。 
            </para>
        </param>
        <param name="timeout">
          <para>時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定した修復タスクの正常性ポリシーを更新します。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>