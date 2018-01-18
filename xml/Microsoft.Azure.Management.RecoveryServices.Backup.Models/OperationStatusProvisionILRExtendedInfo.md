<Type Name="OperationStatusProvisionILRExtendedInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusProvisionILRExtendedInfo">
  <TypeSignature Language="C#" Value="public class OperationStatusProvisionILRExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationStatusProvisionILRExtendedInfo extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusProvisionILRExtendedInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationStatusProvisionILRExtendedInfo&#xA;Inherits OperationStatusExtendedInfo" />
  <TypeSignature Language="F#" Value="type OperationStatusProvisionILRExtendedInfo = class&#xA;    inherit OperationStatusExtendedInfo" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusExtendedInfo</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="56900-101">操作の状態は、ILR プロビジョニング操作の情報を拡張します。</span><span class="sxs-lookup"><span data-stu-id="56900-101">Operation status extended info for ILR provision action.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationStatusProvisionILRExtendedInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusProvisionILRExtendedInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="56900-102">OperationStatusProvisionILRExtendedInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="56900-102">Initializes a new instance of the OperationStatusProvisionILRExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationStatusProvisionILRExtendedInfo (Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget recoveryTarget = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget recoveryTarget) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusProvisionILRExtendedInfo.#ctor(Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional recoveryTarget As InstantItemRecoveryTarget = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusProvisionILRExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusProvisionILRExtendedInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusProvisionILRExtendedInfo recoveryTarget" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recoveryTarget" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget" />
      </Parameters>
      <Docs>
        <param name="recoveryTarget"><span data-ttu-id="56900-103">対象のファイルの詳細/フォルダーを復元します。</span><span class="sxs-lookup"><span data-stu-id="56900-103">Target details for file / folder restore.</span></span></param>
        <summary>
            <span data-ttu-id="56900-104">OperationStatusProvisionILRExtendedInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="56900-104">Initializes a new instance of the OperationStatusProvisionILRExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryTarget">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget RecoveryTarget { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget RecoveryTarget" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusProvisionILRExtendedInfo.RecoveryTarget" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryTarget As InstantItemRecoveryTarget" />
      <MemberSignature Language="F#" Value="member this.RecoveryTarget : Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatusProvisionILRExtendedInfo.RecoveryTarget" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryTarget")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.InstantItemRecoveryTarget</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="56900-105">取得またはファイルのターゲットの詳細を設定/フォルダーを復元します。</span><span class="sxs-lookup"><span data-stu-id="56900-105">Gets or sets target details for file / folder restore.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>