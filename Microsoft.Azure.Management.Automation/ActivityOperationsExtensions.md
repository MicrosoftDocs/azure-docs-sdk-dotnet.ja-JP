<Type Name="ActivityOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.ActivityOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ActivityOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActivityOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ActivityOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActivityOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ActivityOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ActivityGetResponse Get (this Microsoft.Azure.Management.Automation.IActivityOperations operations, string resourceGroupName, string automationAccount, string moduleName, string activityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ActivityGetResponse Get(class Microsoft.Azure.Management.Automation.IActivityOperations operations, string resourceGroupName, string automationAccount, string moduleName, string activityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IActivityOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IActivityOperations, resourceGroupName As String, automationAccount As String, moduleName As String, activityName As String) As ActivityGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IActivityOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ActivityGetResponse" Usage="Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.Get (operations, resourceGroupName, automationAccount, moduleName, activityName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ActivityGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IActivityOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
        <Parameter Name="activityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcff3-101">Microsoft.Azure.Management.Automation.IActivityOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="dcff3-101">Reference to the Microsoft.Azure.Management.Automation.IActivityOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcff3-102">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-102">Required.</span></span> <span data-ttu-id="dcff3-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="dcff3-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="dcff3-104">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-104">Required.</span></span> <span data-ttu-id="dcff3-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="dcff3-105">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="dcff3-106">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-106">Required.</span></span> <span data-ttu-id="dcff3-107">モジュールの名前。</span><span class="sxs-lookup"><span data-stu-id="dcff3-107">The name of module.</span></span>
            </param>
        <param name="activityName">
            <span data-ttu-id="dcff3-108">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-108">Required.</span></span> <span data-ttu-id="dcff3-109">アクティビティの名前。</span><span class="sxs-lookup"><span data-stu-id="dcff3-109">The name of activity.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcff3-110">モジュール名とアクティビティ名によって識別されるモジュールのアクティビティを取得します。</span><span class="sxs-lookup"><span data-stu-id="dcff3-110">Retrieve the activity in the module identified by module name and activity name.</span></span>  <span data-ttu-id="dcff3-111">(詳細については http://aka.ms/azureautomationsdk/activityoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="dcff3-111">(see http://aka.ms/azureautomationsdk/activityoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcff3-112">アクティビティの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="dcff3-112">The response model for the get activity operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ActivityGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IActivityOperations operations, string resourceGroupName, string automationAccount, string moduleName, string activityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ActivityGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IActivityOperations operations, string resourceGroupName, string automationAccount, string moduleName, string activityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IActivityOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IActivityOperations, resourceGroupName As String, automationAccount As String, moduleName As String, activityName As String) As Task(Of ActivityGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IActivityOperations * string * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ActivityGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, moduleName, activityName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ActivityGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IActivityOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
        <Parameter Name="activityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcff3-113">Microsoft.Azure.Management.Automation.IActivityOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="dcff3-113">Reference to the Microsoft.Azure.Management.Automation.IActivityOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcff3-114">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-114">Required.</span></span> <span data-ttu-id="dcff3-115">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="dcff3-115">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="dcff3-116">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-116">Required.</span></span> <span data-ttu-id="dcff3-117">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="dcff3-117">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="dcff3-118">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-118">Required.</span></span> <span data-ttu-id="dcff3-119">モジュールの名前。</span><span class="sxs-lookup"><span data-stu-id="dcff3-119">The name of module.</span></span>
            </param>
        <param name="activityName">
            <span data-ttu-id="dcff3-120">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-120">Required.</span></span> <span data-ttu-id="dcff3-121">アクティビティの名前。</span><span class="sxs-lookup"><span data-stu-id="dcff3-121">The name of activity.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcff3-122">モジュール名とアクティビティ名によって識別されるモジュールのアクティビティを取得します。</span><span class="sxs-lookup"><span data-stu-id="dcff3-122">Retrieve the activity in the module identified by module name and activity name.</span></span>  <span data-ttu-id="dcff3-123">(詳細については http://aka.ms/azureautomationsdk/activityoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="dcff3-123">(see http://aka.ms/azureautomationsdk/activityoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcff3-124">アクティビティの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="dcff3-124">The response model for the get activity operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ActivityListResponse List (this Microsoft.Azure.Management.Automation.IActivityOperations operations, string resourceGroupName, string automationAccount, string moduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ActivityListResponse List(class Microsoft.Azure.Management.Automation.IActivityOperations operations, string resourceGroupName, string automationAccount, string moduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.List(Microsoft.Azure.Management.Automation.IActivityOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IActivityOperations, resourceGroupName As String, automationAccount As String, moduleName As String) As ActivityListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IActivityOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ActivityListResponse" Usage="Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.List (operations, resourceGroupName, automationAccount, moduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ActivityListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IActivityOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcff3-125">Microsoft.Azure.Management.Automation.IActivityOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="dcff3-125">Reference to the Microsoft.Azure.Management.Automation.IActivityOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcff3-126">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-126">Required.</span></span> <span data-ttu-id="dcff3-127">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="dcff3-127">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="dcff3-128">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-128">Required.</span></span> <span data-ttu-id="dcff3-129">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="dcff3-129">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="dcff3-130">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-130">Required.</span></span> <span data-ttu-id="dcff3-131">モジュールの名前。</span><span class="sxs-lookup"><span data-stu-id="dcff3-131">The name of module.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcff3-132">モジュール名によって識別されるモジュール内のアクティビティの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="dcff3-132">Retrieve a list of activities in the module identified by module name.</span></span>  <span data-ttu-id="dcff3-133">(詳細については http://aka.ms/azureautomationsdk/activityoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="dcff3-133">(see http://aka.ms/azureautomationsdk/activityoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcff3-134">一覧のアクティビティ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="dcff3-134">The response model for the list activity operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ActivityListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IActivityOperations operations, string resourceGroupName, string automationAccount, string moduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ActivityListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IActivityOperations operations, string resourceGroupName, string automationAccount, string moduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IActivityOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IActivityOperations, resourceGroupName As String, automationAccount As String, moduleName As String) As Task(Of ActivityListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IActivityOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ActivityListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, moduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ActivityListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IActivityOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcff3-135">Microsoft.Azure.Management.Automation.IActivityOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="dcff3-135">Reference to the Microsoft.Azure.Management.Automation.IActivityOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcff3-136">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-136">Required.</span></span> <span data-ttu-id="dcff3-137">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="dcff3-137">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="dcff3-138">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-138">Required.</span></span> <span data-ttu-id="dcff3-139">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="dcff3-139">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="dcff3-140">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-140">Required.</span></span> <span data-ttu-id="dcff3-141">モジュールの名前。</span><span class="sxs-lookup"><span data-stu-id="dcff3-141">The name of module.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcff3-142">モジュール名によって識別されるモジュール内のアクティビティの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="dcff3-142">Retrieve a list of activities in the module identified by module name.</span></span>  <span data-ttu-id="dcff3-143">(詳細については http://aka.ms/azureautomationsdk/activityoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="dcff3-143">(see http://aka.ms/azureautomationsdk/activityoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcff3-144">一覧のアクティビティ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="dcff3-144">The response model for the list activity operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ActivityListResponse ListNext (this Microsoft.Azure.Management.Automation.IActivityOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ActivityListResponse ListNext(class Microsoft.Azure.Management.Automation.IActivityOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IActivityOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IActivityOperations, nextLink As String) As ActivityListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IActivityOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.ActivityListResponse" Usage="Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ActivityListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IActivityOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcff3-145">Microsoft.Azure.Management.Automation.IActivityOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="dcff3-145">Reference to the Microsoft.Azure.Management.Automation.IActivityOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="dcff3-146">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-146">Required.</span></span> <span data-ttu-id="dcff3-147">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="dcff3-147">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcff3-148">モジュール名によって識別されるモジュールで活動の [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="dcff3-148">Retrieve next list of activities in the module identified by module name.</span></span>  <span data-ttu-id="dcff3-149">(詳細については http://aka.ms/azureautomationsdk/activityoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="dcff3-149">(see http://aka.ms/azureautomationsdk/activityoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcff3-150">一覧のアクティビティ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="dcff3-150">The response model for the list activity operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ActivityListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IActivityOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ActivityListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IActivityOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IActivityOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IActivityOperations, nextLink As String) As Task(Of ActivityListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IActivityOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ActivityListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ActivityOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ActivityListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IActivityOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcff3-151">Microsoft.Azure.Management.Automation.IActivityOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="dcff3-151">Reference to the Microsoft.Azure.Management.Automation.IActivityOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="dcff3-152">必須。</span><span class="sxs-lookup"><span data-stu-id="dcff3-152">Required.</span></span> <span data-ttu-id="dcff3-153">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="dcff3-153">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcff3-154">モジュール名によって識別されるモジュールで活動の [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="dcff3-154">Retrieve next list of activities in the module identified by module name.</span></span>  <span data-ttu-id="dcff3-155">(詳細については http://aka.ms/azureautomationsdk/activityoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="dcff3-155">(see http://aka.ms/azureautomationsdk/activityoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcff3-156">一覧のアクティビティ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="dcff3-156">The response model for the list activity operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>