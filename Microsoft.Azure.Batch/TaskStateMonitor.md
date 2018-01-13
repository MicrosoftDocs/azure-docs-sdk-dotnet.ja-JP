<Type Name="TaskStateMonitor" FullName="Microsoft.Azure.Batch.TaskStateMonitor">
  <TypeSignature Language="C#" Value="public class TaskStateMonitor : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskStateMonitor extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskStateMonitor" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskStateMonitor&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type TaskStateMonitor = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            CloudTask 状態監視するためのユーティリティを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.TaskStateMonitor" />です。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これらの動作は、子オブジェクトによって継承されます。</para>
          <para>変更は、コレクションの順序で適用されます。 最後には、wins を記述します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitAll">
      <MemberSignature Language="C#" Value="public void WaitAll (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, Microsoft.Azure.Batch.Common.TaskState desiredState, TimeSpan timeout, Microsoft.Azure.Batch.ODATAMonitorControl controlParams = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void WaitAll(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, valuetype Microsoft.Azure.Batch.Common.TaskState desiredState, valuetype System.TimeSpan timeout, class Microsoft.Azure.Batch.ODATAMonitorControl controlParams, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskStateMonitor.WaitAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.TimeSpan,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub WaitAll (tasksToMonitor As IEnumerable(Of CloudTask), desiredState As TaskState, timeout As TimeSpan, Optional controlParams As ODATAMonitorControl = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.WaitAll : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.Common.TaskState * TimeSpan * Microsoft.Azure.Batch.ODATAMonitorControl * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="taskStateMonitor.WaitAll (tasksToMonitor, desiredState, timeout, controlParams, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToMonitor" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="desiredState" Type="Microsoft.Azure.Batch.Common.TaskState" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="controlParams" Type="Microsoft.Azure.Batch.ODATAMonitorControl" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToMonitor">監視するタスクのコレクション。</param>
        <param name="desiredState">タスクの対象の状態。 すべてのタスクがこの状態に 1 回以上に達すると、メソッドを終了します。</param>
        <param name="timeout">この呼び出しがタイムアウトするまでに待機する時間の最大量。</param>
        <param name="controlParams">モニター、各ポーリング間隔などのさまざまな設定を制御します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />です。</param>
        <summary>
            モニター、<see cref="T:Microsoft.Azure.Batch.CloudTask" />到達するまでその各メンバーの目的の状態を少なくとも 1 回のコレクション。
            </summary>
        <remarks>
          <para>
            それぞれの状態<see cref="T:Microsoft.Azure.Batch.CloudTask" />インスタンスを呼び出し時に権限を持つであると見なされます。
            インスタンスでは既に、<paramref name="desiredState" />は無視されます。
            <see cref="T:Microsoft.Azure.Batch.CloudTask" />コレクション内のインスタンスが読み取り専用として扱われます。
            つまり、呼び出しが完了したときに (タイムアウトか)、<see cref="T:Microsoft.Azure.Batch.CloudTask" />インスタンスを使用する前に更新する必要があります。
            </para>
          <para>
            これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.TaskStateMonitor.WhenAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.TimeSpan,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">場合にスローされます、<paramref name="timeout" />が経過しました。</exception>
      </Docs>
    </Member>
    <Member MemberName="WhenAll">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task WhenAll (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, Microsoft.Azure.Batch.Common.TaskState desiredState, System.Threading.CancellationToken cancellationToken, Microsoft.Azure.Batch.ODATAMonitorControl controlParams = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task WhenAll(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, valuetype Microsoft.Azure.Batch.Common.TaskState desiredState, valuetype System.Threading.CancellationToken cancellationToken, class Microsoft.Azure.Batch.ODATAMonitorControl controlParams, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskStateMonitor.WhenAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.Threading.CancellationToken,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.WhenAll : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.Common.TaskState * System.Threading.CancellationToken * Microsoft.Azure.Batch.ODATAMonitorControl * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="taskStateMonitor.WhenAll (tasksToMonitor, desiredState, cancellationToken, controlParams, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.TaskStateMonitor/&lt;WhenAll&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToMonitor" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="desiredState" Type="Microsoft.Azure.Batch.Common.TaskState" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="controlParams" Type="Microsoft.Azure.Batch.ODATAMonitorControl" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToMonitor">監視するタスクのコレクション。</param>
        <param name="desiredState">タスクの対象の状態。 すべてのタスクがこの状態に 1 回以上に達すると、メソッドを終了します。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <param name="controlParams">モニター、各ポーリング間隔などのさまざまな設定を制御します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />です。</param>
        <summary>
            モニター、<see cref="T:Microsoft.Azure.Batch.CloudTask" />到達するまでその各メンバーの目的の状態を少なくとも 1 回のコレクション。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>
            それぞれの状態<see cref="T:Microsoft.Azure.Batch.CloudTask" />インスタンスを呼び出し時に権限を持つであると見なされます。
            インスタンスでは既に、<paramref name="desiredState" />は無視されます。
            <see cref="T:Microsoft.Azure.Batch.CloudTask" />コレクション内のインスタンスが読み取り専用として扱われます。
            つまり、呼び出しが完了したときに (タイムアウトか)、<see cref="T:Microsoft.Azure.Batch.CloudTask" />インスタンスを使用する前に更新する必要があります。
            </para>
          <para>
            このメソッドは非同期的に実行されます。
            </para>
        </remarks>
        <exception cref="T:System.OperationCanceledException">場合にスローされます、<paramref name="cancellationToken" />が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="WhenAll">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task WhenAll (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, Microsoft.Azure.Batch.Common.TaskState desiredState, TimeSpan timeout, Microsoft.Azure.Batch.ODATAMonitorControl controlParams = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task WhenAll(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, valuetype Microsoft.Azure.Batch.Common.TaskState desiredState, valuetype System.TimeSpan timeout, class Microsoft.Azure.Batch.ODATAMonitorControl controlParams, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskStateMonitor.WhenAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.TimeSpan,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function WhenAll (tasksToMonitor As IEnumerable(Of CloudTask), desiredState As TaskState, timeout As TimeSpan, Optional controlParams As ODATAMonitorControl = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.WhenAll : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.Common.TaskState * TimeSpan * Microsoft.Azure.Batch.ODATAMonitorControl * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="taskStateMonitor.WhenAll (tasksToMonitor, desiredState, timeout, controlParams, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.TaskStateMonitor/&lt;WhenAll&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToMonitor" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="desiredState" Type="Microsoft.Azure.Batch.Common.TaskState" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="controlParams" Type="Microsoft.Azure.Batch.ODATAMonitorControl" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToMonitor">監視するタスクのコレクション。</param>
        <param name="desiredState">タスクの対象の状態。 すべてのタスクがこの状態に 1 回以上に達すると、メソッドを終了します。</param>
        <param name="timeout">この呼び出しがタイムアウトするまでに待機する時間の最大量。</param>
        <param name="controlParams">モニター、各ポーリング間隔などのさまざまな設定を制御します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />です。</param>
        <summary>
            モニター、<see cref="T:Microsoft.Azure.Batch.CloudTask" />到達するまでその各メンバーの目的の状態を少なくとも 1 回のコレクション。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>
            それぞれの状態<see cref="T:Microsoft.Azure.Batch.CloudTask" />インスタンスを呼び出し時に権限を持つであると見なされます。
            インスタンスでは既に、<paramref name="desiredState" />は無視されます。
            <see cref="T:Microsoft.Azure.Batch.CloudTask" />コレクション内のインスタンスが読み取り専用として扱われます。
            つまり、呼び出しが完了したときに (タイムアウトか)、<see cref="T:Microsoft.Azure.Batch.CloudTask" />インスタンスを使用する前に更新する必要があります。
            </para>
          <para>
            このメソッドは非同期的に実行されます。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">場合にスローされます、<paramref name="timeout" />が経過しました。</exception>
      </Docs>
    </Member>
  </Members>
</Type>