<Type Name="ProtectableObjectOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectableObjectOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectableObjectOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectableObjectOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectableObjectOperationsExtensions = class" />
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
    <Member MemberName="ListCSM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse ListCSM (this Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject csmparameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse ListCSM(class Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject csmparameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions.ListCSM(Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListCSM : Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions.ListCSM (operations, resourceGroupName, resourceName, csmparameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="csmparameters">
            省略可能。 保護可能なオブジェクトはクエリ パラメーターです。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            すべての項目の一覧を取得します。
            </summary>
        <returns>
            CSMItemListOperationResponse の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCSMAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt; ListCSMAsync (this Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject csmparameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt; ListCSMAsync(class Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject csmparameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions.ListCSMAsync(Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListCSMAsync : Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.ProtectableObjectOperationsExtensions.ListCSMAsync (operations, resourceGroupName, resourceName, csmparameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMItemListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMItemQueryObject" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.BackupServices.IProtectableObjectOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。
            </param>
        <param name="resourceName">
            必須。
            </param>
        <param name="csmparameters">
            省略可能。 保護可能なオブジェクトはクエリ パラメーターです。
            </param>
        <param name="customRequestHeaders">
            省略可能。 ヘッダーのパラメーターを要求します。
            </param>
        <summary>
            すべての項目の一覧を取得します。
            </summary>
        <returns>
            CSMItemListOperationResponse の定義。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>