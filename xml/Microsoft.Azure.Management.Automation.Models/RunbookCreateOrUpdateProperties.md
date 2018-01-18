<Type Name="RunbookCreateOrUpdateProperties" FullName="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties">
  <TypeSignature Language="C#" Value="public class RunbookCreateOrUpdateProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RunbookCreateOrUpdateProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RunbookCreateOrUpdateProperties" />
  <TypeSignature Language="F#" Value="type RunbookCreateOrUpdateProperties = class" />
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
            <span data-ttu-id="61a8a-101">Runbook の作成または更新のプロパティに指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="61a8a-101">The parameters supplied to the create or update runbook properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunbookCreateOrUpdateProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="61a8a-102">RunbookCreateOrUpdateProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="61a8a-102">Initializes a new instance of the RunbookCreateOrUpdateProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunbookCreateOrUpdateProperties (string runbookType, Microsoft.Azure.Management.Automation.Models.ContentLink publishContentLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string runbookType, class Microsoft.Azure.Management.Automation.Models.ContentLink publishContentLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.#ctor(System.String,Microsoft.Azure.Management.Automation.Models.ContentLink)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (runbookType As String, publishContentLink As ContentLink)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties : string * Microsoft.Azure.Management.Automation.Models.ContentLink -&gt; Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties" Usage="new Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties (runbookType, publishContentLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="runbookType" Type="System.String" />
        <Parameter Name="publishContentLink" Type="Microsoft.Azure.Management.Automation.Models.ContentLink" />
      </Parameters>
      <Docs>
        <param name="runbookType">To be added.</param>
        <param name="publishContentLink">To be added.</param>
        <summary>
            <span data-ttu-id="61a8a-103">必須の引数で RunbookCreateOrUpdateProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="61a8a-103">Initializes a new instance of the RunbookCreateOrUpdateProperties class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.Description" />
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
            <span data-ttu-id="61a8a-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="61a8a-104">Optional.</span></span> <span data-ttu-id="61a8a-105">取得または runbook の説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="61a8a-105">Gets or sets the description of the runbook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogActivityTrace">
      <MemberSignature Language="C#" Value="public int LogActivityTrace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LogActivityTrace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.LogActivityTrace" />
      <MemberSignature Language="VB.NET" Value="Public Property LogActivityTrace As Integer" />
      <MemberSignature Language="F#" Value="member this.LogActivityTrace : int with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.LogActivityTrace" />
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
            <span data-ttu-id="61a8a-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="61a8a-106">Optional.</span></span> <span data-ttu-id="61a8a-107">取得または runbook のアクティビティ レベルのトレース オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="61a8a-107">Gets or sets the activity-level tracing options of the runbook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogProgress">
      <MemberSignature Language="C#" Value="public bool LogProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool LogProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.LogProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property LogProgress As Boolean" />
      <MemberSignature Language="F#" Value="member this.LogProgress : bool with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.LogProgress" />
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
            <span data-ttu-id="61a8a-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="61a8a-108">Optional.</span></span> <span data-ttu-id="61a8a-109">取得または進行状況のログ オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="61a8a-109">Gets or sets progress log option.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogVerbose">
      <MemberSignature Language="C#" Value="public bool LogVerbose { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool LogVerbose" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.LogVerbose" />
      <MemberSignature Language="VB.NET" Value="Public Property LogVerbose As Boolean" />
      <MemberSignature Language="F#" Value="member this.LogVerbose : bool with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.LogVerbose" />
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
            <span data-ttu-id="61a8a-110">省略可能。</span><span class="sxs-lookup"><span data-stu-id="61a8a-110">Optional.</span></span> <span data-ttu-id="61a8a-111">取得または詳細ログ オプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="61a8a-111">Gets or sets verbose log option.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishContentLink">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.Models.ContentLink PublishContentLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.Models.ContentLink PublishContentLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.PublishContentLink" />
      <MemberSignature Language="VB.NET" Value="Public Property PublishContentLink As ContentLink" />
      <MemberSignature Language="F#" Value="member this.PublishContentLink : Microsoft.Azure.Management.Automation.Models.ContentLink with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.PublishContentLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ContentLink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="61a8a-112">必須。</span><span class="sxs-lookup"><span data-stu-id="61a8a-112">Required.</span></span> <span data-ttu-id="61a8a-113">取得または公開された runbook のコンテンツのリンクを設定します。</span><span class="sxs-lookup"><span data-stu-id="61a8a-113">Gets or sets the published runbook content link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunbookType">
      <MemberSignature Language="C#" Value="public string RunbookType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunbookType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.RunbookType" />
      <MemberSignature Language="VB.NET" Value="Public Property RunbookType As String" />
      <MemberSignature Language="F#" Value="member this.RunbookType : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateProperties.RunbookType" />
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
            <span data-ttu-id="61a8a-114">必須。</span><span class="sxs-lookup"><span data-stu-id="61a8a-114">Required.</span></span> <span data-ttu-id="61a8a-115">取得または runbook の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="61a8a-115">Gets or sets the type of the runbook.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>