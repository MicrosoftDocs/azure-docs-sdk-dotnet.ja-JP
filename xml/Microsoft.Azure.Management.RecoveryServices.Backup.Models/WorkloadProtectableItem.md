<Type Name="WorkloadProtectableItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem">
  <TypeSignature Language="C#" Value="public class WorkloadProtectableItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WorkloadProtectableItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem" />
  <TypeSignature Language="VB.NET" Value="Public Class WorkloadProtectableItem" />
  <TypeSignature Language="F#" Value="type WorkloadProtectableItem = class" />
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
            <span data-ttu-id="51579-101">バックアップ項目の基本クラス。</span><span class="sxs-lookup"><span data-stu-id="51579-101">Base class for backup item.</span></span> <span data-ttu-id="51579-102">ワークロードに固有のバックアップ アイテムは、このクラスから派生します。</span><span class="sxs-lookup"><span data-stu-id="51579-102">Workload-specific backup items are derived from this class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkloadProtectableItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="51579-103">WorkloadProtectableItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="51579-103">Initializes a new instance of the WorkloadProtectableItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkloadProtectableItem (string backupManagementType = null, string friendlyName = null, string protectionState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string friendlyName, string protectionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional friendlyName As String = null, Optional protectionState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem : string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem (backupManagementType, friendlyName, protectionState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="protectionState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupManagementType"><span data-ttu-id="51579-104">項目をバックアップするバックアップ managemenent の型。</span><span class="sxs-lookup"><span data-stu-id="51579-104">Type of backup managemenent to backup an item.</span></span></param>
        <param name="friendlyName"><span data-ttu-id="51579-105">バックアップ項目の表示名。</span><span class="sxs-lookup"><span data-stu-id="51579-105">Friendly name of the backup item.</span></span></param>
        <param name="protectionState"><span data-ttu-id="51579-106">項目のバックアップの状態です。</span><span class="sxs-lookup"><span data-stu-id="51579-106">State of the back up item.</span></span> <span data-ttu-id="51579-107">使用可能な値が含まれます: '無効'、'NotProtected'、'を保護する'、'Protected'</span><span class="sxs-lookup"><span data-stu-id="51579-107">Possible values include: 'Invalid', 'NotProtected', 'Protecting', 'Protected'</span></span></param>
        <summary>
            <span data-ttu-id="51579-108">WorkloadProtectableItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="51579-108">Initializes a new instance of the WorkloadProtectableItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.BackupManagementType" />
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
            <span data-ttu-id="51579-109">取得または項目をバックアップするバックアップ managemenent の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="51579-109">Gets or sets type of backup managemenent to backup an item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.FriendlyName" />
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
            <span data-ttu-id="51579-110">取得またはバックアップ アイテムの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="51579-110">Gets or sets friendly name of the backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionState">
      <MemberSignature Language="C#" Value="public string ProtectionState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.ProtectionState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionState As String" />
      <MemberSignature Language="F#" Value="member this.ProtectionState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem.ProtectionState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectionState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="51579-111">取得または項目のバックアップの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="51579-111">Gets or sets state of the back up item.</span></span> <span data-ttu-id="51579-112">使用可能な値が含まれます: '無効'、'NotProtected'、'を保護する'、'Protected'</span><span class="sxs-lookup"><span data-stu-id="51579-112">Possible values include: 'Invalid', 'NotProtected', 'Protecting', 'Protected'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>