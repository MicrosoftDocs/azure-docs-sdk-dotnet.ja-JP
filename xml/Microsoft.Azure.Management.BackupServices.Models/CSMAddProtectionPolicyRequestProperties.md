<Type Name="CSMAddProtectionPolicyRequestProperties" FullName="Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties">
  <TypeSignature Language="C#" Value="public class CSMAddProtectionPolicyRequestProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CSMAddProtectionPolicyRequestProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class CSMAddProtectionPolicyRequestProperties" />
  <TypeSignature Language="F#" Value="type CSMAddProtectionPolicyRequestProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d9241-101">CSMAddProtectionPolicyRequestProperties オブジェクトの定義。</span><span class="sxs-lookup"><span data-stu-id="d9241-101">The definition of a CSMAddProtectionPolicyRequestProperties object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CSMAddProtectionPolicyRequestProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d9241-102">CSMAddProtectionPolicyRequestProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d9241-102">Initializes a new instance of the CSMAddProtectionPolicyRequestProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule BackupSchedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule BackupSchedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties.BackupSchedule" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSchedule As CSMBackupSchedule" />
      <MemberSignature Language="F#" Value="member this.BackupSchedule : Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties.BackupSchedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9241-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d9241-103">Optional.</span></span> <span data-ttu-id="d9241-104">ProtectionPolicy のバックアップのスケジュール。</span><span class="sxs-lookup"><span data-stu-id="d9241-104">Backup Schedule of ProtectionPolicy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LtrRetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMLongTermRetentionPolicy LtrRetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMLongTermRetentionPolicy LtrRetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties.LtrRetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property LtrRetentionPolicy As CSMLongTermRetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.LtrRetentionPolicy : Microsoft.Azure.Management.BackupServices.Models.CSMLongTermRetentionPolicy with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties.LtrRetentionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMLongTermRetentionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9241-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d9241-105">Optional.</span></span> <span data-ttu-id="d9241-106">長期的な保有期間ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d9241-106">Long Term Retention Policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyName">
      <MemberSignature Language="C#" Value="public string PolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties.PolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyName As String" />
      <MemberSignature Language="F#" Value="member this.PolicyName : string with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties.PolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9241-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d9241-107">Optional.</span></span> <span data-ttu-id="d9241-108">ProtectionPolicy の名前です。</span><span class="sxs-lookup"><span data-stu-id="d9241-108">Name of ProtectionPolicy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMRetentionPolicy RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMRetentionPolicy RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As CSMRetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.BackupServices.Models.CSMRetentionPolicy with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties.RetentionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMRetentionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9241-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d9241-109">Optional.</span></span> <span data-ttu-id="d9241-110">Retention Policy</span><span class="sxs-lookup"><span data-stu-id="d9241-110">Retention Policy</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkloadType">
      <MemberSignature Language="C#" Value="public string WorkloadType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkloadType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties.WorkloadType" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkloadType As String" />
      <MemberSignature Language="F#" Value="member this.WorkloadType : string with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequestProperties.WorkloadType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d9241-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d9241-111">Optional.</span></span> <span data-ttu-id="d9241-112">ProtectionPolicy の WorkloadType します。</span><span class="sxs-lookup"><span data-stu-id="d9241-112">WorkloadType of ProtectionPolicy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>