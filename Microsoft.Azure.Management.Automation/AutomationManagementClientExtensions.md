<Type Name="AutomationManagementClientExtensions" FullName="Microsoft.Azure.Management.Automation.AutomationManagementClientExtensions">
  <TypeSignature Language="C#" Value="public static class AutomationManagementClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AutomationManagementClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.AutomationManagementClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AutomationManagementClientExtensions" />
  <TypeSignature Language="F#" Value="type AutomationManagementClientExtensions = class" />
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
    <Member MemberName="GetOperationResultStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse GetOperationResultStatus (this Microsoft.Azure.Management.Automation.IAutomationManagementClient operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse GetOperationResultStatus(class Microsoft.Azure.Management.Automation.IAutomationManagementClient operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClientExtensions.GetOperationResultStatus(Microsoft.Azure.Management.Automation.IAutomationManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOperationResultStatus (operations As IAutomationManagementClient, operationStatusLink As String) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member GetOperationResultStatus : Microsoft.Azure.Management.Automation.IAutomationManagementClient * string -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClientExtensions.GetOperationResultStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationManagementClient" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51aaa-101">Microsoft.Azure.Management.Automation.IAutomationManagementClient への参照。</span><span class="sxs-lookup"><span data-stu-id="51aaa-101">Reference to the Microsoft.Azure.Management.Automation.IAutomationManagementClient.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="51aaa-102">必須。</span><span class="sxs-lookup"><span data-stu-id="51aaa-102">Required.</span></span> <span data-ttu-id="51aaa-103">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="51aaa-103">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51aaa-104">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="51aaa-104">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="51aaa-105">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="51aaa-105">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51aaa-106">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="51aaa-106">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationResultStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; GetOperationResultStatusAsync (this Microsoft.Azure.Management.Automation.IAutomationManagementClient operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; GetOperationResultStatusAsync(class Microsoft.Azure.Management.Automation.IAutomationManagementClient operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClientExtensions.GetOperationResultStatusAsync(Microsoft.Azure.Management.Automation.IAutomationManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOperationResultStatusAsync (operations As IAutomationManagementClient, operationStatusLink As String) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member GetOperationResultStatusAsync : Microsoft.Azure.Management.Automation.IAutomationManagementClient * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClientExtensions.GetOperationResultStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationManagementClient" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51aaa-107">Microsoft.Azure.Management.Automation.IAutomationManagementClient への参照。</span><span class="sxs-lookup"><span data-stu-id="51aaa-107">Reference to the Microsoft.Azure.Management.Automation.IAutomationManagementClient.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="51aaa-108">必須。</span><span class="sxs-lookup"><span data-stu-id="51aaa-108">Required.</span></span> <span data-ttu-id="51aaa-109">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="51aaa-109">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51aaa-110">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="51aaa-110">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="51aaa-111">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="51aaa-111">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51aaa-112">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="51aaa-112">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse GetOperationStatus (this Microsoft.Azure.Management.Automation.IAutomationManagementClient operations, string requestId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse GetOperationStatus(class Microsoft.Azure.Management.Automation.IAutomationManagementClient operations, string requestId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClientExtensions.GetOperationStatus(Microsoft.Azure.Management.Automation.IAutomationManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOperationStatus (operations As IAutomationManagementClient, requestId As String) As LongRunningOperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member GetOperationStatus : Microsoft.Azure.Management.Automation.IAutomationManagementClient * string -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClientExtensions.GetOperationStatus (operations, requestId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationManagementClient" RefType="this" />
        <Parameter Name="requestId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51aaa-113">Microsoft.Azure.Management.Automation.IAutomationManagementClient への参照。</span><span class="sxs-lookup"><span data-stu-id="51aaa-113">Reference to the Microsoft.Azure.Management.Automation.IAutomationManagementClient.</span></span>
            </param>
        <param name="requestId">
            <span data-ttu-id="51aaa-114">必須。</span><span class="sxs-lookup"><span data-stu-id="51aaa-114">Required.</span></span> <span data-ttu-id="51aaa-115">追跡する要求の要求 ID。要求 ID は、すべての要求に対して x ms 要求 id の応答ヘッダーで返されます。</span><span class="sxs-lookup"><span data-stu-id="51aaa-115">The request ID for the request you wish to track. The request ID is returned in the x-ms-request-id response header for every request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51aaa-116">Get Operation Status 操作には、指定された操作のステータスが返されます。</span><span class="sxs-lookup"><span data-stu-id="51aaa-116">The Get Operation Status operation returns the status of thespecified operation.</span></span> <span data-ttu-id="51aaa-117">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="51aaa-117">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>  <span data-ttu-id="51aaa-118">(詳細については http://msdn.microsoft.com/en-us/library/windowsazure/ee460783.aspx を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51aaa-118">(see http://msdn.microsoft.com/en-us/library/windowsazure/ee460783.aspx for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51aaa-119">応答本文には、かどうかそれが成功したは、処理中、または失敗を示すが、指定した非同期操作の状態が含まれています。</span><span class="sxs-lookup"><span data-stu-id="51aaa-119">The response body contains the status of the specified asynchronous operation, indicating whether it has succeeded, is inprogress, or has failed.</span></span> <span data-ttu-id="51aaa-120">この状態は、Get Operation Status 操作自体に対して返される HTTP ステータス コードと異なることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="51aaa-120">Note that this status is distinct from the HTTP status code returned for the Get Operation Status operation itself.</span></span>  <span data-ttu-id="51aaa-121">非同期操作が成功した場合、応答本文には、成功した要求の HTTP ステータス コードが含まれています。</span><span class="sxs-lookup"><span data-stu-id="51aaa-121">If the asynchronous operation succeeded, the response body includes the HTTP status code for the successful request.</span></span>  <span data-ttu-id="51aaa-122">非同期操作に失敗した場合、応答本文は、失敗した要求の HTTP ステータス コードが含まれています、失敗に関するエラー情報も含まれます。</span><span class="sxs-lookup"><span data-stu-id="51aaa-122">If the asynchronous operation failed, the response body includes the HTTP status code for the failed request, and also includes error information regarding the failure.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt; GetOperationStatusAsync (this Microsoft.Azure.Management.Automation.IAutomationManagementClient operations, string requestId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt; GetOperationStatusAsync(class Microsoft.Azure.Management.Automation.IAutomationManagementClient operations, string requestId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClientExtensions.GetOperationStatusAsync(Microsoft.Azure.Management.Automation.IAutomationManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOperationStatusAsync (operations As IAutomationManagementClient, requestId As String) As Task(Of LongRunningOperationStatusResponse)" />
      <MemberSignature Language="F#" Value="static member GetOperationStatusAsync : Microsoft.Azure.Management.Automation.IAutomationManagementClient * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClientExtensions.GetOperationStatusAsync (operations, requestId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationManagementClient" RefType="this" />
        <Parameter Name="requestId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51aaa-123">Microsoft.Azure.Management.Automation.IAutomationManagementClient への参照。</span><span class="sxs-lookup"><span data-stu-id="51aaa-123">Reference to the Microsoft.Azure.Management.Automation.IAutomationManagementClient.</span></span>
            </param>
        <param name="requestId">
            <span data-ttu-id="51aaa-124">必須。</span><span class="sxs-lookup"><span data-stu-id="51aaa-124">Required.</span></span> <span data-ttu-id="51aaa-125">追跡する要求の要求 ID。要求 ID は、すべての要求に対して x ms 要求 id の応答ヘッダーで返されます。</span><span class="sxs-lookup"><span data-stu-id="51aaa-125">The request ID for the request you wish to track. The request ID is returned in the x-ms-request-id response header for every request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51aaa-126">Get Operation Status 操作には、指定された操作のステータスが返されます。</span><span class="sxs-lookup"><span data-stu-id="51aaa-126">The Get Operation Status operation returns the status of thespecified operation.</span></span> <span data-ttu-id="51aaa-127">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="51aaa-127">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>  <span data-ttu-id="51aaa-128">(詳細については http://msdn.microsoft.com/en-us/library/windowsazure/ee460783.aspx を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51aaa-128">(see http://msdn.microsoft.com/en-us/library/windowsazure/ee460783.aspx for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51aaa-129">応答本文には、かどうかそれが成功したは、処理中、または失敗を示すが、指定した非同期操作の状態が含まれています。</span><span class="sxs-lookup"><span data-stu-id="51aaa-129">The response body contains the status of the specified asynchronous operation, indicating whether it has succeeded, is inprogress, or has failed.</span></span> <span data-ttu-id="51aaa-130">この状態は、Get Operation Status 操作自体に対して返される HTTP ステータス コードと異なることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="51aaa-130">Note that this status is distinct from the HTTP status code returned for the Get Operation Status operation itself.</span></span>  <span data-ttu-id="51aaa-131">非同期操作が成功した場合、応答本文には、成功した要求の HTTP ステータス コードが含まれています。</span><span class="sxs-lookup"><span data-stu-id="51aaa-131">If the asynchronous operation succeeded, the response body includes the HTTP status code for the successful request.</span></span>  <span data-ttu-id="51aaa-132">非同期操作に失敗した場合、応答本文は、失敗した要求の HTTP ステータス コードが含まれています、失敗に関するエラー情報も含まれます。</span><span class="sxs-lookup"><span data-stu-id="51aaa-132">If the asynchronous operation failed, the response body includes the HTTP status code for the failed request, and also includes error information regarding the failure.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>