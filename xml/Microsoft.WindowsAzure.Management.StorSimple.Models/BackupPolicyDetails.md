<Type Name="BackupPolicyDetails" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyDetails">
  <TypeSignature Language="C#" Value="public class BackupPolicyDetails : Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupPolicyDetails extends Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupPolicyDetails&#xA;Inherits BackupPolicy" />
  <TypeSignature Language="F#" Value="type BackupPolicyDetails = class&#xA;    inherit BackupPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupPolicyDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5dd4d-101">BackupPolicyDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5dd4d-101">Initializes a new instance of the BackupPolicyDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSchedules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleDetails&gt; BackupSchedules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleDetails&gt; BackupSchedules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyDetails.BackupSchedules" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSchedules As IList(Of BackupScheduleDetails)" />
      <MemberSignature Language="F#" Value="member this.BackupSchedules : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleDetails&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyDetails.BackupSchedules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupScheduleDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5dd4d-102">必須。</span><span class="sxs-lookup"><span data-stu-id="5dd4d-102">Required.</span></span> <span data-ttu-id="5dd4d-103">このバックアップ ポリシー下にあるバックアップのスケジュール。</span><span class="sxs-lookup"><span data-stu-id="5dd4d-103">The backup schedules under this backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Volumes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo&gt; Volumes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo&gt; Volumes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyDetails.Volumes" />
      <MemberSignature Language="VB.NET" Value="Public Property Volumes As IList(Of VolumePolicyInfo)" />
      <MemberSignature Language="F#" Value="member this.Volumes : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyDetails.Volumes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.VolumePolicyInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5dd4d-104">必須。</span><span class="sxs-lookup"><span data-stu-id="5dd4d-104">Required.</span></span> <span data-ttu-id="5dd4d-105">このバックアップ ポリシー下にある仮想ディスクの一覧。</span><span class="sxs-lookup"><span data-stu-id="5dd4d-105">The list of virtual disks under this backup policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>