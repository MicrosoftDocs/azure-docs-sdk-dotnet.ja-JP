<Type Name="DeploymentOperationProperties" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties">
  <TypeSignature Language="C#" Value="public class DeploymentOperationProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentOperationProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentOperationProperties" />
  <TypeSignature Language="F#" Value="type DeploymentOperationProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="287a1-101">デプロイ操作のプロパティです。</span><span class="sxs-lookup"><span data-stu-id="287a1-101">Deployment operation properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentOperationProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="287a1-102">DeploymentOperationProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="287a1-102">Initializes a new instance of the DeploymentOperationProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentOperationProperties (string provisioningState = null, Nullable&lt;DateTime&gt; timestamp = null, string serviceRequestId = null, string statusCode = null, object statusMessage = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource targetResource = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage request = null, Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage response = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timestamp, string serviceRequestId, string statusCode, object statusMessage, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource targetResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage request, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.#ctor(System.String,System.Nullable{System.DateTime},System.String,System.String,System.Object,Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource,Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage,Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties : string * Nullable&lt;DateTime&gt; * string * string * obj * Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource * Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage * Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties (provisioningState, timestamp, serviceRequestId, statusCode, statusMessage, targetResource, request, response)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="timestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="serviceRequestId" Type="System.String" />
        <Parameter Name="statusCode" Type="System.String" />
        <Parameter Name="statusMessage" Type="System.Object" />
        <Parameter Name="targetResource" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource" />
        <Parameter Name="request" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage" />
        <Parameter Name="response" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage" />
      </Parameters>
      <Docs>
        <param name="provisioningState"><span data-ttu-id="287a1-103">プロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="287a1-103">The state of the provisioning.</span></span></param>
        <param name="timestamp"><span data-ttu-id="287a1-104">日付と操作の時刻。</span><span class="sxs-lookup"><span data-stu-id="287a1-104">The date and time of the operation.</span></span></param>
        <param name="serviceRequestId"><span data-ttu-id="287a1-105">デプロイ操作のサービス要求 id。</span><span class="sxs-lookup"><span data-stu-id="287a1-105">Deployment operation service request id.</span></span></param>
        <param name="statusCode"><span data-ttu-id="287a1-106">操作のステータス コード。</span><span class="sxs-lookup"><span data-stu-id="287a1-106">Operation status code.</span></span></param>
        <param name="statusMessage"><span data-ttu-id="287a1-107">操作のステータス メッセージ。</span><span class="sxs-lookup"><span data-stu-id="287a1-107">Operation status message.</span></span></param>
        <param name="targetResource"><span data-ttu-id="287a1-108">ターゲット リソースです。</span><span class="sxs-lookup"><span data-stu-id="287a1-108">The target resource.</span></span></param>
        <param name="request"><span data-ttu-id="287a1-109">HTTP 要求メッセージ。</span><span class="sxs-lookup"><span data-stu-id="287a1-109">The HTTP request message.</span></span></param>
        <param name="response"><span data-ttu-id="287a1-110">HTTP 応答メッセージ。</span><span class="sxs-lookup"><span data-stu-id="287a1-110">The HTTP response message.</span></span></param>
        <summary>
            <span data-ttu-id="287a1-111">DeploymentOperationProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="287a1-111">Initializes a new instance of the DeploymentOperationProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="287a1-112">取得またはプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="287a1-112">Gets or sets the state of the provisioning.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage Request { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Request" />
      <MemberSignature Language="VB.NET" Value="Public Property Request As HttpMessage" />
      <MemberSignature Language="F#" Value="member this.Request : Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="request")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="287a1-113">取得または HTTP 要求メッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="287a1-113">Gets or sets the HTTP request message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage Response { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Response" />
      <MemberSignature Language="VB.NET" Value="Public Property Response As HttpMessage" />
      <MemberSignature Language="F#" Value="member this.Response : Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="response")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.HttpMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="287a1-114">取得または HTTP 応答メッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="287a1-114">Gets or sets the HTTP response message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceRequestId">
      <MemberSignature Language="C#" Value="public string ServiceRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.ServiceRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceRequestId As String" />
      <MemberSignature Language="F#" Value="member this.ServiceRequestId : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.ServiceRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceRequestId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="287a1-115">取得またはデプロイ操作のサービス要求 id を設定します。</span><span class="sxs-lookup"><span data-stu-id="287a1-115">Gets or sets deployment operation service request id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public string StatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As String" />
      <MemberSignature Language="F#" Value="member this.StatusCode : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="287a1-116">取得または操作の状態コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="287a1-116">Gets or sets operation status code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusMessage">
      <MemberSignature Language="C#" Value="public object StatusMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object StatusMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.StatusMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusMessage As Object" />
      <MemberSignature Language="F#" Value="member this.StatusMessage : obj with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.StatusMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="287a1-117">取得または設定操作のステータス メッセージ。</span><span class="sxs-lookup"><span data-stu-id="287a1-117">Gets or sets operation status message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource TargetResource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource TargetResource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.TargetResource" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResource As TargetResource" />
      <MemberSignature Language="F#" Value="member this.TargetResource : Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.TargetResource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.TargetResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="287a1-118">取得またはターゲット リソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="287a1-118">Gets or sets the target resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Timestamp : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.DeploymentOperationProperties.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="287a1-119">取得または操作の日時を設定します。</span><span class="sxs-lookup"><span data-stu-id="287a1-119">Gets or sets the date and time of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>