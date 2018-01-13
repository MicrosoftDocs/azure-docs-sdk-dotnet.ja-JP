<Type Name="DataLakeAnalyticsAccount" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsAccount : Microsoft.Azure.Management.DataLake.Analytics.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsAccount extends Microsoft.Azure.Management.DataLake.Analytics.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsAccount&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsAccount = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Data Lake Analytics アカウント オブジェクト、名前付きの Data Lake Analytics アカウントに関連付けられているすべての情報を格納します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DataLakeAnalyticsAccount クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccount (string location, string defaultDataLakeStoreAccount, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; dataLakeStoreAccounts, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;DateTime&gt; lastModifiedTime = null, string endpoint = null, Nullable&lt;Guid&gt; accountId = null, Nullable&lt;int&gt; maxDegreeOfParallelism = null, Nullable&lt;int&gt; queryStoreRetention = null, Nullable&lt;int&gt; maxJobCount = null, Nullable&lt;int&gt; systemMaxDegreeOfParallelism = null, Nullable&lt;int&gt; systemMaxJobCount = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; storageAccounts = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; newTier = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; currentTier = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; firewallState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; firewallRules = null, Nullable&lt;int&gt; maxDegreeOfParallelismPerJob = null, Nullable&lt;int&gt; minPriorityPerJob = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; computePolicies = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string defaultDataLakeStoreAccount, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; dataLakeStoreAccounts, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTime, string endpoint, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; accountId, valuetype System.Nullable`1&lt;int32&gt; maxDegreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; queryStoreRetention, valuetype System.Nullable`1&lt;int32&gt; maxJobCount, valuetype System.Nullable`1&lt;int32&gt; systemMaxDegreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; systemMaxJobCount, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; storageAccounts, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; newTier, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; currentTier, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; firewallState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; firewallRules, valuetype System.Nullable`1&lt;int32&gt; maxDegreeOfParallelismPerJob, valuetype System.Nullable`1&lt;int32&gt; minPriorityPerJob, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; computePolicies) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo},System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.Guid},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.TierType},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.TierType},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, defaultDataLakeStoreAccount As String, dataLakeStoreAccounts As IList(Of DataLakeStoreAccountInfo), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional provisioningState As Nullable(Of DataLakeAnalyticsAccountStatus) = null, Optional state As Nullable(Of DataLakeAnalyticsAccountState) = null, Optional creationTime As Nullable(Of DateTime) = null, Optional lastModifiedTime As Nullable(Of DateTime) = null, Optional endpoint As String = null, Optional accountId As Nullable(Of Guid) = null, Optional maxDegreeOfParallelism As Nullable(Of Integer) = null, Optional queryStoreRetention As Nullable(Of Integer) = null, Optional maxJobCount As Nullable(Of Integer) = null, Optional systemMaxDegreeOfParallelism As Nullable(Of Integer) = null, Optional systemMaxJobCount As Nullable(Of Integer) = null, Optional storageAccounts As IList(Of StorageAccountInfo) = null, Optional newTier As Nullable(Of TierType) = null, Optional currentTier As Nullable(Of TierType) = null, Optional firewallState As Nullable(Of FirewallState) = null, Optional firewallAllowAzureIps As Nullable(Of FirewallAllowAzureIpsState) = null, Optional firewallRules As IList(Of FirewallRule) = null, Optional maxDegreeOfParallelismPerJob As Nullable(Of Integer) = null, Optional minPriorityPerJob As Nullable(Of Integer) = null, Optional computePolicies As IList(Of ComputePolicyAccountCreateParameters) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount (location, defaultDataLakeStoreAccount, dataLakeStoreAccounts, id, name, type, tags, provisioningState, state, creationTime, lastModifiedTime, endpoint, accountId, maxDegreeOfParallelism, queryStoreRetention, maxJobCount, systemMaxDegreeOfParallelism, systemMaxJobCount, storageAccounts, newTier, currentTier, firewallState, firewallAllowAzureIps, firewallRules, maxDegreeOfParallelismPerJob, minPriorityPerJob, computePolicies)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="defaultDataLakeStoreAccount" Type="System.String" />
        <Parameter Name="dataLakeStoreAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastModifiedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="accountId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="maxDegreeOfParallelism" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="queryStoreRetention" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxJobCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="systemMaxDegreeOfParallelism" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="systemMaxJobCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" />
        <Parameter Name="newTier" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;" />
        <Parameter Name="currentTier" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;" />
        <Parameter Name="firewallState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt;" />
        <Parameter Name="firewallAllowAzureIps" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt;" />
        <Parameter Name="firewallRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;" />
        <Parameter Name="maxDegreeOfParallelismPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minPriorityPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="computePolicies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt;" />
      </Parameters>
      <Docs>
        <param name="location">リソースの場所</param>
        <param name="defaultDataLakeStoreAccount">既定のデータ lake ストレージ アカウントこの Data Lake Analytics アカウントに関連付けられています。</param>
        <param name="dataLakeStoreAccounts">このアカウントに関連付けられている Data Lake ストレージ アカウントの一覧です。</param>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="tags">リソース タグ</param>
        <param name="provisioningState">Data Lake Analytics アカウントのプロビジョニング状態。 使用可能な値が含まれます: '失敗'、'作成中'、'実行'、'成功'、'パッチ'、'一時停止中'、'再開'、'削除'、'Deleted'</param>
        <param name="state">Data Lake Analytics アカウントの状態。
            使用可能な値が含まれます: 'Active'、'中断'</param>
        <param name="creationTime">アカウントの作成時。</param>
        <param name="lastModifiedTime">アカウントには、最終更新時刻を設定します。</param>
        <param name="endpoint">このアカウントの完全な CName エンドポイント。</param>
        <param name="accountId">この Data Lake Analytics アカウントに関連付けられている一意の識別子。</param>
        <param name="maxDegreeOfParallelism">最大値は、このアカウントの並列処理の次数をサポートします。</param>
        <param name="queryStoreRetention">日数をジョブのメタデータは保持されます。</param>
        <param name="maxJobCount">最大値には、同時に、アカウントで実行されているジョブがサポートされています。</param>
        <param name="systemMaxDegreeOfParallelism">システムには、このアカウントは、ユーザーがアカウントに対して設定できる並列処理の最大値が制限の並列処理の最大のサポートされている範囲が定義されている.</param>
        <param name="systemMaxJobCount">システムでは、同時実行されているアカウントのユーザーが設定できるジョブの最大数を制限するユーザー アカウントが実行されている最大のサポートされているジョブを定義します。</param>
        <param name="storageAccounts">このアカウントに関連付けられている Azure Blob ストレージ アカウントの一覧です。</param>
        <param name="newTier">コミットメントの層を次の月です。
            使用可能な値が含まれます: '消費'、'Commitment_100AUHours'、'Commitment_500AUHours'、'Commitment_1000AUHours'、'Commitment_5000AUHours'、'Commitment_10000AUHours'、'Commitment_50000AUHours'、'Commitment_100000AUHours'、'Commitment_500000AUHours'</param>
        <param name="currentTier">現在の月の使用中コミットメント層です。 使用可能な値が含まれます: '消費'、'Commitment_100AUHours'、'Commitment_500AUHours'、'Commitment_1000AUHours'、'Commitment_5000AUHours'、'Commitment_10000AUHours'、'Commitment_50000AUHours'、'Commitment_100000AUHours'、'Commitment_500000AUHours'</param>
        <param name="firewallState">この Data Lake Analytics アカウントの IP アドレスをファイアウォールの現在の状態。 使用可能な値が含まれます: 'Enabled'、'Disabled'</param>
        <param name="firewallAllowAzureIps">ファイアウォールを介して Azure 内で元の ip アドレスを許可するかの現在の状態。
            ファイアウォールが無効になっている場合は実行されていません。 使用可能な値が含まれます: 'Enabled'、'Disabled'</param>
        <param name="firewallRules">この Data Lake Analytics アカウントに関連付けられているファイアウォール ルールの一覧です。</param>
        <param name="maxDegreeOfParallelismPerJob">最大値は、このアカウント (job) あたりの並列処理の次数をサポートします。</param>
        <param name="minPriorityPerJob">最小値は、このアカウントごとのジョブの優先度をサポートします。</param>
        <param name="computePolicies">このアカウントを作成するコンピューティング ポリシーの一覧です。</param>
        <summary>
            DataLakeAnalyticsAccount クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; AccountId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.AccountId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この Data Lake Analytics アカウントに関連付けられている一意の識別子を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputePolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; ComputePolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; ComputePolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ComputePolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputePolicies As IList(Of ComputePolicyAccountCreateParameters)" />
      <MemberSignature Language="F#" Value="member this.ComputePolicies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ComputePolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.computePolicies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのアカウントを作成するコンピューティング ポリシーの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アカウントの作成時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; CurrentTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; CurrentTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CurrentTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentTier As Nullable(Of TierType)" />
      <MemberSignature Language="F#" Value="member this.CurrentTier : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CurrentTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在の月の使用のコミットメント層を取得します。 使用可能な値が含まれます: '消費'、'Commitment_100AUHours'、'Commitment_500AUHours'、'Commitment_1000AUHours'、'Commitment_5000AUHours'、'Commitment_10000AUHours'、'Commitment_50000AUHours'、'Commitment_100000AUHours'、'Commitment_500000AUHours'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLakeStoreAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; DataLakeStoreAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; DataLakeStoreAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DataLakeStoreAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLakeStoreAccounts As IList(Of DataLakeStoreAccountInfo)" />
      <MemberSignature Language="F#" Value="member this.DataLakeStoreAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DataLakeStoreAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataLakeStoreAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのアカウントに関連付けられている Data Lake ストレージ アカウントの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultDataLakeStoreAccount">
      <MemberSignature Language="C#" Value="public string DefaultDataLakeStoreAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultDataLakeStoreAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DefaultDataLakeStoreAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultDataLakeStoreAccount As String" />
      <MemberSignature Language="F#" Value="member this.DefaultDataLakeStoreAccount : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DefaultDataLakeStoreAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultDataLakeStoreAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの Data Lake Analytics アカウントに関連付けられている既定の data lake ストレージ アカウントを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このアカウントに、完全な CName エンドポイントを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallAllowAzureIps">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallAllowAzureIps" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallAllowAzureIps As Nullable(Of FirewallAllowAzureIpsState)" />
      <MemberSignature Language="F#" Value="member this.FirewallAllowAzureIps : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallAllowAzureIps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallAllowAzureIps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または許可をファイアウォール経由の Azure 内で元の ip アドレスを許可するかの現在の状態を設定します。 ファイアウォールが無効になっている場合は実行されていません。 使用可能な値が含まれます: 'Enabled'、'Disabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; FirewallRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; FirewallRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallRules" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallRules As IList(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="member this.FirewallRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの Data Lake Analytics アカウントに関連付けられているファイアウォール ルールの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; FirewallState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; FirewallState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallState" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallState As Nullable(Of FirewallState)" />
      <MemberSignature Language="F#" Value="member this.FirewallState : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの Data Lake Analytics アカウントの IP アドレスをファイアウォールの現在の状態を設定します。 使用可能な値が含まれます: 'Enabled'、'Disabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アカウントの最終更新時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelism">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelism As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelism : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDegreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのアカウントの並列処理のサポートされている最大限度を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelismPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDegreeOfParallelismPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelismPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelismPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelismPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDegreeOfParallelismPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのアカウントのジョブあたりの並列処理のサポートされている最大限度を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxJobCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxJobCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxJobCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxJobCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxJobCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxJobCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxJobCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxJobCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または同時に、アカウントで実行されている最大のサポートされているジョブを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinPriorityPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinPriorityPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinPriorityPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MinPriorityPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MinPriorityPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinPriorityPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MinPriorityPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minPriorityPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはごとのジョブがこのアカウントの最小のサポートされている優先度を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; NewTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; NewTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.NewTier" />
      <MemberSignature Language="VB.NET" Value="Public Property NewTier As Nullable(Of TierType)" />
      <MemberSignature Language="F#" Value="member this.NewTier : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.NewTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.newTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または次の月のコミットメント層を設定します。 使用可能な値が含まれます: '消費'、'Commitment_100AUHours'、'Commitment_500AUHours'、'Commitment_1000AUHours'、'Commitment_5000AUHours'、'Commitment_10000AUHours'、'Commitment_50000AUHours'、'Commitment_100000AUHours'、'Commitment_500000AUHours'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of DataLakeAnalyticsAccountStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Data Lake Analytics アカウントのプロビジョニング状態を取得します。
            使用可能な値が含まれます: '失敗'、'作成中'、'実行'、'成功'、'パッチ'、'一時停止中'、'再開'、'削除'、'Deleted'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryStoreRetention">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; QueryStoreRetention { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; QueryStoreRetention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.QueryStoreRetention" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryStoreRetention As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.QueryStoreRetention : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.QueryStoreRetention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.queryStoreRetention")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の日数をジョブのメタデータは保持されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of DataLakeAnalyticsAccountState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Data Lake Analytics アカウントの状態を取得します。 使用可能な値が含まれます: 'Active'、'中断'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; StorageAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccounts As IList(Of StorageAccountInfo)" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.StorageAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのアカウントに関連付けられている Azure Blob ストレージ アカウントの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemMaxDegreeOfParallelism">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SystemMaxDegreeOfParallelism { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SystemMaxDegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxDegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemMaxDegreeOfParallelism As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SystemMaxDegreeOfParallelism : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxDegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.systemMaxDegreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このアカウントは、ユーザーがアカウントに対して設定できる並列処理の最大値を制限、システム定義最大サポートされている並列処理の次数を取得する.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemMaxJobCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SystemMaxJobCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SystemMaxJobCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxJobCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemMaxJobCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SystemMaxJobCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxJobCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.systemMaxJobCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            同時実行されているジョブ、ユーザーの最大数を制限するアカウントで実行されている最大の定義済みのサポートされているジョブがアカウントに対して設定できる、システムを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dataLakeAnalyticsAccount.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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