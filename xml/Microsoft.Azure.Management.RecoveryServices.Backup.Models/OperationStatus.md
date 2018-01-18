<Type Name="OperationStatus" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus">
  <TypeSignature Language="C#" Value="public class OperationStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationStatus" />
  <TypeSignature Language="F#" Value="type OperationStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="369d4-101">操作の状態。</span><span class="sxs-lookup"><span data-stu-id="369d4-101">Operation status.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="369d4-102">OperationStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="369d4-102">Initializes a new instance of the OperationStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationStatus (string id = null, string name = null, string status = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError error = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError error, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.#ctor(System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError,Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional status As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional error As OperationStatusError = null, Optional properties As OperationStatusExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus : string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError * Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus (id, name, status, startTime, endTime, error, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="369d4-103">操作の ID。</span><span class="sxs-lookup"><span data-stu-id="369d4-103">ID of the operation.</span></span></param>
        <param name="name"><span data-ttu-id="369d4-104">操作の名前。</span><span class="sxs-lookup"><span data-stu-id="369d4-104">Name of the operation.</span></span></param>
        <param name="status"><span data-ttu-id="369d4-105">操作の状態。</span><span class="sxs-lookup"><span data-stu-id="369d4-105">Operation status.</span></span> <span data-ttu-id="369d4-106">使用可能な値が含まれます: '無効'、'処理中'、'成功'、'失敗'、'キャンセル'</span><span class="sxs-lookup"><span data-stu-id="369d4-106">Possible values include: 'Invalid', 'InProgress', 'Succeeded', 'Failed', 'Canceled'</span></span></param>
        <param name="startTime"><span data-ttu-id="369d4-107">操作の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="369d4-107">Operation start time.</span></span> <span data-ttu-id="369d4-108">形式: iso-8601 です。</span><span class="sxs-lookup"><span data-stu-id="369d4-108">Format: ISO-8601.</span></span></param>
        <param name="endTime"><span data-ttu-id="369d4-109">操作の終了時刻です。</span><span class="sxs-lookup"><span data-stu-id="369d4-109">Operation end time.</span></span> <span data-ttu-id="369d4-110">形式: iso-8601 です。</span><span class="sxs-lookup"><span data-stu-id="369d4-110">Format: ISO-8601.</span></span></param>
        <param name="error"><span data-ttu-id="369d4-111">この操作に関連するエラー情報。</span><span class="sxs-lookup"><span data-stu-id="369d4-111">Error information related to this operation.</span></span></param>
        <param name="properties"><span data-ttu-id="369d4-112">この操作に関連付けられている追加の情報です。</span><span class="sxs-lookup"><span data-stu-id="369d4-112">Additional information associated with this operation.</span></span></param>
        <summary>
            <span data-ttu-id="369d4-113">OperationStatus クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="369d4-113">Initializes a new instance of the OperationStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="369d4-114">取得または操作の終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="369d4-114">Gets or sets operation end time.</span></span> <span data-ttu-id="369d4-115">形式: iso-8601 です。</span><span class="sxs-lookup"><span data-stu-id="369d4-115">Format: ISO-8601.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As OperationStatusError" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="369d4-116">取得またはこの操作に関連するエラー情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="369d4-116">Gets or sets error information related to this operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="369d4-117">取得または操作の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="369d4-117">Gets or sets ID of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="369d4-118">取得または操作の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="369d4-118">Gets or sets name of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As OperationStatusExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="369d4-119">取得またはこの操作に関連付けられている追加の情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="369d4-119">Gets or sets additional information associated with this operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="369d4-120">取得または操作の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="369d4-120">Gets or sets operation start time.</span></span> <span data-ttu-id="369d4-121">形式: iso-8601 です。</span><span class="sxs-lookup"><span data-stu-id="369d4-121">Format: ISO-8601.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="369d4-122">取得または操作の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="369d4-122">Gets or sets operation status.</span></span> <span data-ttu-id="369d4-123">使用可能な値が含まれます: '無効'、'処理中'、'成功'、'失敗'、'キャンセル'</span><span class="sxs-lookup"><span data-stu-id="369d4-123">Possible values include: 'Invalid', 'InProgress', 'Succeeded', 'Failed', 'Canceled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>