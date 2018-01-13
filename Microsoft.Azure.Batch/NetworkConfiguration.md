<Type Name="NetworkConfiguration" FullName="Microsoft.Azure.Batch.NetworkConfiguration">
  <TypeSignature Language="C#" Value="public class NetworkConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.NetworkConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkConfiguration" />
  <TypeSignature Language="F#" Value="type NetworkConfiguration = class&#xA;    interface ITransportObjectProvider&lt;NetworkConfiguration&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            プールのネットワーク構成にします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NetworkConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.NetworkConfiguration" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolEndpointConfiguration EndpointConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolEndpointConfiguration EndpointConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkConfiguration.EndpointConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointConfiguration As PoolEndpointConfiguration" />
      <MemberSignature Language="F#" Value="member this.EndpointConfiguration : Microsoft.Azure.Batch.PoolEndpointConfiguration with get, set" Usage="Microsoft.Azure.Batch.NetworkConfiguration.EndpointConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolEndpointConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Batch プール内の計算ノードのエンドポイントの構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティで作成されたプールに対してのみ指定できます、<see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkConfiguration.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string with get, set" Usage="Microsoft.Azure.Batch.NetworkConfiguration.SubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールのコンピューティング ノードを参加させる、仮想ネットワーク サブネットの ARM リソース識別子を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            仮想ネットワークは、同じリージョンと、Azure Batch アカウントとサブスクリプションにする必要があります。 指定したサブネットに、プール内のノードの数に合わせて十分な空き IP アドレスが必要です。 サブネットには、十分な空き IP アドレスが割り当てられていない、プールは、コンピューティング ノードを割り当てます部分的にし、サイズ変更エラーが発生します。 'MicrosoftAzureBatch' サービス プリンシパルには、指定された VNet の 'クラシック仮想マシン コントリビューター' ロールベースのアクセス制御 (RBAC) の役割が必要です。 指定されたサブネットは、コンピューティング ノードでタスクをスケジュールできる Azure Batch のサービスからの通信を許可する必要があります。 これは、指定された VNet が、関連付けられたネットワーク セキュリティ グループ (NSG) をチェックして検証できます。 NSG によって指定されたサブネット内の計算ノードへの通信が拒否された場合、バッチ サービスはコンピューティング ノードの状態に設定使用できなくなります。 使用して作成されたプールの<see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />のみ ARM 仮想ネットワーク ('Microsoft.Network/virtualNetworks') のサポート、されますが、プールで作成された<see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />ARM とクラシック仮想ネットワークの両方がサポートされます。 指定した VNet にネットワーク セキュリティ グループ (NSG) が関連付けられている場合、予約されているいくつかのシステム ポートの受信通信を有効にする必要があります。 プールで作成された、 <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineConfiguration" />29876 と 29877、ポートを有効にするだけでなく、ポートはポート 22 を Linux およびポート 3389 for Windows です。 プールで作成された、 <see cref="P:Microsoft.Azure.Batch.CloudPool.CloudServiceConfiguration" />、ポート 10100、20100、および 30100 を有効にします。 またポート 443 での Azure ストレージへの発信接続を有効にします。 詳細についてを参照してください: https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>