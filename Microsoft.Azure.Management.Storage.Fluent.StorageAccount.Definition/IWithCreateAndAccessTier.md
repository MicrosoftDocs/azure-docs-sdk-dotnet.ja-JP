<Type Name="IWithCreateAndAccessTier" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreateAndAccessTier">
  <TypeSignature Language="C#" Value="public interface IWithCreateAndAccessTier : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;, Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCreateAndAccessTier implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithBlobStorageAccountKind, class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate, class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCustomDomain, class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithEncryption, class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithGeneralPurposeAccountKind, class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithSku" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreateAndAccessTier" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCreateAndAccessTier&#xA;Implements ICreatable(Of IStorageAccount), IDefinitionWithTags(Of IWithCreate), IWithCreate" />
  <TypeSignature Language="F#" Value="type IWithCreateAndAccessTier = interface&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IStorageAccount&gt;&#xA;    interface IIndexable&#xA;    interface IWithSku&#xA;    interface IWithBlobStorageAccountKind&#xA;    interface IWithGeneralPurposeAccountKind&#xA;    interface IWithEncryption&#xA;    interface IWithCustomDomain&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            設定するアクセス レベルを許可するストレージ アカウント定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAccessTier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithAccessTier (Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier accessTier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate WithAccessTier(valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier accessTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreateAndAccessTier.WithAccessTier(Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier)" />
      <MemberSignature Language="F#" Value="abstract member WithAccessTier : Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate" Usage="iWithCreateAndAccessTier.WithAccessTier accessTier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessTier" Type="Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier" />
      </Parameters>
      <Docs>
        <param name="accessTier">アクセス層の値。</param>
        <summary>
            課金の目的に使用されるアクセス レベルを指定します。
            アクセス層には、7 日に複数回の (168 時間) を変更できません。
            StandardLRS、StandardGRS、StandardRAGRS、または PremiumLRS 勘定科目の種類には、アクセス層を設定することはできません。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ストレージ アカウント定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>