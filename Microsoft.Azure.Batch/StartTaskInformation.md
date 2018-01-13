<Type Name="StartTaskInformation" FullName="Microsoft.Azure.Batch.StartTaskInformation">
  <TypeSignature Language="C#" Value="public class StartTaskInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StartTaskInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.StartTaskInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class StartTaskInformation" />
  <TypeSignature Language="F#" Value="type StartTaskInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            現在の状態、エラーの詳細、終了コード、開始時刻、終了時刻などを含む、開始タスクの詳細なランタイム情報を指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContainerInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.ContainerInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerInformation As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInformation : Microsoft.Azure.Batch.TaskContainerExecutionInformation" Usage="Microsoft.Azure.Batch.StartTaskInformation.ContainerInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskContainerExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクを実行しているコンテナーに関する情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            タスクがコンテナーのコンテキストで実行している場合にのみ、このプロパティが設定されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.StartTaskInformation.EndTime" />
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
            タスクが完了した時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.StartTaskInformation.ExitCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクのコマンドラインで指定されたプログラムの終了コードを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティはタスクがの場合にのみ返されます、<see cref="F:Microsoft.Azure.Batch.Common.StartTaskState.Completed" />状態です。 プロセスの終了コードは、そのプロセスのアプリケーションの開発者によって実装されている特定の規則を反映します。 意思決定を行うコードで終了コード値を使用する場合は、アプリケーションのプロセスによって使用される終了コード規則を理解していることを確認します。 終了コードがコンピューティング ノードなど、オペレーティング システム、プロセスを強制的に終了する場合に生成される可能性がありますに注意してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskFailureInformation FailureInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskFailureInformation FailureInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.FailureInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureInformation As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInformation : Microsoft.Azure.Batch.TaskFailureInformation" Usage="Microsoft.Azure.Batch.StartTaskInformation.FailureInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskFailureInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            存在する場合、タスクの失敗の記述を情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            タスクがである場合にのみ、このプロパティは設定、<see cref="F:Microsoft.Azure.Batch.Common.StartTaskState.Completed" />状態にあり、エラーが発生しました。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRetryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRetryTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRetryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.LastRetryTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRetryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRetryTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.StartTaskInformation.LastRetryTime" />
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
            開始タスクの実行が Batch service によって再試行された最新の時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;" Usage="Microsoft.Azure.Batch.StartTaskInformation.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タスクの実行の結果を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            値が場合<see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />、エラーの詳細は含まれてし、<see cref="P:Microsoft.Azure.Batch.StartTaskInformation.FailureInformation" />プロパティです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryCount">
      <MemberSignature Language="C#" Value="public int RetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.RetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RetryCount : int" Usage="Microsoft.Azure.Batch.StartTaskInformation.RetryCount" />
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
            開始タスクが、バッチ システムによって再試行された回数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.StartTaskInformation.StartTime" />
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
            タスクが実行を開始された時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.StartTaskState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.StartTaskState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.StartTaskInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As StartTaskState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Batch.Common.StartTaskState" Usage="Microsoft.Azure.Batch.StartTaskInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.StartTaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            開始タスクの現在の実行状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>