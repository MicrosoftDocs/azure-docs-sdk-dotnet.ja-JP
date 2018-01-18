<Type Name="VirtualDiskRequest" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest">
  <TypeSignature Language="C#" Value="public class VirtualDiskRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualDiskRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualDiskRequest" />
  <TypeSignature Language="F#" Value="type VirtualDiskRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4651e-101">仮想ディスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="4651e-101">Info about the virtual disk</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualDiskRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4651e-102">VirtualDiskRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4651e-102">Initializes a new instance of the VirtualDiskRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.AccessType AccessType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.AccessType AccessType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.AccessType" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessType As AccessType" />
      <MemberSignature Language="F#" Value="member this.AccessType : Microsoft.WindowsAzure.Management.StorSimple.Models.AccessType with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.AccessType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.AccessType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-103">必須。</span><span class="sxs-lookup"><span data-stu-id="4651e-103">Required.</span></span> <span data-ttu-id="4651e-104">AccessType</span><span class="sxs-lookup"><span data-stu-id="4651e-104">AccessType</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcrIdList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AcrIdList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AcrIdList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.AcrIdList" />
      <MemberSignature Language="VB.NET" Value="Public Property AcrIdList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AcrIdList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.AcrIdList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4651e-105">Optional.</span></span> <span data-ttu-id="4651e-106">参照先の ACR Id の一覧</span><span class="sxs-lookup"><span data-stu-id="4651e-106">List of referenced ACR Ids</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcrList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; AcrList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; AcrList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.AcrList" />
      <MemberSignature Language="VB.NET" Value="Public Property AcrList As IList(Of AccessControlRecord)" />
      <MemberSignature Language="F#" Value="member this.AcrList : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.AcrList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-107">必須。</span><span class="sxs-lookup"><span data-stu-id="4651e-107">Required.</span></span> <span data-ttu-id="4651e-108">アクセス制御レコードの一覧</span><span class="sxs-lookup"><span data-stu-id="4651e-108">List of access control record</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.AppType AppType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.AppType AppType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.AppType" />
      <MemberSignature Language="VB.NET" Value="Public Property AppType As AppType" />
      <MemberSignature Language="F#" Value="member this.AppType : Microsoft.WindowsAzure.Management.StorSimple.Models.AppType with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.AppType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.AppType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-109">必須。</span><span class="sxs-lookup"><span data-stu-id="4651e-109">Required.</span></span> <span data-ttu-id="4651e-110">プライマリまたはアーカイブ済みのボリューム。</span><span class="sxs-lookup"><span data-stu-id="4651e-110">Primary or Archived volume.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataContainer">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainer DataContainer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainer DataContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.DataContainer" />
      <MemberSignature Language="VB.NET" Value="Public Property DataContainer As DataContainer" />
      <MemberSignature Language="F#" Value="member this.DataContainer : Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainer with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.DataContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-111">必須。</span><span class="sxs-lookup"><span data-stu-id="4651e-111">Required.</span></span> <span data-ttu-id="4651e-112">対応するデータ コンテナー</span><span class="sxs-lookup"><span data-stu-id="4651e-112">Corresponding Data Container</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataContainerId">
      <MemberSignature Language="C#" Value="public string DataContainerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.DataContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property DataContainerId As String" />
      <MemberSignature Language="F#" Value="member this.DataContainerId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.DataContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4651e-113">Optional.</span></span> <span data-ttu-id="4651e-114">ディスクのデータ コンテナーの Id</span><span class="sxs-lookup"><span data-stu-id="4651e-114">Data Container Id for the disk</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public string InstanceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InstanceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.InstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-115">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4651e-115">Optional.</span></span> <span data-ttu-id="4651e-116">インスタンス識別子</span><span class="sxs-lookup"><span data-stu-id="4651e-116">The instance identifier</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalInstanceId">
      <MemberSignature Language="C#" Value="public string InternalInstanceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalInstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.InternalInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalInstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InternalInstanceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.InternalInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4651e-117">Optional.</span></span> <span data-ttu-id="4651e-118">仮想ディスクの内部のインスタンス Id</span><span class="sxs-lookup"><span data-stu-id="4651e-118">Internal Instance Id for the virtual disk</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBackupEnabled">
      <MemberSignature Language="C#" Value="public bool IsBackupEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBackupEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.IsBackupEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsBackupEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBackupEnabled : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.IsBackupEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-119">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4651e-119">Optional.</span></span> <span data-ttu-id="4651e-120">True の場合は、この仮想ディスクは、バックアップ ポリシーの一部</span><span class="sxs-lookup"><span data-stu-id="4651e-120">True if this virtual disk is part of any backup policy</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultBackupEnabled">
      <MemberSignature Language="C#" Value="public bool IsDefaultBackupEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDefaultBackupEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.IsDefaultBackupEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDefaultBackupEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDefaultBackupEnabled : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.IsDefaultBackupEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-121">必須。</span><span class="sxs-lookup"><span data-stu-id="4651e-121">Required.</span></span> <span data-ttu-id="4651e-122">既定のバックアップが有効になっている場合は true。</span><span class="sxs-lookup"><span data-stu-id="4651e-122">True if default backup is enabled</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsMonitoringEnabled">
      <MemberSignature Language="C#" Value="public bool IsMonitoringEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsMonitoringEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.IsMonitoringEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsMonitoringEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsMonitoringEnabled : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.IsMonitoringEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-123">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4651e-123">Optional.</span></span> <span data-ttu-id="4651e-124">仮想ディスクの監視が有効になっている場合は true。</span><span class="sxs-lookup"><span data-stu-id="4651e-124">True if monitoring is enabled for the virtual disk</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-125">必須。</span><span class="sxs-lookup"><span data-stu-id="4651e-125">Required.</span></span> <span data-ttu-id="4651e-126">エンティティの名前</span><span class="sxs-lookup"><span data-stu-id="4651e-126">The name of the entity</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Online">
      <MemberSignature Language="C#" Value="public bool Online { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Online" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.Online" />
      <MemberSignature Language="VB.NET" Value="Public Property Online As Boolean" />
      <MemberSignature Language="F#" Value="member this.Online : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.Online" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-127">必須。</span><span class="sxs-lookup"><span data-stu-id="4651e-127">Required.</span></span> <span data-ttu-id="4651e-128">仮想ディスクがオンラインの場合は true。</span><span class="sxs-lookup"><span data-stu-id="4651e-128">True if the virtual disk is online</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationInProgress">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress OperationInProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress OperationInProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.OperationInProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationInProgress As OperationInProgress" />
      <MemberSignature Language="F#" Value="member this.OperationInProgress : Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.OperationInProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.OperationInProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-129">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4651e-129">Optional.</span></span> <span data-ttu-id="4651e-130">実行中を操作します。</span><span class="sxs-lookup"><span data-stu-id="4651e-130">Is operation in progress</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64 with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-131">必須。</span><span class="sxs-lookup"><span data-stu-id="4651e-131">Required.</span></span> <span data-ttu-id="4651e-132">仮想ディスクのサイズ</span><span class="sxs-lookup"><span data-stu-id="4651e-132">Size of Virtual Disk</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VSN">
      <MemberSignature Language="C#" Value="public string VSN { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VSN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.VSN" />
      <MemberSignature Language="VB.NET" Value="Public Property VSN As String" />
      <MemberSignature Language="F#" Value="member this.VSN : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDiskRequest.VSN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4651e-133">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4651e-133">Optional.</span></span> <span data-ttu-id="4651e-134">仮想ディスクの仮想のシリアル番号</span><span class="sxs-lookup"><span data-stu-id="4651e-134">Virtual Serial Number of the virtual disk</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>