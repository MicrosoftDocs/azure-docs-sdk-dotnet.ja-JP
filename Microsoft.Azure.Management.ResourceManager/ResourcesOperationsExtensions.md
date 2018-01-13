<Type Name="ResourcesOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourcesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourcesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourcesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourcesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ResourcesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource BeginCreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource BeginCreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String, parameters As GenericResource) As GenericResource" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースのリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            作成するリソースのリソースの種類。
            </param>
        <param name="resourceName">
            作成するリソースの名前。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="parameters">
            作成またはリソースを更新するためのパラメーター。
            </param>
        <summary>
            リソースを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースのリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            作成するリソースのリソースの種類。
            </param>
        <param name="resourceName">
            作成するリソースの名前。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="parameters">
            作成またはリソースを更新するためのパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource BeginCreateOrUpdateById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource BeginCreateOrUpdateById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateById (operations As IResourcesOperations, resourceId As String, apiVersion As String, parameters As GenericResource) As GenericResource" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateById (operations, resourceId, apiVersion, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="parameters">
            作成またはリソース パラメーターを更新します。
            </param>
        <summary>
            ID でリソースを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; BeginCreateOrUpdateByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; BeginCreateOrUpdateByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateByIdAsync (operations, resourceId, apiVersion, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginCreateOrUpdateByIdAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="parameters">
            作成またはリソース パラメーターを更新します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ID でリソースを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDelete (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            削除するリソースが含まれているリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            リソースの種類。
            </param>
        <param name="resourceName">
            削除するリソースの名前です。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <summary>
            リソースを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            削除するリソースが含まれているリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            リソースの種類。
            </param>
        <param name="resourceName">
            削除するリソースの名前です。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteById">
      <MemberSignature Language="C#" Value="public static void BeginDeleteById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDeleteById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDeleteById (operations As IResourcesOperations, resourceId As String, apiVersion As String)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteById (operations, resourceId, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <summary>
            ID でリソースを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteByIdAsync (operations, resourceId, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginDeleteByIdAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ID でリソースを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginMoveResources">
      <MemberSignature Language="C#" Value="public static void BeginMoveResources (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginMoveResources(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginMoveResources(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginMoveResources (operations As IResourcesOperations, sourceResourceGroupName As String, parameters As ResourcesMoveInfo)" />
      <MemberSignature Language="F#" Value="static member BeginMoveResources : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginMoveResources (operations, sourceResourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="sourceResourceGroupName">
            移動するリソースを含む、リソース グループの名前。
            </param>
        <param name="parameters">
            リソースの移動のパラメーターです。
            </param>
        <summary>
            リソースを 1 つのリソース グループから別のリソース グループに移動します。
            </summary>
        <remarks>
            移動するリソースは、同じソース リソース グループである必要があります。 ターゲット リソース グループは、別のサブスクリプションがあります。 リソースを移動するときに、ソース グループと、対象グループの両方がロックされている操作の実行中です。 これらのグループに対する書き込み操作および削除操作は、移動が完了するまでブロックされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginMoveResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginMoveResourcesAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginMoveResourcesAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginMoveResourcesAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginMoveResourcesAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginMoveResourcesAsync (operations, sourceResourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginMoveResourcesAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="sourceResourceGroupName">
            移動するリソースを含む、リソース グループの名前。
            </param>
        <param name="parameters">
            リソースの移動のパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースを 1 つのリソース グループから別のリソース グループに移動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            移動するリソースは、同じソース リソース グループである必要があります。 ターゲット リソース グループは、別のサブスクリプションがあります。 リソースを移動するときに、ソース グループと、対象グループの両方がロックされている操作の実行中です。 これらのグループに対する書き込み操作および削除操作は、移動が完了するまでブロックされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginValidateMoveResources">
      <MemberSignature Language="C#" Value="public static void BeginValidateMoveResources (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginValidateMoveResources(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginValidateMoveResources(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginValidateMoveResources (operations As IResourcesOperations, sourceResourceGroupName As String, parameters As ResourcesMoveInfo)" />
      <MemberSignature Language="F#" Value="static member BeginValidateMoveResources : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginValidateMoveResources (operations, sourceResourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="sourceResourceGroupName">
            検証するため、リソースを含む、リソース グループの名前に移動します。
            </param>
        <param name="parameters">
            リソースの移動のパラメーターです。
            </param>
        <summary>
            リソースは、別のリソース グループを 1 つのリソース グループから移動できるかどうかを検証します。
            </summary>
        <remarks>
            この操作は、指定したリソースをターゲットに移動できるかどうかを確認します。 移動するリソースは、同じソース リソース グループである必要があります。
            ターゲット リソース グループは、別のサブスクリプションがあります。 検証が成功した場合は、HTTP 応答コード 204 (コンテンツなし) を返します。 検証に失敗した場合は、エラー メッセージを HTTP 応答コード 409 (Conflict) を返します。
            実行時間の長い操作の結果を確認する場所ヘッダーの値に URL を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginValidateMoveResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginValidateMoveResourcesAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginValidateMoveResourcesAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginValidateMoveResourcesAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginValidateMoveResourcesAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginValidateMoveResourcesAsync (operations, sourceResourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginValidateMoveResourcesAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="sourceResourceGroupName">
            検証するため、リソースを含む、リソース グループの名前に移動します。
            </param>
        <param name="parameters">
            リソースの移動のパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースは、別のリソース グループを 1 つのリソース グループから移動できるかどうかを検証します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、指定したリソースをターゲットに移動できるかどうかを確認します。 移動するリソースは、同じソース リソース グループである必要があります。
            ターゲット リソース グループは、別のサブスクリプションがあります。 検証が成功した場合は、HTTP 応答コード 204 (コンテンツなし) を返します。 検証に失敗した場合は、エラー メッセージを HTTP 応答コード 409 (Conflict) を返します。
            実行時間の長い操作の結果を確認する場所ヘッダーの値に URL を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistence">
      <MemberSignature Language="C#" Value="public static bool CheckExistence (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool CheckExistence(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistence(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckExistence (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member CheckExistence : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string -&gt; bool" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistence (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            チェックするリソースを含む、リソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            チェックするリソースのリソース プロバイダーです。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            リソースの種類。
            </param>
        <param name="resourceName">
            存在するかどうかをチェックするリソースの名前。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <summary>
            リソースが存在するかどうかを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;CheckExistenceAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            チェックするリソースを含む、リソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            チェックするリソースのリソース プロバイダーです。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            リソースの種類。
            </param>
        <param name="resourceName">
            存在するかどうかをチェックするリソースの名前。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースが存在するかどうかを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceById">
      <MemberSignature Language="C#" Value="public static bool CheckExistenceById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool CheckExistenceById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckExistenceById (operations As IResourcesOperations, resourceId As String, apiVersion As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member CheckExistenceById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string -&gt; bool" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceById (operations, resourceId, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <summary>
            ID によってリソースが存在するかどうかを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceByIdAsync (operations, resourceId, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;CheckExistenceByIdAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ID によってリソースが存在するかどうかを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String, parameters As GenericResource) As GenericResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースのリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            作成するリソースのリソースの種類。
            </param>
        <param name="resourceName">
            作成するリソースの名前。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="parameters">
            作成またはリソースを更新するためのパラメーター。
            </param>
        <summary>
            リソースを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースのリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            作成するリソースのリソースの種類。
            </param>
        <param name="resourceName">
            作成するリソースの名前。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="parameters">
            作成またはリソースを更新するためのパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource CreateOrUpdateById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource CreateOrUpdateById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateById (operations As IResourcesOperations, resourceId As String, apiVersion As String, parameters As GenericResource) As GenericResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateById (operations, resourceId, apiVersion, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="parameters">
            作成またはリソース パラメーターを更新します。
            </param>
        <summary>
            ID でリソースを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; CreateOrUpdateByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; CreateOrUpdateByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateByIdAsync (operations, resourceId, apiVersion, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;CreateOrUpdateByIdAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="parameters">
            作成またはリソース パラメーターを更新します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ID でリソースを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.Delete (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            削除するリソースが含まれているリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            リソースの種類。
            </param>
        <param name="resourceName">
            削除するリソースの名前です。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <summary>
            リソースを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;DeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            削除するリソースが含まれているリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            リソースの種類。
            </param>
        <param name="resourceName">
            削除するリソースの名前です。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteById">
      <MemberSignature Language="C#" Value="public static void DeleteById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteById (operations As IResourcesOperations, resourceId As String, apiVersion As String)" />
      <MemberSignature Language="F#" Value="static member DeleteById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteById (operations, resourceId, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <summary>
            ID でリソースを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteByIdAsync (operations, resourceId, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;DeleteByIdAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ID でリソースを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource Get (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource Get(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String) As GenericResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.Get (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソースを含む、リソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            リソースのリソースの種類。
            </param>
        <param name="resourceName">
            取得するリソースの名前。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <summary>
            リソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;GetAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するリソースを含む、リソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            リソースのリソースの種類。
            </param>
        <param name="resourceName">
            取得するリソースの名前。
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource GetById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource GetById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetById (operations As IResourcesOperations, resourceId As String, apiVersion As String) As GenericResource" />
      <MemberSignature Language="F#" Value="static member GetById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetById (operations, resourceId, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <summary>
            ID でリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; GetByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; GetByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetByIdAsync (operations, resourceId, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;GetByIdAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceId">
            リソース名とリソースの種類を含む、リソースの完全修飾 ID です。 形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}
            </param>
        <param name="apiVersion">
            操作に使用する API バージョン。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ID でリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; List (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; List(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IResourcesOperations, Optional odataQuery As ODataQuery(Of GenericResourceFilter) = null) As IPage(Of GenericResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.List (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <summary>
            サブスクリプション内のすべてのリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプション内のすべてのリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListByResourceGroup (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListByResourceGroup(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IResourcesOperations, resourceGroupName As String, Optional odataQuery As ODataQuery(Of GenericResourceFilter) = null) As IPage(Of GenericResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループにリソースを取得します。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <summary>
            リソース グループのすべてのリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループにリソースを取得します。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループのすべてのリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IResourcesOperations, nextPageLink As String) As IPage(Of GenericResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            リソース グループのすべてのリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループのすべてのリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IResourcesOperations, nextPageLink As String) As IPage(Of GenericResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            サブスクリプション内のすべてのリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;ListNextAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプション内のすべてのリソースを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveResources">
      <MemberSignature Language="C#" Value="public static void MoveResources (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void MoveResources(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.MoveResources(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub MoveResources (operations As IResourcesOperations, sourceResourceGroupName As String, parameters As ResourcesMoveInfo)" />
      <MemberSignature Language="F#" Value="static member MoveResources : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.MoveResources (operations, sourceResourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="sourceResourceGroupName">
            移動するリソースを含む、リソース グループの名前。
            </param>
        <param name="parameters">
            リソースの移動のパラメーターです。
            </param>
        <summary>
            リソースを 1 つのリソース グループから別のリソース グループに移動します。
            </summary>
        <remarks>
            移動するリソースは、同じソース リソース グループである必要があります。 ターゲット リソース グループは、別のサブスクリプションがあります。 リソースを移動するときに、ソース グループと、対象グループの両方がロックされている操作の実行中です。 これらのグループに対する書き込み操作および削除操作は、移動が完了するまでブロックされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task MoveResourcesAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task MoveResourcesAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.MoveResourcesAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MoveResourcesAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.MoveResourcesAsync (operations, sourceResourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;MoveResourcesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="sourceResourceGroupName">
            移動するリソースを含む、リソース グループの名前。
            </param>
        <param name="parameters">
            リソースの移動のパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースを 1 つのリソース グループから別のリソース グループに移動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            移動するリソースは、同じソース リソース グループである必要があります。 ターゲット リソース グループは、別のサブスクリプションがあります。 リソースを移動するときに、ソース グループと、対象グループの両方がロックされている操作の実行中です。 これらのグループに対する書き込み操作および削除操作は、移動が完了するまでブロックされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateMoveResources">
      <MemberSignature Language="C#" Value="public static void ValidateMoveResources (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateMoveResources(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ValidateMoveResources(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ValidateMoveResources (operations As IResourcesOperations, sourceResourceGroupName As String, parameters As ResourcesMoveInfo)" />
      <MemberSignature Language="F#" Value="static member ValidateMoveResources : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ValidateMoveResources (operations, sourceResourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="sourceResourceGroupName">
            検証するため、リソースを含む、リソース グループの名前に移動します。
            </param>
        <param name="parameters">
            リソースの移動のパラメーターです。
            </param>
        <summary>
            リソースは、別のリソース グループを 1 つのリソース グループから移動できるかどうかを検証します。
            </summary>
        <remarks>
            この操作は、指定したリソースをターゲットに移動できるかどうかを確認します。 移動するリソースは、同じソース リソース グループである必要があります。
            ターゲット リソース グループは、別のサブスクリプションがあります。 検証が成功した場合は、HTTP 応答コード 204 (コンテンツなし) を返します。 検証に失敗した場合は、エラー メッセージを HTTP 応答コード 409 (Conflict) を返します。
            実行時間の長い操作の結果を確認する場所ヘッダーの値に URL を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateMoveResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ValidateMoveResourcesAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ValidateMoveResourcesAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ValidateMoveResourcesAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateMoveResourcesAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ValidateMoveResourcesAsync (operations, sourceResourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;ValidateMoveResourcesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="sourceResourceGroupName">
            検証するため、リソースを含む、リソース グループの名前に移動します。
            </param>
        <param name="parameters">
            リソースの移動のパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースは、別のリソース グループを 1 つのリソース グループから移動できるかどうかを検証します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、指定したリソースをターゲットに移動できるかどうかを確認します。 移動するリソースは、同じソース リソース グループである必要があります。
            ターゲット リソース グループは、別のサブスクリプションがあります。 検証が成功した場合は、HTTP 応答コード 204 (コンテンツなし) を返します。 検証に失敗した場合は、エラー メッセージを HTTP 応答コード 409 (Conflict) を返します。
            実行時間の長い操作の結果を確認する場所ヘッダーの値に URL を取得します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>