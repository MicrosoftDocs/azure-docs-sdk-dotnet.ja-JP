<Type Name="DataLakeAnalyticsAccountPropertiesBasic" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsAccountPropertiesBasic" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsAccountPropertiesBasic extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsAccountPropertiesBasic" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsAccountPropertiesBasic = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1b1e5-101">基になる Data Lake Analytics アカウントに関連付けられている基本的な勘定科目特定のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-101">The basic account specific properties that are associated with an underlying Data Lake Analytics account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountPropertiesBasic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1b1e5-102">DataLakeAnalyticsAccountPropertiesBasic クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-102">Initializes a new instance of the DataLakeAnalyticsAccountPropertiesBasic class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountPropertiesBasic (Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;DateTime&gt; lastModifiedTime = null, string endpoint = null, Nullable&lt;Guid&gt; accountId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTime, string endpoint, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; accountId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.#ctor(System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provisioningState As Nullable(Of DataLakeAnalyticsAccountStatus) = null, Optional state As Nullable(Of DataLakeAnalyticsAccountState) = null, Optional creationTime As Nullable(Of DateTime) = null, Optional lastModifiedTime As Nullable(Of DateTime) = null, Optional endpoint As String = null, Optional accountId As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Guid&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic (provisioningState, state, creationTime, lastModifiedTime, endpoint, accountId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastModifiedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="accountId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="provisioningState"><span data-ttu-id="1b1e5-103">Data Lake Analytics アカウントのプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-103">the provisioning status of the Data Lake Analytics account.</span></span> <span data-ttu-id="1b1e5-104">使用可能な値が含まれます: '失敗'、'作成中'、'実行'、'成功'、'パッチ'、'一時停止中'、'再開'、'削除'、'Deleted'</span><span class="sxs-lookup"><span data-stu-id="1b1e5-104">Possible values include: 'Failed', 'Creating', 'Running', 'Succeeded', 'Patching', 'Suspending', 'Resuming', 'Deleting', 'Deleted'</span></span></param>
        <param name="state"><span data-ttu-id="1b1e5-105">Data Lake Analytics アカウントの状態。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-105">the state of the Data Lake Analytics account.</span></span>
            <span data-ttu-id="1b1e5-106">使用可能な値が含まれます: 'Active'、'中断'</span><span class="sxs-lookup"><span data-stu-id="1b1e5-106">Possible values include: 'Active', 'Suspended'</span></span></param>
        <param name="creationTime"><span data-ttu-id="1b1e5-107">アカウントの作成時。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-107">the account creation time.</span></span></param>
        <param name="lastModifiedTime"><span data-ttu-id="1b1e5-108">アカウントには、最終更新時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-108">the account last modified time.</span></span></param>
        <param name="endpoint"><span data-ttu-id="1b1e5-109">このアカウントの完全な CName エンドポイント。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-109">the full CName endpoint for this account.</span></span></param>
        <param name="accountId"><span data-ttu-id="1b1e5-110">この Data Lake Analytics アカウントに関連付けられている一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-110">The unique identifier associated with this Data Lake Analytics account.</span></span></param>
        <summary>
            <span data-ttu-id="1b1e5-111">DataLakeAnalyticsAccountPropertiesBasic クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-111">Initializes a new instance of the DataLakeAnalyticsAccountPropertiesBasic class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; AccountId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.AccountId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b1e5-112">この Data Lake Analytics アカウントに関連付けられている一意の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-112">Gets the unique identifier associated with this Data Lake Analytics account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b1e5-113">アカウントの作成時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-113">Gets the account creation time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b1e5-114">このアカウントに、完全な CName エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-114">Gets the full CName endpoint for this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastModifiedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b1e5-115">アカウントの最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-115">Gets the account last modified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of DataLakeAnalyticsAccountStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b1e5-116">Data Lake Analytics アカウントのプロビジョニング状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-116">Gets the provisioning status of the Data Lake Analytics account.</span></span>
            <span data-ttu-id="1b1e5-117">使用可能な値が含まれます: '失敗'、'作成中'、'実行'、'成功'、'パッチ'、'一時停止中'、'再開'、'削除'、'Deleted'</span><span class="sxs-lookup"><span data-stu-id="1b1e5-117">Possible values include: 'Failed', 'Creating', 'Running', 'Succeeded', 'Patching', 'Suspending', 'Resuming', 'Deleting', 'Deleted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of DataLakeAnalyticsAccountState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountPropertiesBasic.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b1e5-118">Data Lake Analytics アカウントの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b1e5-118">Gets the state of the Data Lake Analytics account.</span></span> <span data-ttu-id="1b1e5-119">使用可能な値が含まれます: 'Active'、'中断'</span><span class="sxs-lookup"><span data-stu-id="1b1e5-119">Possible values include: 'Active', 'Suspended'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>