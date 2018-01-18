<Type Name="IWithStorageAccount" FullName="Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount">
  <TypeSignature Language="C#" Value="public interface IWithStorageAccount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStorageAccount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStorageAccount" />
  <TypeSignature Language="F#" Value="type IWithStorageAccount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9f4c8-101">ストレージ アカウントの指定を許可するバッチ アカウントの更新の段階です。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-101">The stage of a Batch account update allowing to specify a storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithExistingStorageAccount (Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithExistingStorageAccount(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount.WithExistingStorageAccount(Microsoft.Azure.Management.Storage.Fluent.IStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingStorageAccount (storageAccount As IStorageAccount) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingStorageAccount : Microsoft.Azure.Management.Storage.Fluent.IStorageAccount -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate" Usage="iWithStorageAccount.WithExistingStorageAccount storageAccount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="9f4c8-102">既存のストレージ アカウント。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-102">An existing storage account.</span></span></param>
        <summary>
            <span data-ttu-id="9f4c8-103">Batch アカウントに関連付ける既存のストレージ アカウントを指定します。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-103">Specifies an existing storage account to associate with the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9f4c8-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithNewStorageAccount (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; storageAccountCreatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithNewStorageAccount(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; storageAccountCreatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount.WithNewStorageAccount(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Storage.Fluent.IStorageAccount})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (storageAccountCreatable As ICreatable(Of IStorageAccount)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt; -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate" Usage="iWithStorageAccount.WithNewStorageAccount storageAccountCreatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountCreatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;" />
      </Parameters>
      <Docs>
        <param name="storageAccountCreatable"><span data-ttu-id="9f4c8-105">ストレージ アカウントの定義。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-105">The definition of the storage account.</span></span></param>
        <summary>
            <span data-ttu-id="9f4c8-106">作成し、Batch アカウントに関連付ける新しいストレージ アカウントを指定します。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-106">Specifies a new storage account to create and associate with the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9f4c8-107">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithNewStorageAccount (string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithNewStorageAccount(string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount.WithNewStorageAccount(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (storageAccountName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : string -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate" Usage="iWithStorageAccount.WithNewStorageAccount storageAccountName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName"><span data-ttu-id="9f4c8-108">新しいストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-108">The name of a new storage account.</span></span></param>
        <summary>
            <span data-ttu-id="9f4c8-109">作成し、Batch アカウントに関連付ける新しいストレージ アカウントを指定します。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-109">Specifies a new storage account to create and associate with the Batch account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9f4c8-110">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithoutStorageAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate WithoutStorageAccount() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IWithStorageAccount.WithoutStorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutStorageAccount () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutStorageAccount : unit -&gt; Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate" Usage="iWithStorageAccount.WithoutStorageAccount " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.BatchAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9f4c8-111">関連付けられているストレージ アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-111">Removes the associated storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9f4c8-112">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9f4c8-112">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>