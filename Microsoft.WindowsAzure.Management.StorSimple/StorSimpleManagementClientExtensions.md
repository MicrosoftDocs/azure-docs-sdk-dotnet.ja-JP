<Type Name="StorSimpleManagementClientExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions">
  <TypeSignature Language="C#" Value="public static class StorSimpleManagementClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorSimpleManagementClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorSimpleManagementClientExtensions" />
  <TypeSignature Language="F#" Value="type StorSimpleManagementClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="09788-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="09788-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetOperationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo GetOperationStatus (this Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient operations, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo GetOperationStatus(class Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient operations, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions.GetOperationStatus(Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOperationStatus (operations As IStorSimpleManagementClient, taskId As String) As TaskStatusInfo" />
      <MemberSignature Language="F#" Value="static member GetOperationStatus : Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient * string -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions.GetOperationStatus (operations, taskId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient" RefType="this" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="09788-102">Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient への参照。</span><span class="sxs-lookup"><span data-stu-id="09788-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="09788-103">必須。</span><span class="sxs-lookup"><span data-stu-id="09788-103">Required.</span></span> <span data-ttu-id="09788-104">タスク Id を要求する追跡できます。</span><span class="sxs-lookup"><span data-stu-id="09788-104">The task Id for the request you wish to track.</span></span>
            </param>
        <summary>
            <span data-ttu-id="09788-105">タスクの状態の取得では、指定されたタスク id の状態を返します。非同期タスクを呼び出した後は、呼び出すことができます、タスクが成功したかどうかを決定するタスクの状態の取得に失敗しました。 または、進行中です。</span><span class="sxs-lookup"><span data-stu-id="09788-105">The Get Task Status returns the status of the specified task id. After calling an asynchronous task, you can call Get Task Status to determine whether the task has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="09788-106">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="09788-106">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; GetOperationStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient operations, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; GetOperationStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient operations, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions.GetOperationStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOperationStatusAsync (operations As IStorSimpleManagementClient, taskId As String) As Task(Of TaskStatusInfo)" />
      <MemberSignature Language="F#" Value="static member GetOperationStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions.GetOperationStatusAsync (operations, taskId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient" RefType="this" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="09788-107">Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient への参照。</span><span class="sxs-lookup"><span data-stu-id="09788-107">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="09788-108">必須。</span><span class="sxs-lookup"><span data-stu-id="09788-108">Required.</span></span> <span data-ttu-id="09788-109">タスク Id を要求する追跡できます。</span><span class="sxs-lookup"><span data-stu-id="09788-109">The task Id for the request you wish to track.</span></span>
            </param>
        <summary>
            <span data-ttu-id="09788-110">タスクの状態の取得では、指定されたタスク id の状態を返します。非同期タスクを呼び出した後は、呼び出すことができます、タスクが成功したかどうかを決定するタスクの状態の取得に失敗しました。 または、進行中です。</span><span class="sxs-lookup"><span data-stu-id="09788-110">The Get Task Status returns the status of the specified task id. After calling an asynchronous task, you can call Get Task Status to determine whether the task has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="09788-111">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="09788-111">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>