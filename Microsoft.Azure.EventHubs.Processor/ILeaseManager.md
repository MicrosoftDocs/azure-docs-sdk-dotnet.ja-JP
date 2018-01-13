<Type Name="ILeaseManager" FullName="Microsoft.Azure.EventHubs.Processor.ILeaseManager">
  <TypeSignature Language="C#" Value="public interface ILeaseManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILeaseManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.ILeaseManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILeaseManager" />
  <TypeSignature Language="F#" Value="type ILeaseManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            EventProcessorHost リース Azure Storage 以外の場所を格納する場合は、このインターフェイスを使用して、独自のリース マネージャーを作成できます。  
            
            <para>Azure の記憶域マネージャーは、両方のインターフェイスは、同じクラスによって実装されて、リースと、チェックポイントの両方を同じ記憶域を使用します。自由に統一されたストアの両方の種類のデータがある場合は、同じ処理を行います。</para><para>お実装には、どのような情報を知ることがあるないために、このインターフェイスが初期化メソッドを指定できません。</para></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; AcquireLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; AcquireLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.AcquireLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.AcquireLeaseAsync lease" />
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
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease">既に GetLeaseAsync() から取得した適切なパーティションの情報をリース</param>
        <summary>
            この EventProcessorHost の適切なパーティションでリースを取得します。
            
            <para>別のホストによって既に所有されているリースを取得することに注意してください。リース スティー リングは、他のホストが開始されたときにパーティションが再配布方法です。</para></summary>
        <returns>リースは、その以外の場合は、正常に取得した場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateLeaseIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt; CreateLeaseIfNotExistsAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt; CreateLeaseIfNotExistsAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.CreateLeaseIfNotExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateLeaseIfNotExistsAsync (partitionId As String) As Task(Of Lease)" />
      <MemberSignature Language="F#" Value="abstract member CreateLeaseIfNotExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;" Usage="iLeaseManager.CreateLeaseIfNotExistsAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">リース情報を作成するパーティションの id</param>
        <summary>
            ストアに、リースの情報を作成、特定のパーティションが存在しない場合。 何も実行しない、ストアに既に存在しています。 
            </summary>
        <returns>パーティションの既存または新規に作成されたリース情報</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateLeaseStoreIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; CreateLeaseStoreIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateLeaseStoreIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.CreateLeaseStoreIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateLeaseStoreIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateLeaseStoreIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.CreateLeaseStoreIfNotExistsAsync " />
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
            リースのストアを作成することがない場合、何も存在する場合は。
            </summary>
        <returns>ストアが既にリース場合は true が存在するか、正常に作成されました、false 以外の場合</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.DeleteLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member DeleteLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task" Usage="iLeaseManager.DeleteLeaseAsync lease" />
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
      </Parameters>
      <Docs>
        <param name="lease">既に GetLeaseAsync() から取得した適切なパーティションの情報をリース</param>
        <summary>
            ストアから特定のパーティションのリース情報を削除します。 成功として扱われる特定のパーティションに対するストアドのリースがない場合。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteLeaseStoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; DeleteLeaseStoreAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteLeaseStoreAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.DeleteLeaseStoreAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteLeaseStoreAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteLeaseStoreAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.DeleteLeaseStoreAsync " />
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
            テストするために、EventProcessorHost は便利な関数では使用されません。
            </summary>
        <returns>リース ストアは、その以外の場合は、正常に削除された場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLeases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt; GetAllLeases ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt; GetAllLeases() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.GetAllLeases" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllLeases () As IEnumerable(Of Task(Of Lease))" />
      <MemberSignature Language="F#" Value="abstract member GetAllLeases : unit -&gt; seq&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt;" Usage="iLeaseManager.GetAllLeases " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            すべてのパーティションのリース情報を返します。
            一般的な実装は、すべてのパーティションで GetLeaseAsync() を呼び出すだけでした。
            </summary>
        <returns>リース情報の一覧です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt; GetLeaseAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Lease&gt; GetLeaseAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.GetLeaseAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLeaseAsync (partitionId As String) As Task(Of Lease)" />
      <MemberSignature Language="F#" Value="abstract member GetLeaseAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;" Usage="iLeaseManager.GetLeaseAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Lease&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">リースを取得するパーティションの id</param>
        <summary>
            指定されたパーティションのリース情報を返します。 指定したパーティションのストアにリースが作成されていない場合は null を返すことができます。
            </summary>
        <returns>パーティション、または null の情報をリース</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseDuration : TimeSpan" Usage="Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            テストのほとんどの場合に役立ちます。
            </summary>
        <value>更新されないと、有効期限が切れる前に、リースの期間です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseRenewInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseRenewInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseRenewInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseRenewInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LeaseRenewInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseRenewInterval : TimeSpan" Usage="Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseRenewInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リースをスキャンし、それらを更新か頻度 PartitionManager を指定するリース マネージャーの実装を使用できます。 ホストが動作を中断した後に適切なタイミングでリースを再配布するためには、10 秒などの比較的短い間隔お勧めします。 言うまでもなく偶発的な有効期限を防ぐために、リース期間の半分未満でなければなりません。
            </summary>
        <value>スリープ状態のスキャン間隔</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseStoreExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; LeaseStoreExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; LeaseStoreExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.LeaseStoreExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function LeaseStoreExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member LeaseStoreExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.LeaseStoreExistsAsync " />
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
            リース ストアが存在しますか。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ReleaseLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ReleaseLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.ReleaseLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.ReleaseLeaseAsync lease" />
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
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease">リース付与するには</param>
        <summary>
            このホストで現在保持されている、リースを付けます。
            <para>場合は、リースが盗難にあったされたり有効期限が切れて、解放が必要に応じてでありしようとした場合は失敗します。</para></summary>
        <returns>リースは、その以外の場合は、正常にリリースされた場合は true。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; RenewLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; RenewLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.RenewLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.RenewLeaseAsync lease" />
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
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease">リースを更新します。</param>
        <summary>
            このホストで現在保持されているリースを更新します。
            
            <para>リースが盗難にあった場合または期限切れにした場合リリースされた、更新して更新することはできません。GetLease() し acquireLease() を再度呼び出す必要があります。</para></summary>
        <returns>true の場合、リースは、その以外の場合は、正常に更新されました</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateLeaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; UpdateLeaseAsync (Microsoft.Azure.EventHubs.Processor.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; UpdateLeaseAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ILeaseManager.UpdateLeaseAsync(Microsoft.Azure.EventHubs.Processor.Lease)" />
      <MemberSignature Language="F#" Value="abstract member UpdateLeaseAsync : Microsoft.Azure.EventHubs.Processor.Lease -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iLeaseManager.UpdateLeaseAsync lease" />
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
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
      </Parameters>
      <Docs>
        <param name="lease">新しいリース情報を格納します。</param>
        <summary>
            指定されたリースの情報と、ストアを更新します。
            
            <para>更新するために現在のリースを保持する必要があります。リースが盗まれた、または有効期限が切れた、またはリリースを更新できません。更新プロセス中にリースの有効期限を避けるために、更新プログラムを実行する前にリースを更新する必要があります。</para></summary>
        <returns>更新後に実行された場合は、正常にされていない場合は true</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>