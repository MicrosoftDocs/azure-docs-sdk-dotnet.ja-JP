<Type Name="JobProperties" FullName="Microsoft.Azure.Management.Automation.Models.JobProperties">
  <TypeSignature Language="C#" Value="public class JobProperties : Microsoft.Azure.Management.Automation.Models.JobPropertiesBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobProperties extends Microsoft.Azure.Management.Automation.Models.JobPropertiesBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.JobProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class JobProperties&#xA;Inherits JobPropertiesBase" />
  <TypeSignature Language="F#" Value="type JobProperties = class&#xA;    inherit JobPropertiesBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Automation.Models.JobPropertiesBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92881-101">ジョブのプロパティの定義。</span><span class="sxs-lookup"><span data-stu-id="92881-101">Definition of job properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.JobProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="92881-102">JobProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="92881-102">Initializes a new instance of the JobProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Runbook">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty Runbook { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty Runbook" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobProperties.Runbook" />
      <MemberSignature Language="VB.NET" Value="Public Property Runbook As RunbookAssociationProperty" />
      <MemberSignature Language="F#" Value="member this.Runbook : Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobProperties.Runbook" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92881-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="92881-103">Optional.</span></span> <span data-ttu-id="92881-104">取得または runbook を設定します。</span><span class="sxs-lookup"><span data-stu-id="92881-104">Gets or sets the runbook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunOn">
      <MemberSignature Language="C#" Value="public string RunOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobProperties.RunOn" />
      <MemberSignature Language="VB.NET" Value="Public Property RunOn As String" />
      <MemberSignature Language="F#" Value="member this.RunOn : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobProperties.RunOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92881-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="92881-105">Optional.</span></span> <span data-ttu-id="92881-106">取得または、ジョブが実行される、グループ名を指定する runOn を設定します。</span><span class="sxs-lookup"><span data-stu-id="92881-106">Gets or sets the runOn which specifies the group name where the job is to be executed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartedBy">
      <MemberSignature Language="C#" Value="public string StartedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobProperties.StartedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property StartedBy As String" />
      <MemberSignature Language="F#" Value="member this.StartedBy : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobProperties.StartedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="92881-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="92881-107">Optional.</span></span> <span data-ttu-id="92881-108">取得またはによって開始されたジョブを設定します。</span><span class="sxs-lookup"><span data-stu-id="92881-108">Gets or sets the job started by.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>