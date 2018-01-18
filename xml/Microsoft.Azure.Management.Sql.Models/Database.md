<Type Name="Database" FullName="Microsoft.Azure.Management.Sql.Models.Database">
  <TypeSignature Language="C#" Value="public class Database : Microsoft.Azure.Management.Sql.Models.TrackedResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Database extends Microsoft.Azure.Management.Sql.Models.TrackedResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.Database" />
  <TypeSignature Language="VB.NET" Value="Public Class Database&#xA;Inherits TrackedResource" />
  <TypeSignature Language="F#" Value="type Database = class&#xA;    inherit TrackedResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.TrackedResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2e18c-101">データベースを表します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-101">Represents a database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Database ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.Database.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2e18c-102">データベース クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-102">Initializes a new instance of the Database class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Database (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string kind = null, string collation = null, Nullable&lt;DateTime&gt; creationDate = null, Nullable&lt;long&gt; containmentState = null, Nullable&lt;Guid&gt; currentServiceObjectiveId = null, Nullable&lt;Guid&gt; databaseId = null, Nullable&lt;DateTime&gt; earliestRestoreDate = null, string createMode = null, string sourceDatabaseId = null, Nullable&lt;DateTime&gt; sourceDatabaseDeletionDate = null, Nullable&lt;DateTime&gt; restorePointInTime = null, string recoveryServicesRecoveryPointResourceId = null, string edition = null, string maxSizeBytes = null, Nullable&lt;Guid&gt; requestedServiceObjectiveId = null, string requestedServiceObjectiveName = null, string serviceLevelObjective = null, string status = null, string elasticPoolName = null, string defaultSecondaryLocation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; serviceTierAdvisors = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; transparentDataEncryption = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; recommendedIndex = null, string failoverGroupId = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; readScale = null, string sampleName = null, Nullable&lt;bool&gt; zoneRedundant = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string kind, string collation, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, valuetype System.Nullable`1&lt;int64&gt; containmentState, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; currentServiceObjectiveId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; databaseId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; earliestRestoreDate, string createMode, string sourceDatabaseId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; sourceDatabaseDeletionDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; restorePointInTime, string recoveryServicesRecoveryPointResourceId, string edition, string maxSizeBytes, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestedServiceObjectiveId, string requestedServiceObjectiveName, string serviceLevelObjective, string status, string elasticPoolName, string defaultSecondaryLocation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; serviceTierAdvisors, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; transparentDataEncryption, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; recommendedIndex, string failoverGroupId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReadScale&gt; readScale, string sampleName, valuetype System.Nullable`1&lt;bool&gt; zoneRedundant) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.Database.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{System.Guid},System.Nullable{System.Guid},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.RecommendedIndex},System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.ReadScale},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional kind As String = null, Optional collation As String = null, Optional creationDate As Nullable(Of DateTime) = null, Optional containmentState As Nullable(Of Long) = null, Optional currentServiceObjectiveId As Nullable(Of Guid) = null, Optional databaseId As Nullable(Of Guid) = null, Optional earliestRestoreDate As Nullable(Of DateTime) = null, Optional createMode As String = null, Optional sourceDatabaseId As String = null, Optional sourceDatabaseDeletionDate As Nullable(Of DateTime) = null, Optional restorePointInTime As Nullable(Of DateTime) = null, Optional recoveryServicesRecoveryPointResourceId As String = null, Optional edition As String = null, Optional maxSizeBytes As String = null, Optional requestedServiceObjectiveId As Nullable(Of Guid) = null, Optional requestedServiceObjectiveName As String = null, Optional serviceLevelObjective As String = null, Optional status As String = null, Optional elasticPoolName As String = null, Optional defaultSecondaryLocation As String = null, Optional serviceTierAdvisors As IList(Of ServiceTierAdvisor) = null, Optional transparentDataEncryption As IList(Of TransparentDataEncryption) = null, Optional recommendedIndex As IList(Of RecommendedIndex) = null, Optional failoverGroupId As String = null, Optional readScale As Nullable(Of ReadScale) = null, Optional sampleName As String = null, Optional zoneRedundant As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.Database : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;Guid&gt; * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Models.Database" Usage="new Microsoft.Azure.Management.Sql.Models.Database (location, id, name, type, tags, kind, collation, creationDate, containmentState, currentServiceObjectiveId, databaseId, earliestRestoreDate, createMode, sourceDatabaseId, sourceDatabaseDeletionDate, restorePointInTime, recoveryServicesRecoveryPointResourceId, edition, maxSizeBytes, requestedServiceObjectiveId, requestedServiceObjectiveName, serviceLevelObjective, status, elasticPoolName, defaultSecondaryLocation, serviceTierAdvisors, transparentDataEncryption, recommendedIndex, failoverGroupId, readScale, sampleName, zoneRedundant)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="kind" Type="System.String" />
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
        <param name="location"><span data-ttu-id="2e18c-103">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="2e18c-103">Resource location.</span></span></param>
        <param name="id"><span data-ttu-id="2e18c-104">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="2e18c-104">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="2e18c-105">リソース名。</span><span class="sxs-lookup"><span data-stu-id="2e18c-105">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="2e18c-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="2e18c-106">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="2e18c-107">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="2e18c-107">Resource tags.</span></span></param>
        <param name="kind"><span data-ttu-id="2e18c-108">データベースの種類。</span><span class="sxs-lookup"><span data-stu-id="2e18c-108">Kind of database.</span></span>  <span data-ttu-id="2e18c-109">これは、Azure ポータルのエクスペリエンスで使用されるメタデータです。</span><span class="sxs-lookup"><span data-stu-id="2e18c-109">This is metadata used for the Azure portal experience.</span></span></param>
        <param name="collation"><span data-ttu-id="2e18c-110">データベースの照合順序です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-110">The collation of the database.</span></span> <span data-ttu-id="2e18c-111">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-111">If createMode is not Default, this value is ignored.</span></span></param>
        <param name="creationDate"><span data-ttu-id="2e18c-112">データベース (ISO8601 形式) の作成日。</span><span class="sxs-lookup"><span data-stu-id="2e18c-112">The creation date of the database (ISO8601 format).</span></span></param>
        <param name="containmentState"><span data-ttu-id="2e18c-113">データベースのコンテインメントの状態。</span><span class="sxs-lookup"><span data-stu-id="2e18c-113">The containment state of the database.</span></span></param>
        <param name="currentServiceObjectiveId"><span data-ttu-id="2e18c-114">現在サービス レベル目標の ID データベース。</span><span class="sxs-lookup"><span data-stu-id="2e18c-114">The current service level objective ID of the database.</span></span> <span data-ttu-id="2e18c-115">これは、現在アクティブなサービス レベル目標の ID です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-115">This is the ID of the service level objective that is currently active.</span></span></param>
        <param name="databaseId"><span data-ttu-id="2e18c-116">データベースの ID。</span><span class="sxs-lookup"><span data-stu-id="2e18c-116">The ID of the database.</span></span></param>
        <param name="earliestRestoreDate"><span data-ttu-id="2e18c-117">このレコードの最も早い開始日時を復元は、このデータベース (ISO8601 形式) で使用可能です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-117">This records the earliest start date and time that restore is available for this database (ISO8601 format).</span></span></param>
        <param name="createMode"><span data-ttu-id="2e18c-118">データベースの作成モードを指定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-118">Specifies the mode of database creation.</span></span>
            
             <span data-ttu-id="2e18c-119">既定値: 通常のデータベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-119">Default: regular database creation.</span></span>
            
             <span data-ttu-id="2e18c-120">: コピーには、既存のデータベースのコピーとして、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-120">Copy: creates a database as a copy of an existing database.</span></span>
             <span data-ttu-id="2e18c-121">sourceDatabaseId は、ソース データベースのリソース ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-121">sourceDatabaseId must be specified as the resource ID of the source database.</span></span>
             
            <span data-ttu-id="2e18c-122">OnlineSecondary/NonReadableSecondary: は、既存のデータベースのセカンダリ レプリカ (読み取り可能または不可) としてデータベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-122">OnlineSecondary/NonReadableSecondary: creates a database as a (readable or nonreadable) secondary replica of an existing database.</span></span> <span data-ttu-id="2e18c-123">sourceDatabaseId は、既存のプライマリ データベースのリソース ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-123">sourceDatabaseId must be specified as the resource ID of the existing primary database.</span></span>
             
             <span data-ttu-id="2e18c-124">PointInTimeRestore: ポイントイン タイム バックアップ、既存のデータベースを復元することによって、データベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-124">PointInTimeRestore: Creates a database by restoring a point in time backup of an existing database.</span></span> <span data-ttu-id="2e18c-125">sourceDatabaseId を既存のデータベースのリソース ID として指定する必要があり、restorePointInTime を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-125">sourceDatabaseId must be specified as the resource ID of the existing database, and restorePointInTime must be specified.</span></span>
             
             <span data-ttu-id="2e18c-126">回復:、geo レプリケーションのバックアップを復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-126">Recovery: Creates a database by restoring a geo-replicated backup.</span></span>
            <span data-ttu-id="2e18c-127">sourceDatabaseId は、復元する回復可能なデータベース リソースの ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-127">sourceDatabaseId must be specified as the recoverable database resource ID to restore.</span></span>
             
             <span data-ttu-id="2e18c-128">復元:、削除されたデータベースのバックアップを復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-128">Restore: Creates a database by restoring a backup of a deleted database.</span></span> <span data-ttu-id="2e18c-129">sourceDatabaseId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-129">sourceDatabaseId must be specified.</span></span> <span data-ttu-id="2e18c-130">SourceDatabaseId がデータベースの元のリソース ID である場合は、sourceDatabaseDeletionDate を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-130">If sourceDatabaseId is the database's original resource ID, then sourceDatabaseDeletionDate must be specified.</span></span> <span data-ttu-id="2e18c-131">それ以外の場合 sourceDatabaseId は削除されたデータベースの復元可能なリソース ID である必要があり、sourceDatabaseDeletionDate は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-131">Otherwise sourceDatabaseId must be the restorable dropped database resource ID and sourceDatabaseDeletionDate is ignored.</span></span> <span data-ttu-id="2e18c-132">restorePointInTime はの以前の時点から復元するも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-132">restorePointInTime may also be specified to restore from an earlier point in time.</span></span>
             
             <span data-ttu-id="2e18c-133">RestoreLongTermRetentionBackup:、長期的な保存の資格情報コンテナーから復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-133">RestoreLongTermRetentionBackup: Creates a database by restoring from a long term retention vault.</span></span>
            <span data-ttu-id="2e18c-134">回復ポイントのリソース ID として recoveryServicesRecoveryPointResourceId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-134">recoveryServicesRecoveryPointResourceId must be specified as the recovery point resource ID.</span></span>
             
             <span data-ttu-id="2e18c-135">DataWarehouse エディションには、コピー、NonReadableSecondary、OnlineSecondary および RestoreLongTermRetentionBackup はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="2e18c-135">Copy, NonReadableSecondary, OnlineSecondary and RestoreLongTermRetentionBackup are not supported for DataWarehouse edition.</span></span> <span data-ttu-id="2e18c-136">使用可能な値が含まれます: 'コピー'、'Default'、'NonReadableSecondary'、'OnlineSecondary'、'PointInTimeRestore'、' 復旧'、'Restore'、'RestoreLongTermRetentionBackup'</span><span class="sxs-lookup"><span data-stu-id="2e18c-136">Possible values include: 'Copy', 'Default', 'NonReadableSecondary', 'OnlineSecondary', 'PointInTimeRestore', 'Recovery', 'Restore', 'RestoreLongTermRetentionBackup'</span></span></param>
        <param name="sourceDatabaseId"><span data-ttu-id="2e18c-137">条件付きです。</span><span class="sxs-lookup"><span data-stu-id="2e18c-137">Conditional.</span></span> <span data-ttu-id="2e18c-138">CreateMode がコピー、NonReadableSecondary、OnlineSecondary、PointInTimeRestore、復旧、または復元の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-138">If createMode is Copy, NonReadableSecondary, OnlineSecondary, PointInTimeRestore, Recovery, or Restore, then this value is required.</span></span> <span data-ttu-id="2e18c-139">ソース データベースのリソース ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-139">Specifies the resource ID of the source database.</span></span> <span data-ttu-id="2e18c-140">CreateMode が NonReadableSecondary または OnlineSecondary の場合は、ソース データベースの名前を作成する新しいデータベースと同じにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-140">If createMode is NonReadableSecondary or OnlineSecondary, the name of the source database must be the same as the new database being created.</span></span></param>
        <param name="sourceDatabaseDeletionDate"><span data-ttu-id="2e18c-141">条件付きです。</span><span class="sxs-lookup"><span data-stu-id="2e18c-141">Conditional.</span></span> <span data-ttu-id="2e18c-142">CreateMode は復元 sourceDatabaseId は削除されたデータベースの元のリソース id ではなく、現在の復元可能な削除されたデータベース id) に存在していた場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-142">If createMode is Restore and sourceDatabaseId is the deleted database's original resource id when it existed (as opposed to its current restorable dropped database id), then this value is required.</span></span> <span data-ttu-id="2e18c-143">データベースが削除された日時を指定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-143">Specifies the time that the database was deleted.</span></span></param>
        <param name="restorePointInTime"><span data-ttu-id="2e18c-144">条件付きです。</span><span class="sxs-lookup"><span data-stu-id="2e18c-144">Conditional.</span></span> <span data-ttu-id="2e18c-145">CreateMode が PointInTimeRestore の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-145">If createMode is PointInTimeRestore, this value is required.</span></span> <span data-ttu-id="2e18c-146">CreateMode が復元の場合は、この値は省略できます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-146">If createMode is Restore, this value is optional.</span></span> <span data-ttu-id="2e18c-147">新しいデータベースを作成する復元するソース データベースの時刻 (ISO8601 形式) で、ポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-147">Specifies the point in time (ISO8601 format) of the source database that will be restored to create the new database.</span></span> <span data-ttu-id="2e18c-148">ソース データベースの earliestRestoreDate 値以上にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-148">Must be greater than or equal to the source database's earliestRestoreDate value.</span></span></param>
        <param name="recoveryServicesRecoveryPointResourceId"><span data-ttu-id="2e18c-149">条件付きです。</span><span class="sxs-lookup"><span data-stu-id="2e18c-149">Conditional.</span></span>
             <span data-ttu-id="2e18c-150">CreateMode が RestoreLongTermRetentionBackup の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-150">If createMode is RestoreLongTermRetentionBackup, then this value is required.</span></span> <span data-ttu-id="2e18c-151">復元する回復ポイントのリソース ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-151">Specifies the resource ID of the recovery point to restore from.</span></span></param>
        <param name="edition"><span data-ttu-id="2e18c-152">データベースのエディションです。</span><span class="sxs-lookup"><span data-stu-id="2e18c-152">The edition of the database.</span></span> <span data-ttu-id="2e18c-153">DatabaseEditions 列挙には、有効なすべてのエディションが含まれています。</span><span class="sxs-lookup"><span data-stu-id="2e18c-153">The DatabaseEditions enumeration contains all the valid editions.</span></span> <span data-ttu-id="2e18c-154">CreateMode が NonReadableSecondary または OnlineSecondary の場合は、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-154">If createMode is NonReadableSecondary or OnlineSecondary, this value is ignored.</span></span> <span data-ttu-id="2e18c-155">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-155">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
             <span data-ttu-id="2e18c-156">使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'、'System'、'システム 2'</span><span class="sxs-lookup"><span data-stu-id="2e18c-156">Possible values include: 'Web', 'Business', 'Basic', 'Standard', 'Premium', 'Free', 'Stretch', 'DataWarehouse', 'System', 'System2'</span></span></param>
        <param name="maxSizeBytes"><span data-ttu-id="2e18c-157">バイト単位で表されるデータベースの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="2e18c-157">The max size of the database expressed in bytes.</span></span> <span data-ttu-id="2e18c-158">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-158">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="2e18c-159">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。</span><span class="sxs-lookup"><span data-stu-id="2e18c-159">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span></param>
        <param name="requestedServiceObjectiveId"><span data-ttu-id="2e18c-160">データベースの構成済みのサービス レベル目標 ID。</span><span class="sxs-lookup"><span data-stu-id="2e18c-160">The configured service level objective ID of the database.</span></span> <span data-ttu-id="2e18c-161">これは、データベースに適用されているプロセスでは、サービス レベル目標です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-161">This is the service level objective that is in the process of being applied to the database.</span></span>
             <span data-ttu-id="2e18c-162">正常に更新されると、その currentServiceObjectiveId プロパティの値は一致します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-162">Once successfully updated, it will match the value of currentServiceObjectiveId property.</span></span> <span data-ttu-id="2e18c-163">RequestedServiceObjectiveId と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveId の値は requestedServiceObjectiveName の値をオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="2e18c-163">If requestedServiceObjectiveId and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveId overrides the value of requestedServiceObjectiveName.</span></span> <span data-ttu-id="2e18c-164">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。</span><span class="sxs-lookup"><span data-stu-id="2e18c-164">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span></param>
        <param name="requestedServiceObjectiveName"><span data-ttu-id="2e18c-165">データベースの構成済みのサービス レベル目標の名前。</span><span class="sxs-lookup"><span data-stu-id="2e18c-165">The name of the configured service level objective of the database.</span></span> <span data-ttu-id="2e18c-166">これは、データベースに適用されているプロセスでは、サービス レベル目標です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-166">This is the service level objective that is in the process of being applied to the database.</span></span> <span data-ttu-id="2e18c-167">正常に更新されると、サービス レベル目標のプロパティの値には一致します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-167">Once successfully updated, it will match the value of serviceLevelObjective property.</span></span> <span data-ttu-id="2e18c-168">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-168">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
             <span data-ttu-id="2e18c-169">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</span><span class="sxs-lookup"><span data-stu-id="2e18c-169">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span></param>
        <param name="serviceLevelObjective"><span data-ttu-id="2e18c-170">現在サービス レベル目標のデータベースです。</span><span class="sxs-lookup"><span data-stu-id="2e18c-170">The current service level objective of the database.</span></span> <span data-ttu-id="2e18c-171">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</span><span class="sxs-lookup"><span data-stu-id="2e18c-171">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span></param>
        <param name="status"><span data-ttu-id="2e18c-172">データベースの状態。</span><span class="sxs-lookup"><span data-stu-id="2e18c-172">The status of the database.</span></span></param>
        <param name="elasticPoolName"><span data-ttu-id="2e18c-173">弾力性プール データベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-173">The name of the elastic pool the database is in.</span></span> <span data-ttu-id="2e18c-174">ElasticPoolName と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveName の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-174">If elasticPoolName and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveName is ignored.</span></span> <span data-ttu-id="2e18c-175">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="2e18c-175">Not supported for DataWarehouse edition.</span></span></param>
        <param name="defaultSecondaryLocation"><span data-ttu-id="2e18c-176">このデータベースの既定のセカンダリ地域。</span><span class="sxs-lookup"><span data-stu-id="2e18c-176">The default secondary region for this database.</span></span></param>
        <param name="serviceTierAdvisors"><span data-ttu-id="2e18c-177">このデータベースのサービス層アドバイザーの一覧。</span><span class="sxs-lookup"><span data-stu-id="2e18c-177">The list of service tier advisors for this database.</span></span> <span data-ttu-id="2e18c-178">展開されたプロパティ</span><span class="sxs-lookup"><span data-stu-id="2e18c-178">Expanded property</span></span></param>
        <param name="transparentDataEncryption"><span data-ttu-id="2e18c-179">透過的なデータ暗号化は、このデータベースの情報です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-179">The transparent data encryption info for this database.</span></span></param>
        <param name="recommendedIndex"><span data-ttu-id="2e18c-180">このデータベースの推奨されるインデックスです。</span><span class="sxs-lookup"><span data-stu-id="2e18c-180">The recommended indices for this database.</span></span></param>
        <param name="failoverGroupId"><span data-ttu-id="2e18c-181">このデータベースを含むグループのフェールオーバーのリソースの識別子です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-181">The resource identifier of the failover group containing this database.</span></span></param>
        <param name="readScale"><span data-ttu-id="2e18c-182">条件付きです。</span><span class="sxs-lookup"><span data-stu-id="2e18c-182">Conditional.</span></span> <span data-ttu-id="2e18c-183">データベースが地理的セカンダリの場合は、readScale はかに、このデータベースに対する読み取り専用の接続を許可するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-183">If the database is a geo-secondary, readScale indicates whether read-only connections are allowed to this database or not.</span></span> <span data-ttu-id="2e18c-184">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="2e18c-184">Not supported for DataWarehouse edition.</span></span> <span data-ttu-id="2e18c-185">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="2e18c-185">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="sampleName"><span data-ttu-id="2e18c-186">このデータベースを作成するときに適用するサンプルのスキーマの名前を示します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-186">Indicates the name of the sample schema to apply when creating this database.</span></span> <span data-ttu-id="2e18c-187">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-187">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="2e18c-188">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="2e18c-188">Not supported for DataWarehouse edition.</span></span>
             <span data-ttu-id="2e18c-189">使用可能な値が含まれます: 'AdventureWorksLT'</span><span class="sxs-lookup"><span data-stu-id="2e18c-189">Possible values include: 'AdventureWorksLT'</span></span></param>
        <param name="zoneRedundant"><span data-ttu-id="2e18c-190">このデータベースは、ゾーン冗長、このデータベースのレプリカを意味するかどうかは、複数の可用性ゾーン間で分散行われます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-190">Whether or not this database is zone redundant, which means the replicas of this database will be spread across multiple availability zones.</span></span></param>
        <summary>
             <span data-ttu-id="2e18c-191">データベース クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-191">Initializes a new instance of the Database class.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Collation">
      <MemberSignature Language="C#" Value="public string Collation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Collation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.Collation" />
      <MemberSignature Language="VB.NET" Value="Public Property Collation As String" />
      <MemberSignature Language="F#" Value="member this.Collation : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.Collation" />
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
            <span data-ttu-id="2e18c-192">取得またはデータベースの照合順序を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-192">Gets or sets the collation of the database.</span></span> <span data-ttu-id="2e18c-193">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-193">If createMode is not Default, this value is ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainmentState">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ContainmentState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ContainmentState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.ContainmentState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainmentState As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ContainmentState : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Sql.Models.Database.ContainmentState" />
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
            <span data-ttu-id="2e18c-194">データベースの包含状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-194">Gets the containment state of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMode">
      <MemberSignature Language="C#" Value="public string CreateMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CreateMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.CreateMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateMode As String" />
      <MemberSignature Language="F#" Value="member this.CreateMode : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.CreateMode" />
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
             <span data-ttu-id="2e18c-195">取得または設定は、データベースの作成モードを指定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-195">Gets or sets specifies the mode of database creation.</span></span>
            
             <span data-ttu-id="2e18c-196">既定値: 通常のデータベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-196">Default: regular database creation.</span></span>
            
             <span data-ttu-id="2e18c-197">: コピーには、既存のデータベースのコピーとして、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-197">Copy: creates a database as a copy of an existing database.</span></span>
             <span data-ttu-id="2e18c-198">sourceDatabaseId は、ソース データベースのリソース ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-198">sourceDatabaseId must be specified as the resource ID of the source database.</span></span>
             
            <span data-ttu-id="2e18c-199">OnlineSecondary/NonReadableSecondary: は、既存のデータベースのセカンダリ レプリカ (読み取り可能または不可) としてデータベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-199">OnlineSecondary/NonReadableSecondary: creates a database as a (readable or nonreadable) secondary replica of an existing database.</span></span> <span data-ttu-id="2e18c-200">sourceDatabaseId は、既存のプライマリ データベースのリソース ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-200">sourceDatabaseId must be specified as the resource ID of the existing primary database.</span></span>
             
             <span data-ttu-id="2e18c-201">PointInTimeRestore: ポイントイン タイム バックアップ、既存のデータベースを復元することによって、データベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-201">PointInTimeRestore: Creates a database by restoring a point in time backup of an existing database.</span></span> <span data-ttu-id="2e18c-202">sourceDatabaseId を既存のデータベースのリソース ID として指定する必要があり、restorePointInTime を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-202">sourceDatabaseId must be specified as the resource ID of the existing database, and restorePointInTime must be specified.</span></span>
             
             <span data-ttu-id="2e18c-203">回復:、geo レプリケーションのバックアップを復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-203">Recovery: Creates a database by restoring a geo-replicated backup.</span></span>
            <span data-ttu-id="2e18c-204">sourceDatabaseId は、復元する回復可能なデータベース リソースの ID として指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-204">sourceDatabaseId must be specified as the recoverable database resource ID to restore.</span></span>
             
             <span data-ttu-id="2e18c-205">復元:、削除されたデータベースのバックアップを復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-205">Restore: Creates a database by restoring a backup of a deleted database.</span></span> <span data-ttu-id="2e18c-206">sourceDatabaseId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-206">sourceDatabaseId must be specified.</span></span> <span data-ttu-id="2e18c-207">SourceDatabaseId がデータベースの元のリソース ID である場合は、sourceDatabaseDeletionDate を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-207">If sourceDatabaseId is the database's original resource ID, then sourceDatabaseDeletionDate must be specified.</span></span> <span data-ttu-id="2e18c-208">それ以外の場合 sourceDatabaseId は削除されたデータベースの復元可能なリソース ID である必要があり、sourceDatabaseDeletionDate は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-208">Otherwise sourceDatabaseId must be the restorable dropped database resource ID and sourceDatabaseDeletionDate is ignored.</span></span> <span data-ttu-id="2e18c-209">restorePointInTime はの以前の時点から復元するも指定することがあります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-209">restorePointInTime may also be specified to restore from an earlier point in time.</span></span>
             
             <span data-ttu-id="2e18c-210">RestoreLongTermRetentionBackup:、長期的な保存の資格情報コンテナーから復元することによって、データベースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-210">RestoreLongTermRetentionBackup: Creates a database by restoring from a long term retention vault.</span></span>
            <span data-ttu-id="2e18c-211">回復ポイントのリソース ID として recoveryServicesRecoveryPointResourceId を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-211">recoveryServicesRecoveryPointResourceId must be specified as the recovery point resource ID.</span></span>
             
             <span data-ttu-id="2e18c-212">DataWarehouse エディションには、コピー、NonReadableSecondary、OnlineSecondary および RestoreLongTermRetentionBackup はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="2e18c-212">Copy, NonReadableSecondary, OnlineSecondary and RestoreLongTermRetentionBackup are not supported for DataWarehouse edition.</span></span> <span data-ttu-id="2e18c-213">使用可能な値が含まれます: 'コピー'、'Default'、'NonReadableSecondary'、'OnlineSecondary'、'PointInTimeRestore'、' 復旧'、'Restore'、'RestoreLongTermRetentionBackup'</span><span class="sxs-lookup"><span data-stu-id="2e18c-213">Possible values include: 'Copy', 'Default', 'NonReadableSecondary', 'OnlineSecondary', 'PointInTimeRestore', 'Recovery', 'Restore', 'RestoreLongTermRetentionBackup'</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.Database.CreationDate" />
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
            <span data-ttu-id="2e18c-214">データベース (ISO8601 形式) の作成日を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-214">Gets the creation date of the database (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; CurrentServiceObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; CurrentServiceObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.CurrentServiceObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceObjectiveId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.Database.CurrentServiceObjectiveId" />
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
            <span data-ttu-id="2e18c-215">サービス レベル目標の現在の ID、データベースを取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-215">Gets the current service level objective ID of the database.</span></span> <span data-ttu-id="2e18c-216">これは、現在アクティブなサービス レベル目標の ID です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-216">This is the ID of the service level objective that is currently active.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; DatabaseId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; DatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.DatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.DatabaseId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.Database.DatabaseId" />
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
            <span data-ttu-id="2e18c-217">データベースの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-217">Gets the ID of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSecondaryLocation">
      <MemberSignature Language="C#" Value="public string DefaultSecondaryLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultSecondaryLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.DefaultSecondaryLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSecondaryLocation As String" />
      <MemberSignature Language="F#" Value="member this.DefaultSecondaryLocation : string" Usage="Microsoft.Azure.Management.Sql.Models.Database.DefaultSecondaryLocation" />
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
            <span data-ttu-id="2e18c-218">このデータベースの既定のセカンダリ地域を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-218">Gets the default secondary region for this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EarliestRestoreDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EarliestRestoreDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EarliestRestoreDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.EarliestRestoreDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EarliestRestoreDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EarliestRestoreDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.Database.EarliestRestoreDate" />
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
            <span data-ttu-id="2e18c-219">このデータベース (ISO8601 形式) のこのレコードの最も早い開始日時を復元するが取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-219">Gets this records the earliest start date and time that restore is available for this database (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public string Edition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.Edition" />
      <MemberSignature Language="VB.NET" Value="Public Property Edition As String" />
      <MemberSignature Language="F#" Value="member this.Edition : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.Edition" />
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
            <span data-ttu-id="2e18c-220">取得またはデータベースのエディションを設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-220">Gets or sets the edition of the database.</span></span> <span data-ttu-id="2e18c-221">DatabaseEditions 列挙には、有効なすべてのエディションが含まれています。</span><span class="sxs-lookup"><span data-stu-id="2e18c-221">The DatabaseEditions enumeration contains all the valid editions.</span></span> <span data-ttu-id="2e18c-222">CreateMode が NonReadableSecondary または OnlineSecondary の場合は、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-222">If createMode is NonReadableSecondary or OnlineSecondary, this value is ignored.</span></span> <span data-ttu-id="2e18c-223">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-223">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
            <span data-ttu-id="2e18c-224">使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'、'System'、'システム 2'</span><span class="sxs-lookup"><span data-stu-id="2e18c-224">Possible values include: 'Web', 'Business', 'Basic', 'Standard', 'Premium', 'Free', 'Stretch', 'DataWarehouse', 'System', 'System2'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolName">
      <MemberSignature Language="C#" Value="public string ElasticPoolName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.ElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public Property ElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.ElasticPoolName" />
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
            <span data-ttu-id="2e18c-225">取得またはデータベースが弾力性プールの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-225">Gets or sets the name of the elastic pool the database is in.</span></span> <span data-ttu-id="2e18c-226">ElasticPoolName と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveName の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-226">If elasticPoolName and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveName is ignored.</span></span> <span data-ttu-id="2e18c-227">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="2e18c-227">Not supported for DataWarehouse edition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverGroupId">
      <MemberSignature Language="C#" Value="public string FailoverGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailoverGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.FailoverGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailoverGroupId As String" />
      <MemberSignature Language="F#" Value="member this.FailoverGroupId : string" Usage="Microsoft.Azure.Management.Sql.Models.Database.FailoverGroupId" />
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
            <span data-ttu-id="2e18c-228">このデータベースを含むグループのフェールオーバーのリソース識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-228">Gets the resource identifier of the failover group containing this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.Database.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e18c-229">データベースの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-229">Gets kind of database.</span></span>  <span data-ttu-id="2e18c-230">これは、Azure ポータルのエクスペリエンスで使用されるメタデータです。</span><span class="sxs-lookup"><span data-stu-id="2e18c-230">This is metadata used for the Azure portal experience.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeBytes">
      <MemberSignature Language="C#" Value="public string MaxSizeBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxSizeBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.MaxSizeBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeBytes As String" />
      <MemberSignature Language="F#" Value="member this.MaxSizeBytes : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.MaxSizeBytes" />
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
            <span data-ttu-id="2e18c-231">取得またはバイト数で表されるデータベースの最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-231">Gets or sets the max size of the database expressed in bytes.</span></span> <span data-ttu-id="2e18c-232">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-232">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="2e18c-233">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。</span><span class="sxs-lookup"><span data-stu-id="2e18c-233">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadScale">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; ReadScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReadScale&gt; ReadScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.ReadScale" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadScale As Nullable(Of ReadScale)" />
      <MemberSignature Language="F#" Value="member this.ReadScale : Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.ReadScale" />
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
            <span data-ttu-id="2e18c-234">取得または条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-234">Gets or sets conditional.</span></span> <span data-ttu-id="2e18c-235">データベースが地理的セカンダリの場合は、readScale はかに、このデータベースに対する読み取り専用の接続を許可するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-235">If the database is a geo-secondary, readScale indicates whether read-only connections are allowed to this database or not.</span></span> <span data-ttu-id="2e18c-236">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="2e18c-236">Not supported for DataWarehouse edition.</span></span>
            <span data-ttu-id="2e18c-237">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="2e18c-237">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendedIndex">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; RecommendedIndex { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; RecommendedIndex" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.RecommendedIndex" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecommendedIndex As IList(Of RecommendedIndex)" />
      <MemberSignature Language="F#" Value="member this.RecommendedIndex : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt;" Usage="Microsoft.Azure.Management.Sql.Models.Database.RecommendedIndex" />
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
            <span data-ttu-id="2e18c-238">このデータベースの推奨インデックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-238">Gets the recommended indices for this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryServicesRecoveryPointResourceId">
      <MemberSignature Language="C#" Value="public string RecoveryServicesRecoveryPointResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryServicesRecoveryPointResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.RecoveryServicesRecoveryPointResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryServicesRecoveryPointResourceId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryServicesRecoveryPointResourceId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.RecoveryServicesRecoveryPointResourceId" />
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
            <span data-ttu-id="2e18c-239">取得または条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-239">Gets or sets conditional.</span></span> <span data-ttu-id="2e18c-240">CreateMode が RestoreLongTermRetentionBackup の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-240">If createMode is RestoreLongTermRetentionBackup, then this value is required.</span></span>
            <span data-ttu-id="2e18c-241">復元する回復ポイントのリソース ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-241">Specifies the resource ID of the recovery point to restore from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestedServiceObjectiveId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestedServiceObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.RequestedServiceObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestedServiceObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjectiveId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.RequestedServiceObjectiveId" />
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
            <span data-ttu-id="2e18c-242">取得またはデータベースの構成済みのサービス レベル目標の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-242">Gets or sets the configured service level objective ID of the database.</span></span> <span data-ttu-id="2e18c-243">これは、データベースに適用されているプロセスでは、サービス レベル目標です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-243">This is the service level objective that is in the process of being applied to the database.</span></span> <span data-ttu-id="2e18c-244">正常に更新されると、その currentServiceObjectiveId プロパティの値は一致します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-244">Once successfully updated, it will match the value of currentServiceObjectiveId property.</span></span> <span data-ttu-id="2e18c-245">RequestedServiceObjectiveId と requestedServiceObjectiveName がどちらも更新された場合、requestedServiceObjectiveId の値は requestedServiceObjectiveName の値をオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="2e18c-245">If requestedServiceObjectiveId and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveId overrides the value of requestedServiceObjectiveName.</span></span> <span data-ttu-id="2e18c-246">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"。</span><span class="sxs-lookup"><span data-stu-id="2e18c-246">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjectiveName">
      <MemberSignature Language="C#" Value="public string RequestedServiceObjectiveName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedServiceObjectiveName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.RequestedServiceObjectiveName" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestedServiceObjectiveName As String" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjectiveName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.RequestedServiceObjectiveName" />
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
            <span data-ttu-id="2e18c-247">取得またはデータベースの構成済みのサービス レベル目標の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-247">Gets or sets the name of the configured service level objective of the database.</span></span> <span data-ttu-id="2e18c-248">これは、データベースに適用されているプロセスでは、サービス レベル目標です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-248">This is the service level objective that is in the process of being applied to the database.</span></span> <span data-ttu-id="2e18c-249">正常に更新されると、サービス レベル目標のプロパティの値には一致します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-249">Once successfully updated, it will match the value of serviceLevelObjective property.</span></span>
            <span data-ttu-id="2e18c-250">クエリ機能 API に指定できる値を表示する (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) operationId によって参照される:"Capabilities_ListByLocation"です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-250">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
            <span data-ttu-id="2e18c-251">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</span><span class="sxs-lookup"><span data-stu-id="2e18c-251">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePointInTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RestorePointInTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RestorePointInTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.RestorePointInTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RestorePointInTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RestorePointInTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.RestorePointInTime" />
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
            <span data-ttu-id="2e18c-252">取得または条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-252">Gets or sets conditional.</span></span> <span data-ttu-id="2e18c-253">CreateMode が PointInTimeRestore の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-253">If createMode is PointInTimeRestore, this value is required.</span></span> <span data-ttu-id="2e18c-254">CreateMode が復元の場合は、この値は省略できます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-254">If createMode is Restore, this value is optional.</span></span> <span data-ttu-id="2e18c-255">新しいデータベースを作成する復元するソース データベースの時刻 (ISO8601 形式) で、ポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-255">Specifies the point in time (ISO8601 format) of the source database that will be restored to create the new database.</span></span>
            <span data-ttu-id="2e18c-256">ソース データベースの earliestRestoreDate 値以上にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-256">Must be greater than or equal to the source database's earliestRestoreDate value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SampleName">
      <MemberSignature Language="C#" Value="public string SampleName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SampleName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.SampleName" />
      <MemberSignature Language="VB.NET" Value="Public Property SampleName As String" />
      <MemberSignature Language="F#" Value="member this.SampleName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.SampleName" />
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
            <span data-ttu-id="2e18c-257">取得または設定は、このデータベースを作成するときに適用するサンプルのスキーマの名前を示します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-257">Gets or sets indicates the name of the sample schema to apply when creating this database.</span></span> <span data-ttu-id="2e18c-258">CreateMode が既定ではない場合、この値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-258">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="2e18c-259">DataWarehouse エディションのサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="2e18c-259">Not supported for DataWarehouse edition.</span></span> <span data-ttu-id="2e18c-260">使用可能な値が含まれます: 'AdventureWorksLT'</span><span class="sxs-lookup"><span data-stu-id="2e18c-260">Possible values include: 'AdventureWorksLT'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string ServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.ServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.Database.ServiceLevelObjective" />
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
            <span data-ttu-id="2e18c-261">データベースの現在のサービス レベル目標を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-261">Gets the current service level objective of the database.</span></span> <span data-ttu-id="2e18c-262">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'、'P4'、'P6'、'P11'、'P15'、'System'、'システム 2'、'ElasticPool'</span><span class="sxs-lookup"><span data-stu-id="2e18c-262">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTierAdvisors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ServiceTierAdvisors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ServiceTierAdvisors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.ServiceTierAdvisors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTierAdvisors As IList(Of ServiceTierAdvisor)" />
      <MemberSignature Language="F#" Value="member this.ServiceTierAdvisors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;" Usage="Microsoft.Azure.Management.Sql.Models.Database.ServiceTierAdvisors" />
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
            <span data-ttu-id="2e18c-263">このデータベースのサービス層アドバイザーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-263">Gets the list of service tier advisors for this database.</span></span> <span data-ttu-id="2e18c-264">展開されたプロパティ</span><span class="sxs-lookup"><span data-stu-id="2e18c-264">Expanded property</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDatabaseDeletionDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SourceDatabaseDeletionDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SourceDatabaseDeletionDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.SourceDatabaseDeletionDate" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDatabaseDeletionDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SourceDatabaseDeletionDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.SourceDatabaseDeletionDate" />
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
            <span data-ttu-id="2e18c-265">取得または条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-265">Gets or sets conditional.</span></span> <span data-ttu-id="2e18c-266">CreateMode は復元 sourceDatabaseId は削除されたデータベースの元のリソース id ではなく、現在の復元可能な削除されたデータベース id) に存在していた場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-266">If createMode is Restore and sourceDatabaseId is the deleted database's original resource id when it existed (as opposed to its current restorable dropped database id), then this value is required.</span></span> <span data-ttu-id="2e18c-267">データベースが削除された日時を指定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-267">Specifies the time that the database was deleted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDatabaseId">
      <MemberSignature Language="C#" Value="public string SourceDatabaseId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceDatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.SourceDatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDatabaseId As String" />
      <MemberSignature Language="F#" Value="member this.SourceDatabaseId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.SourceDatabaseId" />
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
            <span data-ttu-id="2e18c-268">取得または条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-268">Gets or sets conditional.</span></span> <span data-ttu-id="2e18c-269">CreateMode がコピー、NonReadableSecondary、OnlineSecondary、PointInTimeRestore、復旧、または復元の場合は、この値が必要です。</span><span class="sxs-lookup"><span data-stu-id="2e18c-269">If createMode is Copy, NonReadableSecondary, OnlineSecondary, PointInTimeRestore, Recovery, or Restore, then this value is required.</span></span> <span data-ttu-id="2e18c-270">ソース データベースのリソース ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-270">Specifies the resource ID of the source database.</span></span> <span data-ttu-id="2e18c-271">CreateMode が NonReadableSecondary または OnlineSecondary の場合は、ソース データベースの名前を作成する新しいデータベースと同じにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2e18c-271">If createMode is NonReadableSecondary or OnlineSecondary, the name of the source database must be the same as the new database being created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.Sql.Models.Database.Status" />
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
            <span data-ttu-id="2e18c-272">データベースの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-272">Gets the status of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransparentDataEncryption">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; TransparentDataEncryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; TransparentDataEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.TransparentDataEncryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransparentDataEncryption As IList(Of TransparentDataEncryption)" />
      <MemberSignature Language="F#" Value="member this.TransparentDataEncryption : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;" Usage="Microsoft.Azure.Management.Sql.Models.Database.TransparentDataEncryption" />
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
            <span data-ttu-id="2e18c-273">このデータベースの透過的なデータの暗号化情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-273">Gets the transparent data encryption info for this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.Database.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="database.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2e18c-274">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-274">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2e18c-275">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="2e18c-275">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ZoneRedundant">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ZoneRedundant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ZoneRedundant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.Database.ZoneRedundant" />
      <MemberSignature Language="VB.NET" Value="Public Property ZoneRedundant As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ZoneRedundant : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.Database.ZoneRedundant" />
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
            <span data-ttu-id="2e18c-276">取得またはこのデータベースが複数の可用性ゾーン、ゾーン冗長、このデータベースのレプリカを意味に分散するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="2e18c-276">Gets or sets whether or not this database is zone redundant, which means the replicas of this database will be spread across multiple availability zones.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>