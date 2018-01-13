<Type Name="FabricClient+TestManagementClient" FullName="System.Fabric.FabricClient+TestManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.TestManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/TestManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.TestManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.TestManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.TestManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>発行し、テスト コマンドを制御するためのメソッドを提供します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelTestCommandAsync (operationId As Guid, force As Boolean) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="operationId">テスト コマンドを取り消すの operationId を示します。</param>
        <param name="force">正常にロールバックして、内部システム状態をクリーンアップがテスト コマンドを実行することによって変更するかどうかを示します。  「解説」を参照してください。</param>
        <summary>
            テスト コマンドを取り消します。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            Force が false の場合、指定されたテスト コマンド適切を停止し、クリーンアップします。  Force が true の場合は、コマンドは中止され、何らかの内部状態の残る可能性があります。  True として force を指定することは、注意して使用する必要があります。  CancelTestCommandAsync() が false の最初に強制セットで同じテスト コマンドで呼び出されるまで、またはテスト コマンドには既にの TestCommandProgressState を除き、true に設定された force 通話 CancelTestCommandAsync() は許可されていませんTestCommandProgressState.RollingBack です。
            説明: TestCommandProgressState.RollingBack では、システムは/コマンドを実行しての原因となった内部システム状態をクリーンアップします。  テスト コマンドのデータの損失が発生する場合のデータは復元されません。  たとえば、StartPartitionDataLossAsync() を呼び出す場合は CancelTestCommandAsync() を呼び出して、システムはコマンドを実行してから内部状態をクリーンアップのみ。  
            コマンドが進行して十分なデータの損失が発生する場合、ターゲット パーティションのデータは復元されません。
            
            
            </para>
          <para>
            重要な注意事項: この API は強制的に起動された場合の = = true、内部の状態の残る可能性があります。  残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">テスト コマンドを取り消すの operationId を示します。</param>
        <param name="force">正常にロールバックして、内部システム状態をクリーンアップがテスト コマンドを実行することによって変更するかどうかを示します。  「解説」を参照してください。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            テスト コマンドを取り消します。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            Force が false の場合、指定されたテスト コマンド適切を停止し、クリーンアップします。  Force が true の場合は、コマンドは中止され、何らかの内部状態の残る可能性があります。  True として force を指定することは、注意して使用する必要があります。  CancelTestCommandAsync() が false の最初に強制セットで同じテスト コマンドで呼び出されるまで、またはテスト コマンドには既にの TestCommandProgressState を除き、true に設定された force 通話 CancelTestCommandAsync() は許可されていませんTestCommandProgressState.RollingBack です。
            説明: TestCommandProgressState.RollingBack では、システムは/コマンドを実行しての原因となった内部システム状態をクリーンアップします。  テスト コマンドのデータの損失が発生する場合のデータは復元されません。  たとえば、StartPartitionDataLossAsync() を呼び出す場合は CancelTestCommandAsync() を呼び出して、システムはコマンドを実行してから内部状態をクリーンアップのみ。  
            コマンドが進行して十分なデータの損失が発生する場合、ターゲット パーティションのデータは復元されません。
            
            
            
            </para>
          <para>
            重要な注意事項: この API は強制的に起動された場合の = = true、内部の状態の残る可能性があります。  残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelTestCommandAsync (operationId As Guid, force As Boolean, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId">テスト コマンドを取り消すの operationId を示します。</param>
        <param name="force">正常にロールバックして、内部システム状態をクリーンアップがテスト コマンドを実行することによって変更するかどうかを示します。  「解説」を参照してください。</param>
        <param name="timeout">API の呼び出しを使用するタイムアウト値。</param>
        <summary>
            テスト コマンドを取り消します。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            Force が false の場合、指定されたテスト コマンド適切を停止し、クリーンアップします。  Force が true の場合は、コマンドは中止され、何らかの内部状態の残る可能性があります。  True として force を指定することは、注意して使用する必要があります。  CancelTestCommandAsync() が false の最初に強制セットで同じテスト コマンドで呼び出されるまで、またはテスト コマンドには既にの TestCommandProgressState を除き、true に設定された force 通話 CancelTestCommandAsync() は許可されていませんTestCommandProgressState.RollingBack です。
            説明: TestCommandProgressState.RollingBack では、システムは/コマンドを実行しての原因となった内部システム状態をクリーンアップします。  テスト コマンドのデータの損失が発生する場合のデータは復元されません。  たとえば、StartPartitionDataLossAsync() を呼び出す場合は CancelTestCommandAsync() を呼び出して、システムはコマンドを実行してから内部状態をクリーンアップのみ。  
            コマンドが進行して十分なデータの損失が発生する場合、ターゲット パーティションのデータは復元されません。
            
            
            
            </para>
          <para>
            重要な注意事項: この API は強制的に起動された場合の = = true、内部の状態の残る可能性があります。  残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">テスト コマンドを取り消すの operationId を示します。</param>
        <param name="force">正常にロールバックして、内部システム状態をクリーンアップがテスト コマンドを実行することによって変更するかどうかを示します。  「解説」を参照してください。</param>
        <param name="timeout">API の呼び出しを使用するタイムアウト値。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            テスト コマンドを取り消します。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            Force が false の場合、指定されたテスト コマンド適切を停止し、クリーンアップします。  Force が true の場合は、コマンドは中止され、何らかの内部状態の残る可能性があります。  True として force を指定することは、注意して使用する必要があります。  CancelTestCommandAsync() が false の最初に強制セットで同じテスト コマンドで呼び出されるまで、またはテスト コマンドには既にの TestCommandProgressState を除き、true に設定された force 通話 CancelTestCommandAsync() は許可されていませんTestCommandProgressState.RollingBack です。
            説明: TestCommandProgressState.RollingBack では、システムは/コマンドを実行しての原因となった内部システム状態をクリーンアップします。  テスト コマンドのデータの損失が発生する場合のデータは復元されません。  たとえば、StartPartitionDataLossAsync() を呼び出す場合は CancelTestCommandAsync() を呼び出して、システムはコマンドを実行してから内部状態をクリーンアップのみ。  
            コマンドが進行して十分なデータの損失が発生する場合、ターゲット パーティションのデータは復元されません。
            
            
            
            </para>
          <para>
            重要な注意事項: この API は強制的に起動された場合の = = true、内部の状態の残る可能性があります。  残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CleanTestStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CleanTestStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CleanTestStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CleanTestStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CleanTestStateAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CleanTestStateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CleanTestStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            クラスターのすべてのテストの状態をクリーンアップします。
            </summary>
        <returns>タスク</returns>
        <remarks>
            フォールト操作; に設定されているクラスター内のすべてのテスト状態をクリーンアップします。StopNode と同様に、またはテスト ドライバーが処理するかどうかは死亡またはクラスターが通常の状態に戻すことを確認する飛行中に、操作が取り消されるこれらの操作の失敗した場合は InvokeDataLoss、RestartPartition および InvokeQuorumLoss この API を呼び出す必要があります。 通常のすべてのエラー操作 CleanTestState のみ呼び出す必要がある場合は、API 操作が中断されるため、API の実行の終了時の状態をクリーンアップします。
            </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
      </Docs>
    </Member>
    <Member MemberName="CleanTestStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CleanTestStateAsync (TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CleanTestStateAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CleanTestStateAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function CleanTestStateAsync (operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.CleanTestStateAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CleanTestStateAsync (operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout">操作の全体的なタイムアウト。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            クラスターのすべてのテストの状態をクリーンアップします。
            </summary>
        <returns>タスク</returns>
        <remarks>
            これらの操作が失敗した場合は、フォールト操作で、InvokeDataLoss、RestartPartition および InvokeQuorumLoss この API に設定されているクラスター内のテストの状態を呼び出す必要がありますすべてがクリーンアップ テスト ドライバーのプロセスが停止または操作が取り消されたかどうか、または中フライト クラスターが通常の状態に戻すことを確認します。 通常のすべてのエラー操作 CleanTestState のみ呼び出す必要がある場合は、API 操作が中断されるため、API の実行の終了時の状態をクリーンアップします。
            </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (System.Fabric.Chaos.DataStructures.ChaosReportFilter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(class System.Fabric.Chaos.DataStructures.ChaosReportFilter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChaosReportAsync (filter As ChaosReportFilter) As Task(Of ChaosReport)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : System.Fabric.Chaos.DataStructures.ChaosReportFilter -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.Fabric.Chaos.DataStructures.ChaosReportFilter" />
      </Parameters>
      <Docs>
        <param name="filter">フィルター処理、<see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />レポートに含まれる秒です。</param>
        <summary>
            Chaos 実行のレポートを取得します。
            </summary>
        <returns>御礼状レポートを実行します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは Service Fabric の例外と、次のエラー コードを検査する必要があります。
            FabricErrorCode.NotReady - Chaos を開始する前にこの API が呼び出された場合。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChaosReportAsync (continuationToken As String) As Task(Of ChaosReport)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync continuationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="continuationToken">継続トークンの一覧については<see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />内、<see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />です。</param>
        <summary>
            Chaos 実行のレポートを取得します。
            </summary>
        <returns>御礼状レポートを実行します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは Service Fabric の例外と、次のエラー コードを検査する必要があります。
            FabricErrorCode.NotReady - Chaos を開始する前にこの API が呼び出された場合。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (System.Fabric.Chaos.DataStructures.ChaosReportFilter filter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(class System.Fabric.Chaos.DataStructures.ChaosReportFilter filter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : System.Fabric.Chaos.DataStructures.ChaosReportFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync (filter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.Fabric.Chaos.DataStructures.ChaosReportFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filter">フィルター処理、<see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />に含まれる秒、<see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />です。</param>
        <param name="operationTimeout">操作の全体的なタイムアウト。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            Chaos 実行のレポートを取得します。
            </summary>
        <returns>御礼状レポートを実行します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは Service Fabric の例外と、次のエラー コードを検査する必要があります。
            FabricErrorCode.NotReady - Chaos を開始する前にこの API が呼び出された場合。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (string continuationToken, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(string continuationToken, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync (continuationToken, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken">継続トークンの一覧については<see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />内、<see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />です。</param>
        <param name="operationTimeout">操作の全体的なタイムアウト。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            Chaos 実行のレポートを取得します。
            </summary>
        <returns>御礼状レポートを実行します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">これらは Service Fabric の例外と、次のエラー コードを検査する必要があります。
            FabricErrorCode.NotReady - Chaos を開始する前にこの API が呼び出された場合。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeTransitionProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt; GetNodeTransitionProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NodeTransitionProgress&gt; GetNodeTransitionProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetNodeTransitionProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeTransitionProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt;" Usage="testManagementClient.GetNodeTransitionProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">StartNodeTransitionAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <param name="timeout">タイムアウトになった。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            StartNodeTransitionAsync() を使用して開始されたコマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionRestartResult を含む PartitionRestartProgress オブジェクト。</returns>
        <remarks>この API を使用して、FaultAnalysisService を有効にする必要があります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionDataLossProgressAsync (operationId As Guid) As Task(Of PartitionDataLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionDataLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <summary>
            StartPartitionDataLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionDataLossResult を含む PartitionDataLossProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>場合、返された PartitionDataLossProgress.State Faulted、= = PartitionDataLossProgress.Result.Exception 原因を特定するを確認します。
            PartitionDataLossProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
                - FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionDataLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            StartPartitionDataLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionDataLossResult を含む PartitionDataLossProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>場合、返された PartitionDataLossProgress.State Faulted、= = PartitionDataLossProgress.Result.Exception 原因を特定するを確認します。
            PartitionDataLossProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
                - FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionDataLossProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionDataLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionDataLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <param name="timeout">タイムアウトになった。</param>
        <summary>
            StartPartitionDataLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionDataLossResult を含む PartitionDataLossProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>場合、返された PartitionDataLossProgress.State Faulted、= = PartitionDataLossProgress.Result.Exception 原因を特定するを確認します。
            PartitionDataLossProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
                - FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionDataLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <param name="timeout">タイムアウトになった。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            StartPartitionDataLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionDataLossResult を含む PartitionDataLossProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>場合、返された PartitionDataLossProgress.State Faulted、= = PartitionDataLossProgress.Result.Exception 原因を特定するを確認します。
            PartitionDataLossProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
                - FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionQuorumLossProgressAsync (operationId As Guid) As Task(Of PartitionQuorumLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionQuorumLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <summary>
            StartPartitionQuorumLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionQuorumLossResult を含む PartitionQuorumLossProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>
            場合、返された PartitionQuorumLossProgress.State Faulted、= = PartitionQuorumLossProgress.Result.Exception 原因を特定するを確認します。
            PartitionQuorumLossProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
                - FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。
                - FabricOnlyValidForStatefulPersistentServicesException - この操作はメモリ内のステートフル サービスに対して有効ではありません。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionQuorumLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            StartPartitionQuorumLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionQuorumLossResult を含む PartitionQuorumLossProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>
            場合、返された PartitionQuorumLossProgress.State Faulted、= = PartitionQuorumLossProgress.Result.Exception 原因を特定するを確認します。
            PartitionQuorumLossProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
                - FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。
                - FabricOnlyValidForStatefulPersistentServicesException - この操作はメモリ内のステートフル サービスに対して有効ではありません。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionQuorumLossProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionQuorumLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionQuorumLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <param name="timeout">タイムアウトになった。</param>
        <summary>
            StartPartitionQuorumLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionQuorumLossResult を含む PartitionQuorumLossProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>
            場合、返された PartitionQuorumLossProgress.State Faulted、= = PartitionQuorumLossProgress.Result.Exception 原因を特定するを確認します。
            PartitionQuorumLossProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
                - FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。
                - FabricOnlyValidForStatefulPersistentServicesException - この操作はメモリ内のステートフル サービスに対して有効ではありません。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionQuorumLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <param name="timeout">タイムアウトになった。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            StartPartitionQuorumLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionQuorumLossResult を含む PartitionQuorumLossProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>
            場合、返された PartitionQuorumLossProgress.State Faulted、= = PartitionQuorumLossProgress.Result.Exception 原因を特定するを確認します。
            PartitionQuorumLossProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
                - FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。
                - FabricOnlyValidForStatefulPersistentServicesException - この操作はメモリ内のステートフル サービスに対して有効ではありません。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionRestartProgressAsync (operationId As Guid) As Task(Of PartitionRestartProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionRestartAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <summary>
            StartPartitionRestartAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionRestartResult を含む PartitionRestartProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>場合、返された PartitionRestartProgress.State Faulted、= = PartitionRestartProgress.Result.Exception 原因を特定するを確認します。
            PartitionRestartProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionRestartAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            StartPartitionRestartAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionRestartResult を含む PartitionRestartProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>場合、返された PartitionRestartProgress.State Faulted、= = PartitionRestartProgress.Result.Exception 原因を特定するを確認します。
            PartitionRestartProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionRestartProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionRestartProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionRestartAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <param name="timeout">タイムアウトになった。</param>
        <summary>
            StartPartitionRestartAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionRestartResult を含む PartitionRestartProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>場合、返された PartitionRestartProgress.State Faulted、= = PartitionRestartProgress.Result.Exception 原因を特定するを確認します。
            PartitionRestartProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId">StartPartitionRestartAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</param>
        <param name="timeout">タイムアウトになった。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            StartPartitionRestartAsync() を使用して開始されたテスト コマンドの進行状況を取得します。
            </summary>
        <returns>TestCommandProgressState と PartitionRestartResult を含む PartitionRestartProgress オブジェクト。</returns>
        <remarks>
          <para>この API を使用して、FaultAnalysisService を有効にする必要があります。</para>
          <para>場合、返された PartitionRestartProgress.State Faulted、= = PartitionRestartProgress.Result.Exception 原因を特定するを確認します。
            PartitionRestartProgress.Result.Exception 値:
              - ArgumentException の入力が無効でした。
              - ErrorCode プロパティを持つ場合は、FabricException:
                - PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            テスト コマンドの状態を取得します。
            </summary>
        <returns>IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</returns>
        <remarks>この API を使用して、FaultAnalysisService を有効にする必要があります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTestCommandStatusListAsync (operationTimeout As TimeSpan) As Task(Of TestCommandStatusList)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync operationTimeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationTimeout">API 呼び出しのタイムアウト期間。</param>
        <summary>
            テスト コマンドの状態を取得します。
            </summary>
        <returns>IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</returns>
        <remarks>この API を使用して、FaultAnalysisService を有効にする必要があります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout">API 呼び出しのタイムアウト期間。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            テスト コマンドの状態を取得します。
            </summary>
        <returns>IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</returns>
        <remarks>この API を使用して、FaultAnalysisService を有効にする必要があります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandStateFilter stateFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandStateFilter stateFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandStateFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (stateFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateFilter" Type="System.Fabric.Query.TestCommandStateFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateFilter">このパラメーターは TestCommandState によるフィルター処理に使用することができます。</param>
        <param name="operationTimeout">API 呼び出しのタイムアウト期間。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            テスト コマンドの状態を取得します。
            </summary>
        <returns>IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</returns>
        <remarks>この API を使用して、FaultAnalysisService を有効にする必要があります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandTypeFilter typeFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandTypeFilter typeFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandTypeFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (typeFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="typeFilter" Type="System.Fabric.Query.TestCommandTypeFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="typeFilter">このパラメーターは TestCommandType によるフィルター処理に使用することができます。</param>
        <param name="operationTimeout">API 呼び出しのタイムアウト期間。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            テスト コマンドの状態を取得します。
            </summary>
        <returns>IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</returns>
        <remarks>この API を使用して、FaultAnalysisService を有効にする必要があります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandStateFilter stateFilter, System.Fabric.Query.TestCommandTypeFilter typeFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandStateFilter stateFilter, valuetype System.Fabric.Query.TestCommandTypeFilter typeFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandStateFilter * System.Fabric.Query.TestCommandTypeFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (stateFilter, typeFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateFilter" Type="System.Fabric.Query.TestCommandStateFilter" />
        <Parameter Name="typeFilter" Type="System.Fabric.Query.TestCommandTypeFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateFilter">このパラメーターは TestCommandState によるフィルター処理に使用することができます。</param>
        <param name="typeFilter">このパラメーターは TestCommandType によるフィルター処理に使用することができます。</param>
        <param name="operationTimeout">API 呼び出しのタイムアウト期間。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            テスト コマンドの状態を取得します。
            </summary>
        <returns>IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</returns>
        <remarks>この API を使用して、FaultAnalysisService を有効にする必要があります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります</param>
        <param name="dataLossMode">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</param>
        <summary>
            この API は、指定されたパーティションのデータ損失を強制的に実行します。 パーティションの OnDataLoss API への呼び出しがトリガーされます。
            </summary>
        <returns>データ損失のパーティションに関する情報を提供する InvokeDataLossResult が選択されました。</returns>
        <remarks>
          <para>
            指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。
            FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</param>
        <param name="dataLossMode">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            この API は、指定されたパーティションのデータ損失を強制的に実行します。 パーティションの OnDataLoss API への呼び出しがトリガーされます。
            </summary>
        <returns>データ損失のパーティションに関する情報を提供する InvokeDataLossResult が選択されました。</returns>
        <remarks>
          <para>
            指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。
            FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</param>
        <param name="dataLossMode">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</param>
        <param name="operationTimeout">操作の全体的なタイムアウト</param>
        <summary>
            この API は、指定されたパーティションのデータ損失を強制的に実行します。 パーティションの OnDataLoss API への呼び出しがトリガーされます。
            </summary>
        <returns>データ損失のパーティションに関する情報を提供する InvokeDataLossResult が選択されました。</returns>
        <remarks>
          <para>
            指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。
            FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</param>
        <param name="dataLossMode">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</param>
        <param name="operationTimeout">操作の全体的なタイムアウト</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            この API は、指定されたパーティションのデータ損失を強制的に実行します。 パーティションの OnDataLoss API への呼び出しがトリガーされます。
            </summary>
        <returns>データ損失のパーティションに関する情報を提供する InvokeDataLossResult が選択されました。</returns>
        <remarks>
          <para>
            指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。
            FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">クォーラム損失に起動されるパーティションです。 <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss または FullQuorumLoss します。</param>
        <param name="quorumLossDuration">クォーラム損失にパーティションを保持する時間の長さ。</param>
        <summary>特定のステートフル サービス パーティションをクォーラム損失状態にします。 </summary>
        <returns>InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></returns>
        <remarks>
          <para>
            FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。
            PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.
            </para>
          <para>
            quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。 パーティションは、quorumLossDuration のクォーラム損失に残ります。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。                 
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.OperationCanceledException">非同期操作が取り消されました。</exception>
        <exception cref="T:System.InvalidOperationException"> 指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">クォーラム損失に起動されるパーティションです。 <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss または FullQuorumLoss します。</param>
        <param name="quorumLossDuration">クォーラム損失にパーティションを保持する時間の長さ。</param>
        <param name="cancellationToken">操作のキャンセル トークン。</param>
        <summary>特定のステートフル サービス パーティションをクォーラム損失状態にします。 </summary>
        <returns>InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></returns>
        <remarks>
          <para>
            FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。
            PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.
            </para>
          <para>
            quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。 パーティションは、quorumLossDuration のクォーラム損失に残ります。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.OperationCanceledException">非同期操作が取り消されました。</exception>
        <exception cref="T:System.InvalidOperationException"> 指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">クォーラム損失に起動されるパーティションです。 <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss または FullQuorumLoss します。</param>
        <param name="quorumLossDuration">クォーラム損失にパーティションを保持する時間の長さ。</param>
        <param name="operationTimeout">すべての操作の全体的なタイムアウト。</param>
        <summary>特定のステートフル サービス パーティションをクォーラム損失状態にします。 </summary>
        <returns>InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></returns>
        <remarks>
          <para>
            FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。
            PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.
            </para>
          <para>
            quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。 パーティションは、quorumLossDuration のクォーラム損失に残ります。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.OperationCanceledException">非同期操作が取り消されました。</exception>
        <exception cref="T:System.InvalidOperationException"> 指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumlossMode, TimeSpan quorumlossDuration, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumlossMode, valuetype System.TimeSpan quorumlossDuration, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumlossMode, quorumlossDuration, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumlossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumlossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">クォーラム損失に起動されるパーティションです。 <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumlossMode">PartialQuorumLoss または FullQuorumLoss します。</param>
        <param name="quorumlossDuration">クォーラム損失にパーティションを保持する時間の長さ。</param>
        <param name="operationTimeout">すべての操作の全体的なタイムアウト。</param>
        <param name="cancellationToken">操作のキャンセル トークン。</param>
        <summary>特定のステートフル サービス パーティションをクォーラム損失状態にします。 </summary>
        <returns>InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></returns>
        <remarks>
          <para>
            FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。
            PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.
            </para>
          <para>
            quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。 パーティションは、quorumLossDuration のクォーラム損失に残ります。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.OperationCanceledException">非同期操作が取り消されました。</exception>
        <exception cref="T:System.InvalidOperationException"> 指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</param>
        <param name="restartPartitionMode"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</param>
        <summary>
            この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。
            </summary>
        <returns>RestartPartitionResult が実際選択されたパーティションに関する情報を得られます。</returns>
        <remarks>
          <para>
            この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">ステートレスなサービスに属しているパーティションに対して、API が呼び出されたかどうか<see cref="T:System.Fabric.RestartPartitionMode" />OnlyActiveSecondaries に設定します。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</param>
        <param name="restartPartitionMode"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。
            </summary>
        <returns>RestartPartitionResult が実際選択されたパーティションに関する情報を得られます。</returns>
        <remarks>
          <para>
            この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">ステートレスなサービスに属しているパーティションに対して、API が呼び出されたかどうか<see cref="T:System.Fabric.RestartPartitionMode" />OnlyActiveSecondaries に設定します。</exception>
        <exception cref="T:System.Fabric.FabricException">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</param>
        <param name="restartPartitionMode"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</param>
        <param name="operationTimeout">操作の全体的なタイムアウト。</param>
        <summary>
            この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。
            </summary>
        <returns>RestartPartitionResult が実際選択されたパーティションに関する情報を得られます。</returns>
        <remarks>
          <para>
            この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">ステートレスなサービスに属しているパーティションに対して、API が呼び出されたかどうか<see cref="T:System.Fabric.RestartPartitionMode" />OnlyActiveSecondaries に設定します。</exception>
        <exception cref="T:System.Fabric.FabricException">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</param>
        <param name="restartPartitionMode"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</param>
        <param name="operationTimeout">操作の全体的なタイムアウト。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。
            </summary>
        <returns>RestartPartitionResult が実際選択されたパーティションに関する情報を得られます。</returns>
        <remarks>
          <para>
            この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            重要な注意事項: この API は、実行中に中断できないする必要があります。  実行中に、この API を中止する可能性があります残した状態です。  
            この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">ステートレスなサービスに属しているパーティションに対して、API が呼び出されたかどうか<see cref="T:System.Fabric.RestartPartitionMode" />OnlyActiveSecondaries に設定します。</exception>
        <exception cref="T:System.Fabric.FabricException">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</exception>
      </Docs>
    </Member>
    <Member MemberName="StartChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartChaosAsync (System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartChaosAsync(class System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartChaosAsync(System.Fabric.Chaos.DataStructures.ChaosParameters)" />
      <MemberSignature Language="F#" Value="member this.StartChaosAsync : System.Fabric.Chaos.DataStructures.ChaosParameters -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartChaosAsync chaosParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="chaosParameters" Type="System.Fabric.Chaos.DataStructures.ChaosParameters" />
      </Parameters>
      <Docs>
        <param name="chaosParameters">
          <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />Chaos; を制御するためのさまざまなパラメーターが含まれていますなど、実行時間、同時実行 fautls などの最大数。 </param>
        <summary>
            この API は、指定されたパラメーター値を持つ Chaos を始めます。
            </summary>
        <returns>タスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricChaosAlreadyRunningException">クラスターで混乱が既に実行されているときに、StartChaos API が呼び出されたときに、この例外がスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartChaosAsync (System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartChaosAsync(class System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartChaosAsync(System.Fabric.Chaos.DataStructures.ChaosParameters,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartChaosAsync : System.Fabric.Chaos.DataStructures.ChaosParameters * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartChaosAsync (chaosParameters, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="chaosParameters" Type="System.Fabric.Chaos.DataStructures.ChaosParameters" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="chaosParameters"> Chaos; を制御するためのさまざまなパラメーターが含まれていますなど、実行時間など、同時実行エラーの最大数。</param>
        <param name="operationTimeout"> 操作の全体的なタイムアウト。</param>
        <param name="cancellationToken"> キャンセル トークン。</param>
        <summary>
            この API は、指定されたパラメーター値を持つ Chaos を始めます。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricChaosAlreadyRunningException">クラスターで混乱が既に実行されているときに、StartChaos API が呼び出されたときに、この例外がスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeTransitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartNodeTransitionAsync (System.Fabric.Description.NodeTransitionDescription description, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartNodeTransitionAsync(class System.Fabric.Description.NodeTransitionDescription description, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartNodeTransitionAsync(System.Fabric.Description.NodeTransitionDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function StartNodeTransitionAsync (description As NodeTransitionDescription, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.StartNodeTransitionAsync : System.Fabric.Description.NodeTransitionDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartNodeTransitionAsync (description, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.NodeTransitionDescription" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">実行するノードの移行の種類を説明するオブジェクト。  移行を開始または停止するノードを指定できます。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">CancellationToken</param>
        <summary>
            クラスター ノードを開始または停止します。  クラスター ノードはプロセスで、OS インスタンスそのものではありません。  ノードを開始するには、description パラメーターに NodeStartDescription の型のオブジェクトに渡します。  ノードを停止するには、型 NodeStopDescription のオブジェクトを渡します。  この API が返されると、操作の進行状況を取得する GetNodeTransitionProgressAsync() を呼び出します。
            </summary>
        <returns>タスク</returns>
        <remarks>この API を使用して、FaultAnalysisService を有効にする必要があります。</remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。        
              ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。      
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
      </Parameters>
      <Docs>
        <param name="operationId"> この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡されます。</param>
        <param name="partitionSelector"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失は発生する必要があります。</param>
        <param name="dataLossMode">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</param>
        <summary>
            この API は、指定されたパーティションのデータ損失を強制的に実行します。 パーティションの OnDataLoss API への呼び出しがトリガーされます。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />です。
            PartialDataLoss - レプリカのクォーラムだけが削除されたと OnDataLoss はパーティションのトリガーしますが、実際のデータが失われるは、インフライトのレプリケーションの存在によって異なります。
            FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            注: この API が呼び出された後に取り消すことができません。 CancelTestCommandAsync() を呼び出して、のみの実行を停止および内部システム状態をクリーンアップします。
            コマンドはデータの損失を十分に離れた進めた場合データは復元されません。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラーです。
            FabricErrorCode.PartitionNotFound - 選択した指定したパーティションが存在しない場合。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</param>
        <param name="partitionSelector"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</param>
        <param name="dataLossMode">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            この API は、指定されたパーティションのデータ損失を強制的に実行します。 パーティションの OnDataLoss API への呼び出しがトリガーされます。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失が転送レプリケーションの存在に依存します。
            FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
          <para>
            注: この API が呼び出された後に取り消すことができません。  CancelTestCommandAsync() を呼び出して、のみの実行を停止および内部システム状態をクリーンアップします。  
            コマンドはデータの損失を十分に離れた進めた場合データは復元されません。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</param>
        <param name="partitionSelector"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</param>
        <param name="dataLossMode">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</param>
        <param name="operationTimeout">操作の全体的なタイムアウト</param>
        <summary>
            この API は、指定されたパーティションのデータ損失を強制的に実行します。 パーティションの OnDataLoss API への呼び出しがトリガーされます。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。
            FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
          <para>
            注: この API が呼び出された後に取り消すことができません。  CancelTestCommandAsync() を呼び出して、のみの実行を停止および内部システム状態をクリーンアップします。  
            コマンドはデータの損失を十分に離れた進めた場合データは復元されません。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</param>
        <param name="partitionSelector"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</param>
        <param name="dataLossMode">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</param>
        <param name="operationTimeout">操作の全体的なタイムアウト</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            この API は、指定されたパーティションのデータ損失を強制的に実行します。 パーティションの OnDataLoss API への呼び出しがトリガーされます。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。
            FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
          <para>
            注: この API が呼び出された後に取り消すことができません。  CancelTestCommandAsync() を呼び出して、のみの実行を停止および内部システム状態をクリーンアップします。
            コマンドはデータの損失を十分に離れた進めた場合データは復元されません。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.InvalidOperationException">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> ユーザー指定の識別子です。  この識別子は、対応する GetProgress API に渡すこともできます。</param>
        <param name="partitionSelector">クォーラム損失に起動されるパーティションです。 <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss または FullQuorumLoss します。</param>
        <param name="quorumLossDuration">クォーラム損失にパーティションを保持する時間の長さ。</param>
        <summary>特定のステートフル サービス パーティションをクォーラム損失状態にします。 </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。
            PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.
            </para>
          <para>
            quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。 パーティションは、quorumLossDuration のクォーラム損失に残ります。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.OperationCanceledException">非同期操作が取り消されました。</exception>
        <exception cref="T:System.InvalidOperationException"> 指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> ユーザー指定の識別子です。  この識別子は、対応する GetProgress API に渡すこともできます。</param>
        <param name="partitionSelector">クォーラム損失に起動されるパーティションです。 <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss または FullQuorumLoss します。</param>
        <param name="quorumLossDuration">クォーラム損失にパーティションを保持する時間の長さ。</param>
        <param name="cancellationToken">操作のキャンセル トークン。</param>
        <summary>特定のステートフル サービス パーティションをクォーラム損失状態にします。 </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。
            PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.
            </para>
          <para>
            quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。 パーティションは、quorumLossDuration のクォーラム損失に残ります。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.OperationCanceledException">非同期操作が取り消されました。</exception>
        <exception cref="T:System.InvalidOperationException"> 指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> ユーザー指定の識別子です。  この識別子は、対応する GetProgress API に渡すこともできます。</param>
        <param name="partitionSelector">クォーラム損失に起動されるパーティションです。 <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode">PartialQuorumLoss または FullQuorumLoss します。</param>
        <param name="quorumLossDuration">クォーラム損失にパーティションを保持する時間の長さ。</param>
        <param name="operationTimeout">すべての操作の全体的なタイムアウト。</param>
        <summary>特定のステートフル サービス パーティションをクォーラム損失状態にします。 </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。
            PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.
            </para>
          <para>
            quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。 パーティションは、quorumLossDuration のクォーラム損失に残ります。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.OperationCanceledException">非同期操作が取り消されました。</exception>
        <exception cref="T:System.InvalidOperationException"> 指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumlossMode, TimeSpan quorumlossDuration, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumlossMode, valuetype System.TimeSpan quorumlossDuration, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumlossMode, quorumlossDuration, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumlossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumlossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> ユーザー指定の識別子です。  この識別子は、対応する GetProgress API に渡すこともできます。</param>
        <param name="partitionSelector">クォーラム損失に起動されるパーティションです。 <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumlossMode">PartialQuorumLoss または FullQuorumLoss します。</param>
        <param name="quorumlossDuration">クォーラム損失にパーティションを保持する時間の長さ。</param>
        <param name="operationTimeout">すべての操作の全体的なタイムアウト。</param>
        <param name="cancellationToken">操作のキャンセル トークン。</param>
        <summary>特定のステートフル サービス パーティションをクォーラム損失状態にします。 </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。
            PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.
            </para>
          <para>
            quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。 パーティションは、quorumLossDuration のクォーラム損失に残ります。
            </para>
          <para>
            この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。
            </para>
          <para>
            ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.OperationCanceledException">非同期操作が取り消されました。</exception>
        <exception cref="T:System.InvalidOperationException"> 指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
      </Parameters>
      <Docs>
        <param name="operationId"> この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</param>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</param>
        <param name="restartPartitionMode"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</param>
        <summary>
            この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。
            </para>
          <para>
            この API は、ステートフルなとステートレス サービスの両方で呼び出すことができます。  
            呼び出しの場合は、ステートレスなサービスで、RestartPartitionMode は RestartPartitionMode.AllReplicasOrInstances をする必要があります。  その他のモードになります ArgumentException、返された結果オブジェクトの内部 GetPartitionRestartProgressAsync() が呼び出されるとします。  GetPartitionRestartProgressAsync() を参照してください。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.ArgumentException">入力が無効でした。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</param>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</param>
        <param name="restartPartitionMode"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。
            </para>
          <para>
            この API は、ステートフルなとステートレス サービスの両方で呼び出すことができます。  
            呼び出しの場合は、ステートレスなサービスで、RestartPartitionMode は RestartPartitionMode.AllReplicasOrInstances をする必要があります。  その他のモードになります ArgumentException、返された結果オブジェクトの内部 GetPartitionRestartProgressAsync() が呼び出されるとします。  GetPartitionRestartProgressAsync() を参照してください。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.ArgumentException">入力が無効でした。</exception>
        <exception cref="T:System.Fabric.FabricException">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</param>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</param>
        <param name="restartPartitionMode"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</param>
        <param name="operationTimeout">操作の全体的なタイムアウト。</param>
        <summary>
            この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。
            </para>
          <para>
            この API は、ステートフルなとステートレス サービスの両方で呼び出すことができます。  
            呼び出しの場合は、ステートレスなサービスで、RestartPartitionMode は RestartPartitionMode.AllReplicasOrInstances をする必要があります。  その他のモードになります ArgumentException、返された結果オブジェクトの内部 GetPartitionRestartProgressAsync() が呼び出されるとします。  GetPartitionRestartProgressAsync() を参照してください。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.ArgumentException">入力が無効でした。</exception>
        <exception cref="T:System.Fabric.FabricException">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</param>
        <param name="partitionSelector">
          <see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</param>
        <param name="restartPartitionMode"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</param>
        <param name="operationTimeout">操作の全体的なタイムアウト。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。
            </para>
          <para>
            この API は、ステートフルなとステートレス サービスの両方で呼び出すことができます。  
            呼び出しの場合は、ステートレスなサービスで、RestartPartitionMode は RestartPartitionMode.AllReplicasOrInstances をする必要があります。  その他のモードになります ArgumentException、返された結果オブジェクトの内部 GetPartitionRestartProgressAsync() が呼び出されるとします。  GetPartitionRestartProgressAsync() を参照してください。
            </para>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。             
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.ArgumentException">入力が無効でした。</exception>
        <exception cref="T:System.Fabric.FabricException">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</exception>
      </Docs>
    </Member>
    <Member MemberName="StopChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopChaosAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopChaosAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StopChaosAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function StopChaosAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.StopChaosAsync : unit -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StopChaosAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            この API は、混乱を停止します。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopChaosAsync (TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopChaosAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StopChaosAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopChaosAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StopChaosAsync (operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"> 操作の全体的なタイムアウト。</param>
        <param name="cancellationToken"> キャンセル トークン</param>
        <summary>
            この API は、混乱を停止します。
            </summary>
        <returns>タスク。</returns>
        <remarks>
          <para>
            この API を使用して、FaultAnalysisService を有効にする必要があります。
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="applicationName">検証に使用するサービスを提供する必要があるアプリケーションの名前。</param>
        <param name="maximumStabilizationTimeout">他の失敗が安定してサービスの操作を待機する時間の最大量。</param>
        <summary>
            この API は、可用性と指定したアプリケーションのすべてのサービスの正常性を検証します。
            </summary>
        <returns>タスク</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricValidationException">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">検証に使用するサービスを提供する必要があるアプリケーションの名前。</param>
        <param name="maximumStabilizationTimeout">他の失敗が安定してサービスの操作を待機する時間の最大量。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API は、可用性と指定したアプリケーションのすべてのサービスの正常性を検証します。
            </summary>
        <returns>タスク</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricValidationException">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">検証に使用するサービスを提供する必要があるアプリケーションの名前。</param>
        <param name="maximumStabilizationTimeout">他の失敗が安定してサービスの操作を待機する時間の最大量。</param>
        <param name="operationTimeout">操作が他のフェールオーバーを完了するため、操作を待機する時間の長さ。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API は、可用性と指定したアプリケーションのすべてのサービスの正常性を検証します。
            </summary>
        <returns>タスク</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricValidationException">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">検証に使用する必要があるサービスの名前。</param>
        <param name="maximumStabilizationTimeout">他の失敗が安定してサービスの操作を待機する時間の最大量。</param>
        <summary>
            この API は、可用性と指定されたサービスの正常性を検証します。
            </summary>
        <returns>タスク</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricValidationException">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">検証に使用する必要があるサービスの名前。</param>
        <param name="maximumStabilizationTimeout">他の失敗が安定してサービスの操作を待機する時間の最大量。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API は、可用性と指定されたサービスの正常性を検証します。
            </summary>
        <returns>タスク</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricValidationException">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">検証に使用する必要があるサービスの名前。</param>
        <param name="maximumStabilizationTimeout">他の失敗が安定してサービスの操作を待機する時間の最大量。</param>
        <param name="operationTimeout">操作が他のフェールオーバーを完了するため、操作を待機する時間の長さ。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API は、可用性と指定されたサービスの正常性を検証します。
            </summary>
        <returns>タスク</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricValidationException">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</exception>
      </Docs>
    </Member>
  </Members>
</Type>