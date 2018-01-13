<Type Name="ICheckpointManager" FullName="Microsoft.Azure.EventHubs.Processor.ICheckpointManager">
  <TypeSignature Language="C#" Value="public interface ICheckpointManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICheckpointManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.ICheckpointManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICheckpointManager" />
  <TypeSignature Language="F#" Value="type ICheckpointManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            EventProcessorHost Azure Storage 以外の場所のチェックポイントを保存する場合は、このインターフェイスを使用して、独自のチェックポイント マネージャーを作成できます。  
            
            <para>Azure の記憶域マネージャーは、両方のインターフェイスは、同じクラスによって実装されて、リースと、チェックポイントの両方を同じ記憶域を使用します。自由に統一されたストアの両方の種類のデータがある場合は、同じ処理を行います。</para><para>お実装には、どのような情報を知ることがあるないために、このインターフェイスが初期化メソッドを指定できません。</para></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckpointStoreExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; CheckpointStoreExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CheckpointStoreExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.CheckpointStoreExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CheckpointStoreExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CheckpointStoreExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iCheckpointManager.CheckpointStoreExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            チェックポイント ストアが存在しますか。
            </summary>
        <returns>存在する場合、false 以外の場合は true</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCheckpointIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; CreateCheckpointIfNotExistsAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; CreateCheckpointIfNotExistsAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.CreateCheckpointIfNotExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCheckpointIfNotExistsAsync (partitionId As String) As Task(Of Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member CreateCheckpointIfNotExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;" Usage="iCheckpointManager.CreateCheckpointIfNotExistsAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">チェックポイントを作成するパーティションの id です。</param>
        <summary>
            存在しない場合は、特定のパーティションのチェックポイントを作成します。 何も存在する場合は。
            新しく作成されたチェックポイントのオフセット/sequenceNumber は、StartOfStream/0 に設定する必要があります。
            </summary>
        <returns>特定のパーティションのチェックポイントを新しく作成されたか、既に存在するかどうか。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCheckpointStoreIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; CreateCheckpointStoreIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateCheckpointStoreIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.CreateCheckpointStoreIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCheckpointStoreIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateCheckpointStoreIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iCheckpointManager.CreateCheckpointStoreIfNotExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            存在しない場合は、チェックポイントのストアを作成します。 何も存在する場合は。
            </summary>
        <returns>チェックポイントのストアは既に存在するか、[ok]、エラーが発生した場合は false が作成された場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteCheckpointAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteCheckpointAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.DeleteCheckpointAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteCheckpointAsync (partitionId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteCheckpointAsync : string -&gt; System.Threading.Tasks.Task" Usage="iCheckpointManager.DeleteCheckpointAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">ストアからチェックポイントを削除するパーティションの id</param>
        <summary>
            特定のパーティションに対してストアド チェックポイントを削除します。 ストアドのチェックポイントを成功として扱われる特定のパーティションがない場合。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; GetCheckpointAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; GetCheckpointAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.GetCheckpointAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCheckpointAsync (partitionId As String) As Task(Of Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member GetCheckpointAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;" Usage="iCheckpointManager.GetCheckpointAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">チェックポイント情報を取得するパーティションの id。</param>
        <summary>
            特定のパーティションに関連付けられているチェックポイント データを取得します。 そのパーティションのチェックポイントが作成されていない場合は null を返す可能性があります。
            </summary>
        <returns>特定のパーティション、または none 以前格納されている場合は null のチェックポイント情報です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateCheckpointAsync (Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateCheckpointAsync(class Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.UpdateCheckpointAsync(Microsoft.Azure.EventHubs.Processor.Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCheckpointAsync : Microsoft.Azure.EventHubs.Processor.Checkpoint -&gt; System.Threading.Tasks.Task" Usage="iCheckpointManager.UpdateCheckpointAsync checkpoint" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use UpdateCheckpointAsync(Lease lease, Checkpoint checkpoint) instead", true)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="checkpoint" Type="Microsoft.Azure.EventHubs.Processor.Checkpoint" />
      </Parameters>
      <Docs>
        <param name="checkpoint">オフセット sequeceNumber でを使用してストアを更新します。</param>
        <summary>
            指定されたチェックポイントのオフセット/sequenceNumber をストア内のチェックポイントを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateCheckpointAsync (Microsoft.Azure.EventHubs.Processor.Lease lease, Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateCheckpointAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease, class Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.UpdateCheckpointAsync(Microsoft.Azure.EventHubs.Processor.Lease,Microsoft.Azure.EventHubs.Processor.Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCheckpointAsync : Microsoft.Azure.EventHubs.Processor.Lease * Microsoft.Azure.EventHubs.Processor.Checkpoint -&gt; System.Threading.Tasks.Task" Usage="iCheckpointManager.UpdateCheckpointAsync (lease, checkpoint)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
        <Parameter Name="checkpoint" Type="Microsoft.Azure.EventHubs.Processor.Checkpoint" />
      </Parameters>
      <Docs>
        <param name="lease">チェックポイントを実行する対象のパーティション情報。</param>
        <param name="checkpoint">オフセット sequeceNumber でを使用してストアを更新します。</param>
        <summary>
            指定されたチェックポイントのオフセット/sequenceNumber をストア内のチェックポイントを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>