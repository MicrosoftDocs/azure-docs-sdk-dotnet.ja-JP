<Type Name="RunbookCreateOrUpdateDraftProperties" FullName="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties">
  <TypeSignature Language="C#" Value="public class RunbookCreateOrUpdateDraftProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RunbookCreateOrUpdateDraftProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RunbookCreateOrUpdateDraftProperties" />
  <TypeSignature Language="F#" Value="type RunbookCreateOrUpdateDraftProperties = class" />
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
            <span data-ttu-id="1e0c4-101">作成または更新 dratft runbook のプロパティに指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-101">The parameters supplied to the create or update dratft runbook properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunbookCreateOrUpdateDraftProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e0c4-102">RunbookCreateOrUpdateDraftProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-102">Initializes a new instance of the RunbookCreateOrUpdateDraftProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunbookCreateOrUpdateDraftProperties (string runbookType, Microsoft.Azure.Management.Automation.Models.RunbookDraft draft);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string runbookType, class Microsoft.Azure.Management.Automation.Models.RunbookDraft draft) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.#ctor(System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraft)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (runbookType As String, draft As RunbookDraft)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties : string * Microsoft.Azure.Management.Automation.Models.RunbookDraft -&gt; Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties" Usage="new Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties (runbookType, draft)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="runbookType" Type="System.String" />
        <Parameter Name="draft" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraft" />
      </Parameters>
      <Docs>
        <param name="runbookType">To be added.</param>
        <param name="draft">To be added.</param>
        <summary>
            <span data-ttu-id="1e0c4-103">必須の引数で RunbookCreateOrUpdateDraftProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-103">Initializes a new instance of the RunbookCreateOrUpdateDraftProperties class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.Description" />
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
            <span data-ttu-id="1e0c4-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-104">Optional.</span></span> <span data-ttu-id="1e0c4-105">取得または runbook の説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-105">Gets or sets the description of the runbook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Draft">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.RunbookDraft Draft { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.RunbookDraft Draft" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.Draft" />
      <MemberSignature Language="VB.NET" Value="Public Property Draft As RunbookDraft" />
      <MemberSignature Language="F#" Value="member this.Draft : Microsoft.Azure.Management.Automation.Models.RunbookDraft with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.Draft" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookDraft</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e0c4-106">必須。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-106">Required.</span></span> <span data-ttu-id="1e0c4-107">取得またはドラフト runbook のプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-107">Gets or sets the draft runbook properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogActivityTrace">
      <MemberSignature Language="C#" Value="public int LogActivityTrace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LogActivityTrace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.LogActivityTrace" />
      <MemberSignature Language="VB.NET" Value="Public Property LogActivityTrace As Integer" />
      <MemberSignature Language="F#" Value="member this.LogActivityTrace : int with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.LogActivityTrace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e0c4-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-108">Optional.</span></span> <span data-ttu-id="1e0c4-109">取得または runbook のアクティビティ レベルのトレース オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-109">Gets or sets the activity-level tracing options of the runbook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogProgress">
      <MemberSignature Language="C#" Value="public bool LogProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool LogProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.LogProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property LogProgress As Boolean" />
      <MemberSignature Language="F#" Value="member this.LogProgress : bool with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.LogProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e0c4-110">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-110">Optional.</span></span> <span data-ttu-id="1e0c4-111">取得または進行状況のログ オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-111">Gets or sets progress log option.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogVerbose">
      <MemberSignature Language="C#" Value="public bool LogVerbose { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool LogVerbose" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.LogVerbose" />
      <MemberSignature Language="VB.NET" Value="Public Property LogVerbose As Boolean" />
      <MemberSignature Language="F#" Value="member this.LogVerbose : bool with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.LogVerbose" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e0c4-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-112">Optional.</span></span> <span data-ttu-id="1e0c4-113">取得または詳細ログ オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-113">Gets or sets verbose log option.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunbookType">
      <MemberSignature Language="C#" Value="public string RunbookType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunbookType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.RunbookType" />
      <MemberSignature Language="VB.NET" Value="Public Property RunbookType As String" />
      <MemberSignature Language="F#" Value="member this.RunbookType : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftProperties.RunbookType" />
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
            <span data-ttu-id="1e0c4-114">必須。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-114">Required.</span></span> <span data-ttu-id="1e0c4-115">取得または runbook の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="1e0c4-115">Gets or sets the type of the runbook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>