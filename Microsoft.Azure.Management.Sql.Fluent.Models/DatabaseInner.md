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
            <span data-ttu-id="1ec9e-101">Azure SQL データベースを表します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-101">Represents an Azure SQL Database.</span></span>
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
            <span data-ttu-id="1ec9e-102">DatabaseInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-102">Initializes a new instance of the DatabaseInner class.</span></span>
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
        <param name="collation"><span data-ttu-id="1ec9e-103">Azure SQL データベースの照合順序です。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-103">The collation of the Azure SQL database.</span></span></param>
        <param name="creationDate"><span data-ttu-id="1ec9e-104">Azure SQL データベース (ISO8601 形式) の作成日。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-104">The creation date of the Azure SQL database (ISO8601 format).</span></span></param>
        <param name="containmentState"><span data-ttu-id="1ec9e-105">Azure SQL データベースのコンテインメントの状態。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-105">The containment state of the Azure SQL database.</span></span></param>
        <param name="currentServiceObjectiveId"><span data-ttu-id="1ec9e-106">現在サービス レベル目標の ID、Azure SQL データベース。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-106">The current Service Level Objective ID of the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-107">これは、現在アクティブなサービス レベル目標の ID です。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-107">This is the ID of the Service Level Objective that is currently active.</span></span></param>
        <param name="databaseId"><span data-ttu-id="1ec9e-108">Azure SQL データベースの ID。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-108">The ID of the Azure SQL database.</span></span></param>
        <param name="earliestRestoreDate"><span data-ttu-id="1ec9e-109">復旧期間は、Azure SQL データベースの日を開始します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-109">The recovery period start date of the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-110">これは、開始日と回復がこの Azure SQL データベース (ISO8601 形式) の使用可能な場合に記録します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-110">This records the start date and time when recovery is available for this Azure SQL Database (ISO8601 format).</span></span></param>
        <param name="createMode"><span data-ttu-id="1ec9e-111">作成するデータベースの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-111">Specifies the type of database to create.</span></span>
            <span data-ttu-id="1ec9e-112">使用可能な値が含まれます: 'コピー'、'Default'、'NonReadableSecondary'、'OnlineSecondary'、'PointInTimeRestore'、'復旧'、'Restore'</span><span class="sxs-lookup"><span data-stu-id="1ec9e-112">Possible values include: 'Copy', 'Default', 'NonReadableSecondary', 'OnlineSecondary', 'PointInTimeRestore', 'Recovery', 'Restore'</span></span></param>
        <param name="sourceDatabaseId"><span data-ttu-id="1ec9e-113">条件付きです。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-113">Conditional.</span></span> <span data-ttu-id="1ec9e-114">ソース データベースのリソース ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-114">Specifies the resource ID of the source database.</span></span> <span data-ttu-id="1ec9e-115">CreateMode が既定値に設定されていない場合は、この値を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-115">If createMode is not set to Default, then this value must be specified.</span></span> <span data-ttu-id="1ec9e-116">ソース データベースの名前は同じである必要があります。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-116">The name of the source database must be the same.</span></span> <span data-ttu-id="1ec9e-117">注: 照合順序、エディション、および MaxSizeBytes 必要があります、同じままのリンクがアクティブな状態です。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-117">NOTE: Collation, Edition, and MaxSizeBytes must remain the same while the link is active.</span></span> <span data-ttu-id="1ec9e-118">これらのパラメーターに指定した値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-118">Values specified for these parameters will be ignored.</span></span></param>
        <param name="edition"><span data-ttu-id="1ec9e-119">Azure SQL データベースのエディションです。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-119">The edition of the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-120">DatabaseEditions 列挙には、有効なすべてのエディションが含まれています。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-120">The DatabaseEditions enumeration contains all the valid editions.</span></span>
            <span data-ttu-id="1ec9e-121">使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'</span><span class="sxs-lookup"><span data-stu-id="1ec9e-121">Possible values include: 'Web', 'Business', 'Basic', 'Standard', 'Premium', 'Free', 'Stretch', 'DataWarehouse'</span></span></param>
        <param name="maxSizeBytes"><span data-ttu-id="1ec9e-122">バイト単位で表される Azure SQL データベースの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-122">The max size of the Azure SQL database expressed in bytes.</span></span> <span data-ttu-id="1ec9e-123">注: (各エディションで配置されている制限事項) だけでなく、次のサイズのみがサポートされて: {100 MB | 500 MB | 1 GB | 5 GB | 10 GB | 20 GB | 30 GB.</span><span class="sxs-lookup"><span data-stu-id="1ec9e-123">Note: Only the following sizes are supported (in addition to limitations being placed on each edition): { 100 MB | 500 MB |1 GB | 5 GB | 10 GB | 20 GB | 30 GB …</span></span> <span data-ttu-id="1ec9e-124">150 GB |200 GB しています.</span><span class="sxs-lookup"><span data-stu-id="1ec9e-124">150 GB | 200 GB …</span></span>
            <span data-ttu-id="1ec9e-125">500 GB}</span><span class="sxs-lookup"><span data-stu-id="1ec9e-125">500 GB }</span></span></param>
        <param name="requestedServiceObjectiveId"><span data-ttu-id="1ec9e-126">構成されたサービス レベル目標の ID、Azure SQL データベース。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-126">The configured Service Level Objective ID of the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-127">これは、サービス レベル目標の Azure SQL データベースに適用されている処理を行っています。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-127">This is the Service Level Objective that is in the process of being applied to the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-128">正常に更新されると、その currentServiceObjectiveId プロパティの値は一致します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-128">Once successfully updated, it will match the value of currentServiceObjectiveId property.</span></span></param>
        <param name="requestedServiceObjectiveName"><span data-ttu-id="1ec9e-129">Azure SQL データベースの構成済みのサービス レベル目標の名前です。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-129">The name of the configured Service Level Objective of the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-130">これは、サービス レベル目標の Azure SQL データベースに適用されている処理を行っています。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-130">This is the Service Level Objective that is in the process of being applied to the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-131">正常に更新されると、サービス レベル目標のプロパティの値には一致します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-131">Once successfully updated, it will match the value of serviceLevelObjective property.</span></span> <span data-ttu-id="1ec9e-132">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'</span><span class="sxs-lookup"><span data-stu-id="1ec9e-132">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3'</span></span></param>
        <param name="serviceLevelObjective"><span data-ttu-id="1ec9e-133">Azure SQL データベースの現在のサービス レベル目標です。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-133">The current Service Level Objective of the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-134">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'</span><span class="sxs-lookup"><span data-stu-id="1ec9e-134">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3'</span></span></param>
        <param name="status"><span data-ttu-id="1ec9e-135">Azure SQL データベースの状態です。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-135">The status of the Azure SQL database.</span></span></param>
        <param name="elasticPoolName"><span data-ttu-id="1ec9e-136">データベースが Azure SQL 弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-136">The name of the Azure SQL Elastic Pool the database is in.</span></span></param>
        <param name="defaultSecondaryLocation"><span data-ttu-id="1ec9e-137">このデータベースの既定のセカンダリ地域。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-137">The default secondary region for this database.</span></span></param>
        <param name="serviceTierAdvisors"><span data-ttu-id="1ec9e-138">このデータベースのサービス層アドバイザーの一覧。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-138">The list of service tier advisors for this database.</span></span> <span data-ttu-id="1ec9e-139">展開されたプロパティ</span><span class="sxs-lookup"><span data-stu-id="1ec9e-139">Expanded property</span></span></param>
        <param name="upgradeHint"><span data-ttu-id="1ec9e-140">このデータベースのアップグレードのヒント。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-140">The upgrade hint for this database.</span></span></param>
        <param name="schemas"><span data-ttu-id="1ec9e-141">このデータベースからスキーマです。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-141">The schemas from this database.</span></span></param>
        <param name="transparentDataEncryption"><span data-ttu-id="1ec9e-142">透過的なデータ暗号化は、このデータベースの情報です。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-142">The transparent data encryption info for this database.</span></span></param>
        <param name="recommendedIndex"><span data-ttu-id="1ec9e-143">このデータベースの推奨されるインデックスです。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-143">The recommended indices for this database.</span></span></param>
        <summary>
            <span data-ttu-id="1ec9e-144">DatabaseInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-144">Initializes a new instance of the DatabaseInner class.</span></span>
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
            <span data-ttu-id="1ec9e-145">取得または Azure SQL データベースの照合順序を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-145">Gets or sets the collation of the Azure SQL database.</span></span>
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
            <span data-ttu-id="1ec9e-146">Azure SQL データベースのコンテインメントの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-146">Gets the containment state of the Azure SQL database.</span></span>
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
            <span data-ttu-id="1ec9e-147">取得または設定を作成するデータベースの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-147">Gets or sets specifies the type of database to create.</span></span> <span data-ttu-id="1ec9e-148">使用可能な値が含まれます: 'コピー'、'Default'、'NonReadableSecondary'、'OnlineSecondary'、'PointInTimeRestore'、'復旧'、'Restore'</span><span class="sxs-lookup"><span data-stu-id="1ec9e-148">Possible values include: 'Copy', 'Default', 'NonReadableSecondary', 'OnlineSecondary', 'PointInTimeRestore', 'Recovery', 'Restore'</span></span>
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
            <span data-ttu-id="1ec9e-149">Azure SQL データベース (ISO8601 形式) の作成日を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-149">Gets the creation date of the Azure SQL database (ISO8601 format).</span></span>
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
            <span data-ttu-id="1ec9e-150">Azure SQL データベースの現在のサービス レベル目標の ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-150">Gets the current Service Level Objective ID of the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-151">これは、現在アクティブなサービス レベル目標の ID です。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-151">This is the ID of the Service Level Objective that is currently active.</span></span>
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
            <span data-ttu-id="1ec9e-152">Azure SQL データベースの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-152">Gets the ID of the Azure SQL database.</span></span>
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
            <span data-ttu-id="1ec9e-153">このデータベースの既定のセカンダリ地域を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-153">Gets the default secondary region for this database.</span></span>
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
            <span data-ttu-id="1ec9e-154">Azure SQL データベースの復旧期間の開始日を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-154">Gets the recovery period start date of the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-155">これは、開始日と回復がこの Azure SQL データベース (ISO8601 形式) の使用可能な場合に記録します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-155">This records the start date and time when recovery is available for this Azure SQL Database (ISO8601 format).</span></span>
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
            <span data-ttu-id="1ec9e-156">取得または Azure SQL データベースのエディションを設定します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-156">Gets or sets the edition of the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-157">DatabaseEditions 列挙には、有効なすべてのエディションが含まれています。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-157">The DatabaseEditions enumeration contains all the valid editions.</span></span>
            <span data-ttu-id="1ec9e-158">使用可能な値が含まれます: 'Web'、'ビジネス'、'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'</span><span class="sxs-lookup"><span data-stu-id="1ec9e-158">Possible values include: 'Web', 'Business', 'Basic', 'Standard', 'Premium', 'Free', 'Stretch', 'DataWarehouse'</span></span>
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
            <span data-ttu-id="1ec9e-159">取得またはデータベースが Azure SQL 弾力性プールの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-159">Gets or sets the name of the Azure SQL Elastic Pool the database is in.</span></span>
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
            <span data-ttu-id="1ec9e-160">取得またはバイト数で表される Azure SQL データベースの最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-160">Gets or sets the max size of the Azure SQL database expressed in bytes.</span></span> <span data-ttu-id="1ec9e-161">注: (各エディションで配置されている制限事項) だけでなく、次のサイズのみがサポートされて: {100 MB | 500 MB | 1 GB | 5 GB | 10 GB | 20 GB | 30 GB.</span><span class="sxs-lookup"><span data-stu-id="1ec9e-161">Note: Only the following sizes are supported (in addition to limitations being placed on each edition): { 100 MB | 500 MB |1 GB | 5 GB | 10 GB | 20 GB | 30 GB …</span></span> <span data-ttu-id="1ec9e-162">150 GB |200 GB しています.</span><span class="sxs-lookup"><span data-stu-id="1ec9e-162">150 GB | 200 GB …</span></span> <span data-ttu-id="1ec9e-163">500 GB}</span><span class="sxs-lookup"><span data-stu-id="1ec9e-163">500 GB }</span></span>
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
            <span data-ttu-id="1ec9e-164">このデータベースの推奨インデックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-164">Gets the recommended indices for this database.</span></span>
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
            <span data-ttu-id="1ec9e-165">取得または Azure SQL データベースの構成済みのサービス レベル目標の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-165">Gets or sets the configured Service Level Objective ID of the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-166">これは、サービス レベル目標の Azure SQL データベースに適用されている処理を行っています。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-166">This is the Service Level Objective that is in the process of being applied to the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-167">正常に更新されると、その currentServiceObjectiveId プロパティの値は一致します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-167">Once successfully updated, it will match the value of currentServiceObjectiveId property.</span></span>
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
            <span data-ttu-id="1ec9e-168">取得または Azure SQL データベースの構成済みのサービス レベル目標の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-168">Gets or sets the name of the configured Service Level Objective of the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-169">これは、サービス レベル目標の Azure SQL データベースに適用されている処理を行っています。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-169">This is the Service Level Objective that is in the process of being applied to the Azure SQL database.</span></span> <span data-ttu-id="1ec9e-170">正常に更新されると、サービス レベル目標のプロパティの値には一致します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-170">Once successfully updated, it will match the value of serviceLevelObjective property.</span></span> <span data-ttu-id="1ec9e-171">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'</span><span class="sxs-lookup"><span data-stu-id="1ec9e-171">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3'</span></span>
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
            <span data-ttu-id="1ec9e-172">このデータベースからスキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-172">Gets the schemas from this database.</span></span>
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
            <span data-ttu-id="1ec9e-173">Azure SQL データベースの現在のサービス レベル目標を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-173">Gets the current Service Level Objective of the Azure SQL database.</span></span>
            <span data-ttu-id="1ec9e-174">使用可能な値が含まれます: 'Basic'、'S0'、'S1'、'S2'、'S3'、'P1'、'P2'、'P3'</span><span class="sxs-lookup"><span data-stu-id="1ec9e-174">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3'</span></span>
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
            <span data-ttu-id="1ec9e-175">このデータベースのサービス層アドバイザーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-175">Gets the list of service tier advisors for this database.</span></span> <span data-ttu-id="1ec9e-176">展開されたプロパティ</span><span class="sxs-lookup"><span data-stu-id="1ec9e-176">Expanded property</span></span>
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
            <span data-ttu-id="1ec9e-177">取得または条件を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-177">Gets or sets conditional.</span></span> <span data-ttu-id="1ec9e-178">ソース データベースのリソース ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-178">Specifies the resource ID of the source database.</span></span> <span data-ttu-id="1ec9e-179">CreateMode が既定値に設定されていない場合は、この値を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-179">If createMode is not set to Default, then this value must be specified.</span></span> <span data-ttu-id="1ec9e-180">ソース データベースの名前は同じである必要があります。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-180">The name of the source database must be the same.</span></span>
            <span data-ttu-id="1ec9e-181">注: 照合順序、エディション、および MaxSizeBytes 必要があります、同じままのリンクがアクティブな状態です。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-181">NOTE: Collation, Edition, and MaxSizeBytes must remain the same while the link is active.</span></span> <span data-ttu-id="1ec9e-182">これらのパラメーターに指定した値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-182">Values specified for these parameters will be ignored.</span></span>
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
            <span data-ttu-id="1ec9e-183">Azure SQL データベースの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-183">Gets the status of the Azure SQL database.</span></span>
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
            <span data-ttu-id="1ec9e-184">このデータベースの透過的なデータの暗号化情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-184">Gets the transparent data encryption info for this database.</span></span>
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
            <span data-ttu-id="1ec9e-185">このデータベースのアップグレードのヒントを取得します。</span><span class="sxs-lookup"><span data-stu-id="1ec9e-185">Gets the upgrade hint for this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>