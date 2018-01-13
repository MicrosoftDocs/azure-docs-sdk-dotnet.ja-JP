<Type Name="IStatisticsOperations" FullName="Microsoft.Azure.Management.Automation.IStatisticsOperations">
  <TypeSignature Language="C#" Value="public interface IStatisticsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatisticsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IStatisticsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatisticsOperations" />
  <TypeSignature Language="F#" Value="type IStatisticsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="36d6a-101">オートメーションの統計情報をサービス操作。</span><span class="sxs-lookup"><span data-stu-id="36d6a-101">Service operation for automation statistics.</span></span>  <span data-ttu-id="36d6a-102">(詳細については http://aka.ms/azureautomationsdk/statisticsoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="36d6a-102">(see http://aka.ms/azureautomationsdk/statisticsoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.StatisticsListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.StatisticsListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IStatisticsOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.StatisticsListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.Automation.Models.StatisticsListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt;" Usage="iStatisticsOperations.ListAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.StatisticsListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="36d6a-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="36d6a-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="36d6a-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="36d6a-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="36d6a-105">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="36d6a-105">The parameters supplied to the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="36d6a-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="36d6a-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36d6a-107">アカウントの統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="36d6a-107">Retrieve the statistics for the account.</span></span>  <span data-ttu-id="36d6a-108">(詳細については http://aka.ms/azureautomationsdk/statisticsoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="36d6a-108">(see http://aka.ms/azureautomationsdk/statisticsoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36d6a-109">一覧の統計情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="36d6a-109">The response model for the list statistics operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>