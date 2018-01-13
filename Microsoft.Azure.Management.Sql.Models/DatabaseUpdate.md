<Type Name="DatabaseUpdate" FullName="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate">
  <TypeSignature Language="C#" Value="public class DatabaseUpdate : Microsoft.Azure.Management.Sql.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseUpdate extends Microsoft.Azure.Management.Sql.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseUpdate&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DatabaseUpdate = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            データベースの更新を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DatabaseUpdate クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseUpdate (string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string collation = null, Nullable&lt;DateTime&gt; creationDate = null, Nullable&lt;long&gt; containmentState = null, Nullable&lt;Guid&gt; currentServiceObjectiveId = null, Nullable&lt;Guid&gt; databaseId = null, Nullable&lt;DateTime&gt; earliestRestoreDate = null, string createMode = null, string sourceDatabaseId = null, Nullable&lt;DateTime&gt; sourceDatabaseDeletionDate = null, Nullable&lt;DateTime&gt; restorePointInTime = null, string recoveryServicesRecoveryPointResourceId = null, string edition = null, string maxSizeBytes = null, Nullable&lt;Guid&gt; requestedServiceObjectiveId = null, string requestedServiceObjectiveName = null, string serviceLevelObjective = null, string status = null, string elasticPoolName = null, string defaultSecondaryLocation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; serviceTierAdvisors = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; transparentDataEncryption = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; recommendedIndex = null, string failoverGroupId = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; readScale = null, string sampleName = null, Nullable&lt;bool&gt; zoneRedundant = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string collation, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, valuetype System.Nullable`1&lt;int64&gt; containmentState, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; currentServiceObjectiveId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; databaseId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; earliestRestoreDate, string createMode, string sourceDatabaseId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; sourceDatabaseDeletionDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; restorePointInTime, string recoveryServicesRecoveryPointResourceId, string edition, string maxSizeBytes, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestedServiceObjectiveId, string requestedServiceObjectiveName, string serviceLevelObjective, string status, string elasticPoolName, string defaultSecondaryLocation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; serviceTierAdvisors, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; transparentDataEncryption, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; recommendedIndex, string failoverGroupId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReadScale&gt; readScale, string sampleName, valuetype System.Nullable`1&lt;bool&gt; zoneRedundant) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.#ctor(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{System.Guid},System.Nullable{System.Guid},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.RecommendedIndex},System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.ReadScale},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional collation As String = null, Optional creationDate As Nullable(Of DateTime) = null, Optional containmentState As Nullable(Of Long) = null, Optional currentServiceObjectiveId As Nullable(Of Guid) = null, Optional databaseId As Nullable(Of Guid) = null, Optional earliestRestoreDate As Nullable(Of DateTime) = null, Optional createMode As String = null, Optional sourceDatabaseId As String = null, Optional sourceDatabaseDeletionDate As Nullable(Of DateTime) = null, Optional restorePointInTime As Nullable(Of DateTime) = null, Optional recoveryServicesRecoveryPointResourceId As String = null, Optional edition As String = null, Optional maxSizeBytes As String = null, Optional requestedServiceObjectiveId As Nullable(Of Guid) = null, Optional requestedServiceObjectiveName As String = null, Optional serviceLevelObjective As String = null, Optional status As String = null, Optional elasticPoolName As String = null, Optional defaultSecondaryLocation As String = null, Optional serviceTierAdvisors As IList(Of ServiceTierAdvisor) = null, Optional transparentDataEncryption As IList(Of TransparentDataEncryption) = null, Optional recommendedIndex As IList(Of RecommendedIndex) = null, Optional failoverGroupId As String = null, Optional readScale As Nullable(Of ReadScale) = null, Optional sampleName As String = null, Optional zoneRedundant As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DatabaseUpdate : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;Guid&gt; * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" Usage="new Microsoft.Azure.Management.Sql.Models.DatabaseUpdate (id, name, type, tags, collation, creationDate, containmentState, currentServiceObjectiveId, databaseId, earliestRestoreDate, createMode, sourceDatabaseId, sourceDatabaseDeletionDate, restorePointInTime, recoveryServicesRecoveryPointResourceId, edition, maxSizeBytes, requestedServiceObjectiveId, requestedServiceObjectiveName, serviceLevelObjective, status, elasticPoolName, defaultSecondaryLocation, serviceTierAdvisors, transparentDataEncryption, recommendedIndex, failoverGroupId, readScale, sampleName, zoneRedundant)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="collation" Type="System.String" />
        <Parameter Name="creationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="containmentState" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="currentServiceObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="databaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="earliestRestoreDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="createMode" Type="System.String" />
        <Parameter Name="sourceDatabaseId" Type="System.String" />
        <Parameter Name="sourceDatabaseDeletionDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="restorePointInTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recoveryServicesRecoveryPointResourceId" Type="System.String" />
        <Parameter Name="edition" Type="System.String" />
        <Parameter Name="maxSizeBytes" Type="System.String" />
        <Parameter Name="requestedServiceObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="requestedServiceObjectiveName" Type="System.String" />
        <Parameter Name="serviceLevelObjective" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="defaultSecondaryLocation" Type="System.String" />
        <Parameter Name="serviceTierAdvisors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;" />
        <Parameter Name="transparentDataEncryption" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;" />
        <Parameter Name="recommendedIndex" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt;" />
        <Parameter Name="failoverGroupId" Type="System.String" />
        <Parameter Name="readScale" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt;" />
        <Parameter Name="sampleName" Type="System.String" />
        <Parameter Name="zoneRedundant" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="tags">リソース タグ。</param>
        <param name="collation">データベースの照合順序です。 CreateMode が既定ではない場合、この値は無視されます。</param>
        <param name="creationDate">データベース (ISO8601 形式) の作成日。</param>
        <param name="containmentState">データベースのコンテインメントの状態。</param>
        <param name="currentServiceObjectiveId">現在サービス レベル目標の ID データベース。 これは、現在アクティブなサービス レベル目標の ID です。</param>
        <param name="databaseId">データベースの ID。</param>
        <param name="earliestRestoreDate">このレコードの最も早い開始日時を復元は、このデータベース (ISO8601 形式) で使用可能です。</param>
        <param name="createMode">データベースの作成モードを指定します。
            
             既定値: 通常のデータベースを作成します。
            
             : コピーには、既存のデータベースのコピーとして、データベースが作成されます。
             sourceDatabaseId は、ソース データベースのリソース ID として指定する必要があります。
             
            OnlineSecondary/NonReadableSecondary: は、既存のデータベースのセカンダリ レプリカ (読み取り可能または不可) としてデータベースを作成します。 sourceDatabaseId は、既存のプライマリ データベースのリソース ID として指定する必要があります。
             
             PointInTimeRestore: ポイントイン タイム バックアップ、既存のデータベースを復元することによって、データベースを作成します。 sourceDatabaseId を既存のデータベースのリソース ID として指定する必要があり、restorePointInTime を指定する必要があります。
             
             回復:、geo レプリケーションのバックアップを復元することによって、データベースが作成されます。
            sourceDatabaseId は、復元する回復可能なデータベース リソースの ID として指定する必要があります。
             
             復元:、削除されたデータベースのバックアップを復元することによって、データベースが作成されます。 sourceDatabaseId を指定する必要があります。 SourceDatabaseId がデータベースの元のリソース ID である場合は、sourceDatabaseDeletionDate を指定する必要があります。 それ以外の場合 sourceDatabaseId は削除されたデータベースの復元可能なリソース ID である必要があり、sourceDatabaseDeletionDate は無視されます。 restorePointInTime はの以前の時点から復元するも指定することがあります。
             
             RestoreLongTermRetentionBackup:、長期的な保存の資格情報コンテナーから復元することによって、データベースが作成されます。
            回復ポイントのリソース ID として recoveryServicesRecoveryPointResourceId を指定する必要があります。
             
             DataWarehouse エディションには、コピー、NonReadableSecondary、OnlineSecondary および RestoreLongTermRetentionBackup はサポートされていません。 使用可能な値が含まれます: 'コピー'、'Default'、'NonReadableSecondary'、'OnlineSecondary'、'PointInTimeRestore'、' 復旧'、'Restore'、'RestoreLongTermRetentionBackup'</param>
        <param name="sourceDatabaseId">条件付きです。 CreateMode がコピー、NonReadableSecondary、OnlineSecondary、PointInTimeRestore、復旧、または復元の場合は、この値が必要です。 ソース データベースのリソース ID を指定します。 CreateMode が NonReadableSecondary または OnlineSecondary の場合は、ソース データベースの名前を作成する新しいデータベースと同じにする必要があります。</param>
        <param name="sourceDatabaseDeletionDate">条件付きです。 CreateMode は復元 sourceDatabaseId は削除されたデータベースの元のリソース id ではなく、現在の復元可能な削除されたデータベース id) に存在していた場合は、この値が必要です。 データベースが削除された日時を指定します。</param>
        <param name="restorePointInTime">条件付きです。 CreateMode が PointInTimeRestore の場合は、この値が必要です。 CreateMode が復元の場合は、この値は省略できます。 新しいデータベースを作成する復元するソース データベースの時刻 (ISO8601 形式) で、ポイントを指定します。 ソース データベースの earliestRestoreDate 値以上にする必要があります。</param>
        <param name="recoveryServicesRecoveryPointResourceId">条件付きです。
             CreateMode が RestoreLongTermRetentionBackup の場合は、この値が必要です。 復元する回復ポイントのリソース ID を指定します。</param>
        <param name="edition">データベースのエディションです。 DatabaseEditions 列挙には、有効なすべてのエディションが含まれています。 CreateMode が NonReadableSecondary または OnlineSecondary の場合は、この値は無視されます。 クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。
             使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'、'System'、'システム 2'</param>
        <param name="maxSizeBytes">バイト単位で表されるデータベースの最大サイズ。 CreateMode が既定ではない場合、この値は無視されます。 クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。</param>
        <param name="requestedServiceObjectiveId">データベースの構成済みのサービス レベル目標 ID。 これは、データベースに適用されているプロセスでは、サービス レベル目標です。
             正常に更新されると、その currentServiceObjectiveId プロパティの値は一致します。 RequestedServiceObjectiveId と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveId の値は requestedServiceObjectiveName の値をオーバーライドします。 クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。</param>
        <param name="requestedServiceObjectiveName">データベースの構成済みのサービス レベル目標の名前。 これは、データベースに適用されているプロセスでは、サービス レベル目標です。 正常に更新されると、サービス レベル目標のプロパティの値には一致します。 クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。
             使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</param>
        <param name="serviceLevelObjective">現在サービス レベル目標のデータベースです。 使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</param>
        <param name="status">データベースの状態。</param>
        <param name="elasticPoolName">弾力性プール データベースの名前です。 ElasticPoolName と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveName の値は無視されます。 DataWarehouse エディションのサポートされていません。</param>
        <param name="defaultSecondaryLocation">このデータベースの既定のセカンダリ地域。</param>
        <param name="serviceTierAdvisors">このデータベースのサービス層アドバイザーの一覧。 展開されたプロパティ</param>
        <param name="transparentDataEncryption">透過的なデータ暗号化は、このデータベースの情報です。</param>
        <param name="recommendedIndex">このデータベースの推奨されるインデックスです。</param>
        <param name="failoverGroupId">このデータベースを含むグループのフェールオーバーのリソースの識別子です。</param>
        <param name="readScale">条件付きです。 データベースが地理的セカンダリの場合は、readScale はかに、このデータベースに対する読み取り専用の接続を許可するかどうかを示します。 DataWarehouse エディションのサポートされていません。 使用可能な値が含まれます: 'Enabled'、'Disabled'</param>
        <param name="sampleName">このデータベースを作成するときに適用するサンプルのスキーマの名前を示します。 CreateMode が既定ではない場合、この値は無視されます。 DataWarehouse エディションのサポートされていません。
             使用可能な値が含まれます: 'AdventureWorksLT'</param>
        <param name="zoneRedundant">このデータベースは、ゾーン冗長、このデータベースのレプリカを意味するかどうかは、複数の可用性ゾーン間で分散行われます。</param>
        <summary>
             DatabaseUpdate クラスの新しいインスタンスを初期化します。
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Collation">
      <MemberSignature Language="C#" Value="public string Collation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Collation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Collation" />
      <MemberSignature Language="VB.NET" Value="Public Property Collation As String" />
      <MemberSignature Language="F#" Value="member this.Collation : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Collation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.collation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータベースの照合順序を設定します。 CreateMode が既定ではない場合、この値は無視されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainmentState">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ContainmentState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ContainmentState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ContainmentState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainmentState As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ContainmentState : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ContainmentState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containmentState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            データベースの包含状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMode">
      <MemberSignature Language="C#" Value="public string CreateMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CreateMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreateMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateMode As String" />
      <MemberSignature Language="F#" Value="member this.CreateMode : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreateMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             取得または設定は、データベースの作成モードを指定します。
            
             既定値: 通常のデータベースを作成します。
            
             : コピーには、既存のデータベースのコピーとして、データベースが作成されます。
             sourceDatabaseId は、ソース データベースのリソース ID として指定する必要があります。
             
            OnlineSecondary/NonReadableSecondary: は、既存のデータベースのセカンダリ レプリカ (読み取り可能または不可) としてデータベースを作成します。 sourceDatabaseId は、既存のプライマリ データベースのリソース ID として指定する必要があります。
             
             PointInTimeRestore: ポイントイン タイム バックアップ、既存のデータベースを復元することによって、データベースを作成します。 sourceDatabaseId を既存のデータベースのリソース ID として指定する必要があり、restorePointInTime を指定する必要があります。
             
             回復:、geo レプリケーションのバックアップを復元することによって、データベースが作成されます。
            sourceDatabaseId は、復元する回復可能なデータベース リソースの ID として指定する必要があります。
             
             復元:、削除されたデータベースのバックアップを復元することによって、データベースが作成されます。 sourceDatabaseId を指定する必要があります。 SourceDatabaseId がデータベースの元のリソース ID である場合は、sourceDatabaseDeletionDate を指定する必要があります。 それ以外の場合 sourceDatabaseId は削除されたデータベースの復元可能なリソース ID である必要があり、sourceDatabaseDeletionDate は無視されます。 restorePointInTime はの以前の時点から復元するも指定することがあります。
             
             RestoreLongTermRetentionBackup:、長期的な保存の資格情報コンテナーから復元することによって、データベースが作成されます。
            回復ポイントのリソース ID として recoveryServicesRecoveryPointResourceId を指定する必要があります。
             
             DataWarehouse エディションには、コピー、NonReadableSecondary、OnlineSecondary および RestoreLongTermRetentionBackup はサポートされていません。 使用可能な値が含まれます: 'コピー'、'Default'、'NonReadableSecondary'、'OnlineSecondary'、'PointInTimeRestore'、' 復旧'、'Restore'、'RestoreLongTermRetentionBackup'
             </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            データベース (ISO8601 形式) の作成日を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; CurrentServiceObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; CurrentServiceObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CurrentServiceObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceObjectiveId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CurrentServiceObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentServiceObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービス レベル目標の現在の ID、データベースを取得します。 これは、現在アクティブなサービス レベル目標の ID です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; DatabaseId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; DatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.DatabaseId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DatabaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            データベースの ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSecondaryLocation">
      <MemberSignature Language="C#" Value="public string DefaultSecondaryLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultSecondaryLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DefaultSecondaryLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSecondaryLocation As String" />
      <MemberSignature Language="F#" Value="member this.DefaultSecondaryLocation : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DefaultSecondaryLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultSecondaryLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベースの既定のセカンダリ地域を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EarliestRestoreDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EarliestRestoreDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EarliestRestoreDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.EarliestRestoreDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EarliestRestoreDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EarliestRestoreDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.EarliestRestoreDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.earliestRestoreDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベース (ISO8601 形式) のこのレコードの最も早い開始日時を復元するが取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public string Edition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Edition" />
      <MemberSignature Language="VB.NET" Value="Public Property Edition As String" />
      <MemberSignature Language="F#" Value="member this.Edition : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Edition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.edition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータベースのエディションを設定します。 DatabaseEditions 列挙には、有効なすべてのエディションが含まれています。 CreateMode が NonReadableSecondary または OnlineSecondary の場合は、この値は無視されます。 クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。
            使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'、'System'、'システム 2'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolName">
      <MemberSignature Language="C#" Value="public string ElasticPoolName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public Property ElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.elasticPoolName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータベースが弾力性プールの名前を設定します。 ElasticPoolName と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveName の値は無視されます。 DataWarehouse エディションのサポートされていません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverGroupId">
      <MemberSignature Language="C#" Value="public string FailoverGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailoverGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.FailoverGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailoverGroupId As String" />
      <MemberSignature Language="F#" Value="member this.FailoverGroupId : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.FailoverGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.failoverGroupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベースを含むグループのフェールオーバーのリソース識別子を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeBytes">
      <MemberSignature Language="C#" Value="public string MaxSizeBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxSizeBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.MaxSizeBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeBytes As String" />
      <MemberSignature Language="F#" Value="member this.MaxSizeBytes : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.MaxSizeBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxSizeBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバイト数で表されるデータベースの最大サイズを設定します。 CreateMode が既定ではない場合、この値は無視されます。 クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadScale">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; ReadScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReadScale&gt; ReadScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ReadScale" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadScale As Nullable(Of ReadScale)" />
      <MemberSignature Language="F#" Value="member this.ReadScale : Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ReadScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または条件を設定します。 データベースが地理的セカンダリの場合は、readScale はかに、このデータベースに対する読み取り専用の接続を許可するかどうかを示します。 DataWarehouse エディションのサポートされていません。
            使用可能な値が含まれます: 'Enabled'、'Disabled'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendedIndex">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; RecommendedIndex { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; RecommendedIndex" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecommendedIndex" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecommendedIndex As IList(Of RecommendedIndex)" />
      <MemberSignature Language="F#" Value="member this.RecommendedIndex : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecommendedIndex" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recommendedIndex")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベースの推奨インデックスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryServicesRecoveryPointResourceId">
      <MemberSignature Language="C#" Value="public string RecoveryServicesRecoveryPointResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryServicesRecoveryPointResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecoveryServicesRecoveryPointResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryServicesRecoveryPointResourceId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryServicesRecoveryPointResourceId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecoveryServicesRecoveryPointResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recoveryServicesRecoveryPointResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または条件を設定します。 CreateMode が RestoreLongTermRetentionBackup の場合は、この値が必要です。
            復元する回復ポイントのリソース ID を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestedServiceObjectiveId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestedServiceObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestedServiceObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjectiveId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedServiceObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータベースの構成済みのサービス レベル目標の ID を設定します。 これは、データベースに適用されているプロセスでは、サービス レベル目標です。 正常に更新されると、その currentServiceObjectiveId プロパティの値は一致します。 RequestedServiceObjectiveId と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveId の値は requestedServiceObjectiveName の値をオーバーライドします。 クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjectiveName">
      <MemberSignature Language="C#" Value="public string RequestedServiceObjectiveName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedServiceObjectiveName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveName" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestedServiceObjectiveName As String" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjectiveName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedServiceObjectiveName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータベースの構成済みのサービス レベル目標の名前を設定します。 これは、データベースに適用されているプロセスでは、サービス レベル目標です。 正常に更新されると、サービス レベル目標のプロパティの値には一致します。
            クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。
            使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePointInTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RestorePointInTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RestorePointInTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RestorePointInTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RestorePointInTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RestorePointInTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RestorePointInTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.restorePointInTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または条件を設定します。 CreateMode が PointInTimeRestore の場合は、この値が必要です。 CreateMode が復元の場合は、この値は省略できます。 新しいデータベースを作成する復元するソース データベースの時刻 (ISO8601 形式) で、ポイントを指定します。
            ソース データベースの earliestRestoreDate 値以上にする必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SampleName">
      <MemberSignature Language="C#" Value="public string SampleName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SampleName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SampleName" />
      <MemberSignature Language="VB.NET" Value="Public Property SampleName As String" />
      <MemberSignature Language="F#" Value="member this.SampleName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SampleName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sampleName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、このデータベースを作成するときに適用するサンプルのスキーマの名前を示します。 CreateMode が既定ではない場合、この値は無視されます。 DataWarehouse エディションのサポートされていません。 使用可能な値が含まれます: 'AdventureWorksLT'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string ServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            データベースの現在のサービス レベル目標を取得します。 使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTierAdvisors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ServiceTierAdvisors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ServiceTierAdvisors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceTierAdvisors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTierAdvisors As IList(Of ServiceTierAdvisor)" />
      <MemberSignature Language="F#" Value="member this.ServiceTierAdvisors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceTierAdvisors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceTierAdvisors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベースのサービス層アドバイザーの一覧を取得します。 展開されたプロパティ
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDatabaseDeletionDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SourceDatabaseDeletionDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SourceDatabaseDeletionDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseDeletionDate" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDatabaseDeletionDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SourceDatabaseDeletionDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseDeletionDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceDatabaseDeletionDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または条件を設定します。 CreateMode は復元 sourceDatabaseId は削除されたデータベースの元のリソース id ではなく、現在の復元可能な削除されたデータベース id) に存在していた場合は、この値が必要です。 データベースが削除された日時を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDatabaseId">
      <MemberSignature Language="C#" Value="public string SourceDatabaseId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceDatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDatabaseId As String" />
      <MemberSignature Language="F#" Value="member this.SourceDatabaseId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceDatabaseId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または条件を設定します。 CreateMode がコピー、NonReadableSecondary、OnlineSecondary、PointInTimeRestore、復旧、または復元の場合は、この値が必要です。 ソース データベースのリソース ID を指定します。 CreateMode が NonReadableSecondary または OnlineSecondary の場合は、ソース データベースの名前を作成する新しいデータベースと同じにする必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            データベースの状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソース タグを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransparentDataEncryption">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; TransparentDataEncryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; TransparentDataEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.TransparentDataEncryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransparentDataEncryption As IList(Of TransparentDataEncryption)" />
      <MemberSignature Language="F#" Value="member this.TransparentDataEncryption : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.TransparentDataEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.transparentDataEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベースの透過的なデータの暗号化情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ZoneRedundant">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ZoneRedundant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ZoneRedundant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ZoneRedundant" />
      <MemberSignature Language="VB.NET" Value="Public Property ZoneRedundant As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ZoneRedundant : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ZoneRedundant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.zoneRedundant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのデータベースが複数の可用性ゾーン、ゾーン冗長、このデータベースのレプリカを意味に分散するかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>