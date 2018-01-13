<Type Name="StreamingJobsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StreamingJobsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StreamingJobsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StreamingJobsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StreamingJobsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            StreamingJobsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob BeginCreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob BeginCreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplace (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="streamingJob">
            新しいストリーミング ジョブを作成または既存の置換に使用される、ストリーミング ジョブの定義。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="ifMatch">
            ストリーミング ジョブの ETag。 常に、現在のレコード セットを上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *' セットを記録が、既存の更新を防ぐために、新しいストリーミング ジョブを作成するには、します。 その他の値は、412 の前提条件が失敗の応答になります。
            </param>
        <summary>
            ストリーミング ジョブを作成するか、既存のストリーミング ジョブを置き換えます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; BeginCreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; BeginCreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplaceAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginCreateOrReplaceAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="streamingJob">
            新しいストリーミング ジョブを作成または既存の置換に使用される、ストリーミング ジョブの定義。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="ifMatch">
            ストリーミング ジョブの ETag。 常に、現在のレコード セットを上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *' セットを記録が、既存の更新を防ぐために、新しいストリーミング ジョブを作成するには、します。 その他の値は、412 の前提条件が失敗の応答になります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストリーミング ジョブを作成するか、既存のストリーミング ジョブを置き換えます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDelete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <summary>
            ストリーミング ジョブを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストリーミング ジョブを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static void BeginStart (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStart(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStart(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStart (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional startJobParameters As StartStreamingJobParameters = null)" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStart (operations, resourceGroupName, jobName, startJobParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="startJobParameters">
            ストリーミング ジョブ操作の開始に適用可能なパラメーターです。
            </param>
        <summary>
            ストリーミング ジョブを開始します。 ジョブが開始される入力イベントの処理を開始、出力が生成されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStartAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStartAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStartAsync (operations, resourceGroupName, jobName, startJobParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginStartAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="startJobParameters">
            ストリーミング ジョブ操作の開始に適用可能なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストリーミング ジョブを開始します。 ジョブが開始される入力イベントの処理を開始、出力が生成されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStop">
      <MemberSignature Language="C#" Value="public static void BeginStop (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStop(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStop(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStop (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStop : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStop (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <summary>
            実行中のストリーミング ジョブを停止します。 これにより、実行中のストリーミング ジョブの入力イベントを処理して、出力を生成を停止します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStopAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginStopAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            実行中のストリーミング ジョブを停止します。 これにより、実行中のストリーミング ジョブの入力イベントを処理して、出力を生成を停止します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplace (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="streamingJob">
            新しいストリーミング ジョブを作成または既存の置換に使用される、ストリーミング ジョブの定義。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="ifMatch">
            ストリーミング ジョブの ETag。 常に、現在のレコード セットを上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *' セットを記録が、既存の更新を防ぐために、新しいストリーミング ジョブを作成するには、します。 その他の値は、412 の前提条件が失敗の応答になります。
            </param>
        <summary>
            ストリーミング ジョブを作成するか、既存のストリーミング ジョブを置き換えます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplaceAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="streamingJob">
            新しいストリーミング ジョブを作成または既存の置換に使用される、ストリーミング ジョブの定義。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="ifMatch">
            ストリーミング ジョブの ETag。 常に、現在のレコード セットを上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *' セットを記録が、既存の更新を防ぐために、新しいストリーミング ジョブを作成するには、します。 その他の値は、412 の前提条件が失敗の応答になります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストリーミング ジョブを作成するか、既存のストリーミング ジョブを置き換えます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Delete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <summary>
            ストリーミング ジョブを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストリーミング ジョブを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Get (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Get(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional expand As String = null) As StreamingJob" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Get (operations, resourceGroupName, jobName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="expand">
            $ は、OData クエリ パラメーターを展開します。 これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。 既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。
            </param>
        <summary>
            指定したストリーミング ジョブの詳細を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="expand">
            $ は、OData クエリ パラメーターを展開します。 これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。 既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したストリーミング ジョブの詳細を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; List (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; List(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.List(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IStreamingJobsOperations, Optional expand As String = null) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.List (operations, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="expand">
            $ は、OData クエリ パラメーターを展開します。 これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。 既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。
            </param>
        <summary>
            すべての所定のサブスクリプションでストリーミング ジョブの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListAsync (operations, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="expand">
            $ は、OData クエリ パラメーターを展開します。 これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。 既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての所定のサブスクリプションでストリーミング ジョブの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroup (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroup(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IStreamingJobsOperations, resourceGroupName As String, Optional expand As String = null) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="expand">
            $ は、OData クエリ パラメーターを展開します。 これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。 既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。
            </param>
        <summary>
            指定されたリソース グループ内のストリーミング ジョブのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="expand">
            $ は、OData クエリ パラメーターを展開します。 これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。 既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソース グループ内のストリーミング ジョブのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IStreamingJobsOperations, nextPageLink As String) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            指定されたリソース グループ内のストリーミング ジョブのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたリソース グループ内のストリーミング ジョブのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListNext (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListNext(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNext(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IStreamingJobsOperations, nextPageLink As String) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            すべての所定のサブスクリプションでストリーミング ジョブの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての所定のサブスクリプションでストリーミング ジョブの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static void Start (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Start(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Start(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Start (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional startJobParameters As StartStreamingJobParameters = null)" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Start (operations, resourceGroupName, jobName, startJobParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="startJobParameters">
            ストリーミング ジョブ操作の開始に適用可能なパラメーターです。
            </param>
        <summary>
            ストリーミング ジョブを開始します。 ジョブが開始される入力イベントの処理を開始、出力が生成されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StartAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StartAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StartAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StartAsync (operations, resourceGroupName, jobName, startJobParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;StartAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="startJobParameters">
            ストリーミング ジョブ操作の開始に適用可能なパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ストリーミング ジョブを開始します。 ジョブが開始される入力イベントの処理を開始、出力が生成されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static void Stop (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Stop(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Stop(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Stop (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Stop (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <summary>
            実行中のストリーミング ジョブを停止します。 これにより、実行中のストリーミング ジョブの入力イベントを処理して、出力を生成を停止します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StopAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StopAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;StopAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            実行中のストリーミング ジョブを停止します。 これにより、実行中のストリーミング ジョブの入力イベントを処理して、出力を生成を停止します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Update (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Update(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Update (operations, streamingJob, resourceGroupName, jobName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="streamingJob">
            ストリーミング ジョブ オブジェクトを使用します。 ここで指定したプロパティで既存のストリーミング ジョブ (ie 対応するプロパティが上書きされます。そのプロパティが更新されます)。 ここでは null に設定されている任意のプロパティがありことを意味既存の入力の対応するプロパティは同じままこの PATCH 操作の結果として変更されません。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="ifMatch">
            ストリーミング ジョブの ETag。 常に、現在のレコード セットを上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <summary>
            既存のストリーミング ジョブを更新します。 これは、(ie 部分的に更新を使用できます。 1 つまたは 2 つのプロパティの更新)、残りのジョブ定義の影響を与えずに、ストリーミング ジョブです。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.UpdateAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="streamingJob">
            ストリーミング ジョブ オブジェクトを使用します。 ここで指定したプロパティで既存のストリーミング ジョブ (ie 対応するプロパティが上書きされます。そのプロパティが更新されます)。 ここでは null に設定されている任意のプロパティがありことを意味既存の入力の対応するプロパティは同じままこの PATCH 操作の結果として変更されません。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="ifMatch">
            ストリーミング ジョブの ETag。 常に、現在のレコード セットを上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のストリーミング ジョブを更新します。 これは、(ie 部分的に更新を使用できます。 1 つまたは 2 つのプロパティの更新)、残りのジョブ定義の影響を与えずに、ストリーミング ジョブです。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>