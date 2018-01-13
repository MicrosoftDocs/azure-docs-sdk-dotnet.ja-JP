<Type Name="SubtaskInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation">
  <TypeSignature Language="C#" Value="public class SubtaskInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubtaskInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class SubtaskInformation" />
  <TypeSignature Language="F#" Value="type SubtaskInformation = class" />
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
            Azure Batch のサブタスクについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubtaskInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SubtaskInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubtaskInformation (Nullable&lt;int&gt; id = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation nodeInfo = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;int&gt; exitCode = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; state = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; previousState = null, Nullable&lt;DateTime&gt; previousStateTransitionTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; id, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation nodeInfo, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;int32&gt; exitCode, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; previousState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; previousStateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.#ctor(System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.SubtaskState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.SubtaskState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As Nullable(Of Integer) = null, Optional nodeInfo As ComputeNodeInformation = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional exitCode As Nullable(Of Integer) = null, Optional containerInfo As TaskContainerExecutionInformation = null, Optional failureInfo As TaskFailureInformation = null, Optional state As Nullable(Of SubtaskState) = null, Optional stateTransitionTime As Nullable(Of DateTime) = null, Optional previousState As Nullable(Of SubtaskState) = null, Optional previousStateTransitionTime As Nullable(Of DateTime) = null, Optional result As Nullable(Of TaskExecutionResult) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation : Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation (id, nodeInfo, startTime, endTime, exitCode, containerInfo, failureInfo, state, stateTransitionTime, previousState, previousStateTransitionTime, result)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="nodeInfo" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="exitCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="containerInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" />
        <Parameter Name="failureInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="previousState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt;" />
        <Parameter Name="previousStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;" />
      </Parameters>
      <Docs>
        <param name="id">サブタスクの ID。</param>
        <param name="nodeInfo">サブタスクが実行したコンピューティング ノードに関する情報です。</param>
        <param name="startTime">サブタスクが実行を開始された時刻。 サブタスクが再起動した場合は再試行、サブタスクが実行を開始する、最新の時間です。</param>
        <param name="endTime">サブタスクが完了した時刻。</param>
        <param name="exitCode">サブタスクのコマンド ラインで指定されたプログラムの終了コード。</param>
        <param name="containerInfo">タスクを実行しているコンテナーについて説明します。</param>
        <param name="failureInfo">存在する場合、タスクの失敗を説明する情報です。</param>
        <param name="state">サブタスクの現在の状態。</param>
        <param name="stateTransitionTime">その現在の状態、サブタスクになった時刻。</param>
        <param name="previousState">サブタスクの以前の状態。</param>
        <param name="previousStateTransitionTime">サブタスクを以前の状態が入力された時刻。</param>
        <param name="result">タスクの実行の結果。</param>
        <summary>
            SubtaskInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.ContainerInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerInfo As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInfo : Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.ContainerInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクを実行しているコンテナーに関する情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            タスクがコンテナーのコンテキストで実行している場合にのみ、このプロパティが設定されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブタスクが完了した時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            完了済みの状態では、サブタスクの場合にのみ、このプロパティが設定されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.ExitCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブタスクのコマンド ラインで指定されたプログラムの終了コードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            サブタスクが完了した状態である場合にのみ、このプロパティが設定されます。
            一般に、プロセスの終了コードは、そのプロセスのアプリケーションの開発者によって実装されている特定の規則を反映します。 意思決定を行うコードで終了コード値を使用する場合は、アプリケーションのプロセスによって使用される終了コード規則を理解していることを確認します。 ただし、バッチ サービスには (タイムアウト、または API を使用してユーザーの終了) のためのサブタスクが終了した場合、オペレーティング システム定義の終了コードを参照してください可能性があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.FailureInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureInfo As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInfo : Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.FailureInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failureInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または存在する場合に、タスクの失敗を示す情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティは、タスクが完了した状態の場合にのみ設定され、エラーが発生しました。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Id : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブタスクの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation NodeInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation NodeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.NodeInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeInfo As ComputeNodeInformation" />
      <MemberSignature Language="F#" Value="member this.NodeInfo : Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.NodeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブタスクが実行したコンピューティング ノードに関する情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; PreviousState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousState As Nullable(Of SubtaskState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブタスクの以前の状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            サブタスクが実行中の初期状態にある場合、このプロパティは設定されません。 使用可能な値が含まれます: 'を準備する'、'実行中'、'完了'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブタスクが以前の状態を入力する時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            サブタスクが実行中の初期状態にある場合、このプロパティは設定されません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="result")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクの実行の結果を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            場合は、値は '失敗'、エラーの詳細は failureInfo プロパティで確認できます。 使用可能な値が含まれます: 'は success'、'失敗'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブタスクが実行を開始された時刻を設定します。 サブタスクが再起動した場合は再試行、サブタスクが実行を開始する、最新の時間です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of SubtaskState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブタスクの現在の状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値が含まれます: 'を準備する'、'実行中'、'完了'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはサブタスクが、現在の状態を入力する時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="subtaskInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>