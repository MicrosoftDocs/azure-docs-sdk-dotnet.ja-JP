<Type Name="NetworkConfiguration" FullName="Microsoft.Azure.Management.Batch.Models.NetworkConfiguration">
  <TypeSignature Language="C#" Value="public class NetworkConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.NetworkConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkConfiguration" />
  <TypeSignature Language="F#" Value="type NetworkConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.NetworkConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            NetworkConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkConfiguration (string subnetId = null, Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration endpointConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string subnetId, class Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration endpointConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.NetworkConfiguration.#ctor(System.String,Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional subnetId As String = null, Optional endpointConfiguration As PoolEndpointConfiguration = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.NetworkConfiguration : string * Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration -&gt; Microsoft.Azure.Management.Batch.Models.NetworkConfiguration" Usage="new Microsoft.Azure.Management.Batch.Models.NetworkConfiguration (subnetId, endpointConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="subnetId" Type="System.String" />
        <Parameter Name="endpointConfiguration" Type="Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration" />
      </Parameters>
      <Docs>
        <param name="subnetId">プールのコンピューティング ノードを参加させる、仮想ネットワーク サブネットの ARM リソース識別子。 これは、フォーム/subscriptions/{サブスクリプション} {グループ} 必要な/providers/{プロバイダー}/virtualNetworks/{ネットワーク}/subnets/{サブネット} です。</param>
        <param name="endpointConfiguration">上のエンドポイントの構成は、Batch プール内のノードを計算します。</param>
        <summary>
            NetworkConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration EndpointConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration EndpointConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.NetworkConfiguration.EndpointConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointConfiguration As PoolEndpointConfiguration" />
      <MemberSignature Language="F#" Value="member this.EndpointConfiguration : Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.NetworkConfiguration.EndpointConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpointConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.PoolEndpointConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Batch プール内の計算ノードのエンドポイントの構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            プールのエンドポイント構成は、virtualMachineConfiguration プロパティを使用してプールでのみサポートされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.NetworkConfiguration.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.NetworkConfiguration.SubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subnetId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールのコンピューティング ノードを参加させる、仮想ネットワーク サブネットの ARM リソース識別子を設定します。 これは、フォーム/subscriptions/{サブスクリプション} {グループ} 必要な/providers/{プロバイダー}/virtualNetworks/{ネットワーク}/subnets/{サブネット} です。
            </summary>
        <value>To be added.</value>
        <remarks>
            仮想ネットワークは、同じリージョンと、Azure Batch アカウントとサブスクリプションにする必要があります。 指定したサブネットに、プール内のノードの数に合わせて十分な空き IP アドレスが必要です。
            サブネットには、十分な空き IP アドレスが割り当てられていない、プールは、コンピューティング ノードを割り当てます部分的にし、サイズ変更エラーが発生します。
            'MicrosoftAzureBatch' サービス プリンシパルには、指定された VNet の 'クラシック仮想マシン コントリビューター' ロールベースのアクセス制御 (RBAC) の役割が必要です。 指定されたサブネットは、コンピューティング ノードでタスクをスケジュールできる Azure Batch のサービスからの通信を許可する必要があります。 これは、指定された VNet が、関連付けられたネットワーク セキュリティ グループ (NSG) をチェックして検証できます。 NSG によって指定されたサブネット内の計算ノードへの通信が拒否された場合、バッチ サービスはコンピューティング ノードの状態に設定使用できなくなります。 バッチ virtualMachineConfiguration を使用して作成されたプールのアカウントは、VNet を使用するために poolAllocationMode userSubscription が必要です。 指定した VNet にネットワーク セキュリティ グループ (NSG) が関連付けられている場合、予約されているいくつかのシステム ポートの受信通信を有効にする必要があります。 仮想マシン構成で作成されたプールの場合、ポート 29876 と 29877 を有効にしたうえで、Linux の場合はポート 22 を、Windows の場合はポート 3389 を有効にします。 クラウド サービス構成で作成されたプールの場合、10100、20100、30100 の各ポートを有効にします。 またポート 443 での Azure ストレージへの発信接続を有効にします。 詳細についてを参照してください: https://docs.microsoft.com/en-us/azure/batch/batch-api-basics#virtual-network-vnet-and-firewall-configuration
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.NetworkConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>