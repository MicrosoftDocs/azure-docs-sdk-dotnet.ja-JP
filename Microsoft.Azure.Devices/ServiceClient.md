<Type Name="ServiceClient" FullName="Microsoft.Azure.Devices.ServiceClient">
  <TypeSignature Language="C#" Value="public abstract class ServiceClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.ServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ServiceClient = class&#xA;    interface IDisposable" />
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
            サービスがメッセージを送信するデバイスに使用できるメソッドが含まれます
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="serviceClient.CloseAsync " />
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
            サービスのインスタンスを閉じる
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.ServiceClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.ServiceClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As ServiceClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.Devices.ServiceClient" Usage="Microsoft.Azure.Devices.ServiceClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.ServiceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Iot hub への接続文字列</param>
        <summary>
            指定された接続文字列からサービスを作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.ServiceClient CreateFromConnectionString (string connectionString, Microsoft.Azure.Devices.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.ServiceClient CreateFromConnectionString(string connectionString, valuetype Microsoft.Azure.Devices.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.CreateFromConnectionString(System.String,Microsoft.Azure.Devices.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * Microsoft.Azure.Devices.TransportType -&gt; Microsoft.Azure.Devices.ServiceClient" Usage="Microsoft.Azure.Devices.ServiceClient.CreateFromConnectionString (connectionString, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.ServiceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="transportType" Type="Microsoft.Azure.Devices.TransportType" />
      </Parameters>
      <Docs>
        <param name="connectionString">Iot hub への接続文字列</param>
        <param name="transportType">Amqp または Websocket トランスポート経由での Amqp を使用するかどうかを指定します</param>
        <summary>
            指定したトランスポートの種類を使用して、指定された接続文字列からサービスを作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="serviceClient.Dispose " />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="serviceClient.Dispose disposing" />
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
    <Member MemberName="GetFeedbackReceiver">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.FeedbackReceiver&lt;Microsoft.Azure.Devices.FeedbackBatch&gt; GetFeedbackReceiver ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.FeedbackReceiver`1&lt;class Microsoft.Azure.Devices.FeedbackBatch&gt; GetFeedbackReceiver() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.GetFeedbackReceiver" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetFeedbackReceiver () As FeedbackReceiver(Of FeedbackBatch)" />
      <MemberSignature Language="F#" Value="abstract member GetFeedbackReceiver : unit -&gt; Microsoft.Azure.Devices.FeedbackReceiver&lt;Microsoft.Azure.Devices.FeedbackBatch&gt;" Usage="serviceClient.GetFeedbackReceiver " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.FeedbackReceiver&lt;Microsoft.Azure.Devices.FeedbackBatch&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            FeedbackReceiver を取得します。
            </summary>
        <returns>FeedbackReceiver のインスタンス</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileNotificationReceiver">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.FileNotificationReceiver&lt;Microsoft.Azure.Devices.FileNotification&gt; GetFileNotificationReceiver ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.FileNotificationReceiver`1&lt;class Microsoft.Azure.Devices.FileNotification&gt; GetFileNotificationReceiver() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.GetFileNotificationReceiver" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetFileNotificationReceiver () As FileNotificationReceiver(Of FileNotification)" />
      <MemberSignature Language="F#" Value="abstract member GetFileNotificationReceiver : unit -&gt; Microsoft.Azure.Devices.FileNotificationReceiver&lt;Microsoft.Azure.Devices.FileNotification&gt;" Usage="serviceClient.GetFileNotificationReceiver " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.FileNotificationReceiver&lt;Microsoft.Azure.Devices.FileNotification&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            FeedbackReceiver を取得します。
            </summary>
        <returns>FeedbackReceiver のインスタンス</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatisticsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt; GetServiceStatisticsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.ServiceStatistics&gt; GetServiceStatisticsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.GetServiceStatisticsAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetServiceStatisticsAsync () As Task(Of ServiceStatistics)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatisticsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt;" Usage="serviceClient.GetServiceStatisticsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Iot Hub のサービスの統計を取得します。
            </summary>
        <returns>現在のサービス統計情報を含む ServiceStatistics オブジェクトを返します</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatisticsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt; GetServiceStatisticsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.ServiceStatistics&gt; GetServiceStatisticsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.GetServiceStatisticsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatisticsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt;" Usage="serviceClient.GetServiceStatisticsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
            これにより、トークンは、操作をキャンセルできます。
            </param>
        <summary>
            Iot Hub のサービスの統計を取得します。
            </summary>
        <returns>現在のサービス統計情報を含む ServiceStatistics オブジェクトを返します</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeDeviceMethodAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt; InvokeDeviceMethodAsync (string deviceId, Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt; InvokeDeviceMethodAsync(string deviceId, class Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.InvokeDeviceMethodAsync(System.String,Microsoft.Azure.Devices.CloudToDeviceMethod)" />
      <MemberSignature Language="F#" Value="abstract member InvokeDeviceMethodAsync : string * Microsoft.Azure.Devices.CloudToDeviceMethod -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt;" Usage="serviceClient.InvokeDeviceMethodAsync (deviceId, cloudToDeviceMethod)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cloudToDeviceMethod" Type="Microsoft.Azure.Devices.CloudToDeviceMethod" />
      </Parameters>
      <Docs>
        <param name="deviceId">デバイス Id</param>
        <param name="cloudToDeviceMethod">デバイス メソッドのパラメーター (デバイスへのパススルー)</param>
        <summary>
            対話形式でデバイスのメソッドを呼び出します
            </summary>
        <returns>メソッドの結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeDeviceMethodAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt; InvokeDeviceMethodAsync (string deviceId, Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt; InvokeDeviceMethodAsync(string deviceId, class Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.InvokeDeviceMethodAsync(System.String,Microsoft.Azure.Devices.CloudToDeviceMethod,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeDeviceMethodAsync : string * Microsoft.Azure.Devices.CloudToDeviceMethod * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt;" Usage="serviceClient.InvokeDeviceMethodAsync (deviceId, cloudToDeviceMethod, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cloudToDeviceMethod" Type="Microsoft.Azure.Devices.CloudToDeviceMethod" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">デバイス Id</param>
        <param name="cloudToDeviceMethod">デバイス メソッドのパラメーター (デバイスへのパススルー)</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            対話形式でデバイスのメソッドを呼び出します
            </summary>
        <returns>メソッドの結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="serviceClient.OpenAsync " />
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
            サービス インスタンスを開く
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeMessageQueueAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt; PurgeMessageQueueAsync (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.PurgeMessageQueueResult&gt; PurgeMessageQueueAsync(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.PurgeMessageQueueAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function PurgeMessageQueueAsync (deviceId As String) As Task(Of PurgeMessageQueueResult)" />
      <MemberSignature Language="F#" Value="abstract member PurgeMessageQueueAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt;" Usage="serviceClient.PurgeMessageQueueAsync deviceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"></param>
        <summary>
            デバイスのキューからすべてのメッセージを削除します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeMessageQueueAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt; PurgeMessageQueueAsync (string deviceId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.PurgeMessageQueueResult&gt; PurgeMessageQueueAsync(string deviceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.PurgeMessageQueueAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeMessageQueueAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt;" Usage="serviceClient.PurgeMessageQueueAsync (deviceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"></param>
        <param name="cancellationToken"></param>
        <summary>
            デバイスのキューからすべてのメッセージを削除します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task SendAsync (string deviceId, Microsoft.Azure.Devices.Message message, Nullable&lt;TimeSpan&gt; timeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(string deviceId, class Microsoft.Azure.Devices.Message message, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.SendAsync(System.String,Microsoft.Azure.Devices.Message,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : string * Microsoft.Azure.Devices.Message * Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task" Usage="serviceClient.SendAsync (deviceId, message, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="message" Type="Microsoft.Azure.Devices.Message" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="deviceId">ターゲット デバイスのデバイス識別子</param>
        <param name="message">通知が含まれるメッセージ</param>
        <param name="timeout">操作のタイムアウトをオーバーライドします。 使用されている使用 OperationTimeout 既定しない場合</param>
        <summary>
            指定されたデバイスに一方向の通知を送信します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>