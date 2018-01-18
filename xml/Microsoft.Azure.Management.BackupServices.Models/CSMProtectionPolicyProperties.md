<Type Name="CSMProtectionPolicyProperties" FullName="Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties">
  <TypeSignature Language="C#" Value="public class CSMProtectionPolicyProperties : Microsoft.Azure.Management.BackupServices.Models.CSMBaseObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CSMProtectionPolicyProperties extends Microsoft.Azure.Management.BackupServices.Models.CSMBaseObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class CSMProtectionPolicyProperties&#xA;Inherits CSMBaseObject" />
  <TypeSignature Language="F#" Value="type CSMProtectionPolicyProperties = class&#xA;    inherit CSMBaseObject" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.BackupServices.Models.CSMBaseObject</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5132a-101">CSMProtectionPolicyProperties オブジェクトの定義。</span><span class="sxs-lookup"><span data-stu-id="5132a-101">The definition of a CSMProtectionPolicyProperties object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CSMProtectionPolicyProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5132a-102">CSMProtectionPolicyProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5132a-102">Initializes a new instance of the CSMProtectionPolicyProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule BackupSchedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule BackupSchedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties.BackupSchedule" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSchedule As CSMBackupSchedule" />
      <MemberSignature Language="F#" Value="member this.BackupSchedule : Microsoft.Azure.Management.BackupServices.Models.CSMBackupSchedule with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties.BackupSchedule" />
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
            <span data-ttu-id="5132a-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5132a-103">Optional.</span></span> <span data-ttu-id="5132a-104">ProtectionPolicy のバックアップのスケジュール。</span><span class="sxs-lookup"><span data-stu-id="5132a-104">Backup Schedule of ProtectionPolicy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LtrRetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMLongTermRetentionPolicy LtrRetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMLongTermRetentionPolicy LtrRetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties.LtrRetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property LtrRetentionPolicy As CSMLongTermRetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.LtrRetentionPolicy : Microsoft.Azure.Management.BackupServices.Models.CSMLongTermRetentionPolicy with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties.LtrRetentionPolicy" />
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
            <span data-ttu-id="5132a-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5132a-105">Optional.</span></span> <span data-ttu-id="5132a-106">長期的な保有期間ポリシー。</span><span class="sxs-lookup"><span data-stu-id="5132a-106">Long Term Retention Policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyName">
      <MemberSignature Language="C#" Value="public string PolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties.PolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyName As String" />
      <MemberSignature Language="F#" Value="member this.PolicyName : string with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties.PolicyName" />
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
            <span data-ttu-id="5132a-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5132a-107">Optional.</span></span> <span data-ttu-id="5132a-108">ProtectionPolicy の名前です。</span><span class="sxs-lookup"><span data-stu-id="5132a-108">Name of ProtectionPolicy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BackupServices.Models.CSMRetentionPolicy RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.Models.CSMRetentionPolicy RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As CSMRetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.BackupServices.Models.CSMRetentionPolicy with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties.RetentionPolicy" />
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
            <span data-ttu-id="5132a-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5132a-109">Optional.</span></span> <span data-ttu-id="5132a-110">Retention Policy</span><span class="sxs-lookup"><span data-stu-id="5132a-110">Retention Policy</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkloadType">
      <MemberSignature Language="C#" Value="public string WorkloadType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkloadType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties.WorkloadType" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkloadType As String" />
      <MemberSignature Language="F#" Value="member this.WorkloadType : string with get, set" Usage="Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyProperties.WorkloadType" />
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
            <span data-ttu-id="5132a-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5132a-111">Optional.</span></span> <span data-ttu-id="5132a-112">ProtectionPolicy の WorkloadType します。</span><span class="sxs-lookup"><span data-stu-id="5132a-112">WorkloadType of ProtectionPolicy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>