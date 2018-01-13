<Type Name="ManagementLocksOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ManagementLocksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ManagementLocksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ManagementLocksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ManagementLocksOperationsExtensions = class" />
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
            ManagementLocksOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevel (operations, resourceGroupName, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ロックするリソース グループの名前。
            </param>
        <param name="lockName">
            ロックの名前です。 ロック名は 260 文字の最大値にできます。 含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。
            </param>
        <param name="parameters">
            管理ロックのパラメーターです。
            </param>
        <summary>
            作成するか、リソース グループ レベルの管理ロックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。 管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevelAsync (operations, resourceGroupName, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateAtResourceGroupLevelAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ロックするリソース グループの名前。
            </param>
        <param name="lockName">
            ロックの名前です。 ロック名は 260 文字の最大値にできます。 含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。
            </param>
        <param name="parameters">
            管理ロックのパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、リソース グループ レベルの管理ロックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。 管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtResourceLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ロック リソースを含む、リソース グループの名前。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間のリソースをロックします。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            ロックするリソースのリソースの種類。
            </param>
        <param name="resourceName">
            ロックするリソースの名前。
            </param>
        <param name="lockName">
            ロックの名前。 ロック名は 260 文字の最大値にできます。 含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。
            </param>
        <param name="parameters">
            作成または管理ロックを更新するためのパラメーター。
            </param>
        <summary>
            作成するか、リソース レベルまたはリソースの下の任意のレベルでの管理ロックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。 管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateAtResourceLevelAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ロック リソースを含む、リソース グループの名前。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間のリソースをロックします。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            ロックするリソースのリソースの種類。
            </param>
        <param name="resourceName">
            ロックするリソースの名前。
            </param>
        <param name="lockName">
            ロックの名前。 ロック名は 260 文字の最大値にできます。 含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。
            </param>
        <param name="parameters">
            作成または管理ロックを更新するためのパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、リソース レベルまたはリソースの下の任意のレベルでの管理ロックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。 管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAtSubscriptionLevel (operations As IManagementLocksOperations, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevel (operations, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="lockName">
            ロックの名前。 ロック名は 260 文字の最大値にできます。 含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。
            </param>
        <param name="parameters">
            管理ロックのパラメーターです。
            </param>
        <summary>
            作成するか、サブスクリプション レベルでの管理ロックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。 管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevelAsync (operations, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateAtSubscriptionLevelAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="lockName">
            ロックの名前。 ロック名は 260 文字の最大値にできます。 含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。
            </param>
        <param name="parameters">
            管理ロックのパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、サブスクリプション レベルでの管理ロックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。 管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateByScope">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateByScope (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateByScope(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScope(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateByScope (operations As IManagementLocksOperations, scope As String, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateByScope : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScope (operations, scope, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="scope">
            ロックのスコープです。 割り当てのスコープを提供するときに使用して 'のサブスクリプション/{subscriptionid}' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' のリソース グループのサブスクリプションの場合と 'サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/providers/{resourceProviderNamespace}/{parentResourcePathIfPresent}/{resourcetype}/{resourcename}' のリソース。
            </param>
        <param name="lockName">
            ロックの名前。
            </param>
        <param name="parameters">
            作成または管理ロック パラメーターを更新します。
            </param>
        <summary>
            作成またはスコープでの管理ロックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateByScopeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateByScopeAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateByScopeAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScopeAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateByScopeAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScopeAsync (operations, scope, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateByScopeAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="scope">
            ロックのスコープです。 割り当てのスコープを提供するときに使用して 'のサブスクリプション/{subscriptionid}' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' のリソース グループのサブスクリプションの場合と 'サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/providers/{resourceProviderNamespace}/{parentResourcePathIfPresent}/{resourcetype}/{resourcename}' のリソース。
            </param>
        <param name="lockName">
            ロックの名前。
            </param>
        <param name="parameters">
            作成または管理ロック パラメーターを更新します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成またはスコープでの管理ロックを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static void DeleteAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevel (operations, resourceGroupName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ロックを含むリソース グループの名前。
            </param>
        <param name="lockName">
            削除するロックの名前。
            </param>
        <summary>
            リソース グループ レベルでの管理ロックを削除します。
            </summary>
        <remarks>
            管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevelAsync (operations, resourceGroupName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteAtResourceGroupLevelAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ロックを含むリソース グループの名前。
            </param>
        <param name="lockName">
            削除するロックの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ レベルでの管理ロックを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceLevel">
      <MemberSignature Language="C#" Value="public static void DeleteAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            削除すると、ロック リソースを含む、リソース グループの名前。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間を削除するロックを持つリソースのです。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            削除するロックを持つリソースのリソースの種類。
            </param>
        <param name="resourceName">
            ロックを削除すると、リソースの名前。
            </param>
        <param name="lockName">
            削除するロックの名前です。
            </param>
        <summary>
            リソースまたはリソースの下の任意のレベルのロックの管理を削除します。
            </summary>
        <remarks>
            管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteAtResourceLevelAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            削除すると、ロック リソースを含む、リソース グループの名前。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間を削除するロックを持つリソースのです。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            削除するロックを持つリソースのリソースの種類。
            </param>
        <param name="resourceName">
            ロックを削除すると、リソースの名前。
            </param>
        <param name="lockName">
            削除するロックの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースまたはリソースの下の任意のレベルのロックの管理を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static void DeleteAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAtSubscriptionLevel (operations As IManagementLocksOperations, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevel (operations, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="lockName">
            削除するロックの名前。
            </param>
        <summary>
            サブスクリプション レベルでの管理ロックを削除します。
            </summary>
        <remarks>
            管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevelAsync (operations, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteAtSubscriptionLevelAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="lockName">
            削除するロックの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプション レベルでの管理ロックを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。 組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByScope">
      <MemberSignature Language="C#" Value="public static void DeleteByScope (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteByScope(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScope(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteByScope (operations As IManagementLocksOperations, scope As String, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteByScope : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScope (operations, scope, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="scope">
            ロックのスコープです。
            </param>
        <param name="lockName">
            ロックの名前。
            </param>
        <summary>
            スコープでの管理ロックを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByScopeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteByScopeAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteByScopeAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScopeAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteByScopeAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScopeAsync (operations, scope, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteByScopeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="scope">
            ロックのスコープです。
            </param>
        <param name="lockName">
            ロックの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            スコープでの管理ロックを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevel (operations, resourceGroupName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ロックされているリソース グループの名前。
            </param>
        <param name="lockName">
            取得するロックの名前です。
            </param>
        <summary>
            リソース グループ レベルでの管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevelAsync (operations, resourceGroupName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetAtResourceGroupLevelAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ロックされているリソース グループの名前。
            </param>
        <param name="lockName">
            取得するロックの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループ レベルでの管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            SQL データベースと同様に、一部のサービスで必要な追加のパスのパラメーターです。
            </param>
        <param name="resourceType">
            リソースの型。
            </param>
        <param name="resourceName">
            リソースの名前。
            </param>
        <param name="lockName">
            ロックの名前。
            </param>
        <summary>
            リソースまたはリソースの下の任意のレベルの管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetAtResourceLevelAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソース グループの名前。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            SQL データベースと同様に、一部のサービスで必要な追加のパスのパラメーターです。
            </param>
        <param name="resourceType">
            リソースの型。
            </param>
        <param name="resourceName">
            リソースの名前。
            </param>
        <param name="lockName">
            ロックの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースまたはリソースの下の任意のレベルの管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAtSubscriptionLevel (operations As IManagementLocksOperations, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevel (operations, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="lockName">
            取得するロックの名前です。
            </param>
        <summary>
            サブスクリプション レベルでの管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevelAsync (operations, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetAtSubscriptionLevelAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="lockName">
            取得するロックの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプション レベルでの管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByScope">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetByScope (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetByScope(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScope(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetByScope (operations As IManagementLocksOperations, scope As String, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetByScope : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScope (operations, scope, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="scope">
            ロックのスコープです。
            </param>
        <param name="lockName">
            ロックの名前。
            </param>
        <summary>
            スコープでの管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByScopeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetByScopeAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetByScopeAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScopeAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByScopeAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScopeAsync (operations, scope, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetByScopeAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="scope">
            ロックのスコープです。
            </param>
        <param name="lockName">
            ロックの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            スコープでの管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, Optional odataQuery As ODataQuery(Of ManagementLockObject) = null) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevel (operations, resourceGroupName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するロックを含むリソース グループの名前。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <summary>
            リソース グループのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelAsync (operations, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceGroupLevelAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            取得するロックを含むリソース グループの名前。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソース グループのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevelNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevelNext (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevelNext(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNext(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceGroupLevelNext (operations As IManagementLocksOperations, nextPageLink As String) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevelNext : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
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
            リソース グループのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevelNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelNextAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelNextAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNextAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevelNextAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceGroupLevelNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
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
            リソース グループのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, Optional odataQuery As ODataQuery(Of ManagementLockObject) = null) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ロックされたリソースを含むリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            ロックされたリソースのリソースの種類。
            </param>
        <param name="resourceName">
            ロックされたリソースの名前です。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <summary>
            リソースまたはリソースの下の任意のレベルのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceLevelAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            ロックされたリソースを含むリソース グループの名前。 名前は大文字小文字を区別します。
            </param>
        <param name="resourceProviderNamespace">
            リソース プロバイダーの名前空間です。
            </param>
        <param name="parentResourcePath">
            親のリソース id です。
            </param>
        <param name="resourceType">
            ロックされたリソースのリソースの種類。
            </param>
        <param name="resourceName">
            ロックされたリソースの名前です。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            リソースまたはリソースの下の任意のレベルのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevelNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevelNext (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevelNext(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNext(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceLevelNext (operations As IManagementLocksOperations, nextPageLink As String) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevelNext : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
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
            リソースまたはリソースの下の任意のレベルのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevelNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelNextAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelNextAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNextAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevelNextAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceLevelNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
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
            リソースまたはリソースの下の任意のレベルのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtSubscriptionLevel (operations As IManagementLocksOperations, Optional odataQuery As ODataQuery(Of ManagementLockObject) = null) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevel (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <summary>
            サブスクリプションのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtSubscriptionLevelAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
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
            サブスクリプションのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevelNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevelNext (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevelNext(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNext(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtSubscriptionLevelNext (operations As IManagementLocksOperations, nextPageLink As String) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevelNext : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
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
            サブスクリプションのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevelNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelNextAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelNextAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNextAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevelNextAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtSubscriptionLevelNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
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
            サブスクリプションのすべての管理ロックを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>