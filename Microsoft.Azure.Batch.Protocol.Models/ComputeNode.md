<Type Name="ComputeNode" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNode">
  <TypeSignature Language="C#" Value="public class ComputeNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNode extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNode" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNode" />
  <TypeSignature Language="F#" Value="type ComputeNode = class" />
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
            バッチ サービスでコンピューティング ノードです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.#ctor" />
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
            ComputeNode クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNode (string id = null, string url = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; state = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; schedulingState = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;DateTime&gt; lastBootTime = null, Nullable&lt;DateTime&gt; allocationTime = null, string ipAddress = null, string affinityId = null, string vmSize = null, Nullable&lt;int&gt; totalTasksRun = null, Nullable&lt;int&gt; runningTasksCount = null, Nullable&lt;int&gt; totalTasksSucceeded = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; recentTasks = null, Microsoft.Azure.Batch.Protocol.Models.StartTask startTask = null, Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation startTaskInfo = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; errors = null, Nullable&lt;bool&gt; isDedicated = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration endpointConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string url, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; state, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; schedulingState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastBootTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; allocationTime, string ipAddress, string affinityId, string vmSize, valuetype System.Nullable`1&lt;int32&gt; totalTasksRun, valuetype System.Nullable`1&lt;int32&gt; runningTasksCount, valuetype System.Nullable`1&lt;int32&gt; totalTasksSucceeded, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; recentTasks, class Microsoft.Azure.Batch.Protocol.Models.StartTask startTask, class Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation startTaskInfo, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; errors, valuetype System.Nullable`1&lt;bool&gt; isDedicated, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration endpointConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.SchedulingState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskInformation},Microsoft.Azure.Batch.Protocol.Models.StartTask,Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError},System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ComputeNode : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; * Microsoft.Azure.Batch.Protocol.Models.StartTask * Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNode" Usage="new Microsoft.Azure.Batch.Protocol.Models.ComputeNode (id, url, state, schedulingState, stateTransitionTime, lastBootTime, allocationTime, ipAddress, affinityId, vmSize, totalTasksRun, runningTasksCount, totalTasksSucceeded, recentTasks, startTask, startTaskInfo, certificateReferences, errors, isDedicated, endpointConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt;" />
        <Parameter Name="schedulingState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastBootTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="allocationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ipAddress" Type="System.String" />
        <Parameter Name="affinityId" Type="System.String" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="totalTasksRun" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="runningTasksCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="totalTasksSucceeded" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recentTasks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt;" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Batch.Protocol.Models.StartTask" />
        <Parameter Name="startTaskInfo" Type="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation" />
        <Parameter Name="certificateReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt;" />
        <Parameter Name="isDedicated" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="endpointConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration" />
      </Parameters>
      <Docs>
        <param name="id">コンピューティング ノードの ID。</param>
        <param name="url">コンピューティング ノードの URL です。</param>
        <param name="state">コンピューティング ノードの現在の状態。</param>
        <param name="schedulingState">コンピューティング ノードがタスクのスケジュール設定に使用できるかどうか。</param>
        <param name="stateTransitionTime">その現在の状態、コンピューティング ノードになった時刻。</param>
        <param name="lastBootTime">コンピューティング ノードが開始された時刻。</param>
        <param name="allocationTime">この計算ノードがプールに割り当てられ時間。</param>
        <param name="ipAddress">その他のコンピューティング ノードがこの計算ノードとの通信に使用できる IP アドレス。</param>
        <param name="affinityId">渡すことができるスケジュール タスクを要求できるタスクを追加するときにこのノードの識別子です。</param>
        <param name="vmSize">コンピューティング ノードをホストする仮想マシンのサイズ。</param>
        <param name="totalTasksRun">コンピューティング ノードで完了したジョブ タスクの合計数。 これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。</param>
        <param name="runningTasksCount">コンピューティング ノードでは、実行中のジョブのタスクの合計数。 これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。</param>
        <param name="totalTasksSucceeded">正常に (exitCode 0) が完了したジョブのタスクの合計数、コンピューティング ノード上。
            これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。</param>
        <param name="recentTasks">状態が最近変更されたタスクの一覧。</param>
        <param name="startTask">コンピューティング ノードで、プールに参加を実行する指定されたタスク。</param>
        <param name="startTaskInfo">コンピューティング ノードで、開始タスクの実行に関するランタイム情報。</param>
        <param name="certificateReferences">コンピューティング ノードにインストールされている証明書の一覧です。</param>
        <param name="errors">コンピューティング ノードで現在発生しているエラーの一覧。</param>
        <param name="isDedicated">この計算ノードが専用ノードかどうか。 False の場合、優先度の低いノードです。</param>
        <param name="endpointConfiguration">コンピューティング ノードのエンドポイント構成。</param>
        <summary>
            ComputeNode クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityId">
      <MemberSignature Language="C#" Value="public string AffinityId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AffinityId" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityId As String" />
      <MemberSignature Language="F#" Value="member this.AffinityId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AffinityId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の識別子をこのノードでタスクをスケジュールすることを要求するタスクを追加するときに渡すことができます。
            </summary>
        <value>To be added.</value>
        <remarks>
            これはソフト アフィニティだけであることに注意してください。 ターゲット ノードがビジー状態、またはタスクのスケジュール時に使用できない、タスクがスケジュールされる他の場所。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AllocationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AllocationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AllocationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allocationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールにこのコンピューティング ノードが割り当てられた時間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードにインストールされている証明書の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            Windows では、ノードを計算するため、バッチ サービスは、場所と指定された証明書ストアに証明書をインストールします。 Linux 計算ノードでは、証明書は、タスクの作業ディレクトリと変数 AZ_BATCH_CERTIFICATES_DIR がこの場所にクエリするタスクに指定された環境の内部ディレクトリに保存されます。 'RemoteUser' の可視性を持つ証明書は、'certs' ディレクトリは、ユーザーのホーム ディレクトリに作成 (など/home/{ユーザー名}/certs) および証明書はそのディレクトリに配置します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration EndpointConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration EndpointConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.EndpointConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointConfiguration As ComputeNodeEndpointConfiguration" />
      <MemberSignature Language="F#" Value="member this.EndpointConfiguration : Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.EndpointConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpointConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードのエンドポイント構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of ComputeNodeError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードで現在発生しているエラーの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Id" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            プールに追加されるすべてのノードには、一意の ID が割り当てられます
            ノードは、プールからを削除するたびにすべてのローカル ファイルが削除され、ID が解放され、新しいノードで再利用できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public string IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As String" />
      <MemberSignature Language="F#" Value="member this.IpAddress : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはその他のコンピューティング ノードがこの計算ノードとの通信に使用できる IP アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            プールに追加されるすべてのノードには、一意の IP アドレスが割り当てられます。
            ノードは、プールからを削除するたびにすべてのローカル ファイルが削除され、IP アドレスが解放され、新しいノードで再利用できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDedicated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IsDedicated" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDedicated As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDedicated : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IsDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDedicated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのコンピューティング ノードは、専用のノードかどうかを設定します。 False の場合、優先度の低いノードです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBootTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastBootTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastBootTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.LastBootTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBootTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastBootTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.LastBootTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastBootTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードを開始した時刻を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティは、ノードの状態が使用できない場合に存在していない可能性があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecentTasks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; RecentTasks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; RecentTasks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RecentTasks" />
      <MemberSignature Language="VB.NET" Value="Public Property RecentTasks As IList(Of TaskInformation)" />
      <MemberSignature Language="F#" Value="member this.RecentTasks : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RecentTasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recentTasks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または状態が最近変更されたタスクの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティは、プールに割り当てられているために、このノード上には、少なくとも 1 つのタスクが実行が場合にのみ存在します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RunningTasksCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RunningTasksCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RunningTasksCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RunningTasksCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RunningTasksCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RunningTasksCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RunningTasksCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runningTasksCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードでは、実行中のジョブのタスクの合計数を設定します。 これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulingState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; SchedulingState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; SchedulingState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.SchedulingState" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulingState As Nullable(Of SchedulingState)" />
      <MemberSignature Language="F#" Value="member this.SchedulingState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.SchedulingState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedulingState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードがタスクのスケジュール設定に使用できるかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値が含まれます: 'enabled'、'disabled'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.Protocol.Models.StartTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードで、プールに参加を実行する指定されたタスクを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTaskInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation StartTaskInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation StartTaskInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTaskInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTaskInfo As StartTaskInformation" />
      <MemberSignature Language="F#" Value="member this.StartTaskInfo : Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTaskInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTaskInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードで、開始タスクの実行に関するランタイム情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of ComputeNodeState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.State" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードの現在の状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            優先度の低いノードが占有されています。 別のノードが利用可能になったら、切り替えだった場合、ノード上で実行されているタスクを再スケジュールされます。 使用可能な値が含まれます: 'アイドル'、'再起動中'、'再イメージ化'、'実行中'、'使用不可'、'作成中'、'開始'、'waitingForStartTask'、'startTaskFailed'、'unknown'、'leavingPool'、'オフライン'、'割り込ま'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StateTransitionTime" />
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
            取得または計算ノードが、現在の状態を入力する時間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksRun">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksRun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksRun" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalTasksRun As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksRun : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalTasksRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードで完了したジョブ タスクの合計数を設定します。 これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksSucceeded { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalTasksSucceeded As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksSucceeded : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalTasksSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を正常に (exitCode 0) が完了したジョブのタスクの合計数、コンピューティング ノード上。 これには、ジョブ マネージャー タスクと通常のタスクがジョブの準備、ジョブのリリースまたは開始タスクではなくが含まれます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードの URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computeNode.Validate " />
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
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードをホストする仮想マシンのサイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            クラウド サービス プール (プール cloudServiceConfiguration で作成された) の仮想マシンの利用可能なサイズについては、クラウド サービス (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/) のサイズを参照してください。
            バッチには、ExtraSmall、A1V2 A2V2 を除くすべてのクラウド サービス VM サイズがサポートしています。 (プール virtualMachineConfiguration で作成した) 仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (Linux) (https://azure.microsoft.com/documentation/articles/ の仮想マシンのサイズを参照してください。仮想マシンの linux-サイズ/) または仮想マシン (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/) のサイズ。
            バッチには、STANDARD_A0 と premium storage (STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>