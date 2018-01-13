<Type Name="IStatefulServicePartition" FullName="System.Fabric.IStatefulServicePartition">
  <TypeSignature Language="C#" Value="public interface IStatefulServicePartition : System.Fabric.IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatefulServicePartition implements class System.Fabric.IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatefulServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatefulServicePartition&#xA;Implements IServicePartition" />
  <TypeSignature Language="F#" Value="type IStatefulServicePartition = interface&#xA;    interface IServicePartition" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IServicePartition</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>ステートフル サービス レプリカに関連付けられているパーティションを表します。 </para>
    </summary>
    <remarks>
      <para><see cref="T:System.Fabric.IServicePartition" /> の派生クラスです。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateReplicator">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricReplicator CreateReplicator (System.Fabric.IStateProvider stateProvider, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.FabricReplicator CreateReplicator(class System.Fabric.IStateProvider stateProvider, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="abstract member CreateReplicator : System.Fabric.IStateProvider * System.Fabric.ReplicatorSettings -&gt; System.Fabric.FabricReplicator" Usage="iStatefulServicePartition.CreateReplicator (stateProvider, replicatorSettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricReplicator</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateProvider" Type="System.Fabric.IStateProvider" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="stateProvider">
          <para><see cref="T:System.Fabric.IStateProvider" />いる、返された<see cref="T:System.Fabric.FabricReplicator" />関連付けする必要があります。 これは、多くの場合、同じオブジェクトを実装する<see cref="T:System.Fabric.IStatefulServiceReplica" />、特定のサービスを異なる方法で考慮することがありますが、します。 </para>
        </param>
        <param name="replicatorSettings">
          <para><see cref="T:System.Fabric.ReplicatorSettings" />いる、返された<see cref="T:System.Fabric.FabricReplicator" />構成する必要があります。 </para>
        </param>
        <summary>
          <para>作成、<see cref="T:System.Fabric.FabricReplicator" />指定された設定で、レプリカに返します。 </para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.FabricReplicator" /> を返します。</para>
        </returns>
        <remarks>
          <para>このメソッドは、作成に使用する必要があります、<see cref="T:System.Fabric.FabricReplicator" />サービスとして、<see cref="T:System.Fabric.IStateReplicator" />ステートフルなサービスを実装する<see cref="T:System.Fabric.IStateProvider" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus ReadStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus ReadStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IStatefulServicePartition.ReadStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.ReadStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.IStatefulServicePartition.ReadStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>読み取り操作に関して、レプリカの準備の確認に使用されます。 </para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.PartitionAccessStatus" /> を返します。</para>
        </value>
        <remarks>
          <para><see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />レプリカが読み取り操作は、顧客の要求を処理する前に確認する必要があります。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                これは、パーティション オブジェクトが閉じていることを示します。 レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportReplicaHealth">
      <MemberSignature Language="C#" Value="public void ReportReplicaHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportReplicaHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportReplicaHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportReplicaHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iStatefulServicePartition.ReportReplicaHealth healthInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</param>
        <summary>
            パーティションの現在のステートフル サービス レプリカの正常性を報告します。
            </summary>
        <returns />
        <remarks>
          <para>正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。
            パーティションは、正常性ストアに、レポートを送信するのに内部ヘルス クライアントを使用します。
            クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。
            使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。
            </para>
          <para>詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                これは、パーティション オブジェクトが閉じていることを示します。 レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportReplicaHealth">
      <MemberSignature Language="C#" Value="public void ReportReplicaHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportReplicaHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportReplicaHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportReplicaHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iStatefulServicePartition.ReportReplicaHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</param>
        <param name="sendOptions">
          <para><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</para>
        </param>
        <summary>
            パーティションの現在のステートフル サービス レプリカの正常性を報告します。
            </summary>
        <returns />
        <remarks>
          <para>正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。
            内部的には、パーティションは、正常性ストアに、レポートを送信するのに内部ヘルス クライアントを使用します。
            クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。
            レポートに高優先順位がある場合は、直ちに送信する送信オプションを指定できます。
            </para>
          <para>詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                これは、パーティション オブジェクトが閉じていることを示します。 レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="WriteStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus WriteStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus WriteStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IStatefulServicePartition.WriteStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.WriteStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.IStatefulServicePartition.WriteStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>書き込み操作についてそのパーティションの準備の確認に使用されます。 </para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.PartitionAccessStatus" /> を返します。</para>
        </value>
        <remarks>
          <para><see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" />レプリカは、書き込み操作は、顧客の要求をサービスする前に確認する必要があります。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                これは、パーティション オブジェクトが閉じていることを示します。 レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>