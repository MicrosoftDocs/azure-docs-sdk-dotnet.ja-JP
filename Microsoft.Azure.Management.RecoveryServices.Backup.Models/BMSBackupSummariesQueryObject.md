<Type Name="BMSBackupSummariesQueryObject" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject">
  <TypeSignature Language="C#" Value="public class BMSBackupSummariesQueryObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BMSBackupSummariesQueryObject extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject" />
  <TypeSignature Language="VB.NET" Value="Public Class BMSBackupSummariesQueryObject" />
  <TypeSignature Language="F#" Value="type BMSBackupSummariesQueryObject = class" />
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
            <span data-ttu-id="ff1f7-101">バックアップの概要をフェッチするパラメーターのクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="ff1f7-101">Query parameters to fetch backup summaries.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BMSBackupSummariesQueryObject ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ff1f7-102">BMSBackupSummariesQueryObject クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ff1f7-102">Initializes a new instance of the BMSBackupSummariesQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BMSBackupSummariesQueryObject (string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject : string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject type" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="ff1f7-103">このコンテナーのバックアップの管理の種類。</span><span class="sxs-lookup"><span data-stu-id="ff1f7-103">Backup management type for this container.</span></span>
            <span data-ttu-id="ff1f7-104">使用可能な値が含まれます: '無効'、'BackupProtectedItemCountSummary'、'BackupProtectionContainerCountSummary'</span><span class="sxs-lookup"><span data-stu-id="ff1f7-104">Possible values include: 'Invalid', 'BackupProtectedItemCountSummary', 'BackupProtectionContainerCountSummary'</span></span></param>
        <summary>
            <span data-ttu-id="ff1f7-105">BMSBackupSummariesQueryObject クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ff1f7-105">Initializes a new instance of the BMSBackupSummariesQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSBackupSummariesQueryObject.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff1f7-106">取得または、このコンテナーのバックアップの管理の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="ff1f7-106">Gets or sets backup management type for this container.</span></span> <span data-ttu-id="ff1f7-107">使用可能な値が含まれます: '無効'、'BackupProtectedItemCountSummary'、'BackupProtectionContainerCountSummary'</span><span class="sxs-lookup"><span data-stu-id="ff1f7-107">Possible values include: 'Invalid', 'BackupProtectedItemCountSummary', 'BackupProtectionContainerCountSummary'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>