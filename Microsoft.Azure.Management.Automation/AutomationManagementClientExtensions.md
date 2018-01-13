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
            Microsoft.Azure.Management.Automation.IAutomationManagementClient への参照。
            </param>
        <param name="operationStatusLink">
            必須。 Begin 操作によって返される location 値です。
            </param>
        <summary>
            Get Operation Status 操作では、指定された操作の状態を返します。 非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
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
            Microsoft.Azure.Management.Automation.IAutomationManagementClient への参照。
            </param>
        <param name="operationStatusLink">
            必須。 Begin 操作によって返される location 値です。
            </param>
        <summary>
            Get Operation Status 操作では、指定された操作の状態を返します。 非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。
            </summary>
        <returns>
            時間の長いの応答を標準のサービス操作を実行します。
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
            Microsoft.Azure.Management.Automation.IAutomationManagementClient への参照。
            </param>
        <param name="requestId">
            必須。 追跡する要求の要求 ID。要求 ID は、すべての要求に対して x ms 要求 id の応答ヘッダーで返されます。
            </param>
        <summary>
            Get Operation Status 操作には、指定された操作のステータスが返されます。 非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。  (詳細については http://msdn.microsoft.com/en-us/library/windowsazure/ee460783.aspx を参照してください)
            </summary>
        <returns>
            応答本文には、かどうかそれが成功したは、処理中、または失敗を示すが、指定した非同期操作の状態が含まれています。 この状態は、Get Operation Status 操作自体に対して返される HTTP ステータス コードと異なることに注意してください。  非同期操作が成功した場合、応答本文には、成功した要求の HTTP ステータス コードが含まれています。  非同期操作に失敗した場合、応答本文は、失敗した要求の HTTP ステータス コードが含まれています、失敗に関するエラー情報も含まれます。
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
            Microsoft.Azure.Management.Automation.IAutomationManagementClient への参照。
            </param>
        <param name="requestId">
            必須。 追跡する要求の要求 ID。要求 ID は、すべての要求に対して x ms 要求 id の応答ヘッダーで返されます。
            </param>
        <summary>
            Get Operation Status 操作には、指定された操作のステータスが返されます。 非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。  (詳細については http://msdn.microsoft.com/en-us/library/windowsazure/ee460783.aspx を参照してください)
            </summary>
        <returns>
            応答本文には、かどうかそれが成功したは、処理中、または失敗を示すが、指定した非同期操作の状態が含まれています。 この状態は、Get Operation Status 操作自体に対して返される HTTP ステータス コードと異なることに注意してください。  非同期操作が成功した場合、応答本文には、成功した要求の HTTP ステータス コードが含まれています。  非同期操作に失敗した場合、応答本文は、失敗した要求の HTTP ステータス コードが含まれています、失敗に関するエラー情報も含まれます。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>