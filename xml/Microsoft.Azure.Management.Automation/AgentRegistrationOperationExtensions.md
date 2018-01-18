<Type Name="AgentRegistrationOperationExtensions" FullName="Microsoft.Azure.Management.Automation.AgentRegistrationOperationExtensions">
  <TypeSignature Language="C#" Value="public static class AgentRegistrationOperationExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AgentRegistrationOperationExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.AgentRegistrationOperationExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AgentRegistrationOperationExtensions" />
  <TypeSignature Language="F#" Value="type AgentRegistrationOperationExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse Get (this Microsoft.Azure.Management.Automation.IAgentRegistrationOperation operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse Get(class Microsoft.Azure.Management.Automation.IAgentRegistrationOperation operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AgentRegistrationOperationExtensions.Get(Microsoft.Azure.Management.Automation.IAgentRegistrationOperation,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAgentRegistrationOperation, resourceGroupName As String, automationAccount As String) As AgentRegistrationGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IAgentRegistrationOperation * string * string -&gt; Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse" Usage="Microsoft.Azure.Management.Automation.AgentRegistrationOperationExtensions.Get (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAgentRegistrationOperation" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a4cc-101">Microsoft.Azure.Management.Automation.IAgentRegistrationOperation への参照。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-101">Reference to the Microsoft.Azure.Management.Automation.IAgentRegistrationOperation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a4cc-102">必須。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-102">Required.</span></span> <span data-ttu-id="8a4cc-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="8a4cc-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8a4cc-104">必須。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-104">Required.</span></span> <span data-ttu-id="8a4cc-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-105">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a4cc-106">自動化エージェント登録情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-106">Retrieve the automation agent registration information.</span></span>  <span data-ttu-id="8a4cc-107">(詳細については http://aka.ms/azureautomationsdk/agentregistrationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="8a4cc-107">(see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8a4cc-108">エージェント登録情報の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-108">The response model for the get agent registration information operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IAgentRegistrationOperation operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IAgentRegistrationOperation operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AgentRegistrationOperationExtensions.GetAsync(Microsoft.Azure.Management.Automation.IAgentRegistrationOperation,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IAgentRegistrationOperation, resourceGroupName As String, automationAccount As String) As Task(Of AgentRegistrationGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IAgentRegistrationOperation * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AgentRegistrationOperationExtensions.GetAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAgentRegistrationOperation" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a4cc-109">Microsoft.Azure.Management.Automation.IAgentRegistrationOperation への参照。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-109">Reference to the Microsoft.Azure.Management.Automation.IAgentRegistrationOperation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a4cc-110">必須。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-110">Required.</span></span> <span data-ttu-id="8a4cc-111">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="8a4cc-111">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8a4cc-112">必須。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-112">Required.</span></span> <span data-ttu-id="8a4cc-113">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-113">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a4cc-114">自動化エージェント登録情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-114">Retrieve the automation agent registration information.</span></span>  <span data-ttu-id="8a4cc-115">(詳細については http://aka.ms/azureautomationsdk/agentregistrationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="8a4cc-115">(see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8a4cc-116">エージェント登録情報の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-116">The response model for the get agent registration information operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse RegenerateKey (this Microsoft.Azure.Management.Automation.IAgentRegistrationOperation operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse RegenerateKey(class Microsoft.Azure.Management.Automation.IAgentRegistrationOperation operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AgentRegistrationOperationExtensions.RegenerateKey(Microsoft.Azure.Management.Automation.IAgentRegistrationOperation,System.String,System.String,Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKey (operations As IAgentRegistrationOperation, resourceGroupName As String, automationAccount As String, keyName As AgentRegistrationRegenerateKeyParameter) As AgentRegistrationRegenerateKeyResponse" />
      <MemberSignature Language="F#" Value="static member RegenerateKey : Microsoft.Azure.Management.Automation.IAgentRegistrationOperation * string * string * Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter -&gt; Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse" Usage="Microsoft.Azure.Management.Automation.AgentRegistrationOperationExtensions.RegenerateKey (operations, resourceGroupName, automationAccount, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAgentRegistrationOperation" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="keyName" Type="Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a4cc-117">Microsoft.Azure.Management.Automation.IAgentRegistrationOperation への参照。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-117">Reference to the Microsoft.Azure.Management.Automation.IAgentRegistrationOperation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a4cc-118">必須。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-118">Required.</span></span> <span data-ttu-id="8a4cc-119">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="8a4cc-119">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8a4cc-120">必須。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-120">Required.</span></span> <span data-ttu-id="8a4cc-121">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-121">The automation account name.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="8a4cc-122">必須。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-122">Required.</span></span> <span data-ttu-id="8a4cc-123">再生成するエージェントの登録キーの名前</span><span class="sxs-lookup"><span data-stu-id="8a4cc-123">The name of the agent registration key to be regenerated</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a4cc-124">プライマリまたはセカンダリのエージェント登録キーを再生成 (詳細については http://aka.ms/azureautomationsdk/agentregistrationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="8a4cc-124">Regenerate a primary or secondary agent registration key  (see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8a4cc-125">エージェント登録キーの応答モデルは、操作を再生成します。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-125">The response model for the agent registration key regenerate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt; RegenerateKeyAsync (this Microsoft.Azure.Management.Automation.IAgentRegistrationOperation operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt; RegenerateKeyAsync(class Microsoft.Azure.Management.Automation.IAgentRegistrationOperation operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AgentRegistrationOperationExtensions.RegenerateKeyAsync(Microsoft.Azure.Management.Automation.IAgentRegistrationOperation,System.String,System.String,Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeyAsync (operations As IAgentRegistrationOperation, resourceGroupName As String, automationAccount As String, keyName As AgentRegistrationRegenerateKeyParameter) As Task(Of AgentRegistrationRegenerateKeyResponse)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeyAsync : Microsoft.Azure.Management.Automation.IAgentRegistrationOperation * string * string * Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AgentRegistrationOperationExtensions.RegenerateKeyAsync (operations, resourceGroupName, automationAccount, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAgentRegistrationOperation" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="keyName" Type="Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a4cc-126">Microsoft.Azure.Management.Automation.IAgentRegistrationOperation への参照。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-126">Reference to the Microsoft.Azure.Management.Automation.IAgentRegistrationOperation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a4cc-127">必須。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-127">Required.</span></span> <span data-ttu-id="8a4cc-128">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="8a4cc-128">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8a4cc-129">必須。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-129">Required.</span></span> <span data-ttu-id="8a4cc-130">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-130">The automation account name.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="8a4cc-131">必須。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-131">Required.</span></span> <span data-ttu-id="8a4cc-132">再生成するエージェントの登録キーの名前</span><span class="sxs-lookup"><span data-stu-id="8a4cc-132">The name of the agent registration key to be regenerated</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a4cc-133">プライマリまたはセカンダリのエージェント登録キーを再生成 (詳細については http://aka.ms/azureautomationsdk/agentregistrationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="8a4cc-133">Regenerate a primary or secondary agent registration key  (see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8a4cc-134">エージェント登録キーの応答モデルは、操作を再生成します。</span><span class="sxs-lookup"><span data-stu-id="8a4cc-134">The response model for the agent registration key regenerate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>