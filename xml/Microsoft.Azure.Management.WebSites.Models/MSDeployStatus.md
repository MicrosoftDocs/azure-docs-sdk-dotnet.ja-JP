<Type Name="MSDeployStatus" FullName="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus">
  <TypeSignature Language="C#" Value="public class MSDeployStatus : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MSDeployStatus extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class MSDeployStatus&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type MSDeployStatus = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4beaf-101">MSDeploy ARM 応答</span><span class="sxs-lookup"><span data-stu-id="4beaf-101">MSDeploy ARM response</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MSDeployStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4beaf-102">MSDeployStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4beaf-102">Initializes a new instance of the MSDeployStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MSDeployStatus (string id = null, string name = null, string kind = null, string type = null, string deployer = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt; provisioningState = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;bool&gt; complete = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string deployer, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;bool&gt; complete) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional deployer As String = null, Optional provisioningState As Nullable(Of MSDeployProvisioningState) = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional complete As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.MSDeployStatus : string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.MSDeployStatus" Usage="new Microsoft.Azure.Management.WebSites.Models.MSDeployStatus (id, name, kind, type, deployer, provisioningState, startTime, endTime, complete)" />
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
        <Parameter Name="deployer" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="complete" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="4beaf-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="4beaf-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="4beaf-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="4beaf-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="4beaf-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="4beaf-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="4beaf-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="4beaf-106">Resource type.</span></span></param>
        <param name="deployer"><span data-ttu-id="4beaf-107">配置するユーザーのユーザー名</span><span class="sxs-lookup"><span data-stu-id="4beaf-107">Username of deployer</span></span></param>
        <param name="provisioningState"><span data-ttu-id="4beaf-108">プロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="4beaf-108">Provisioning state.</span></span> <span data-ttu-id="4beaf-109">使用可能な値が含まれます: '受け入れられたら'、'実行中'、'成功'、'失敗'、'キャンセル'</span><span class="sxs-lookup"><span data-stu-id="4beaf-109">Possible values include: 'accepted', 'running', 'succeeded', 'failed', 'canceled'</span></span></param>
        <param name="startTime"><span data-ttu-id="4beaf-110">デプロイ操作の開始時刻</span><span class="sxs-lookup"><span data-stu-id="4beaf-110">Start time of deploy operation</span></span></param>
        <param name="endTime"><span data-ttu-id="4beaf-111">デプロイ操作の時間の終了時刻</span><span class="sxs-lookup"><span data-stu-id="4beaf-111">End time of deploy operation</span></span></param>
        <param name="complete"><span data-ttu-id="4beaf-112">展開の操作が完了したかどうか</span><span class="sxs-lookup"><span data-stu-id="4beaf-112">Whether the deployment operation has completed</span></span></param>
        <summary>
            <span data-ttu-id="4beaf-113">MSDeployStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4beaf-113">Initializes a new instance of the MSDeployStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Complete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Complete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.Complete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Complete As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Complete : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.Complete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.complete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4beaf-114">展開の操作が完了したかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="4beaf-114">Gets whether the deployment operation has completed</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deployer">
      <MemberSignature Language="C#" Value="public string Deployer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Deployer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.Deployer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Deployer As String" />
      <MemberSignature Language="F#" Value="member this.Deployer : string" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.Deployer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deployer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4beaf-115">配置するユーザーのユーザー名を取得します。</span><span class="sxs-lookup"><span data-stu-id="4beaf-115">Gets username of deployer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4beaf-116">デプロイ操作の取得時間の終了時刻</span><span class="sxs-lookup"><span data-stu-id="4beaf-116">Gets end time of deploy operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of MSDeployProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4beaf-117">プロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="4beaf-117">Gets provisioning state.</span></span> <span data-ttu-id="4beaf-118">使用可能な値が含まれます: '受け入れられたら'、'実行中'、'成功'、'失敗'、'キャンセル'</span><span class="sxs-lookup"><span data-stu-id="4beaf-118">Possible values include: 'accepted', 'running', 'succeeded', 'failed', 'canceled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployStatus.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4beaf-119">操作の展開の開始時刻を取得</span><span class="sxs-lookup"><span data-stu-id="4beaf-119">Gets start time of deploy operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>