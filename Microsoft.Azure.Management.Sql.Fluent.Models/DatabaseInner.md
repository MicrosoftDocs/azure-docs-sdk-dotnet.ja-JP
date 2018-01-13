<Type Name="DatabaseInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner">
  <TypeSignature Language="C#" Value="public class DatabaseInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DatabaseInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure SQL データベースを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DatabaseInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string collation = null, Nullable&lt;DateTime&gt; creationDate = null, Nullable&lt;long&gt; containmentState = null, Nullable&lt;Guid&gt; currentServiceObjectiveId = null, string databaseId = null, Nullable&lt;DateTime&gt; earliestRestoreDate = null, string createMode = null, string sourceDatabaseId = null, string edition = null, string maxSizeBytes = null, Nullable&lt;Guid&gt; requestedServiceObjectiveId = null, string requestedServiceObjectiveName = null, string serviceLevelObjective = null, string status = null, string elasticPoolName = null, string defaultSecondaryLocation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt; serviceTierAdvisors = null, Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeHint upgradeHint = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.SchemaInner&gt; schemas = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; transparentDataEncryption = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt; recommendedIndex = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string collation, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, valuetype System.Nullable`1&lt;int64&gt; containmentState, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; currentServiceObjectiveId, string databaseId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; earliestRestoreDate, string createMode, string sourceDatabaseId, string edition, string maxSizeBytes, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestedServiceObjectiveId, string requestedServiceObjectiveName, string serviceLevelObjective, string status, string elasticPoolName, string defaultSecondaryLocation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt; serviceTierAdvisors, class Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeHint upgradeHint, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.SchemaInner&gt; schemas, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; transparentDataEncryption, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt; recommendedIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{System.Guid},System.String,System.Nullable{System.DateTime},System.String,System.String,System.String,System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner},Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeHint,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Fluent.Models.SchemaInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; * string * Nullable&lt;DateTime&gt; * string * string * string * string * Nullable&lt;Guid&gt; * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt; * Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeHint * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.SchemaInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner (location, id, name, type, tags, collation, creationDate, containmentState, currentServiceObjectiveId, databaseId, earliestRestoreDate, createMode, sourceDatabaseId, edition, maxSizeBytes, requestedServiceObjectiveId, requestedServiceObjectiveName, serviceLevelObjective, status, elasticPoolName, defaultSecondaryLocation, serviceTierAdvisors, upgradeHint, schemas, transparentDataEncryption, recommendedIndex)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="collation" Type="System.String" />
        <Parameter Name="creationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="containmentState" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="currentServiceObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="earliestRestoreDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="createMode" Type="System.String" />
        <Parameter Name="sourceDatabaseId" Type="System.String" />
        <Parameter Name="edition" Type="System.String" />
        <Parameter Name="maxSizeBytes" Type="System.String" />
        <Parameter Name="requestedServiceObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="requestedServiceObjectiveName" Type="System.String" />
        <Parameter Name="serviceLevelObjective" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="defaultSecondaryLocation" Type="System.String" />
        <Parameter Name="serviceTierAdvisors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;" />
        <Parameter Name="upgradeHint" Type="Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeHint" />
        <Parameter Name="schemas" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.SchemaInner&gt;" />
        <Parameter Name="transparentDataEncryption" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;" />
        <Parameter Name="recommendedIndex" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="collation">Azure SQL データベースの照合順序です。</param>
        <param name="creationDate">Azure SQL データベース (ISO8601 形式) の作成日。</param>
        <param name="containmentState">Azure SQL データベースのコンテインメントの状態。</param>
        <param name="currentServiceObjectiveId">現在サービス レベル目標の ID、Azure SQL データベース。 これは、現在アクティブなサービス レベル目標の ID です。</param>
        <param name="databaseId">Azure SQL データベースの ID。</param>
        <param name="earliestRestoreDate">復旧期間は、Azure SQL データベースの日を開始します。 これは、開始日と回復がこの Azure SQL データベース (ISO8601 形式) の使用可能な場合に記録します。</param>
        <param name="createMode">作成するデータベースの種類を指定します。
            使用可能な値が含まれます: 'コピー'、'Default'、'NonReadableSecondary'、'OnlineSecondary'、'PointInTimeRestore'、'復旧'、'Restore'</param>
        <param name="sourceDatabaseId">条件付きです。 ソース データベースのリソース ID を指定します。 CreateMode が既定値に設定されていない場合は、この値を指定する必要があります。 ソース データベースの名前は同じである必要があります。 注: 照合順序、エディション、および MaxSizeBytes 必要があります、同じままのリンクがアクティブな状態です。 これらのパラメーターに指定した値は無視されます。</param>
        <param name="edition">Azure SQL データベースのエディションです。 DatabaseEditions 列挙には、有効なすべてのエディションが含まれています。
            使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'</param>
        <param name="maxSizeBytes">バイト単位で表される Azure SQL データベースの最大サイズ。 注: (各エディションで配置されている制限事項) だけでなく、次のサイズのみがサポートされて: {100 MB | 500 MB | 1 GB | 5 GB | 10 GB | 20 GB | 30 GB. 150 GB |200 GB しています.
            500 GB}</param>
        <param name="requestedServiceObjectiveId">構成されたサービス レベル目標の ID、Azure SQL データベース。 これは、サービス レベル目標の Azure SQL データベースに適用されている処理を行っています。 正常に更新されると、その currentServiceObjectiveId プロパティの値は一致します。</param>
        <param name="requestedServiceObjectiveName">Azure SQL データベースの構成済みのサービス レベル目標の名前です。 これは、サービス レベル目標の Azure SQL データベースに適用されている処理を行っています。 正常に更新されると、サービス レベル目標のプロパティの値には一致します。 使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'</param>
        <param name="serviceLevelObjective">Azure SQL データベースの現在のサービス レベル目標です。 使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'</param>
        <param name="status">Azure SQL データベースの状態です。</param>
        <param name="elasticPoolName">データベースが Azure SQL 弾力性プールの名前。</param>
        <param name="defaultSecondaryLocation">このデータベースの既定のセカンダリ地域。</param>
        <param name="serviceTierAdvisors">このデータベースのサービス層アドバイザーの一覧。 展開されたプロパティ</param>
        <param name="upgradeHint">このデータベースのアップグレードのヒント。</param>
        <param name="schemas">このデータベースからスキーマです。</param>
        <param name="transparentDataEncryption">透過的なデータ暗号化は、このデータベースの情報です。</param>
        <param name="recommendedIndex">このデータベースの推奨されるインデックスです。</param>
        <summary>
            DatabaseInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Collation">
      <MemberSignature Language="C#" Value="public string Collation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Collation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.Collation" />
      <MemberSignature Language="VB.NET" Value="Public Property Collation As String" />
      <MemberSignature Language="F#" Value="member this.Collation : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.Collation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得または Azure SQL データベースの照合順序を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainmentState">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ContainmentState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ContainmentState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.ContainmentState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainmentState As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ContainmentState : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.ContainmentState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Azure SQL データベースのコンテインメントの状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMode">
      <MemberSignature Language="C#" Value="public string CreateMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CreateMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.CreateMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateMode As String" />
      <MemberSignature Language="F#" Value="member this.CreateMode : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.CreateMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得または設定を作成するデータベースの種類を指定します。 使用可能な値が含まれます: 'コピー'、'Default'、'NonReadableSecondary'、'OnlineSecondary'、'PointInTimeRestore'、'復旧'、'Restore'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Azure SQL データベース (ISO8601 形式) の作成日を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; CurrentServiceObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; CurrentServiceObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.CurrentServiceObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceObjectiveId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.CurrentServiceObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Azure SQL データベースの現在のサービス レベル目標の ID を取得します。 これは、現在アクティブなサービス レベル目標の ID です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseId">
      <MemberSignature Language="C#" Value="public string DatabaseId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.DatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseId As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseId : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.DatabaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure SQL データベースの ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSecondaryLocation">
      <MemberSignature Language="C#" Value="public string DefaultSecondaryLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultSecondaryLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.DefaultSecondaryLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSecondaryLocation As String" />
      <MemberSignature Language="F#" Value="member this.DefaultSecondaryLocation : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.DefaultSecondaryLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.EarliestRestoreDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EarliestRestoreDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EarliestRestoreDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.EarliestRestoreDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Azure SQL データベースの復旧期間の開始日を取得します。 これは、開始日と回復がこの Azure SQL データベース (ISO8601 形式) の使用可能な場合に記録します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public string Edition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.Edition" />
      <MemberSignature Language="VB.NET" Value="Public Property Edition As String" />
      <MemberSignature Language="F#" Value="member this.Edition : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.Edition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得または Azure SQL データベースのエディションを設定します。 DatabaseEditions 列挙には、有効なすべてのエディションが含まれています。
            使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolName">
      <MemberSignature Language="C#" Value="public string ElasticPoolName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.ElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public Property ElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.ElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得またはデータベースが Azure SQL 弾力性プールの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeBytes">
      <MemberSignature Language="C#" Value="public string MaxSizeBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxSizeBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.MaxSizeBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeBytes As String" />
      <MemberSignature Language="F#" Value="member this.MaxSizeBytes : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.MaxSizeBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得またはバイト数で表される Azure SQL データベースの最大サイズを設定します。 注: (各エディションで配置されている制限事項) だけでなく、次のサイズのみがサポートされて: {100 MB | 500 MB | 1 GB | 5 GB | 10 GB | 20 GB | 30 GB. 150 GB |200 GB しています. 500 GB}
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendedIndex">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt; RecommendedIndex { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt; RecommendedIndex" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.RecommendedIndex" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecommendedIndex As IList(Of RecommendedIndexInner)" />
      <MemberSignature Language="F#" Value="member this.RecommendedIndex : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.RecommendedIndex" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recommendedIndex")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedIndexInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベースの推奨インデックスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestedServiceObjectiveId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestedServiceObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.RequestedServiceObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestedServiceObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjectiveId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.RequestedServiceObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得または Azure SQL データベースの構成済みのサービス レベル目標の ID を設定します。 これは、サービス レベル目標の Azure SQL データベースに適用されている処理を行っています。 正常に更新されると、その currentServiceObjectiveId プロパティの値は一致します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjectiveName">
      <MemberSignature Language="C#" Value="public string RequestedServiceObjectiveName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedServiceObjectiveName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.RequestedServiceObjectiveName" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestedServiceObjectiveName As String" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjectiveName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.RequestedServiceObjectiveName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得または Azure SQL データベースの構成済みのサービス レベル目標の名前を設定します。 これは、サービス レベル目標の Azure SQL データベースに適用されている処理を行っています。 正常に更新されると、サービス レベル目標のプロパティの値には一致します。 使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schemas">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.SchemaInner&gt; Schemas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.SchemaInner&gt; Schemas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.Schemas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Schemas As IList(Of SchemaInner)" />
      <MemberSignature Language="F#" Value="member this.Schemas : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.SchemaInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.Schemas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schemas")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.SchemaInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベースからスキーマを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string ServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.ServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.ServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Azure SQL データベースの現在のサービス レベル目標を取得します。
            使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTierAdvisors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt; ServiceTierAdvisors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt; ServiceTierAdvisors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.ServiceTierAdvisors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTierAdvisors As IList(Of ServiceTierAdvisorInner)" />
      <MemberSignature Language="F#" Value="member this.ServiceTierAdvisors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.ServiceTierAdvisors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceTierAdvisors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベースのサービス層アドバイザーの一覧を取得します。 展開されたプロパティ
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDatabaseId">
      <MemberSignature Language="C#" Value="public string SourceDatabaseId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceDatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.SourceDatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDatabaseId As String" />
      <MemberSignature Language="F#" Value="member this.SourceDatabaseId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.SourceDatabaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            取得または条件を設定します。 ソース データベースのリソース ID を指定します。 CreateMode が既定値に設定されていない場合は、この値を指定する必要があります。 ソース データベースの名前は同じである必要があります。
            注: 照合順序、エディション、および MaxSizeBytes 必要があります、同じままのリンクがアクティブな状態です。 これらのパラメーターに指定した値は無視されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Azure SQL データベースの状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransparentDataEncryption">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; TransparentDataEncryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt; TransparentDataEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.TransparentDataEncryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransparentDataEncryption As IList(Of TransparentDataEncryptionInner)" />
      <MemberSignature Language="F#" Value="member this.TransparentDataEncryption : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.TransparentDataEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.transparentDataEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベースの透過的なデータの暗号化情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeHint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeHint UpgradeHint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeHint UpgradeHint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.UpgradeHint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeHint As UpgradeHint" />
      <MemberSignature Language="F#" Value="member this.UpgradeHint : Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeHint" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner.UpgradeHint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.upgradeHint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.Models.UpgradeHint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このデータベースのアップグレードのヒントを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>