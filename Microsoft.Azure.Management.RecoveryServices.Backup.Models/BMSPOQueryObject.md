<Type Name="BMSPOQueryObject" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject">
  <TypeSignature Language="C#" Value="public class BMSPOQueryObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BMSPOQueryObject extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject" />
  <TypeSignature Language="VB.NET" Value="Public Class BMSPOQueryObject" />
  <TypeSignature Language="F#" Value="type BMSPOQueryObject = class" />
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
            <span data-ttu-id="2ca16-101">バックアップできるリスト項目をフィルターします。</span><span class="sxs-lookup"><span data-stu-id="2ca16-101">Filters to list items that can be backed up.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BMSPOQueryObject ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ca16-102">BMSPOQueryObject クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ca16-102">Initializes a new instance of the BMSPOQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BMSPOQueryObject (string backupManagementType = null, string status = null, string friendlyName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string status, string friendlyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional status As String = null, Optional friendlyName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject : string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject (backupManagementType, status, friendlyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="friendlyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupManagementType"><span data-ttu-id="2ca16-103">バックアップの管理の種類。</span><span class="sxs-lookup"><span data-stu-id="2ca16-103">Backup management type.</span></span> <span data-ttu-id="2ca16-104">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="2ca16-104">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="status"><span data-ttu-id="2ca16-105">バックアップの状態のクエリ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="2ca16-105">Backup status query parameter.</span></span></param>
        <param name="friendlyName"><span data-ttu-id="2ca16-106">フレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="2ca16-106">Friendly name.</span></span></param>
        <summary>
            <span data-ttu-id="2ca16-107">BMSPOQueryObject クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2ca16-107">Initializes a new instance of the BMSPOQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject.BackupManagementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupManagementType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca16-108">取得またはバックアップの管理の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ca16-108">Gets or sets backup management type.</span></span> <span data-ttu-id="2ca16-109">使用可能な値が含まれます: '無効'、'AzureIaasVM'、'MAB'、'DPM'、'AzureBackupServer'、'仮想'</span><span class="sxs-lookup"><span data-stu-id="2ca16-109">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ca16-110">取得またはフレンドリ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="2ca16-110">Gets or sets friendly name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSPOQueryObject.Status" />
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
            <span data-ttu-id="2ca16-111">取得またはバックアップの状態のクエリ パラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="2ca16-111">Gets or sets backup status query parameter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>