<Type Name="IServicePartition" FullName="System.Fabric.IServicePartition">
  <TypeSignature Language="C#" Value="public interface IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServicePartition" />
  <TypeSignature Language="F#" Value="type IServicePartition = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1201:ElementsMustAppearInTheCorrectOrder", Justification="Preserve order of public interface member from V1.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>パーティションに属しを実行時に、システムとの対話をサービスのメソッドを提供に関する情報をサービスを提供します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PartitionInfo">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation PartitionInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation PartitionInfo" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IServicePartition.PartitionInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionInfo As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.PartitionInfo : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.IServicePartition.PartitionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アクセスできるように、<see cref="T:System.Fabric.ServicePartitionInformation" />パーティションの種類および ID を格納する、サービスの</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.ServicePartitionInformation" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                これは、パーティション オブジェクトが閉じていることを示します。 レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportFault">
      <MemberSignature Language="C#" Value="public void ReportFault (System.Fabric.FaultType faultType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportFault(valuetype System.Fabric.FaultType faultType) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />
      <MemberSignature Language="F#" Value="abstract member ReportFault : System.Fabric.FaultType -&gt; unit" Usage="iServicePartition.ReportFault faultType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="faultType" Type="System.Fabric.FaultType" />
      </Parameters>
      <Docs>
        <param name="faultType">
          <para><see cref="T:System.Fabric.FaultType" />サービスで検出されました。</para>
        </param>
        <summary>
          <para>ランタイムにはエラーを報告するレプリカを有効にする元となることできません回復しする必要がありますを再起動または削除、エラーが発生することを示します。</para>
        </summary>
        <remarks>
          <para>エラーは通常、サービス コードには、回復できない問題が発生したときに報告されます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                これは、パーティション オブジェクトが閉じていることを示します。 レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportLoad">
      <MemberSignature Language="C#" Value="public void ReportLoad (System.Collections.Generic.IEnumerable&lt;System.Fabric.LoadMetric&gt; metrics);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportLoad(class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.LoadMetric&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportLoad (metrics As IEnumerable(Of LoadMetric))" />
      <MemberSignature Language="F#" Value="abstract member ReportLoad : seq&lt;System.Fabric.LoadMetric&gt; -&gt; unit" Usage="iServicePartition.ReportLoad metrics" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metrics" Type="System.Collections.Generic.IEnumerable&lt;System.Fabric.LoadMetric&gt;" />
      </Parameters>
      <Docs>
        <param name="metrics">
          <para>コレクション<see cref="T:System.Fabric.LoadMetric" />の負荷を報告します。 </para>
        </param>
        <summary>
          <para>負荷分散のメトリックのセットの負荷を報告します。 いつでも、負荷を報告することができます、<see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />メソッドの 1 つまたは複数のプロパティを提供し、<see cref="T:System.Fabric.LoadMetric" />メソッドです。</para>
        </summary>
        <remarks>
          <para>用意されているものに対応する、報告されたメトリック、<see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" />の一部として、<see cref="T:System.Fabric.Description.ServiceDescription" />サービスの作成に使用されます。 説明には存在しない負荷メトリックは無視されます。 カスタム メトリックを報告機能では、サービスを分散させる追加のカスタム情報を基にした Service Fabric を使用します。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                これは、パーティション オブジェクトが閉じていることを示します。 レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportMoveCost">
      <MemberSignature Language="C#" Value="public void ReportMoveCost (System.Fabric.MoveCost moveCost);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportMoveCost(valuetype System.Fabric.MoveCost moveCost) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportMoveCost(System.Fabric.MoveCost)" />
      <MemberSignature Language="F#" Value="abstract member ReportMoveCost : System.Fabric.MoveCost -&gt; unit" Usage="iServicePartition.ReportMoveCost moveCost" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="moveCost" Type="System.Fabric.MoveCost" />
      </Parameters>
      <Docs>
        <param name="moveCost">
          <para>報告<see cref="T:System.Fabric.MoveCost" />です。</para>
        </param>
        <summary>
          <para>レプリカの移動コストを報告します。</para>
        </summary>
        <remarks>
          <para>サービスは、このメソッドを使用してレプリカの移動コストをレポートできます。 サービス ファブリック リソース残高は、クラスター内の最適なバランスを検索するときに、読み込み情報と、各レプリカの移動コストの両方を調べます。 リソースの残高は分散を実現するために低コストでレプリカを移動たいとします。 </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                これは、パーティション オブジェクトが閉じていることを示します。 レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportPartitionHealth">
      <MemberSignature Language="C#" Value="public void ReportPartitionHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportPartitionHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportPartitionHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportPartitionHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iServicePartition.ReportPartitionHealth healthInfo" />
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
            現在のパーティションの正常性を報告します。 
            </summary>
        <returns />
        <remarks>
          <para>正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。
            パーティションは、正常性ストアに、レポートを送信するのに内部ヘルス クライアントを使用します。
            クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。
            使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。
            </para>
          <para>詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                これは、パーティション オブジェクトが閉じていることを示します。 レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportPartitionHealth">
      <MemberSignature Language="C#" Value="public void ReportPartitionHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportPartitionHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportPartitionHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportPartitionHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iServicePartition.ReportPartitionHealth (healthInfo, sendOptions)" />
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
          <para><see cref="T:System.Fabric.Health.HealthReportSendOptions" />パーティション レポートを送信する方法を制御します。</para>
        </param>
        <summary>
            現在のパーティションの正常性を報告します。 
            </summary>
        <returns />
        <remarks>
          <para>正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。
            パーティションは、正常性ストアに、レポートを送信するのに内部ヘルス クライアントを使用します。
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
  </Members>
</Type>