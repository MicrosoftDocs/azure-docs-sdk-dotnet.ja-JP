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
            自動化エージェント登録情報をサービス操作。  (詳細については http://aka.ms/azureautomationsdk/agentregistrationoperations を参照してください)
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
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            自動化エージェント登録情報を取得します。  (詳細については http://aka.ms/azureautomationsdk/agentregistrationoperations を参照してください)
            </summary>
        <returns>
            エージェント登録情報の取得操作の応答モデル。
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
            リソース グループの名前
            </param>
        <param name="automationAccount">
            オートメーション アカウントの名前。
            </param>
        <param name="keyName">
            再生成するエージェントの登録キーの名前
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            プライマリまたはセカンダリのエージェント登録キーを再生成 (詳細については http://aka.ms/azureautomationsdk/agentregistrationoperations を参照してください)
            </summary>
        <returns>
            エージェント登録キーの応答モデルは、操作を再生成します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>