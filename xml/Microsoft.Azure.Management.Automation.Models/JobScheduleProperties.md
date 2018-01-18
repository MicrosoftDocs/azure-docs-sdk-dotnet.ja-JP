<Type Name="JobScheduleProperties" FullName="Microsoft.Azure.Management.Automation.Models.JobScheduleProperties">
  <TypeSignature Language="C#" Value="public class JobScheduleProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.JobScheduleProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleProperties" />
  <TypeSignature Language="F#" Value="type JobScheduleProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="26a9b-101">ジョブ スケジュール パラメーターの定義。</span><span class="sxs-lookup"><span data-stu-id="26a9b-101">Definition of job schedule parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.JobScheduleProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="26a9b-102">JobScheduleProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="26a9b-102">Initializes a new instance of the JobScheduleProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Guid Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobScheduleProperties.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As Guid" />
      <MemberSignature Language="F#" Value="member this.Id : Guid with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobScheduleProperties.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26a9b-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26a9b-103">Optional.</span></span> <span data-ttu-id="26a9b-104">取得またはジョブ スケジュールの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="26a9b-104">Gets or sets the id of job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobScheduleProperties.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobScheduleProperties.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26a9b-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26a9b-105">Optional.</span></span> <span data-ttu-id="26a9b-106">取得またはジョブ スケジュールのパラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="26a9b-106">Gets or sets the parameters of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Runbook">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty Runbook { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty Runbook" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobScheduleProperties.Runbook" />
      <MemberSignature Language="VB.NET" Value="Public Property Runbook As RunbookAssociationProperty" />
      <MemberSignature Language="F#" Value="member this.Runbook : Microsoft.Azure.Management.Automation.Models.RunbookAssociationProperty with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobScheduleProperties.Runbook" />
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
            <span data-ttu-id="26a9b-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26a9b-107">Optional.</span></span> <span data-ttu-id="26a9b-108">取得または runbook を設定します。</span><span class="sxs-lookup"><span data-stu-id="26a9b-108">Gets or sets the runbook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunOn">
      <MemberSignature Language="C#" Value="public string RunOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobScheduleProperties.RunOn" />
      <MemberSignature Language="VB.NET" Value="Public Property RunOn As String" />
      <MemberSignature Language="F#" Value="member this.RunOn : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobScheduleProperties.RunOn" />
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
            <span data-ttu-id="26a9b-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26a9b-109">Optional.</span></span> <span data-ttu-id="26a9b-110">取得またはスケジュールされたジョブを実行するハイブリッド worker グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="26a9b-110">Gets or sets the hybrid worker group that the scheduled job should run on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobScheduleProperties.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As ScheduleAssociationProperty" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobScheduleProperties.Schedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ScheduleAssociationProperty</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26a9b-111">省略可能。</span><span class="sxs-lookup"><span data-stu-id="26a9b-111">Optional.</span></span> <span data-ttu-id="26a9b-112">取得またはスケジュールを設定します。</span><span class="sxs-lookup"><span data-stu-id="26a9b-112">Gets or sets the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>