<Type Name="IStatelessServicePartition" FullName="System.Fabric.IStatelessServicePartition">
  <TypeSignature Language="C#" Value="public interface IStatelessServicePartition : System.Fabric.IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatelessServicePartition implements class System.Fabric.IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatelessServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatelessServicePartition&#xA;Implements IServicePartition" />
  <TypeSignature Language="F#" Value="type IStatelessServicePartition = interface&#xA;    interface IServicePartition" />
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
      <para>ステートレス サービス インスタンスに関連付けられているパーティションを表します。</para>
    </summary>
    <remarks>
      <para>パラメーターとして、ステートレスなサービスを提供、<see cref="T:System.Fabric.IServicePartition" />です。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ReportInstanceHealth">
      <MemberSignature Language="C#" Value="public void ReportInstanceHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportInstanceHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportInstanceHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportInstanceHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iStatelessServicePartition.ReportInstanceHealth healthInfo" />
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
            パーティションの現在のステートレスなサービス インスタンスの正常性に関する情報を報告します。 
            </summary>
        <returns />
        <remarks>
          <para>正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。
            パーティションは、正常性ストアに、レポートを送信するのに内部ヘルス クライアントを使用します。
            使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。
            </para>
          <para>詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                これは、パーティション オブジェクトが閉じていることを示します。 レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportInstanceHealth">
      <MemberSignature Language="C#" Value="public void ReportInstanceHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportInstanceHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportInstanceHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportInstanceHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iStatelessServicePartition.ReportInstanceHealth (healthInfo, sendOptions)" />
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
            パーティションの現在のステートレスなサービス インスタンスの正常性に関する情報を報告します。 
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