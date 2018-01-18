<Type Name="MaintenanceRedeployStatus" FullName="Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus">
  <TypeSignature Language="C#" Value="public class MaintenanceRedeployStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MaintenanceRedeployStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class MaintenanceRedeployStatus" />
  <TypeSignature Language="F#" Value="type MaintenanceRedeployStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5e12a-101">メンテナンス操作の状態です。</span><span class="sxs-lookup"><span data-stu-id="5e12a-101">Maintenance Operation Status.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MaintenanceRedeployStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5e12a-102">MaintenanceRedeployStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5e12a-102">Initializes a new instance of the MaintenanceRedeployStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MaintenanceRedeployStatus (Nullable&lt;bool&gt; isCustomerInitiatedMaintenanceAllowed = null, Nullable&lt;DateTime&gt; preMaintenanceWindowStartTime = null, Nullable&lt;DateTime&gt; preMaintenanceWindowEndTime = null, Nullable&lt;DateTime&gt; maintenanceWindowStartTime = null, Nullable&lt;DateTime&gt; maintenanceWindowEndTime = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.MaintenanceOperationResultCodeTypes&gt; lastOperationResultCode = null, string lastOperationMessage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; isCustomerInitiatedMaintenanceAllowed, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; preMaintenanceWindowStartTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; preMaintenanceWindowEndTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; maintenanceWindowStartTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; maintenanceWindowEndTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.MaintenanceOperationResultCodeTypes&gt; lastOperationResultCode, string lastOperationMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.#ctor(System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Compute.Models.MaintenanceOperationResultCodeTypes},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional isCustomerInitiatedMaintenanceAllowed As Nullable(Of Boolean) = null, Optional preMaintenanceWindowStartTime As Nullable(Of DateTime) = null, Optional preMaintenanceWindowEndTime As Nullable(Of DateTime) = null, Optional maintenanceWindowStartTime As Nullable(Of DateTime) = null, Optional maintenanceWindowEndTime As Nullable(Of DateTime) = null, Optional lastOperationResultCode As Nullable(Of MaintenanceOperationResultCodeTypes) = null, Optional lastOperationMessage As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus : Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.MaintenanceOperationResultCodeTypes&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus" Usage="new Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus (isCustomerInitiatedMaintenanceAllowed, preMaintenanceWindowStartTime, preMaintenanceWindowEndTime, maintenanceWindowStartTime, maintenanceWindowEndTime, lastOperationResultCode, lastOperationMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isCustomerInitiatedMaintenanceAllowed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="preMaintenanceWindowStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="preMaintenanceWindowEndTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maintenanceWindowStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maintenanceWindowEndTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastOperationResultCode" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.MaintenanceOperationResultCodeTypes&gt;" />
        <Parameter Name="lastOperationMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="isCustomerInitiatedMaintenanceAllowed"><span data-ttu-id="5e12a-103">顧客がメンテナンスを実行できる場合は true。</span><span class="sxs-lookup"><span data-stu-id="5e12a-103">True, if customer is allowed to perform Maintenance.</span></span></param>
        <param name="preMaintenanceWindowStartTime"><span data-ttu-id="5e12a-104">前のメンテナンス期間の開始時刻。</span><span class="sxs-lookup"><span data-stu-id="5e12a-104">Start Time for the Pre Maintenance Window.</span></span></param>
        <param name="preMaintenanceWindowEndTime"><span data-ttu-id="5e12a-105">前のメンテナンス期間の終了時刻です。</span><span class="sxs-lookup"><span data-stu-id="5e12a-105">End Time for the Pre Maintenance Window.</span></span></param>
        <param name="maintenanceWindowStartTime"><span data-ttu-id="5e12a-106">メンテナンス期間の開始時刻。</span><span class="sxs-lookup"><span data-stu-id="5e12a-106">Start Time for the Maintenance Window.</span></span></param>
        <param name="maintenanceWindowEndTime"><span data-ttu-id="5e12a-107">メンテナンス期間の終了時刻です。</span><span class="sxs-lookup"><span data-stu-id="5e12a-107">End Time for the Maintenance Window.</span></span></param>
        <param name="lastOperationResultCode"><span data-ttu-id="5e12a-108">最後のメンテナンス操作の結果コード。</span><span class="sxs-lookup"><span data-stu-id="5e12a-108">The Last Maintenance Operation Result Code.</span></span> <span data-ttu-id="5e12a-109">使用可能な値が含まれます 'None'、'RetryLater'、'MaintenanceAborted'、'MaintenanceCompleted'。</span><span class="sxs-lookup"><span data-stu-id="5e12a-109">Possible values include: 'None', 'RetryLater', 'MaintenanceAborted', 'MaintenanceCompleted'</span></span></param>
        <param name="lastOperationMessage"><span data-ttu-id="5e12a-110">最後のメンテナンス操作に対して返されるメッセージ。</span><span class="sxs-lookup"><span data-stu-id="5e12a-110">Message returned for the last Maintenance Operation.</span></span></param>
        <summary>
            <span data-ttu-id="5e12a-111">MaintenanceRedeployStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5e12a-111">Initializes a new instance of the MaintenanceRedeployStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCustomerInitiatedMaintenanceAllowed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsCustomerInitiatedMaintenanceAllowed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsCustomerInitiatedMaintenanceAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.IsCustomerInitiatedMaintenanceAllowed" />
      <MemberSignature Language="VB.NET" Value="Public Property IsCustomerInitiatedMaintenanceAllowed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsCustomerInitiatedMaintenanceAllowed : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.IsCustomerInitiatedMaintenanceAllowed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isCustomerInitiatedMaintenanceAllowed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e12a-112">取得または顧客がメンテナンスを実行できる場合は true を設定します。</span><span class="sxs-lookup"><span data-stu-id="5e12a-112">Gets or sets true, if customer is allowed to perform Maintenance.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOperationMessage">
      <MemberSignature Language="C#" Value="public string LastOperationMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastOperationMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.LastOperationMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property LastOperationMessage As String" />
      <MemberSignature Language="F#" Value="member this.LastOperationMessage : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.LastOperationMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastOperationMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e12a-113">取得または最後のメンテナンス操作に対して返されるメッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="5e12a-113">Gets or sets message returned for the last Maintenance Operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOperationResultCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.MaintenanceOperationResultCodeTypes&gt; LastOperationResultCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.MaintenanceOperationResultCodeTypes&gt; LastOperationResultCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.LastOperationResultCode" />
      <MemberSignature Language="VB.NET" Value="Public Property LastOperationResultCode As Nullable(Of MaintenanceOperationResultCodeTypes)" />
      <MemberSignature Language="F#" Value="member this.LastOperationResultCode : Nullable&lt;Microsoft.Azure.Management.Compute.Models.MaintenanceOperationResultCodeTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.LastOperationResultCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastOperationResultCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.MaintenanceOperationResultCodeTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e12a-114">取得または最後のメンテナンス操作の結果コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="5e12a-114">Gets or sets the Last Maintenance Operation Result Code.</span></span> <span data-ttu-id="5e12a-115">使用可能な値が含まれます 'None'、'RetryLater'、'MaintenanceAborted'、'MaintenanceCompleted'。</span><span class="sxs-lookup"><span data-stu-id="5e12a-115">Possible values include: 'None', 'RetryLater', 'MaintenanceAborted', 'MaintenanceCompleted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaintenanceWindowEndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; MaintenanceWindowEndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; MaintenanceWindowEndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.MaintenanceWindowEndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaintenanceWindowEndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.MaintenanceWindowEndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.MaintenanceWindowEndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maintenanceWindowEndTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e12a-116">取得またはメンテナンス期間の終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="5e12a-116">Gets or sets end Time for the Maintenance Window.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaintenanceWindowStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; MaintenanceWindowStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; MaintenanceWindowStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.MaintenanceWindowStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaintenanceWindowStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.MaintenanceWindowStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.MaintenanceWindowStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maintenanceWindowStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e12a-117">取得または設定、メンテナンス期間の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="5e12a-117">Gets or sets start Time for the Maintenance Window.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreMaintenanceWindowEndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreMaintenanceWindowEndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreMaintenanceWindowEndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.PreMaintenanceWindowEndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreMaintenanceWindowEndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreMaintenanceWindowEndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.PreMaintenanceWindowEndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preMaintenanceWindowEndTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e12a-118">取得または前のメンテナンス期間の終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="5e12a-118">Gets or sets end Time for the Pre Maintenance Window.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreMaintenanceWindowStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreMaintenanceWindowStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreMaintenanceWindowStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.PreMaintenanceWindowStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreMaintenanceWindowStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreMaintenanceWindowStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.MaintenanceRedeployStatus.PreMaintenanceWindowStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preMaintenanceWindowStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5e12a-119">取得または設定の前のメンテナンス期間の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="5e12a-119">Gets or sets start Time for the Pre Maintenance Window.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>