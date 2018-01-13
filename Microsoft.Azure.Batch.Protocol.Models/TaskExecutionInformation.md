<Type Name="TaskExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation">
  <TypeSignature Language="C#" Value="public class TaskExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskExecutionInformation" />
  <TypeSignature Language="F#" Value="type TaskExecutionInformation = class" />
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
            タスクの実行に関する情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.#ctor" />
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
            TaskExecutionInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskExecutionInformation (int retryCount, int requeueCount, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;int&gt; exitCode = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo = null, Nullable&lt;DateTime&gt; lastRetryTime = null, Nullable&lt;DateTime&gt; lastRequeueTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 retryCount, int32 requeueCount, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;int32&gt; exitCode, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRetryTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRequeueTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.#ctor(System.Int32,System.Int32,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (retryCount As Integer, requeueCount As Integer, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional exitCode As Nullable(Of Integer) = null, Optional containerInfo As TaskContainerExecutionInformation = null, Optional failureInfo As TaskFailureInformation = null, Optional lastRetryTime As Nullable(Of DateTime) = null, Optional lastRequeueTime As Nullable(Of DateTime) = null, Optional result As Nullable(Of TaskExecutionResult) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation : int * int * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation (retryCount, requeueCount, startTime, endTime, exitCode, containerInfo, failureInfo, lastRetryTime, lastRequeueTime, result)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retryCount" Type="System.Int32" />
        <Parameter Name="requeueCount" Type="System.Int32" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="exitCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="containerInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" />
        <Parameter Name="failureInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" />
        <Parameter Name="lastRetryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastRequeueTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;" />
      </Parameters>
      <Docs>
        <param name="retryCount">Batch サービスによりタスクが再試行された回数。</param>
        <param name="requeueCount">Batch サービスによりタスクがユーザー要求の結果として再度キューに入れられる回数です。</param>
        <param name="startTime">タスクの実行が開始した時刻です。</param>
        <param name="endTime">タスクが完了した時刻です。</param>
        <param name="exitCode">タスクのコマンドラインで指定されたプログラムの終了コード。</param>
        <param name="containerInfo">タスクを実行しているコンテナーについて説明します。</param>
        <param name="failureInfo">存在する場合、タスクの失敗を説明する情報です。</param>
        <param name="lastRetryTime">タスクの再試行が実行を開始する最新の時間。</param>
        <param name="lastRequeueTime">タスクがされてキューに再登録、Batch service によって、ユーザーの要求の結果として、最新の時刻。</param>
        <param name="result">タスクの実行の結果。</param>
        <summary>
            TaskExecutionInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.ContainerInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerInfo As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInfo : Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.ContainerInfo" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.EndTime" />
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
            取得またはタスクが完了した時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            タスクが完了済みの状態の場合にのみ、このプロパティが設定されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.ExitCode" />
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
            取得またはタスクのコマンドラインで指定されたプログラムの終了コードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティは、タスクが完了した状態で場合にのみに設定されます。 一般に、プロセスの終了コードは、そのプロセスのアプリケーションの開発者によって実装されている特定の規則を反映します。 意思決定を行うコードで終了コード値を使用する場合は、アプリケーションのプロセスによって使用される終了コード規則を理解していることを確認します。 ただし、バッチ サービスには (タイムアウト、または API を使用してユーザーの終了) のためのタスクが終了した場合、オペレーティング システム定義の終了コードを参照してください可能性があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.FailureInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureInfo As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInfo : Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.FailureInfo" />
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
    <Member MemberName="LastRequeueTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRequeueTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRequeueTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.LastRequeueTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastRequeueTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRequeueTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.LastRequeueTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastRequeueTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定するタスクがされてキューに再登録、Batch service によって、ユーザーの要求の結果として、最新の時間。
            </summary>
        <value>To be added.</value>
        <remarks>
            RequeueCount が 0 以外の場合にのみ、このプロパティが設定されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRetryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRetryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRetryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.LastRetryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastRetryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRetryTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.LastRetryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastRetryTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクの再試行が実行を開始する最新の時間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            この要素は、タスクが再試行された場合にのみ存在 (つまり retryCount が 0 以外)。 存在する場合、これは通常、開始時刻と同じですが再試行; 以外の理由により、タスクが再起動された場合は異なる場合があります。たとえば、再試行中にコンピューティング ノードを再起動すると場合、startTime が更新されますが、lastRetryTime はありません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequeueCount">
      <MemberSignature Language="C#" Value="public int RequeueCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RequeueCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.RequeueCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RequeueCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RequeueCount : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.RequeueCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requeueCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクがされてキューに再登録、Batch service によって、ユーザーの要求の結果として回数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            実行の再配置、プール (プールのサイズ変更/圧縮) または、ジョブを無効にされている場合、ユーザーはからユーザー削除のノードが実行されているタスクのノードであるを指定するとします。 この回数は、タスクがこうした理由により何回キューに入れられたかを追跡します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.Result" />
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
    <Member MemberName="RetryCount">
      <MemberSignature Language="C#" Value="public int RetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.RetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RetryCount : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.RetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクが、Batch service によって再試行された回数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            タスクのアプリケーション エラー (0 以外の終了コード) は再試行処理前のエラー (タスクを実行できませんでした) され、ファイルのアップロード エラーは再試行されません。 バッチ サービスは、制約で指定された上限に達するまでタスクを再試行します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.StartTime" />
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
            取得またはタスクが実行を開始された時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            '' 実行中の状態に対応して、実行タスクは、リソース ファイルまたはアプリケーション パッケージでは、次に、開始時刻を指定する場合のダウンロードまたは展開これらのタスクが開始された時間を反映するためです。 タスクが再起動または再実行された場合は、タスクが実行を開始したつい最近の時刻となります。 このプロパティは、実行中または完了の状態にあるタスクにのみ存在します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskExecutionInformation.Validate " />
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