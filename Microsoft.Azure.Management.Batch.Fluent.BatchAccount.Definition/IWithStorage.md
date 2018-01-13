<Type Name="IWithStorage" FullName="Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithStorage">
  <TypeSignature Language="C#" Value="public interface IWithStorage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStorage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithStorage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStorage" />
  <TypeSignature Language="F#" Value="type IWithStorage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ストレージ アカウントを Batch アカウントに関連付けるを許可するバッチ アカウント定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithExistingStorageAccount (Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithExistingStorageAccount(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithStorage.WithExistingStorageAccount(Microsoft.Azure.Management.Storage.Fluent.IStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingStorageAccount (storageAccount As IStorageAccount) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingStorageAccount : Microsoft.Azure.Management.Storage.Fluent.IStorageAccount -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate" Usage="iWithStorage.WithExistingStorageAccount storageAccount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" />
      </Parameters>
      <Docs>
        <param name="storageAccount">既存のストレージ アカウント。</param>
        <summary>
            Batch アカウントに関連付ける既存のストレージ アカウントを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithNewStorageAccount (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; storageAccountCreatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithNewStorageAccount(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; storageAccountCreatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithStorage.WithNewStorageAccount(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Storage.Fluent.IStorageAccount})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (storageAccountCreatable As ICreatable(Of IStorageAccount)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate" Usage="iWithStorage.WithNewStorageAccount storageAccountCreatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountCreatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;" />
      </Parameters>
      <Docs>
        <param name="storageAccountCreatable">と共に作成して、Batch アカウントで使用するストレージ アカウントです。</param>
        <summary>
            Batch アカウントに関連付ける新しいストレージ アカウントを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithNewStorageAccount (string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate WithNewStorageAccount(string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithStorage.WithNewStorageAccount(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (storageAccountName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : string -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate" Usage="iWithStorage.WithNewStorageAccount storageAccountName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName">新しいストレージ アカウントの名前。</param>
        <summary>
            作成すること、この Batch アカウントに関連付けられている新しいストレージ アカウントの名前を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>