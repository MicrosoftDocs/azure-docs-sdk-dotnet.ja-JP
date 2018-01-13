<Type Name="IaasVMRestoreRequest" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest">
  <TypeSignature Language="C#" Value="public class IaasVMRestoreRequest : Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IaasVMRestoreRequest extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequest" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class IaasVMRestoreRequest&#xA;Inherits RestoreRequest" />
  <TypeSignature Language="F#" Value="type IaasVMRestoreRequest = class&#xA;    inherit RestoreRequest" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequest</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            IaaS VM のワークロードに固有の復元します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaasVMRestoreRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            IaasVMRestoreRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaasVMRestoreRequest (string recoveryPointId = null, string recoveryType = null, string sourceResourceId = null, string targetVirtualMachineId = null, string targetResourceGroupId = null, string storageAccountId = null, string virtualNetworkId = null, string subnetId = null, string targetDomainNameId = null, string region = null, string affinityGroup = null, Nullable&lt;bool&gt; createNewCloudService = null, Nullable&lt;bool&gt; originalStorageAccountOption = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails encryptionDetails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string recoveryPointId, string recoveryType, string sourceResourceId, string targetVirtualMachineId, string targetResourceGroupId, string storageAccountId, string virtualNetworkId, string subnetId, string targetDomainNameId, string region, string affinityGroup, valuetype System.Nullable`1&lt;bool&gt; createNewCloudService, valuetype System.Nullable`1&lt;bool&gt; originalStorageAccountOption, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails encryptionDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest : string * string * string * string * string * string * string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest (recoveryPointId, recoveryType, sourceResourceId, targetVirtualMachineId, targetResourceGroupId, storageAccountId, virtualNetworkId, subnetId, targetDomainNameId, region, affinityGroup, createNewCloudService, originalStorageAccountOption, encryptionDetails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="recoveryType" Type="System.String" />
        <Parameter Name="sourceResourceId" Type="System.String" />
        <Parameter Name="targetVirtualMachineId" Type="System.String" />
        <Parameter Name="targetResourceGroupId" Type="System.String" />
        <Parameter Name="storageAccountId" Type="System.String" />
        <Parameter Name="virtualNetworkId" Type="System.String" />
        <Parameter Name="subnetId" Type="System.String" />
        <Parameter Name="targetDomainNameId" Type="System.String" />
        <Parameter Name="region" Type="System.String" />
        <Parameter Name="affinityGroup" Type="System.String" />
        <Parameter Name="createNewCloudService" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="originalStorageAccountOption" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="encryptionDetails" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails" />
      </Parameters>
      <Docs>
        <param name="recoveryPointId">回復するバックアップ コピーの ID です。</param>
        <param name="recoveryType">この回復の種類。 使用可能な値が含まれます: '無効'、'OriginalLocation'、'AlternateLocation'、'RestoreDisks'</param>
        <param name="sourceResourceId">復旧中は、VM の完全修飾の ARM ID です。</param>
        <param name="targetVirtualMachineId">これは、作成される VM の完全な ARM Id です。
            例:/subscriptions/{subId}/resourcegroups/{rg}/provider/Microsoft.Compute/virtualmachines/{vm} の</param>
        <param name="targetResourceGroupId">これは、このバーチャル マシンと他の成果物を作成するリソース グループの ARM Id です。
            例:/subscriptions/{subId} 必要な {rg} の</param>
        <param name="storageAccountId">復元する VM を持っているストレージ アカウントの完全修飾の ARM ID です。</param>
        <param name="virtualNetworkId">これは、仮想ネットワーク、仮想マシンに追加される vnet の Id です。
            リンクの access の結合操作のアクセス許可のユーザーが検証されます。</param>
        <param name="subnetId">サブネット ID は ID に関連付けられているサブネットの VM を復元します。 {VnetID}/Subnet/{subnetname} なりますクラシック Vm のと、Azure リソース マネージャーの vm になります ARM リソース ID が、サブネットを表すために使用します。</param>
        <param name="targetDomainNameId">復元中の VM に関連付けられる、ドメイン名の完全修飾の ARM ID です。 これには、のみを従来の仮想マシンが適用されます。</param>
        <param name="region">バーチャル マシンを復元する領域です。</param>
        <param name="affinityGroup">復元する仮想マシンに関連付けられているアフィニティ グループ。 従来のコンピューティング仮想マシンでのみ使用されます。</param>
        <param name="createNewCloudService">VM を復元中に、新しいクラウド サービスを作成する必要があります。 これが false の場合、バックアップの時点では、VM は同じクラウド サービスに復元されます。</param>
        <param name="originalStorageAccountOption">To be added.</param>
        <param name="encryptionDetails">VM がバックアップ時に暗号化された場合に必要な詳細です。</param>
        <summary>
            IaasVMRestoreRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityGroup">
      <MemberSignature Language="C#" Value="public string AffinityGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.AffinityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityGroup As String" />
      <MemberSignature Language="F#" Value="member this.AffinityGroup : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.AffinityGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または復元する仮想マシンに関連付けられているアフィニティ グループを設定します。 従来のコンピューティング仮想マシンでのみ使用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNewCloudService">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CreateNewCloudService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CreateNewCloudService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.CreateNewCloudService" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateNewCloudService As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CreateNewCloudService : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.CreateNewCloudService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createNewCloudService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、VM を復元中に、新しいクラウド サービスを作成します必要があります。 これが false の場合、バックアップの時点では、VM は同じクラウド サービスに復元されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails EncryptionDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails EncryptionDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.EncryptionDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionDetails As EncryptionDetails" />
      <MemberSignature Language="F#" Value="member this.EncryptionDetails : Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.EncryptionDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または VM がバックアップ時に暗号化された場合に必要な詳細情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginalStorageAccountOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OriginalStorageAccountOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OriginalStorageAccountOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.OriginalStorageAccountOption" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginalStorageAccountOption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OriginalStorageAccountOption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.OriginalStorageAccountOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="originalStorageAccountOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointId">
      <MemberSignature Language="C#" Value="public string RecoveryPointId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryPointId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.RecoveryPointId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.RecoveryPointId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または回復するバックアップ コピーの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryType">
      <MemberSignature Language="C#" Value="public string RecoveryType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.RecoveryType" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryType As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.RecoveryType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この回復の種類を設定します。 使用可能な値が含まれます: '無効'、'OriginalLocation'、'AlternateLocation'、'RestoreDisks'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Region">
      <MemberSignature Language="C#" Value="public string Region { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Region" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.Region" />
      <MemberSignature Language="VB.NET" Value="Public Property Region As String" />
      <MemberSignature Language="F#" Value="member this.Region : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.Region" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="region")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバーチャル マシンを復元する地域を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceResourceId">
      <MemberSignature Language="C#" Value="public string SourceResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.SourceResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceResourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceResourceId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.SourceResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または復旧中は、VM の完全修飾の ARM ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountId">
      <MemberSignature Language="C#" Value="public string StorageAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.StorageAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.StorageAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または復元する VM を持っているストレージ アカウントの完全修飾の ARM ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.SubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            取得またはサブネット ID を設定する、ID に関連付けられているサブネットには、VM を復元します。 {VnetID}/Subnet/{subnetname} なりますクラシック Vm のと、Azure リソース マネージャーの vm になります ARM リソース ID が、サブネットを表すために使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDomainNameId">
      <MemberSignature Language="C#" Value="public string TargetDomainNameId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetDomainNameId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetDomainNameId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDomainNameId As String" />
      <MemberSignature Language="F#" Value="member this.TargetDomainNameId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetDomainNameId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetDomainNameId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または復元中の VM に関連付けられる、ドメイン名の完全修飾の ARM ID を設定します。 これには、のみを従来の仮想マシンが適用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceGroupId">
      <MemberSignature Language="C#" Value="public string TargetResourceGroupId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetResourceGroupId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceGroupId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceGroupId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetResourceGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceGroupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定に、これはこのバーチャル マシンと他の成果物を作成するリソース グループの ARM Id です。
            例:/subscriptions/{subId} 必要な {rg} の
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetVirtualMachineId">
      <MemberSignature Language="C#" Value="public string TargetVirtualMachineId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetVirtualMachineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetVirtualMachineId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetVirtualMachineId As String" />
      <MemberSignature Language="F#" Value="member this.TargetVirtualMachineId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetVirtualMachineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetVirtualMachineId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定が作成される VM の完全な ARM Id です。
            例:/subscriptions/{subId}/resourcegroups/{rg}/provider/Microsoft.Compute/virtualmachines/{vm} の
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkId">
      <MemberSignature Language="C#" Value="public string VirtualNetworkId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualNetworkId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.VirtualNetworkId" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.VirtualNetworkId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualNetworkId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想ネットワーク、仮想マシンに追加される vnet の Id になります。
            リンクの access の結合操作のアクセス許可のユーザーが検証されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>