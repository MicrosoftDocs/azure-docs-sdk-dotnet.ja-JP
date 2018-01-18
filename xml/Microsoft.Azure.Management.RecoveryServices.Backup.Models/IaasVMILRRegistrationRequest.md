<Type Name="IaasVMILRRegistrationRequest" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest">
  <TypeSignature Language="C#" Value="public class IaasVMILRRegistrationRequest : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IaasVMILRRegistrationRequest extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class IaasVMILRRegistrationRequest&#xA;Inherits ILRRequest" />
  <TypeSignature Language="F#" Value="type IaasVMILRRegistrationRequest = class&#xA;    inherit ILRRequest" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8cf84-101">IaaS VM のバックアップ コピーからファイルとフォルダーを復元します。</span><span class="sxs-lookup"><span data-stu-id="8cf84-101">Restore files/folders from a backup copy of IaaS VM.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaasVMILRRegistrationRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8cf84-102">IaasVMILRRegistrationRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8cf84-102">Initializes a new instance of the IaasVMILRRegistrationRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaasVMILRRegistrationRequest (string recoveryPointId = null, string virtualMachineId = null, string initiatorName = null, Nullable&lt;bool&gt; renewExistingRegistration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string recoveryPointId, string virtualMachineId, string initiatorName, valuetype System.Nullable`1&lt;bool&gt; renewExistingRegistration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest.#ctor(System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional recoveryPointId As String = null, Optional virtualMachineId As String = null, Optional initiatorName As String = null, Optional renewExistingRegistration As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest : string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest (recoveryPointId, virtualMachineId, initiatorName, renewExistingRegistration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="virtualMachineId" Type="System.String" />
        <Parameter Name="initiatorName" Type="System.String" />
        <Parameter Name="renewExistingRegistration" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="recoveryPointId"><span data-ttu-id="8cf84-103">IaaS VM のバックアップ コピーからファイルとフォルダーを復元する必要の ID です。</span><span class="sxs-lookup"><span data-stu-id="8cf84-103">ID of the IaaS VM backup copy from where the files/folders have to be restored.</span></span></param>
        <param name="virtualMachineId"><span data-ttu-id="8cf84-104">完全修飾の ARM ID の仮想マシンがファイル/フォルダーを復元する必要です。</span><span class="sxs-lookup"><span data-stu-id="8cf84-104">Fully qualified ARM ID of the virtual machine whose the files / folders have to be restored.</span></span></param>
        <param name="initiatorName"><span data-ttu-id="8cf84-105">iSCSI イニシエーターの名前です。</span><span class="sxs-lookup"><span data-stu-id="8cf84-105">iSCSI initiator name.</span></span></param>
        <param name="renewExistingRegistration"><span data-ttu-id="8cf84-106">既存の iSCSI サーバーとの登録を更新するかどうか。</span><span class="sxs-lookup"><span data-stu-id="8cf84-106">Whether to renew existing registration with the iSCSI server.</span></span></param>
        <summary>
            <span data-ttu-id="8cf84-107">IaasVMILRRegistrationRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8cf84-107">Initializes a new instance of the IaasVMILRRegistrationRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitiatorName">
      <MemberSignature Language="C#" Value="public string InitiatorName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InitiatorName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest.InitiatorName" />
      <MemberSignature Language="VB.NET" Value="Public Property InitiatorName As String" />
      <MemberSignature Language="F#" Value="member this.InitiatorName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest.InitiatorName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="initiatorName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cf84-108">取得または iSCSI イニシエーター名を設定します。</span><span class="sxs-lookup"><span data-stu-id="8cf84-108">Gets or sets iSCSI initiator name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointId">
      <MemberSignature Language="C#" Value="public string RecoveryPointId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryPointId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest.RecoveryPointId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest.RecoveryPointId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cf84-109">取得またはファイル/フォルダーを復元する必要から IaaS VM のバックアップ コピーの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="8cf84-109">Gets or sets ID of the IaaS VM backup copy from where the files/folders have to be restored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewExistingRegistration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RenewExistingRegistration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RenewExistingRegistration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest.RenewExistingRegistration" />
      <MemberSignature Language="VB.NET" Value="Public Property RenewExistingRegistration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RenewExistingRegistration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest.RenewExistingRegistration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="renewExistingRegistration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cf84-110">取得または iSCSI サーバーとの既存の登録を更新するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="8cf84-110">Gets or sets whether to renew existing registration with the iSCSI server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineId">
      <MemberSignature Language="C#" Value="public string VirtualMachineId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest.VirtualMachineId" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMILRRegistrationRequest.VirtualMachineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8cf84-111">取得または設定 ARM ID の仮想マシンのファイル/フォルダーを復元する必要は完全修飾します。</span><span class="sxs-lookup"><span data-stu-id="8cf84-111">Gets or sets fully qualified ARM ID of the virtual machine whose the files / folders have to be restored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>