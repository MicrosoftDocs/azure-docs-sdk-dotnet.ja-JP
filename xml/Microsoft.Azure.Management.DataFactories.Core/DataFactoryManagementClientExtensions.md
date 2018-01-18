<Type Name="DataFactoryManagementClientExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions">
  <TypeSignature Language="C#" Value="public static class DataFactoryManagementClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataFactoryManagementClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataFactoryManagementClientExtensions" />
  <TypeSignature Language="F#" Value="type DataFactoryManagementClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
    <Member MemberName="GetLongRunningOperationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse GetLongRunningOperationStatus (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse GetLongRunningOperationStatus(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions.GetLongRunningOperationStatus(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLongRunningOperationStatus (operations As IDataFactoryManagementClient, operationStatusLink As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member GetLongRunningOperationStatus : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions.GetLongRunningOperationStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f078-101">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient への参照。</span><span class="sxs-lookup"><span data-stu-id="2f078-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="2f078-102">必須。</span><span class="sxs-lookup"><span data-stu-id="2f078-102">Required.</span></span> <span data-ttu-id="2f078-103">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="2f078-103">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f078-104">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="2f078-104">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="2f078-105">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="2f078-105">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2f078-106">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="2f078-106">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLongRunningOperationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; GetLongRunningOperationStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; GetLongRunningOperationStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions.GetLongRunningOperationStatusAsync(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLongRunningOperationStatusAsync (operations As IDataFactoryManagementClient, operationStatusLink As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member GetLongRunningOperationStatusAsync : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryManagementClientExtensions.GetLongRunningOperationStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2f078-107">Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient への参照。</span><span class="sxs-lookup"><span data-stu-id="2f078-107">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="2f078-108">必須。</span><span class="sxs-lookup"><span data-stu-id="2f078-108">Required.</span></span> <span data-ttu-id="2f078-109">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="2f078-109">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2f078-110">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="2f078-110">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="2f078-111">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="2f078-111">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2f078-112">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="2f078-112">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>