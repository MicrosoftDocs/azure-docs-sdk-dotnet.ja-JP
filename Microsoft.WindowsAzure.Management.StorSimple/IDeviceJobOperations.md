<Type Name="IDeviceJobOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations">
  <TypeSignature Language="C#" Value="public interface IDeviceJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDeviceJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDeviceJobOperations" />
  <TypeSignature Language="F#" Value="type IDeviceJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            デバイスのジョブに関連するすべての操作
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync (string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync(string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.BeginUpdateDeviceJobAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateDeviceJobAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="iDeviceJobOperations.BeginUpdateDeviceJobAsync (deviceId, jobId, updateRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            デバイスの id
            </param>
        <param name="jobId">
            更新するジョブの id
            </param>
        <param name="updateRequest">
            データを要求する、実行されるアクションが含まれています
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            デバイスのジョブを更新する非同期タスクを開始します。
            </summary>
        <returns>
            これは、非同期呼び出しは、すべてのタスク応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync (string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int skip, int top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync(string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int32 skip, int32 top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.GetAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Int32,System.Int32,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * string * string * string * int * int * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;" Usage="iDeviceJobOperations.GetAsync (deviceId, jobType, jobStatus, jobId, startTime, endTime, skip, top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="jobStatus" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            ジョブのデバイスのデバイス id
            </param>
        <param name="jobType">
            DeviceJob の種類
            </param>
        <param name="jobStatus">
            ジョブの状態
            </param>
        <param name="jobId">
            ジョブの id
            </param>
        <param name="startTime">
            ジョブの開始時刻、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '
            </param>
        <param name="endTime">
            終了時刻をジョブに、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '
            </param>
        <param name="skip">
            改ページ パラメーター。 、つまり返される最初のエントリのインデックスをスキップするエントリの数
            </param>
        <param name="top">
            改ページ パラメーター。 'Skip' のエントリ数をスキップした後に返される項目の数
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>To be added.</summary>
        <returns>
            デバイスのジョブの取得のクエリの応答モデル
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync (string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync(string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.UpdateDeviceJobAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceJobAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iDeviceJobOperations.UpdateDeviceJobAsync (deviceId, jobId, updateRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            デバイスの id
            </param>
        <param name="jobId">
            更新するジョブの id
            </param>
        <param name="updateRequest">
            データを要求する、実行されるアクションが含まれています
            </param>
        <param name="customRequestHeaders">
            カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            デバイスのジョブを更新します。
            </summary>
        <returns>
            非同期タスクに関する情報
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>