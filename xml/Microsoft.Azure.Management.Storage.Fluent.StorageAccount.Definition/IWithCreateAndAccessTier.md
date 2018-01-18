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
            <span data-ttu-id="996e1-101">設定するアクセス レベルを許可するストレージ アカウント定義します。</span><span class="sxs-lookup"><span data-stu-id="996e1-101">A storage account definition allowing access tier to be set.</span></span>
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
        <param name="accessTier"><span data-ttu-id="996e1-102">アクセス層の値。</span><span class="sxs-lookup"><span data-stu-id="996e1-102">The access tier value.</span></span></param>
        <summary>
            <span data-ttu-id="996e1-103">課金の目的に使用されるアクセス レベルを指定します。</span><span class="sxs-lookup"><span data-stu-id="996e1-103">Specifies the access tier used for billing.</span></span>
            <span data-ttu-id="996e1-104">アクセス層には、7 日に複数回の (168 時間) を変更できません。</span><span class="sxs-lookup"><span data-stu-id="996e1-104">Access tier cannot be changed more than once every 7 days (168 hours).</span></span>
            <span data-ttu-id="996e1-105">StandardLRS、StandardGRS、StandardRAGRS、または PremiumLRS 勘定科目の種類には、アクセス層を設定することはできません。</span><span class="sxs-lookup"><span data-stu-id="996e1-105">Access tier cannot be set for StandardLRS, StandardGRS, StandardRAGRS, or PremiumLRS account types.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="996e1-106">ストレージ アカウント定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="996e1-106">The next stage of storage account definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>