<Type Name="IVault" FullName="Microsoft.Azure.Management.KeyVault.Fluent.IVault">
  <TypeSignature Language="C#" Value="public interface IVault : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManager,Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.KeyVault.Fluent.IVault&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVault implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManager, class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.IVault&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.IVault" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVault&#xA;Implements IGroupableResource(Of IKeyVaultManager, VaultInner), IHasInner(Of VaultInner), IHasManager(Of IKeyVaultManager), IRefreshable(Of IVault), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IVault = interface&#xA;    interface IGroupableResource&lt;IKeyVaultManager, VaultInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IKeyVaultManager&gt;&#xA;    interface IHasInner&lt;VaultInner&gt;&#xA;    interface IRefreshable&lt;IVault&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManager,Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.VaultInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.KeyVault.Fluent.IKeyVaultManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.KeyVault.Fluent.IVault&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.KeyVault.Fluent.Vault.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure Key Vault の変更できないクライアント側表現。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AccessPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy&gt; AccessPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy&gt; AccessPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.IVault.AccessPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessPolicies As IList(Of IAccessPolicy)" />
      <MemberSignature Language="F#" Value="member this.AccessPolicies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy&gt;" Usage="Microsoft.Azure.Management.KeyVault.Fluent.IVault.AccessPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>Key vault にアクセスする 0 ~ 16 id の配列。 すべて</value>
        <value>配列内の id は、キー コンテナーのと同じテナント ID を使用する必要があります。</value>
        <value>テナントの id。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForDeployment">
      <MemberSignature Language="C#" Value="public bool EnabledForDeployment { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnabledForDeployment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.IVault.EnabledForDeployment" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledForDeployment As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnabledForDeployment : bool" Usage="Microsoft.Azure.Management.KeyVault.Fluent.IVault.EnabledForDeployment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>Azure の仮想マシンを許可するかどうか</value>
        <value>key vault からシークレットとして格納されている証明書を取得します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForDiskEncryption">
      <MemberSignature Language="C#" Value="public bool EnabledForDiskEncryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnabledForDiskEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.IVault.EnabledForDiskEncryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledForDiskEncryption As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnabledForDiskEncryption : bool" Usage="Microsoft.Azure.Management.KeyVault.Fluent.IVault.EnabledForDiskEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>Azure ディスクの暗号化を許可するかどうか</value>
        <value>vault からシークレットを取得し、キーのラップを解除します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForTemplateDeployment">
      <MemberSignature Language="C#" Value="public bool EnabledForTemplateDeployment { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnabledForTemplateDeployment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.IVault.EnabledForTemplateDeployment" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledForTemplateDeployment As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnabledForTemplateDeployment : bool" Usage="Microsoft.Azure.Management.KeyVault.Fluent.IVault.EnabledForTemplateDeployment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>Azure Resource Manager を許可するかどうか</value>
        <value>key vault からシークレットを取得します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.IVault.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.KeyVault.Fluent.IVault.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>SKU の詳細。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.IVault.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.Azure.Management.KeyVault.Fluent.IVault.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>Azure Active Directory テナント ID のために使用する必要があります。</value>
        <value>key vault への要求を認証します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VaultUri">
      <MemberSignature Language="C#" Value="public string VaultUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VaultUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Fluent.IVault.VaultUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VaultUri As String" />
      <MemberSignature Language="F#" Value="member this.VaultUri : string" Usage="Microsoft.Azure.Management.KeyVault.Fluent.IVault.VaultUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>キーとシークレットの操作を実行する資格情報コンテナーの URI。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>