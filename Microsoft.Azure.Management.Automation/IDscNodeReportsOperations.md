<Type Name="IDscNodeReportsOperations" FullName="Microsoft.Azure.Management.Automation.IDscNodeReportsOperations">
  <TypeSignature Language="C#" Value="public interface IDscNodeReportsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDscNodeReportsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDscNodeReportsOperations" />
  <TypeSignature Language="F#" Value="type IDscNodeReportsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="19790-101">サービスのノードのレポートを操作します。</span><span class="sxs-lookup"><span data-stu-id="19790-101">Service operation for node reports.</span></span>  <span data-ttu-id="19790-102">(詳細については http://aka.ms/azureautomationsdk/dscnodereportoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="19790-102">(see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, Guid nodeId, Guid reportId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Guid reportId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.GetAsync(System.String,System.String,System.Guid,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Guid * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt;" Usage="iDscNodeReportsOperations.GetAsync (resourceGroupName, automationAccount, nodeId, reportId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="reportId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="19790-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="19790-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="19790-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="19790-104">The automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="19790-105">Dsc ノードの id。</span><span class="sxs-lookup"><span data-stu-id="19790-105">The Dsc node id.</span></span>
            </param>
        <param name="reportId">
            <span data-ttu-id="19790-106">レポートの id。</span><span class="sxs-lookup"><span data-stu-id="19790-106">The report id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19790-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19790-107">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19790-108">ノード id とレポートの id では、Dsc ノード レポート データを取得します。 (詳細については http://aka.ms/azureautomationsdk/dscnodereportoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="19790-108">Retrieve the Dsc node report data by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="19790-109">Get 応答モデル dsc ノード レポートを操作します。</span><span class="sxs-lookup"><span data-stu-id="19790-109">The response model for the get dsc node report operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt; GetContentAsync (string resourceGroupName, string automationAccount, Guid nodeId, Guid reportId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt; GetContentAsync(string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Guid reportId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.GetContentAsync(System.String,System.String,System.Guid,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetContentAsync : string * string * Guid * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt;" Usage="iDscNodeReportsOperations.GetContentAsync (resourceGroupName, automationAccount, nodeId, reportId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="reportId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="19790-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="19790-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="19790-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="19790-111">The automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="19790-112">Dsc ノードの id。</span><span class="sxs-lookup"><span data-stu-id="19790-112">The Dsc node id.</span></span>
            </param>
        <param name="reportId">
            <span data-ttu-id="19790-113">レポートの id。</span><span class="sxs-lookup"><span data-stu-id="19790-113">The report id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19790-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19790-114">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19790-115">ノード id とレポートの id での Dsc ノード レポートを取得します。 (詳細については http://aka.ms/azureautomationsdk/dscnodereportoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="19790-115">Retrieve the Dsc node reports by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="19790-116">ノード レポート コンテンツの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="19790-116">The response model for the get node report content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;" Usage="iDscNodeReportsOperations.ListAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="19790-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="19790-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="19790-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="19790-118">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="19790-119">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="19790-119">The parameters supplied to the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19790-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19790-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19790-121">ノード id とレポートの id では、Dsc ノード レポート リストを取得します。 (詳細については http://aka.ms/azureautomationsdk/dscnodereportoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="19790-121">Retrieve the Dsc node report list by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="19790-122">一覧の dsc ノードの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="19790-122">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;" Usage="iDscNodeReportsOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="19790-123">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="19790-123">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="19790-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="19790-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="19790-125">ノード id とレポートの id では、Dsc ノード レポート リストを取得します。 (詳細については http://aka.ms/azureautomationsdk/dscnodereportoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="19790-125">Retrieve the Dsc node report list by node id and report id.  (see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="19790-126">一覧の dsc ノードの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="19790-126">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>