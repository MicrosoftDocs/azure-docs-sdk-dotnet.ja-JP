<Type Name="CSMProtectionPolicyOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CSMProtectionPolicyOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CSMProtectionPolicyOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CSMProtectionPolicyOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CSMProtectionPolicyOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Add (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest cSMAddProtectionPolicyRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Add(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest cSMAddProtectionPolicyRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Add(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Add (operations, resourceGroupName, resourceName, policyName, cSMAddProtectionPolicyRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cSMAddProtectionPolicyRequest" Type="Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="policyName">
            必須。 保護ポリシーを更新する名前。
            </param>
        <param name="cSMAddProtectionPolicyRequest">
            必須。 保護ポリシーの作成要求。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            新しい保護ポリシーを作成します。
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; AddAsync (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest cSMAddProtectionPolicyRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; AddAsync(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest cSMAddProtectionPolicyRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.AddAsync(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.AddAsync (operations, resourceGroupName, resourceName, policyName, cSMAddProtectionPolicyRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cSMAddProtectionPolicyRequest" Type="Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="policyName">
            必須。 保護ポリシーを更新する名前。
            </param>
        <param name="cSMAddProtectionPolicyRequest">
            必須。 保護ポリシーの作成要求。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            新しい保護ポリシーを作成します。
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Delete(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Delete (operations, resourceGroupName, resourceName, policyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="policyName">
            必須。 保護ポリシーを削除する名前。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            保護ポリシーを削除します。
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceName, policyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="policyName">
            必須。 保護ポリシーを削除する名前。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            保護ポリシーを削除します。
            </summary>
        <returns>
            HTTP ステータス コードと要求 ID を含む標準サービスの応答
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse List (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse List(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.List(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.List (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            すべての保護ポリシーの一覧を取得します。
            </summary>
        <returns>
            CSMProtectionPolicyListOperationResponse の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt; ListAsync (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt; ListAsync(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.ListAsync(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.ListAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            すべての保護ポリシーの一覧を取得します。
            </summary>
        <returns>
            CSMProtectionPolicyListOperationResponse の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse Update (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest cSMUpdateProtectionPolicyRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse Update(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest cSMUpdateProtectionPolicyRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Update(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Update (operations, resourceGroupName, resourceName, policyName, cSMUpdateProtectionPolicyRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cSMUpdateProtectionPolicyRequest" Type="Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="policyName">
            必須。 保護ポリシーを更新する名前。
            </param>
        <param name="cSMUpdateProtectionPolicyRequest">
            必須。 保護ポリシーの作成要求。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            保護ポリシーを更新します。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateAsync (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest cSMUpdateProtectionPolicyRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateAsync(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest cSMUpdateProtectionPolicyRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.UpdateAsync (operations, resourceGroupName, resourceName, policyName, cSMUpdateProtectionPolicyRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cSMUpdateProtectionPolicyRequest" Type="Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="policyName">
            必須。 保護ポリシーを更新する名前。
            </param>
        <param name="cSMUpdateProtectionPolicyRequest">
            必須。 保護ポリシーの作成要求。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            保護ポリシーを更新します。
            </summary>
        <returns>
            操作の応答の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>