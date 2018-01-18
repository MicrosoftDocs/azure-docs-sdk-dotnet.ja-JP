<Type Name="StatisticsOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StatisticsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StatisticsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StatisticsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StatisticsOperationsExtensions = class" />
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
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.StatisticsListResponse List (this Microsoft.Azure.Management.Automation.IStatisticsOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.StatisticsListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.StatisticsListResponse List(class Microsoft.Azure.Management.Automation.IStatisticsOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.StatisticsListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions.List(Microsoft.Azure.Management.Automation.IStatisticsOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.StatisticsListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IStatisticsOperations, resourceGroupName As String, automationAccount As String, parameters As StatisticsListParameters) As StatisticsListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IStatisticsOperations * string * string * Microsoft.Azure.Management.Automation.Models.StatisticsListParameters -&gt; Microsoft.Azure.Management.Automation.Models.StatisticsListResponse" Usage="Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions.List (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.StatisticsListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IStatisticsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.StatisticsListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb98c-101">Microsoft.Azure.Management.Automation.IStatisticsOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb98c-101">Reference to the Microsoft.Azure.Management.Automation.IStatisticsOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb98c-102">必須。</span><span class="sxs-lookup"><span data-stu-id="fb98c-102">Required.</span></span> <span data-ttu-id="fb98c-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb98c-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb98c-104">必須。</span><span class="sxs-lookup"><span data-stu-id="fb98c-104">Required.</span></span> <span data-ttu-id="fb98c-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb98c-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fb98c-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="fb98c-106">Optional.</span></span> <span data-ttu-id="fb98c-107">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fb98c-107">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb98c-108">アカウントの統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="fb98c-108">Retrieve the statistics for the account.</span></span>  <span data-ttu-id="fb98c-109">(詳細については http://aka.ms/azureautomationsdk/statisticsoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb98c-109">(see http://aka.ms/azureautomationsdk/statisticsoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb98c-110">一覧の統計情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fb98c-110">The response model for the list statistics operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IStatisticsOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.StatisticsListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IStatisticsOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.StatisticsListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IStatisticsOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.StatisticsListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IStatisticsOperations, resourceGroupName As String, automationAccount As String, parameters As StatisticsListParameters) As Task(Of StatisticsListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IStatisticsOperations * string * string * Microsoft.Azure.Management.Automation.Models.StatisticsListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IStatisticsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.StatisticsListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb98c-111">Microsoft.Azure.Management.Automation.IStatisticsOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb98c-111">Reference to the Microsoft.Azure.Management.Automation.IStatisticsOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb98c-112">必須。</span><span class="sxs-lookup"><span data-stu-id="fb98c-112">Required.</span></span> <span data-ttu-id="fb98c-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb98c-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb98c-114">必須。</span><span class="sxs-lookup"><span data-stu-id="fb98c-114">Required.</span></span> <span data-ttu-id="fb98c-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb98c-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fb98c-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="fb98c-116">Optional.</span></span> <span data-ttu-id="fb98c-117">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fb98c-117">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb98c-118">アカウントの統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="fb98c-118">Retrieve the statistics for the account.</span></span>  <span data-ttu-id="fb98c-119">(詳細については http://aka.ms/azureautomationsdk/statisticsoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb98c-119">(see http://aka.ms/azureautomationsdk/statisticsoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb98c-120">一覧の統計情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fb98c-120">The response model for the list statistics operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>