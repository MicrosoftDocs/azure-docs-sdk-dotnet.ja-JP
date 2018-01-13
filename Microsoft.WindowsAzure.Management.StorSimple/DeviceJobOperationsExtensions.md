<Type Name="DeviceJobOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceJobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceJobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceJobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceJobOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            これは、StorSimple のオブジェクトを管理する rest ベースの API
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDeviceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceJob (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceJob(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJob(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceJob : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJob (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイスの id
            </param>
        <param name="jobId">
            必須。 更新するジョブの id
            </param>
        <param name="updateRequest">
            必須。 データを要求する、実行されるアクションが含まれています
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
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
    <Member MemberName="BeginUpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJobAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceJobAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJobAsync (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイスの id
            </param>
        <param name="jobId">
            必須。 更新するジョブの id
            </param>
        <param name="updateRequest">
            必須。 データを要求する、実行されるアクションが含まれています
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int skip, int top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int32 skip, int32 top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Int32,System.Int32,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * string * string * string * string * int * int * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.Get (operations, deviceId, jobType, jobStatus, jobId, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="jobStatus" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。
            </param>
        <param name="deviceId">
            省略可能。 ジョブのデバイスのデバイス id
            </param>
        <param name="jobType">
            省略可能。 DeviceJob の種類
            </param>
        <param name="jobStatus">
            省略可能。 ジョブの状態
            </param>
        <param name="jobId">
            省略可能。 ジョブの id
            </param>
        <param name="startTime">
            省略可能。 ジョブの開始時刻、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '
            </param>
        <param name="endTime">
            省略可能。 終了時刻をジョブに、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '
            </param>
        <param name="skip">
            必須。 改ページ パラメーター。 、つまり返される最初のエントリのインデックスをスキップするエントリの数
            </param>
        <param name="top">
            必須。 改ページ パラメーター。 'Skip' のエントリ数をスキップした後に返される項目の数
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            デバイスのジョブの取得のクエリの応答モデル
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int skip, int top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int32 skip, int32 top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Int32,System.Int32,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * string * string * string * string * int * int * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.GetAsync (operations, deviceId, jobType, jobStatus, jobId, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="jobStatus" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。
            </param>
        <param name="deviceId">
            省略可能。 ジョブのデバイスのデバイス id
            </param>
        <param name="jobType">
            省略可能。 DeviceJob の種類
            </param>
        <param name="jobStatus">
            省略可能。 ジョブの状態
            </param>
        <param name="jobId">
            省略可能。 ジョブの id
            </param>
        <param name="startTime">
            省略可能。 ジョブの開始時刻、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '
            </param>
        <param name="endTime">
            省略可能。 終了時刻をジョブに、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '
            </param>
        <param name="skip">
            必須。 改ページ パラメーター。 、つまり返される最初のエントリのインデックスをスキップするエントリの数
            </param>
        <param name="top">
            必須。 改ページ パラメーター。 'Skip' のエントリ数をスキップした後に返される項目の数
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
            </param>
        <summary>To be added.</summary>
        <returns>
            デバイスのジョブの取得のクエリの応答モデル
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceJob (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceJob(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJob(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceJob : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJob (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイスの id
            </param>
        <param name="jobId">
            必須。 更新するジョブの id
            </param>
        <param name="updateRequest">
            必須。 データを要求する、実行されるアクションが含まれています
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
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
    <Member MemberName="UpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJobAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceJobAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJobAsync (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。
            </param>
        <param name="deviceId">
            必須。 デバイスの id
            </param>
        <param name="jobId">
            必須。 更新するジョブの id
            </param>
        <param name="updateRequest">
            必須。 データを要求する、実行されるアクションが含まれています
            </param>
        <param name="customRequestHeaders">
            必須。 カスタム要求ヘッダーをクライアントが使用する必要があります。
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