<Type Name="JobClient" FullName="Microsoft.Azure.Devices.JobClient">
  <TypeSignature Language="C#" Value="public abstract class JobClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit JobClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.JobClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class JobClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type JobClient = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            ジョブの管理
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected JobClient ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CancelJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CancelJobAsync (jobId As String) As Task(Of JobResponse)" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.CancelJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId">キャンセルするジョブの id</param>
        <summary>
            指定した ID を使用してジョブを取り消します/削除
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; CancelJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CancelJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.CancelJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">キャンセルするジョブの id</param>
        <param name="cancellationToken">タスクのキャンセル トークン</param>
        <summary>
            指定した ID を使用してジョブを取り消します/削除
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="jobClient.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            JobClient インスタンスを終了し、そのリソースを破棄します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.JobClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.JobClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As JobClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.Devices.JobClient" Usage="Microsoft.Azure.Devices.JobClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.JobClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"> Iot Hub の接続文字列。</param>
        <summary>
            Iot ハブの接続文字列から、JobClient を作成します。
            </summary>
        <returns> JobClient インスタンス。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery () As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : unit -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            どのジョブからすべてのジョブの種類と状態の応答が取得されますページによってページ IQuery を取得します。
            </summary>
        <returns>IQuery</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (Nullable&lt;int&gt; pageSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(valuetype System.Nullable`1&lt;int32&gt; pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (pageSize As Nullable(Of Integer)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : Nullable&lt;int&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery pageSize" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pageSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="pageSize">ジョブ応答をページの数</param>
        <summary>
            IQuery 使用されるジョブ応答がページによってページが取得され、ページ サイズを指定の取得します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (Nullable&lt;Microsoft.Azure.Devices.JobType&gt; jobType, Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; jobStatus);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobType&gt; jobType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobStatus&gt; jobStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery(System.Nullable{Microsoft.Azure.Devices.JobType},System.Nullable{Microsoft.Azure.Devices.JobStatus})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (jobType As Nullable(Of JobType), jobStatus As Nullable(Of JobStatus)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : Nullable&lt;Microsoft.Azure.Devices.JobType&gt; * Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery (jobType, jobStatus)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobType" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobType&gt;" />
        <Parameter Name="jobStatus" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="jobType">クエリにジョブの種類。 クエリを実行しない場合は null になります。</param>
        <param name="jobStatus">ジョブの状態をクエリします。 クエリを実行しない場合は null になります。</param>
        <summary>
            取得するジョブを指定した jobType と jobStatus に対する応答が取得されますページによってページ IQuery
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (Nullable&lt;Microsoft.Azure.Devices.JobType&gt; jobType, Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; jobStatus, Nullable&lt;int&gt; pageSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobType&gt; jobType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Devices.JobStatus&gt; jobStatus, valuetype System.Nullable`1&lt;int32&gt; pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.CreateQuery(System.Nullable{Microsoft.Azure.Devices.JobType},System.Nullable{Microsoft.Azure.Devices.JobStatus},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (jobType As Nullable(Of JobType), jobStatus As Nullable(Of JobStatus), pageSize As Nullable(Of Integer)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : Nullable&lt;Microsoft.Azure.Devices.JobType&gt; * Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="jobClient.CreateQuery (jobType, jobStatus, pageSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobType" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobType&gt;" />
        <Parameter Name="jobStatus" Type="System.Nullable&lt;Microsoft.Azure.Devices.JobStatus&gt;" />
        <Parameter Name="pageSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="jobType">クエリにジョブの種類。 クエリを実行しない場合は null になります。</param>
        <param name="jobStatus">ジョブの状態をクエリします。 クエリを実行しない場合は null になります。</param>
        <param name="pageSize">ジョブ応答をページの数</param>
        <summary>
            JobType jobStatus ページ単位で取得し、ページ サイズを指定するジョブをへの応答が指定された IQuery を取得します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="jobClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="jobClient.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
          <c>true</c>マネージ コードとアンマネージ リソースを解放するには<c>false</c>アンマネージ リソースだけを解放します。</param>
        <summary>
            リリースでは、アンマネージし、必要に応じてマネージ リソース。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.GetJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetJobAsync (jobId As String) As Task(Of JobResponse)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.GetJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId">取得するジョブの id</param>
        <summary>
            指定した ID を使用してジョブを取得します。
            </summary>
        <returns>一致する JobResponse オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; GetJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.GetJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.GetJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">取得するジョブの id</param>
        <param name="cancellationToken">タスクのキャンセル トークン</param>
        <summary>
            指定した ID を使用してジョブを取得します。
            </summary>
        <returns>一致する JobResponse オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="jobClient.OpenAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            JobClient インスタンスを明示的に開きます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleDeviceMethodAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, DateTime startTimeUtc, long maxExecutionTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleDeviceMethodAsync(System.String,System.String,Microsoft.Azure.Devices.CloudToDeviceMethod,System.DateTime,System.Int64)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleDeviceMethodAsync : string * string * Microsoft.Azure.Devices.CloudToDeviceMethod * DateTime * int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleDeviceMethodAsync (jobId, queryCondition, cloudToDeviceMethod, startTimeUtc, maxExecutionTimeInSeconds)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="cloudToDeviceMethod" Type="Microsoft.Azure.Devices.CloudToDeviceMethod" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="jobId">このジョブの一意のジョブ Id</param>
        <param name="queryCondition">ジョブを実行するデバイスを評価する条件をクエリします。</param>
        <param name="cloudToDeviceMethod">メソッドの呼び出しのパラメーター</param>
        <param name="startTimeUtc">ジョブを開始する Utc の日付時刻</param>
        <param name="maxExecutionTimeInSeconds">最大実行時間 (秒)、つまり、ttl 期間のジョブを実行できます。</param>
        <summary>
            1 つまたは複数のデバイスでデバイス メソッドを実行する新しいジョブを作成します。
            </summary>
        <returns>JobResponse オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleDeviceMethodAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, DateTime startTimeUtc, long maxExecutionTimeInSeconds, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleDeviceMethodAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleDeviceMethodAsync(System.String,System.String,Microsoft.Azure.Devices.CloudToDeviceMethod,System.DateTime,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleDeviceMethodAsync : string * string * Microsoft.Azure.Devices.CloudToDeviceMethod * DateTime * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleDeviceMethodAsync (jobId, queryCondition, cloudToDeviceMethod, startTimeUtc, maxExecutionTimeInSeconds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="cloudToDeviceMethod" Type="Microsoft.Azure.Devices.CloudToDeviceMethod" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">このジョブの一意のジョブ Id</param>
        <param name="queryCondition">ジョブを実行するデバイスを評価する条件をクエリします。</param>
        <param name="cloudToDeviceMethod">メソッドの呼び出しのパラメーター</param>
        <param name="startTimeUtc">ジョブを開始する Utc の日付時刻</param>
        <param name="maxExecutionTimeInSeconds">最大実行時間 (秒)、つまり、ttl 期間のジョブを実行できます。</param>
        <param name="cancellationToken">タスクのキャンセル トークン</param>
        <summary>
            1 つまたは複数のデバイスでデバイス メソッドを実行する新しいジョブを作成します。
            </summary>
        <returns>JobResponse オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleTwinUpdateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.Shared.Twin twin, DateTime startTimeUtc, long maxExecutionTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.Shared.Twin twin, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleTwinUpdateAsync(System.String,System.String,Microsoft.Azure.Devices.Shared.Twin,System.DateTime,System.Int64)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleTwinUpdateAsync : string * string * Microsoft.Azure.Devices.Shared.Twin * DateTime * int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleTwinUpdateAsync (jobId, queryCondition, twin, startTimeUtc, maxExecutionTimeInSeconds)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="twin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="jobId">このジョブの一意のジョブ Id</param>
        <param name="queryCondition">ジョブを実行するデバイスを評価する条件をクエリします。</param>
        <param name="twin">対になったオブジェクトの更新を使用するには</param>
        <param name="startTimeUtc">ジョブを開始する Utc の日付時刻</param>
        <param name="maxExecutionTimeInSeconds">最大実行時間 (秒)、つまり、ttl 期間のジョブを実行できます。</param>
        <summary>
            対になったタグと 1 つまたは複数のデバイスで必要なプロパティを更新する、新しいジョブを作成します。
            </summary>
        <returns>JobResponse オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleTwinUpdateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync (string jobId, string queryCondition, Microsoft.Azure.Devices.Shared.Twin twin, DateTime startTimeUtc, long maxExecutionTimeInSeconds, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobResponse&gt; ScheduleTwinUpdateAsync(string jobId, string queryCondition, class Microsoft.Azure.Devices.Shared.Twin twin, valuetype System.DateTime startTimeUtc, int64 maxExecutionTimeInSeconds, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.JobClient.ScheduleTwinUpdateAsync(System.String,System.String,Microsoft.Azure.Devices.Shared.Twin,System.DateTime,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleTwinUpdateAsync : string * string * Microsoft.Azure.Devices.Shared.Twin * DateTime * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;" Usage="jobClient.ScheduleTwinUpdateAsync (jobId, queryCondition, twin, startTimeUtc, maxExecutionTimeInSeconds, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="queryCondition" Type="System.String" />
        <Parameter Name="twin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="startTimeUtc" Type="System.DateTime" />
        <Parameter Name="maxExecutionTimeInSeconds" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">このジョブの一意のジョブ Id</param>
        <param name="queryCondition">ジョブを実行するデバイスを評価する条件をクエリします。</param>
        <param name="twin">対になったオブジェクトの更新を使用するには</param>
        <param name="startTimeUtc">ジョブを開始する Utc の日付時刻</param>
        <param name="maxExecutionTimeInSeconds">最大実行時間 (秒)、つまり、ttl 期間のジョブを実行できます。</param>
        <param name="cancellationToken">タスクのキャンセル トークン</param>
        <summary>
            対になったタグと 1 つまたは複数のデバイスで必要なプロパティを更新する、新しいジョブを作成します。
            </summary>
        <returns>JobResponse オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>