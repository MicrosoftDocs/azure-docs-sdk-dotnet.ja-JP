<Type Name="IAgentRegistrationOperation" FullName="Microsoft.Azure.Management.Automation.IAgentRegistrationOperation">
  <TypeSignature Language="C#" Value="public interface IAgentRegistrationOperation" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAgentRegistrationOperation" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IAgentRegistrationOperation" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAgentRegistrationOperation" />
  <TypeSignature Language="F#" Value="type IAgentRegistrationOperation = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="426ed-101">自動化エージェント登録情報をサービス操作。</span><span class="sxs-lookup"><span data-stu-id="426ed-101">Service operation for automation agent registration information.</span></span>  <span data-ttu-id="426ed-102">(詳細については http://aka.ms/azureautomationsdk/agentregistrationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="426ed-102">(see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAgentRegistrationOperation.GetAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt;" Usage="iAgentRegistrationOperation.GetAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="426ed-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="426ed-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="426ed-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="426ed-104">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="426ed-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="426ed-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="426ed-106">自動化エージェント登録情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="426ed-106">Retrieve the automation agent registration information.</span></span>  <span data-ttu-id="426ed-107">(詳細については http://aka.ms/azureautomationsdk/agentregistrationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="426ed-107">(see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="426ed-108">エージェント登録情報の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="426ed-108">The response model for the get agent registration information operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt; RegenerateKeyAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter keyName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt; RegenerateKeyAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAgentRegistrationOperation.RegenerateKeyAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyAsync : string * string * Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt;" Usage="iAgentRegistrationOperation.RegenerateKeyAsync (resourceGroupName, automationAccount, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="keyName" Type="Microsoft.Azure.Management.Automation.Models.AgentRegistrationRegenerateKeyParameter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="426ed-109">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="426ed-109">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="426ed-110">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="426ed-110">The automation account name.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="426ed-111">再生成するエージェントの登録キーの名前</span><span class="sxs-lookup"><span data-stu-id="426ed-111">The name of the agent registration key to be regenerated</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="426ed-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="426ed-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="426ed-113">プライマリまたはセカンダリのエージェント登録キーを再生成 (詳細については http://aka.ms/azureautomationsdk/agentregistrationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="426ed-113">Regenerate a primary or secondary agent registration key  (see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="426ed-114">エージェント登録キーの応答モデルは、操作を再生成します。</span><span class="sxs-lookup"><span data-stu-id="426ed-114">The response model for the agent registration key regenerate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>