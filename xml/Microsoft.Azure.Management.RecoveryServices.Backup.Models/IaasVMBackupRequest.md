<Type Name="IaasVMBackupRequest" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMBackupRequest">
  <TypeSignature Language="C#" Value="public class IaasVMBackupRequest : Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IaasVMBackupRequest extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMBackupRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class IaasVMBackupRequest&#xA;Inherits BackupRequest" />
  <TypeSignature Language="F#" Value="type IaasVMBackupRequest = class&#xA;    inherit BackupRequest" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupRequest</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="03d7f-101">IaaS VM のワークロードに固有のバックアップの要求です。</span><span class="sxs-lookup"><span data-stu-id="03d7f-101">IaaS VM workload-specific backup request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaasVMBackupRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMBackupRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="03d7f-102">IaasVMBackupRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="03d7f-102">Initializes a new instance of the IaasVMBackupRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaasVMBackupRequest (Nullable&lt;DateTime&gt; recoveryPointExpiryTimeInUTC = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; recoveryPointExpiryTimeInUTC) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMBackupRequest.#ctor(System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional recoveryPointExpiryTimeInUTC As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMBackupRequest : Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMBackupRequest" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMBackupRequest recoveryPointExpiryTimeInUTC" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recoveryPointExpiryTimeInUTC" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="recoveryPointExpiryTimeInUTC"><span data-ttu-id="03d7f-103">バックアップ コピーは、指定された時間 (UTC) の後に切れます。</span><span class="sxs-lookup"><span data-stu-id="03d7f-103">Backup copy will expire after the time specified (UTC).</span></span></param>
        <summary>
            <span data-ttu-id="03d7f-104">IaasVMBackupRequest クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="03d7f-104">Initializes a new instance of the IaasVMBackupRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointExpiryTimeInUTC">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RecoveryPointExpiryTimeInUTC { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RecoveryPointExpiryTimeInUTC" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMBackupRequest.RecoveryPointExpiryTimeInUTC" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointExpiryTimeInUTC As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointExpiryTimeInUTC : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMBackupRequest.RecoveryPointExpiryTimeInUTC" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointExpiryTimeInUTC")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="03d7f-105">時間の後にバックアップ コピーの有効期限を取得または設定 (UTC) を指定します。</span><span class="sxs-lookup"><span data-stu-id="03d7f-105">Gets or sets backup copy will expire after the time specified (UTC).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>