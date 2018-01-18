<Type Name="RestoreRequest" FullName="Microsoft.Azure.Management.WebSites.Models.RestoreRequest">
  <TypeSignature Language="C#" Value="public class RestoreRequest : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RestoreRequest extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.RestoreRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class RestoreRequest&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type RestoreRequest = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c944f-101">復元要求の説明です。</span><span class="sxs-lookup"><span data-stu-id="c944f-101">Description of a restore request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c944f-102">RestoreRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c944f-102">Initializes a new instance of the RestoreRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreRequest (string id = null, string name = null, string kind = null, string type = null, string storageAccountUrl = null, string blobName = null, Nullable&lt;bool&gt; overwrite = null, string siteName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; databases = null, Nullable&lt;bool&gt; ignoreConflictingHostNames = null, Nullable&lt;bool&gt; ignoreDatabases = null, string appServicePlan = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; operationType = null, Nullable&lt;bool&gt; adjustConnectionStrings = null, string hostingEnvironment = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string storageAccountUrl, string blobName, valuetype System.Nullable`1&lt;bool&gt; overwrite, string siteName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; databases, valuetype System.Nullable`1&lt;bool&gt; ignoreConflictingHostNames, valuetype System.Nullable`1&lt;bool&gt; ignoreDatabases, string appServicePlan, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; operationType, valuetype System.Nullable`1&lt;bool&gt; adjustConnectionStrings, string hostingEnvironment) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional storageAccountUrl As String = null, Optional blobName As String = null, Optional overwrite As Nullable(Of Boolean) = null, Optional siteName As String = null, Optional databases As IList(Of DatabaseBackupSetting) = null, Optional ignoreConflictingHostNames As Nullable(Of Boolean) = null, Optional ignoreDatabases As Nullable(Of Boolean) = null, Optional appServicePlan As String = null, Optional operationType As Nullable(Of BackupRestoreOperationType) = null, Optional adjustConnectionStrings As Nullable(Of Boolean) = null, Optional hostingEnvironment As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.RestoreRequest : string * string * string * string * string * string * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.RestoreRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.RestoreRequest (id, name, kind, type, storageAccountUrl, blobName, overwrite, siteName, databases, ignoreConflictingHostNames, ignoreDatabases, appServicePlan, operationType, adjustConnectionStrings, hostingEnvironment)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="storageAccountUrl" Type="System.String" />
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="overwrite" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt;" />
        <Parameter Name="ignoreConflictingHostNames" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ignoreDatabases" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="appServicePlan" Type="System.String" />
        <Parameter Name="operationType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt;" />
        <Parameter Name="adjustConnectionStrings" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostingEnvironment" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="c944f-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="c944f-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="c944f-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="c944f-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="c944f-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="c944f-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="c944f-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="c944f-106">Resource type.</span></span></param>
        <param name="storageAccountUrl"><span data-ttu-id="c944f-107">コンテナーの SAS URL。</span><span class="sxs-lookup"><span data-stu-id="c944f-107">SAS URL to the container.</span></span></param>
        <param name="blobName"><span data-ttu-id="c944f-108">バックアップが格納されている blob の名前。</span><span class="sxs-lookup"><span data-stu-id="c944f-108">Name of a blob which contains the backup.</span></span></param>
        <param name="overwrite"><span data-ttu-id="c944f-109">&lt;コード&gt;true&lt;/code&gt; 、復元操作が対象とするアプリケーション; を上書きできる場合それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="c944f-109">&lt;code&gt;true&lt;/code&gt; if the restore operation can overwrite target app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="c944f-110">&lt;コード&gt;true&lt;/code&gt;を既存のアプリケーションを復元しようとしている場合に必要です。</span><span class="sxs-lookup"><span data-stu-id="c944f-110">&lt;code&gt;true&lt;/code&gt; is needed if trying to restore over an existing app.</span></span></param>
        <param name="siteName"><span data-ttu-id="c944f-111">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="c944f-111">Name of an app.</span></span></param>
        <param name="databases"><span data-ttu-id="c944f-112">復元するデータベースのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="c944f-112">Collection of databases which should be restored.</span></span> <span data-ttu-id="c944f-113">この一覧には、バックアップに含まれているデータベースの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="c944f-113">This list has to match the list of databases included in the backup.</span></span></param>
        <param name="ignoreConflictingHostNames"><span data-ttu-id="c944f-114">カスタム ドメインを使用してアプリを復元するときに、ロジックを変更します。</span><span class="sxs-lookup"><span data-stu-id="c944f-114">Changes a logic when restoring an app with custom domains.</span></span> <span data-ttu-id="c944f-115">&lt;コード&gt;true&lt;/code&gt;カスタム ドメインを自動的に削除します。</span><span class="sxs-lookup"><span data-stu-id="c944f-115">&lt;code&gt;true&lt;/code&gt; to remove custom domains automatically.</span></span> <span data-ttu-id="c944f-116">場合&lt;コード&gt;false&lt;/code&gt;、復元しているが、操作中に競合のため失敗する可能性があります、アプリのオブジェクトにカスタム ドメインを追加します。</span><span class="sxs-lookup"><span data-stu-id="c944f-116">If &lt;code&gt;false&lt;/code&gt;, custom domains are added to the app's object when it is being restored, but that might fail due to conflicts during the operation.</span></span></param>
        <param name="ignoreDatabases"><span data-ttu-id="c944f-117">データベースを無視し、サイトのコンテンツの復元のみ</span><span class="sxs-lookup"><span data-stu-id="c944f-117">Ignore the databases and only restore the site content</span></span></param>
        <param name="appServicePlan"><span data-ttu-id="c944f-118">App service プランに復元されたサイトを所有するを指定します。</span><span class="sxs-lookup"><span data-stu-id="c944f-118">Specify app service plan that will own restored site.</span></span></param>
        <param name="operationType"><span data-ttu-id="c944f-119">操作の種類。</span><span class="sxs-lookup"><span data-stu-id="c944f-119">Operation type.</span></span> <span data-ttu-id="c944f-120">使用可能な値が含まれます: 'Default'、' Clone'、'再配置'、'Snapshot'</span><span class="sxs-lookup"><span data-stu-id="c944f-120">Possible values include: 'Default', 'Clone', 'Relocation', 'Snapshot'</span></span></param>
        <param name="adjustConnectionStrings"><span data-ttu-id="c944f-121">&lt;コード&gt;true&lt;/code&gt; SiteConfig.ConnectionStrings を新しいアプリ; に設定する必要がある場合それ以外の場合、&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="c944f-121">&lt;code&gt;true&lt;/code&gt; if SiteConfig.ConnectionStrings should be set in new app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="hostingEnvironment"><span data-ttu-id="c944f-122">App Service 環境名、(場合にのみ、アプリの App Service 環境を復元) が必要な場合です。</span><span class="sxs-lookup"><span data-stu-id="c944f-122">App Service Environment name, if needed (only when restoring an app to an App Service Environment).</span></span></param>
        <summary>
            <span data-ttu-id="c944f-123">RestoreRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c944f-123">Initializes a new instance of the RestoreRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdjustConnectionStrings">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AdjustConnectionStrings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AdjustConnectionStrings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AdjustConnectionStrings" />
      <MemberSignature Language="VB.NET" Value="Public Property AdjustConnectionStrings As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AdjustConnectionStrings : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AdjustConnectionStrings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.adjustConnectionStrings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c944f-124">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; 場合は新しいアプリ; SiteConfig.ConnectionStrings を設定する必要がそれ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code。&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="c944f-124">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if SiteConfig.ConnectionStrings should be set in new app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServicePlan">
      <MemberSignature Language="C#" Value="public string AppServicePlan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServicePlan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AppServicePlan" />
      <MemberSignature Language="VB.NET" Value="Public Property AppServicePlan As String" />
      <MemberSignature Language="F#" Value="member this.AppServicePlan : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.AppServicePlan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appServicePlan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c944f-125">取得または設定は、復元されたサイトを所有する app service プランを指定します。</span><span class="sxs-lookup"><span data-stu-id="c944f-125">Gets or sets specify app service plan that will own restored site.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobName">
      <MemberSignature Language="C#" Value="public string BlobName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.BlobName" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobName As String" />
      <MemberSignature Language="F#" Value="member this.BlobName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.BlobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blobName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c944f-126">取得またはバックアップが格納されている blob の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="c944f-126">Gets or sets name of a blob which contains the backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; Databases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Databases" />
      <MemberSignature Language="VB.NET" Value="Public Property Databases As IList(Of DatabaseBackupSetting)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c944f-127">取得または復元するデータベースのコレクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="c944f-127">Gets or sets collection of databases which should be restored.</span></span> <span data-ttu-id="c944f-128">この一覧には、バックアップに含まれているデータベースの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="c944f-128">This list has to match the list of databases included in the backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironment">
      <MemberSignature Language="C#" Value="public string HostingEnvironment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostingEnvironment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.HostingEnvironment" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironment As String" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironment : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.HostingEnvironment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c944f-129">取得または (場合にのみ、アプリの App Service 環境を復元) が必要な場合に、app Service 環境名を設定します。</span><span class="sxs-lookup"><span data-stu-id="c944f-129">Gets or sets app Service Environment name, if needed (only when restoring an app to an App Service Environment).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreConflictingHostNames">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreConflictingHostNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreConflictingHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreConflictingHostNames" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreConflictingHostNames As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreConflictingHostNames : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreConflictingHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ignoreConflictingHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c944f-130">取得またはカスタム ドメインを使用してアプリを復元するときに、変更、ロジックを設定します。</span><span class="sxs-lookup"><span data-stu-id="c944f-130">Gets or sets changes a logic when restoring an app with custom domains.</span></span> <span data-ttu-id="c944f-131">&amp;lt; コード&amp;gt; true&amp;lt;/code&amp;gt; のカスタム ドメインを自動的に削除します。</span><span class="sxs-lookup"><span data-stu-id="c944f-131">&amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to remove custom domains automatically.</span></span> <span data-ttu-id="c944f-132">場合&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;、復元しているが、操作中に競合のため失敗する可能性があります、アプリのオブジェクトにカスタム ドメインを追加します。</span><span class="sxs-lookup"><span data-stu-id="c944f-132">If &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;, custom domains are added to the app's object when it is being restored, but that might fail due to conflicts during the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreDatabases">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreDatabases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreDatabases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreDatabases" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreDatabases As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreDatabases : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.IgnoreDatabases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ignoreDatabases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c944f-133">データベースを無視し、サイトのコンテンツの復元のみを取得または設定</span><span class="sxs-lookup"><span data-stu-id="c944f-133">Gets or sets ignore the databases and only restore the site content</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; OperationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; OperationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationType As Nullable(Of BackupRestoreOperationType)" />
      <MemberSignature Language="F#" Value="member this.OperationType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c944f-134">取得または操作の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="c944f-134">Gets or sets operation type.</span></span> <span data-ttu-id="c944f-135">使用可能な値が含まれます: 'Default'、' Clone'、'再配置'、'Snapshot'</span><span class="sxs-lookup"><span data-stu-id="c944f-135">Possible values include: 'Default', 'Clone', 'Relocation', 'Snapshot'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Overwrite">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Overwrite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Overwrite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Overwrite" />
      <MemberSignature Language="VB.NET" Value="Public Property Overwrite As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Overwrite : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.Overwrite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.overwrite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c944f-136">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt;、復元操作が対象とするアプリケーション; を上書きできる場合それ以外の場合、 &amp;lt; コード&amp;gt; false&amp;lt;/code。&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="c944f-136">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the restore operation can overwrite target app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            <span data-ttu-id="c944f-137">&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; を既存のアプリケーションを復元しようとしている場合に必要です。</span><span class="sxs-lookup"><span data-stu-id="c944f-137">&amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; is needed if trying to restore over an existing app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteName">
      <MemberSignature Language="C#" Value="public string SiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.SiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteName As String" />
      <MemberSignature Language="F#" Value="member this.SiteName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.SiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c944f-138">取得またはアプリの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="c944f-138">Gets or sets name of an app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountUrl">
      <MemberSignature Language="C#" Value="public string StorageAccountUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RestoreRequest.StorageAccountUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountUrl As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RestoreRequest.StorageAccountUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c944f-139">取得またはコンテナー SAS URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="c944f-139">Gets or sets SAS URL to the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>