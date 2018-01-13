<Type Name="HDInsightOnDemandLinkedService" FullName="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService">
  <TypeSignature Language="C#" Value="public class HDInsightOnDemandLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HDInsightOnDemandLinkedService extends Microsoft.Azure.Management.DataFactory.Models.LinkedService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class HDInsightOnDemandLinkedService&#xA;Inherits LinkedService" />
  <TypeSignature Language="F#" Value="type HDInsightOnDemandLinkedService = class&#xA;    inherit LinkedService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.LinkedService</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("HDInsightOnDemand")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5c037-101">HDInsight オンデマンドのリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="5c037-101">HDInsight ondemand linked service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightOnDemandLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5c037-102">HDInsightOnDemandLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5c037-102">Initializes a new instance of the HDInsightOnDemandLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightOnDemandLinkedService (object clusterSize, object timeToLive, object version, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object hostSubscriptionId, object tenant, object clusterResourceGroup, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia = null, string description = null, object servicePrincipalId = null, Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey = null, object clusterNamePrefix = null, object clusterUserName = null, Microsoft.Azure.Management.DataFactory.Models.SecureString clusterPassword = null, object clusterSshUserName = null, Microsoft.Azure.Management.DataFactory.Models.SecureString clusterSshPassword = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; additionalLinkedServiceNames = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference hcatalogLinkedServiceName = null, object clusterType = null, object sparkVersion = null, object coreConfiguration = null, object hBaseConfiguration = null, object hdfsConfiguration = null, object hiveConfiguration = null, object mapReduceConfiguration = null, object oozieConfiguration = null, object stormConfiguration = null, object yarnConfiguration = null, object encryptedCredential = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object clusterSize, object timeToLive, object version, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, object hostSubscriptionId, object tenant, object clusterResourceGroup, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference connectVia, string description, object servicePrincipalId, class Microsoft.Azure.Management.DataFactory.Models.SecureString servicePrincipalKey, object clusterNamePrefix, object clusterUserName, class Microsoft.Azure.Management.DataFactory.Models.SecureString clusterPassword, object clusterSshUserName, class Microsoft.Azure.Management.DataFactory.Models.SecureString clusterSshPassword, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; additionalLinkedServiceNames, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference hcatalogLinkedServiceName, object clusterType, object sparkVersion, object coreConfiguration, object hBaseConfiguration, object hdfsConfiguration, object hiveConfiguration, object mapReduceConfiguration, object oozieConfiguration, object stormConfiguration, object yarnConfiguration, object encryptedCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.#ctor(System.Object,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Object,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference,System.String,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Object,Microsoft.Azure.Management.DataFactory.Models.SecureString,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clusterSize As Object, timeToLive As Object, version As Object, linkedServiceName As LinkedServiceReference, hostSubscriptionId As Object, tenant As Object, clusterResourceGroup As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional connectVia As IntegrationRuntimeReference = null, Optional description As String = null, Optional servicePrincipalId As Object = null, Optional servicePrincipalKey As SecureString = null, Optional clusterNamePrefix As Object = null, Optional clusterUserName As Object = null, Optional clusterPassword As SecureString = null, Optional clusterSshUserName As Object = null, Optional clusterSshPassword As SecureString = null, Optional additionalLinkedServiceNames As IList(Of LinkedServiceReference) = null, Optional hcatalogLinkedServiceName As LinkedServiceReference = null, Optional clusterType As Object = null, Optional sparkVersion As Object = null, Optional coreConfiguration As Object = null, Optional hBaseConfiguration As Object = null, Optional hdfsConfiguration As Object = null, Optional hiveConfiguration As Object = null, Optional mapReduceConfiguration As Object = null, Optional oozieConfiguration As Object = null, Optional stormConfiguration As Object = null, Optional yarnConfiguration As Object = null, Optional encryptedCredential As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService : obj * obj * obj * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * obj * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference * string * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * obj * Microsoft.Azure.Management.DataFactory.Models.SecureString * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * obj * obj * obj * obj * obj * obj * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService" Usage="new Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService (clusterSize, timeToLive, version, linkedServiceName, hostSubscriptionId, tenant, clusterResourceGroup, additionalProperties, connectVia, description, servicePrincipalId, servicePrincipalKey, clusterNamePrefix, clusterUserName, clusterPassword, clusterSshUserName, clusterSshPassword, additionalLinkedServiceNames, hcatalogLinkedServiceName, clusterType, sparkVersion, coreConfiguration, hBaseConfiguration, hdfsConfiguration, hiveConfiguration, mapReduceConfiguration, oozieConfiguration, stormConfiguration, yarnConfiguration, encryptedCredential)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clusterSize" Type="System.Object" />
        <Parameter Name="timeToLive" Type="System.Object" />
        <Parameter Name="version" Type="System.Object" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="hostSubscriptionId" Type="System.Object" />
        <Parameter Name="tenant" Type="System.Object" />
        <Parameter Name="clusterResourceGroup" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="connectVia" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeReference" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="servicePrincipalId" Type="System.Object" />
        <Parameter Name="servicePrincipalKey" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="clusterNamePrefix" Type="System.Object" />
        <Parameter Name="clusterUserName" Type="System.Object" />
        <Parameter Name="clusterPassword" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="clusterSshUserName" Type="System.Object" />
        <Parameter Name="clusterSshPassword" Type="Microsoft.Azure.Management.DataFactory.Models.SecureString" />
        <Parameter Name="additionalLinkedServiceNames" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;" />
        <Parameter Name="hcatalogLinkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="clusterType" Type="System.Object" />
        <Parameter Name="sparkVersion" Type="System.Object" />
        <Parameter Name="coreConfiguration" Type="System.Object" />
        <Parameter Name="hBaseConfiguration" Type="System.Object" />
        <Parameter Name="hdfsConfiguration" Type="System.Object" />
        <Parameter Name="hiveConfiguration" Type="System.Object" />
        <Parameter Name="mapReduceConfiguration" Type="System.Object" />
        <Parameter Name="oozieConfiguration" Type="System.Object" />
        <Parameter Name="stormConfiguration" Type="System.Object" />
        <Parameter Name="yarnConfiguration" Type="System.Object" />
        <Parameter Name="encryptedCredential" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="clusterSize"><span data-ttu-id="5c037-103">クラスター内の worker/データ ノードの数です。</span><span class="sxs-lookup"><span data-stu-id="5c037-103">Number of worker/data nodes in the cluster.</span></span> <span data-ttu-id="5c037-104">推奨値: 4 です。</span><span class="sxs-lookup"><span data-stu-id="5c037-104">Suggestion value: 4.</span></span> <span data-ttu-id="5c037-105">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="timeToLive"><span data-ttu-id="5c037-106">オンデマンド HDInsight クラスターに許可されるアイドル時間です。</span><span class="sxs-lookup"><span data-stu-id="5c037-106">The allowed idle time for the on-demand HDInsight cluster.</span></span> <span data-ttu-id="5c037-107">他のアクティブなジョブがクラスターにない場合、アクティビティ実行の完了後にオンデマンド HDInsight クラスターが起動状態を維持する時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-107">Specifies how long the on-demand HDInsight cluster stays alive after completion of an activity run if there are no other active jobs in the cluster.</span></span> <span data-ttu-id="5c037-108">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5c037-108">The minimum value is 5 mins.</span></span> <span data-ttu-id="5c037-109">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-109">Type: string (or Expression with resultType string).</span></span></param>
        <param name="version"><span data-ttu-id="5c037-110">HDInsight クラスターのバージョン。</span><span class="sxs-lookup"><span data-stu-id="5c037-110">Version of the HDInsight cluster.</span></span>  <span data-ttu-id="5c037-111">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-111">Type: string (or Expression with resultType string).</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="5c037-112">データを保存し、処理するためにオンデマンド クラスターで使用される Azure Storage のリンクされたサービスです。</span><span class="sxs-lookup"><span data-stu-id="5c037-112">Azure Storage linked service to be used by the on-demand cluster for storing and processing data.</span></span></param>
        <param name="hostSubscriptionId"><span data-ttu-id="5c037-113">クラスターをホストするお客様のサブスクリプション。</span><span class="sxs-lookup"><span data-stu-id="5c037-113">The customer’s subscription to host the cluster.</span></span> <span data-ttu-id="5c037-114">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-114">Type: string (or Expression with resultType string).</span></span></param>
        <param name="tenant"><span data-ttu-id="5c037-115">テナント id/名前が、サービス プリンシパルが属しています。</span><span class="sxs-lookup"><span data-stu-id="5c037-115">The Tenant id/name to which the service principal belongs.</span></span> <span data-ttu-id="5c037-116">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-116">Type: string (or Expression with resultType string).</span></span></param>
        <param name="clusterResourceGroup"><span data-ttu-id="5c037-117">リソース グループは、クラスターが属しています。</span><span class="sxs-lookup"><span data-stu-id="5c037-117">The resource group where the cluster belongs.</span></span> <span data-ttu-id="5c037-118">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-118">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="5c037-119">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="5c037-119">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="connectVia"><span data-ttu-id="5c037-120">統合のランタイム参照。</span><span class="sxs-lookup"><span data-stu-id="5c037-120">The integration runtime reference.</span></span></param>
        <param name="description"><span data-ttu-id="5c037-121">リンクされたサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="5c037-121">Linked service description.</span></span></param>
        <param name="servicePrincipalId"><span data-ttu-id="5c037-122">HostSubscriptionId のサービス プリンシパル id。</span><span class="sxs-lookup"><span data-stu-id="5c037-122">The service principal id for the hostSubscriptionId.</span></span> <span data-ttu-id="5c037-123">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-123">Type: string (or Expression with resultType string).</span></span></param>
        <param name="servicePrincipalKey"><span data-ttu-id="5c037-124">サービス プリンシパルの id キーです。</span><span class="sxs-lookup"><span data-stu-id="5c037-124">The key for the service principal id.</span></span></param>
        <param name="clusterNamePrefix"><span data-ttu-id="5c037-125">クラスター名のプレフィックスを後置形式はタイムスタンプを持つ個別になります。</span><span class="sxs-lookup"><span data-stu-id="5c037-125">The prefix of cluster name, postfix will be distinct with timestamp.</span></span> <span data-ttu-id="5c037-126">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-126">Type: string (or Expression with resultType string).</span></span></param>
        <param name="clusterUserName"><span data-ttu-id="5c037-127">クラスターにアクセスするユーザー名。</span><span class="sxs-lookup"><span data-stu-id="5c037-127">The username to access the cluster.</span></span>
            <span data-ttu-id="5c037-128">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-128">Type: string (or Expression with resultType string).</span></span></param>
        <param name="clusterPassword"><span data-ttu-id="5c037-129">クラスターにアクセスするパスワードです。</span><span class="sxs-lookup"><span data-stu-id="5c037-129">The password to access the cluster.</span></span></param>
        <param name="clusterSshUserName"><span data-ttu-id="5c037-130">クラスターのノードにリモートで接続する SSH のユーザー名 (Linux の場合)。</span><span class="sxs-lookup"><span data-stu-id="5c037-130">The username to SSH remotely connect to cluster’s node (for Linux).</span></span> <span data-ttu-id="5c037-131">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-131">Type: string (or Expression with resultType string).</span></span></param>
        <param name="clusterSshPassword"><span data-ttu-id="5c037-132">SSH パスワードは、(Linux) のクラスターのノードをリモートで接続します。</span><span class="sxs-lookup"><span data-stu-id="5c037-132">The password to SSH remotely connect cluster’s node (for Linux).</span></span></param>
        <param name="additionalLinkedServiceNames"><span data-ttu-id="5c037-133">Data Factory サービスがあなたの代わりに登録できるように、HDInsight の「リンクされたサービス」の追加ストレージ アカウントを指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-133">Specifies additional storage accounts for the HDInsight linked service so that the Data Factory service can register them on your behalf.</span></span></param>
        <param name="hcatalogLinkedServiceName"><span data-ttu-id="5c037-134">HCatalog データベースを指す Azure SQL のリンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="5c037-134">The name of Azure SQL linked service that point to the HCatalog database.</span></span> <span data-ttu-id="5c037-135">オンデマンド HDInsight クラスターは、Azure SQL データベースを metastore として使用して作成されます。</span><span class="sxs-lookup"><span data-stu-id="5c037-135">The on-demand HDInsight cluster is created by using the Azure SQL database as the metastore.</span></span></param>
        <param name="clusterType"><span data-ttu-id="5c037-136">クラスターの種類。</span><span class="sxs-lookup"><span data-stu-id="5c037-136">The cluster type.</span></span> <span data-ttu-id="5c037-137">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-137">Type: string (or Expression with resultType string).</span></span></param>
        <param name="sparkVersion"><span data-ttu-id="5c037-138">Spark クラスターの種類が '発言' の場合のバージョン。</span><span class="sxs-lookup"><span data-stu-id="5c037-138">The version of spark if the cluster type is 'spark'.</span></span> <span data-ttu-id="5c037-139">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-139">Type: string (or Expression with resultType string).</span></span></param>
        <param name="coreConfiguration"><span data-ttu-id="5c037-140">作成する HDInsight クラスターに core 構成パラメーター (core-site.xml と同じ) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-140">Specifies the core configuration parameters (as in core-site.xml) for the HDInsight cluster to be created.</span></span></param>
        <param name="hBaseConfiguration"><span data-ttu-id="5c037-141">HDInsight クラスターに HBase 構成パラメーター (hbase-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-141">Specifies the HBase configuration parameters (hbase-site.xml) for the HDInsight cluster.</span></span></param>
        <param name="hdfsConfiguration"><span data-ttu-id="5c037-142">HDInsight クラスターに HDFS 構成パラメーター (hdfs-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-142">Specifies the HDFS configuration parameters (hdfs-site.xml) for the HDInsight cluster.</span></span></param>
        <param name="hiveConfiguration"><span data-ttu-id="5c037-143">HDInsight クラスターに hive 構成パラメーター (hive-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-143">Specifies the hive configuration parameters (hive-site.xml) for the HDInsight cluster.</span></span></param>
        <param name="mapReduceConfiguration"><span data-ttu-id="5c037-144">HDInsight クラスターに MapReduce 構成パラメーター (mapred-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-144">Specifies the MapReduce configuration parameters (mapred-site.xml) for the HDInsight cluster.</span></span></param>
        <param name="oozieConfiguration"><span data-ttu-id="5c037-145">HDInsight クラスターに Oozie 構成パラメーター (oozie-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-145">Specifies the Oozie configuration parameters (oozie-site.xml) for the HDInsight cluster.</span></span></param>
        <param name="stormConfiguration"><span data-ttu-id="5c037-146">HDInsight クラスターに Storm 構成パラメーター (storm-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-146">Specifies the Storm configuration parameters (storm-site.xml) for the HDInsight cluster.</span></span></param>
        <param name="yarnConfiguration"><span data-ttu-id="5c037-147">HDInsight クラスターに Yarn 構成パラメーター (yarn-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-147">Specifies the Yarn configuration parameters (yarn-site.xml) for the HDInsight cluster.</span></span></param>
        <param name="encryptedCredential"><span data-ttu-id="5c037-148">暗号化された資格情報の認証に使用します。</span><span class="sxs-lookup"><span data-stu-id="5c037-148">The encrypted credential used for authentication.</span></span> <span data-ttu-id="5c037-149">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="5c037-149">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="5c037-150">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-150">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="5c037-151">HDInsightOnDemandLinkedService クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5c037-151">Initializes a new instance of the HDInsightOnDemandLinkedService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalLinkedServiceNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; AdditionalLinkedServiceNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; AdditionalLinkedServiceNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.AdditionalLinkedServiceNames" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalLinkedServiceNames As IList(Of LinkedServiceReference)" />
      <MemberSignature Language="F#" Value="member this.AdditionalLinkedServiceNames : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.AdditionalLinkedServiceNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.additionalLinkedServiceNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-152">取得または設定できるように、Data Factory サービスで自動的に登録することができます、HDInsight のリンクされたサービスの追加のストレージ アカウントを指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-152">Gets or sets specifies additional storage accounts for the HDInsight linked service so that the Data Factory service can register them on your behalf.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterNamePrefix">
      <MemberSignature Language="C#" Value="public object ClusterNamePrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterNamePrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterNamePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterNamePrefix As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterNamePrefix : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterNamePrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterNamePrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-153">プレフィックスの設定を取得またはクラスター名の後置にタイムスタンプを持つ個別なります。</span><span class="sxs-lookup"><span data-stu-id="5c037-153">Gets or sets the prefix of cluster name, postfix will be distinct with timestamp.</span></span> <span data-ttu-id="5c037-154">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-154">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ClusterPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ClusterPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.ClusterPassword : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-155">取得またはクラスターにアクセスするパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-155">Gets or sets the password to access the cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterResourceGroup">
      <MemberSignature Language="C#" Value="public object ClusterResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterResourceGroup As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterResourceGroup : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterResourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-156">取得またはクラスターが属している、リソース グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-156">Gets or sets the resource group where the cluster belongs.</span></span> <span data-ttu-id="5c037-157">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-157">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterSize">
      <MemberSignature Language="C#" Value="public object ClusterSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterSize As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterSize : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-158">取得または、クラスター内のワーカー/データ ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-158">Gets or sets number of worker/data nodes in the cluster.</span></span> <span data-ttu-id="5c037-159">推奨値: 4 です。</span><span class="sxs-lookup"><span data-stu-id="5c037-159">Suggestion value: 4.</span></span> <span data-ttu-id="5c037-160">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-160">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterSshPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ClusterSshPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ClusterSshPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSshPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterSshPassword As SecureString" />
      <MemberSignature Language="F#" Value="member this.ClusterSshPassword : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSshPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterSshPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-161">取得または SSH をリモートでパスワードを設定 (Linux) のクラスターのノードを接続します。</span><span class="sxs-lookup"><span data-stu-id="5c037-161">Gets or sets the password to SSH remotely connect cluster’s node (for Linux).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterSshUserName">
      <MemberSignature Language="C#" Value="public object ClusterSshUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterSshUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSshUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterSshUserName As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterSshUserName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterSshUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterSshUserName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-162">取得または設定する SSH ユーザー名をリモートで接続をクラスターのノードに (for Linux)。</span><span class="sxs-lookup"><span data-stu-id="5c037-162">Gets or sets the username to SSH remotely connect to cluster’s node (for Linux).</span></span> <span data-ttu-id="5c037-163">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-163">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterType">
      <MemberSignature Language="C#" Value="public object ClusterType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterType As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterType : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-164">取得またはクラスターの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-164">Gets or sets the cluster type.</span></span> <span data-ttu-id="5c037-165">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-165">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterUserName">
      <MemberSignature Language="C#" Value="public object ClusterUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ClusterUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterUserName As Object" />
      <MemberSignature Language="F#" Value="member this.ClusterUserName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ClusterUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.clusterUserName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-166">取得またはクラスターにアクセスするユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-166">Gets or sets the username to access the cluster.</span></span> <span data-ttu-id="5c037-167">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-167">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CoreConfiguration">
      <MemberSignature Language="C#" Value="public object CoreConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object CoreConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.CoreConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CoreConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.CoreConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.CoreConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.coreConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-168">取得または設定を作成する HDInsight クラスターの (core-site.xml) と同じコア構成パラメーターを指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-168">Gets or sets specifies the core configuration parameters (as in core-site.xml) for the HDInsight cluster to be created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public object EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As Object" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.EncryptedCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.encryptedCredential")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-169">取得または認証に使用される暗号化された資格情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-169">Gets or sets the encrypted credential used for authentication.</span></span>
            <span data-ttu-id="5c037-170">資格情報は、統合ランタイム資格情報マネージャーを使用して暗号化されます。</span><span class="sxs-lookup"><span data-stu-id="5c037-170">Credentials are encrypted using the integration runtime credential manager.</span></span> <span data-ttu-id="5c037-171">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-171">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HBaseConfiguration">
      <MemberSignature Language="C#" Value="public object HBaseConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HBaseConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HBaseConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property HBaseConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.HBaseConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HBaseConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hBaseConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-172">取得または設定は、HDInsight クラスターの HBase 構成パラメーター (hbase site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-172">Gets or sets specifies the HBase configuration parameters (hbase-site.xml) for the HDInsight cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HcatalogLinkedServiceName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference HcatalogLinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference HcatalogLinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HcatalogLinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property HcatalogLinkedServiceName As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.HcatalogLinkedServiceName : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HcatalogLinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hcatalogLinkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-173">リンクされた Azure SQL の名前を取得または設定はサービスを指す HCatalog データベースです。</span><span class="sxs-lookup"><span data-stu-id="5c037-173">Gets or sets the name of Azure SQL linked service that point to the HCatalog database.</span></span> <span data-ttu-id="5c037-174">オンデマンド HDInsight クラスターは、Azure SQL データベースを metastore として使用して作成されます。</span><span class="sxs-lookup"><span data-stu-id="5c037-174">The on-demand HDInsight cluster is created by using the Azure SQL database as the metastore.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HdfsConfiguration">
      <MemberSignature Language="C#" Value="public object HdfsConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HdfsConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HdfsConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property HdfsConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.HdfsConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HdfsConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hdfsConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-175">取得または設定は、HDInsight クラスターの HDFS 構成パラメーター (hdfs-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-175">Gets or sets specifies the HDFS configuration parameters (hdfs-site.xml) for the HDInsight cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HiveConfiguration">
      <MemberSignature Language="C#" Value="public object HiveConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HiveConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HiveConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property HiveConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.HiveConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HiveConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hiveConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-176">取得または設定は、HDInsight クラスターの hive 構成パラメーター (hive-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-176">Gets or sets specifies the hive configuration parameters (hive-site.xml) for the HDInsight cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostSubscriptionId">
      <MemberSignature Language="C#" Value="public object HostSubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object HostSubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HostSubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property HostSubscriptionId As Object" />
      <MemberSignature Language="F#" Value="member this.HostSubscriptionId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.HostSubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.hostSubscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-177">取得またはクラスターをホストする顧客のサブスクリプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-177">Gets or sets the customer’s subscription to host the cluster.</span></span> <span data-ttu-id="5c037-178">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-178">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.linkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-179">取得または保存して、データの処理のオンデマンドのクラスターで使用される azure Storage のリンクされたサービスを設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-179">Gets or sets azure Storage linked service to be used by the on-demand cluster for storing and processing data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MapReduceConfiguration">
      <MemberSignature Language="C#" Value="public object MapReduceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object MapReduceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.MapReduceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property MapReduceConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.MapReduceConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.MapReduceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.mapReduceConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-180">取得または設定は、HDInsight クラスターの MapReduce 構成パラメーター (mapred-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-180">Gets or sets specifies the MapReduce configuration parameters (mapred-site.xml) for the HDInsight cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OozieConfiguration">
      <MemberSignature Language="C#" Value="public object OozieConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object OozieConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.OozieConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property OozieConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.OozieConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.OozieConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.oozieConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-181">取得または設定は、HDInsight クラスターの Oozie 構成パラメーター (oozie-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-181">Gets or sets specifies the Oozie configuration parameters (oozie-site.xml) for the HDInsight cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalId">
      <MemberSignature Language="C#" Value="public object ServicePrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object ServicePrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ServicePrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalId As Object" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalId : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ServicePrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.servicePrincipalId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-182">取得または、hostSubscriptionId のサービス プリンシパルの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-182">Gets or sets the service principal id for the hostSubscriptionId.</span></span>
            <span data-ttu-id="5c037-183">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-183">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.SecureString ServicePrincipalKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ServicePrincipalKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalKey As SecureString" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalKey : Microsoft.Azure.Management.DataFactory.Models.SecureString with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.ServicePrincipalKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.servicePrincipalKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-184">取得またはサービス プリンシパルの id キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-184">Gets or sets the key for the service principal id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SparkVersion">
      <MemberSignature Language="C#" Value="public object SparkVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object SparkVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.SparkVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property SparkVersion As Object" />
      <MemberSignature Language="F#" Value="member this.SparkVersion : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.SparkVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.sparkVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-185">取得またはクラスターの種類が 'spark' である場合に、spark のバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-185">Gets or sets the version of spark if the cluster type is 'spark'.</span></span>
            <span data-ttu-id="5c037-186">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-186">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StormConfiguration">
      <MemberSignature Language="C#" Value="public object StormConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object StormConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.StormConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property StormConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.StormConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.StormConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.stormConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-187">取得または設定は、HDInsight クラスターの Storm 構成パラメーター (storm-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-187">Gets or sets specifies the Storm configuration parameters (storm-site.xml) for the HDInsight cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tenant">
      <MemberSignature Language="C#" Value="public object Tenant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Tenant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.Tenant" />
      <MemberSignature Language="VB.NET" Value="Public Property Tenant As Object" />
      <MemberSignature Language="F#" Value="member this.Tenant : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.Tenant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.tenant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-188">取得またはサービス プリンシパルが所属するテナント id または名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-188">Gets or sets the Tenant id/name to which the service principal belongs.</span></span> <span data-ttu-id="5c037-189">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-189">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public object TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As Object" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.timeToLive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-190">取得またはオンデマンド HDInsight クラスターの最大アイドル時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-190">Gets or sets the allowed idle time for the on-demand HDInsight cluster.</span></span> <span data-ttu-id="5c037-191">他のアクティブなジョブがクラスターにない場合、アクティビティ実行の完了後にオンデマンド HDInsight クラスターが起動状態を維持する時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-191">Specifies how long the on-demand HDInsight cluster stays alive after completion of an activity run if there are no other active jobs in the cluster.</span></span> <span data-ttu-id="5c037-192">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5c037-192">The minimum value is 5 mins.</span></span> <span data-ttu-id="5c037-193">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-193">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hDInsightOnDemandLinkedService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5c037-194">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5c037-194">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5c037-195">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5c037-195">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public object Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Object" />
      <MemberSignature Language="F#" Value="member this.Version : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-196">取得またはバージョンの HDInsight クラスターを設定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-196">Gets or sets version of the HDInsight cluster.</span></span>  <span data-ttu-id="5c037-197">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="5c037-197">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="YarnConfiguration">
      <MemberSignature Language="C#" Value="public object YarnConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object YarnConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.YarnConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property YarnConfiguration As Object" />
      <MemberSignature Language="F#" Value="member this.YarnConfiguration : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.HDInsightOnDemandLinkedService.YarnConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.yarnConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c037-198">取得または設定は、HDInsight クラスターの Yarn 構成パラメーター (yarn-site.xml) を指定します。</span><span class="sxs-lookup"><span data-stu-id="5c037-198">Gets or sets specifies the Yarn configuration parameters (yarn-site.xml) for the HDInsight cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>