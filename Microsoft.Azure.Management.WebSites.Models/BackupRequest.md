<Type Name="BackupRequest" FullName="Microsoft.Azure.Management.WebSites.Models.BackupRequest">
  <TypeSignature Language="C#" Value="public class BackupRequest : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupRequest extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.BackupRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupRequest&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type BackupRequest = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="cf2de-101">実行されるバックアップの説明です。</span><span class="sxs-lookup"><span data-stu-id="cf2de-101">Description of a backup which will be performed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.BackupRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cf2de-102">BackupRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cf2de-102">Initializes a new instance of the BackupRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupRequest (string id = null, string name = null, string kind = null, string type = null, string backupRequestName = null, Nullable&lt;bool&gt; enabled = null, string storageAccountUrl = null, Microsoft.Azure.Management.WebSites.Models.BackupSchedule backupSchedule = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; databases = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; backupRequestType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string backupRequestName, valuetype System.Nullable`1&lt;bool&gt; enabled, string storageAccountUrl, class Microsoft.Azure.Management.WebSites.Models.BackupSchedule backupSchedule, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; databases, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; backupRequestType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.BackupRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.WebSites.Models.BackupSchedule,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting},System.Nullable{Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.BackupRequest : string * string * string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.WebSites.Models.BackupSchedule * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.BackupRequest" Usage="new Microsoft.Azure.Management.WebSites.Models.BackupRequest (id, name, kind, type, backupRequestName, enabled, storageAccountUrl, backupSchedule, databases, backupRequestType)" />
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
        <Parameter Name="backupRequestName" Type="System.String" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="storageAccountUrl" Type="System.String" />
        <Parameter Name="backupSchedule" Type="Microsoft.Azure.Management.WebSites.Models.BackupSchedule" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt;" />
        <Parameter Name="backupRequestType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="cf2de-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="cf2de-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="cf2de-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="cf2de-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="cf2de-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="cf2de-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="cf2de-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="cf2de-106">Resource type.</span></span></param>
        <param name="backupRequestName"><span data-ttu-id="cf2de-107">バックアップの名前です。</span><span class="sxs-lookup"><span data-stu-id="cf2de-107">Name of the backup.</span></span></param>
        <param name="enabled"><span data-ttu-id="cf2de-108">バックアップ スケジュールが有効になっている場合は true (含める必要がある場合)、バックアップのスケジュールを無効にする場合は false。</span><span class="sxs-lookup"><span data-stu-id="cf2de-108">True if the backup schedule is enabled (must be included in that case), false if the backup schedule should be disabled.</span></span></param>
        <param name="storageAccountUrl"><span data-ttu-id="cf2de-109">コンテナーの SAS URL。</span><span class="sxs-lookup"><span data-stu-id="cf2de-109">SAS URL to the container.</span></span></param>
        <param name="backupSchedule"><span data-ttu-id="cf2de-110">定期的に実行される場合に、バックアップのスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="cf2de-110">Schedule for the backup if it is executed periodically.</span></span></param>
        <param name="databases"><span data-ttu-id="cf2de-111">バックアップに含まれているデータベース。</span><span class="sxs-lookup"><span data-stu-id="cf2de-111">Databases included in the backup.</span></span></param>
        <param name="backupRequestType"><span data-ttu-id="cf2de-112">バックアップの種類。</span><span class="sxs-lookup"><span data-stu-id="cf2de-112">Type of the backup.</span></span> <span data-ttu-id="cf2de-113">使用可能な値が含まれます: 'Default'、' Clone'、'再配置'、'Snapshot'</span><span class="sxs-lookup"><span data-stu-id="cf2de-113">Possible values include: 'Default', 'Clone', 'Relocation', 'Snapshot'</span></span></param>
        <summary>
            <span data-ttu-id="cf2de-114">BackupRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cf2de-114">Initializes a new instance of the BackupRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupRequestName">
      <MemberSignature Language="C#" Value="public string BackupRequestName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupRequestName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupRequest.BackupRequestName" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupRequestName As String" />
      <MemberSignature Language="F#" Value="member this.BackupRequestName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.BackupRequest.BackupRequestName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf2de-115">取得またはバックアップの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="cf2de-115">Gets or sets name of the backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupRequestType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; BackupRequestType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; BackupRequestType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupRequest.BackupRequestType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupRequestType As Nullable(Of BackupRestoreOperationType)" />
      <MemberSignature Language="F#" Value="member this.BackupRequestType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.BackupRequest.BackupRequestType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupRestoreOperationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf2de-116">取得またはバックアップの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="cf2de-116">Gets or sets type of the backup.</span></span> <span data-ttu-id="cf2de-117">使用可能な値が含まれます: 'Default'、' Clone'、'再配置'、'Snapshot'</span><span class="sxs-lookup"><span data-stu-id="cf2de-117">Possible values include: 'Default', 'Clone', 'Relocation', 'Snapshot'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.BackupSchedule BackupSchedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.BackupSchedule BackupSchedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupRequest.BackupSchedule" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSchedule As BackupSchedule" />
      <MemberSignature Language="F#" Value="member this.BackupSchedule : Microsoft.Azure.Management.WebSites.Models.BackupSchedule with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.BackupRequest.BackupSchedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupSchedule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.BackupSchedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf2de-118">取得または定期的に実行される場合に、バックアップのスケジュールを設定します。</span><span class="sxs-lookup"><span data-stu-id="cf2de-118">Gets or sets schedule for the backup if it is executed periodically.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; Databases { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupRequest.Databases" />
      <MemberSignature Language="VB.NET" Value="Public Property Databases As IList(Of DatabaseBackupSetting)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.BackupRequest.Databases" />
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
            <span data-ttu-id="cf2de-119">取得またはバックアップに含まれているデータベースを設定します。</span><span class="sxs-lookup"><span data-stu-id="cf2de-119">Gets or sets databases included in the backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupRequest.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.BackupRequest.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cf2de-120">取得または設定、バックアップ スケジュールが有効になっている場合は true (含める必要がある場合)、バックアップのスケジュールを無効にする場合は false。</span><span class="sxs-lookup"><span data-stu-id="cf2de-120">Gets or sets true if the backup schedule is enabled (must be included in that case), false if the backup schedule should be disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountUrl">
      <MemberSignature Language="C#" Value="public string StorageAccountUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupRequest.StorageAccountUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountUrl As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.BackupRequest.StorageAccountUrl" />
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
            <span data-ttu-id="cf2de-121">取得またはコンテナー SAS URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="cf2de-121">Gets or sets SAS URL to the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.BackupRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cf2de-122">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="cf2de-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cf2de-123">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf2de-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>